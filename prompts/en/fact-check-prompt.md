# Fact-Checking Prompt for a Text

## Context fields

- **Material to check** — the exact text, set of claims, or link; include the language, date, and revision version if known.
- **Purpose of the check** — the decision, publication, or action the result should support; completing the check does not authorize that action.
- **Intended audience** — who will use the check, for what purpose, and with what level of subject-matter knowledge.
- **Risks and claim types** — which claims are critical and what level of confidence is needed: for example, dates, numbers, laws, medical, financial, technical, or causal claims.
- **Scope and boundaries** — the parts of the material and claim types to check, plus explicit exclusions.
- **Source constraints** — mandatory limits on period, geography, available sources, verification methods, and prohibitions.
- **Required output format** — the language, structure, length, and form of the report that suit the intended audience.

Copy the text below and fill in the fields in square brackets. Add or remove fields as needed.

```text
Create a ready-to-use prompt for fact-checking a completed text or set of claims.

Context:
- Material to check: [text, claims, or link; language and version]
- Purpose of the check: [decision, publication, or action the result should support]
- Intended audience: [who will use the check]
- Risks and claim types: [critical types and required confidence]
- Scope and boundaries: [material parts, claim types, exclusions]
- Source constraints: [period, geography, sources, verification methods, prohibitions]
- Required output format: [language, structure, length, and form]

First, assess the inputs. If critical information about the material, purpose, boundaries, period, risks, or format is missing, ask no more than five clarifying questions and stop. Do not create the final prompt until the answers are provided.

If the critical information is sufficient, return only one self-contained prompt in English in a code block, with no explanation before or after it.

The prompt you create must specify:
1. the role of an independent verifier, the objective, audience, material, boundaries, and required level of confidence;
2. a breakdown of the material into individual material claims, with an explicit label for:
   - a verifiable fact;
   - an observation from the supplied material;
   - a conclusion or interpretation;
   - a hypothesis;
   - an opinion or recommendation;
   - a claim that cannot be verified from accessible evidence;
3. for every material, verifiable claim: a verdict of `supported`, `partially supported`, `contradicted by sources`, `not supported`, or `insufficient evidence`; the original wording, direct source links, title, author or organization, source type, publication, update, or access date, and a brief limitation;
4. source and precision rules:
   - for changing external facts, search for and verify current sources online unless the task explicitly restricts sources;
   - prefer primary documents, data, studies, and official sources; use a secondary source only when its method is transparent or to locate a primary source;
   - do not use an AI response, search results, an aggregator, forum, social-media post, or retelling as standalone confirmation;
   - do not make the wording broader than what the source supports or present inaccessible evidence as a confirmed fact;
   - for a material, contested, comparative, or causal claim, compare at least two independent sources; sources that repeat the same press release, original report, or one another are not independent;
5. separate identification of contradictions, outdated data, unverifiable claims, missing sources, and correction priority; keep proposed edits separate from verification findings and limit them to supported information;
6. this final structure: concise conclusion, method and coverage, claims table, critical issues, limitations of the check, and necessary next checks;
7. constraints concerning secrets, personal data, and confidential information, plus a rule not to publish, send data, or take external actions without separate permission.

Do not fact-check the material yourself and do not replace unknown inputs with assumptions.
```
