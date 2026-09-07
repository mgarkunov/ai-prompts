# Research Prompt

## Context fields

- **Research objective** — the knowledge needed to make a decision; do not replace it with an expected conclusion.
- **Decision** — the specific choice or action the findings should inform; name the decision owner if known.
- **Intended audience** — who will read the result, for what purpose, and with what level of subject-matter knowledge.
- **Scope and boundaries** — the objects, topic, and period to investigate, plus anything that must be explicitly excluded.
- **Research questions** — distinct, answerable questions whose answers will advance the decision.
- **Constraints** — mandatory limits on time, geography, data, sources, access, and permitted actions.
- **Required output format** — the language, structure, length, and form that suit the intended audience.

Copy the text below and fill in the fields in square brackets. Add or remove fields as needed.

```text
Create a ready-to-use prompt for conducting research.

Context:
- Research objective: [knowledge that needs to be obtained]
- Decision: [choice or action the findings should inform]
- Intended audience: [who will use the result]
- Scope and boundaries: [objects, topic, period, inclusions, and exclusions]
- Research questions: [list of questions]
- Constraints: [time, geography, data, sources, prohibitions]
- Required output format: [language, structure, length, and form]

First, assess the inputs. If critical information about the question, decision, scope, period, or format is missing, ask no more than five clarifying questions and stop. Do not create the final prompt until the answers are provided.

If the critical information is sufficient, return only one self-contained prompt in English in a code block, with no explanation before or after it.

The prompt you create must specify:
1. the researcher's role, objective, audience, questions, and boundaries;
2. a method for finding and comparing evidence, plus this required structure for the final output:
   - a concise answer to the research question;
   - scope, method, and evaluation criteria;
   - a table of key claims: claim, type, supporting sources, date or period, and a brief limitation;
   - limitations, contradictions, and unknowns;
   - recommendations kept separate from facts and conclusions;
3. an explicit distinction and label for:
   - a fact — a verifiable claim with a source;
   - an observation — what data or a source directly shows;
   - a conclusion — an interpretation of observations that explains the logical link;
   - a hypothesis — a testable but not yet confirmed assumption;
   - a recommendation — a proposed action based on a conclusion and its limitations;
4. concise fact-checking requirements:
   - quality and search: for changing external facts, search for and verify current sources online unless the task explicitly restricts sources; prefer primary documents, data, studies, and official sources; use a secondary source only when its method is transparent or to locate a primary source; use an AI response, search results, an aggregator, forum, social-media post, or retelling only to find candidate sources;
   - links and precision: next to every material fact, provide a direct link, title, author or organization, source type, and publication, update, or access date; do not make the wording broader than what the source supports; do not present a claim without an accessible basis for independent verification as a confirmed fact;
   - independence and method: for a material, contested, comparative, or causal conclusion, compare at least two independent sources; sources that repeat the same press release, original report, or one another are not independent; for a comparison, calculation, or causal conclusion, state the method, input data, period, units, assumptions, and limitations; do not present correlation as causation;
   - uncertainty: record the verification date for a changing fact; explicitly label an unknown, contradiction, hypothesis, and conclusion; when data or reliable sources are insufficient, state what is missing, how it limits the conclusion, and what verification is needed; do not invent facts, links, quotations, numbers, or sources;
5. constraints concerning secrets, personal data, and confidential information;
6. a rule not to take external actions, publish, or send data without separate permission.

Do not conduct the research itself and do not replace unknown inputs with assumptions.
```
