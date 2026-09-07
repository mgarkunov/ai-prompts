# Decision Analysis Prompt

## Context fields

- **Decision** — the specific choice, action, or decision not to act; state what remains the decision owner's authority.
- **Decision owner and audience** — who makes the decision and who will use the analysis, including the audience's level of subject-matter knowledge.
- **Options** — all known alternatives, including the status quo when relevant; do not add guessed alternatives.
- **Objectives and criteria** — what success means and the defined criteria for comparing options; provide weights and thresholds only when they have a basis.
- **Evidence** — confirmed facts, data, research, constraints, and prior decisions with a source or owner.
- **Boundaries and horizon** — scope, period, geography, budget, resources, prohibitions, and other conditions that limit the conclusion's applicability.
- **Required output format** — the language, structure, length, and form of analysis that suit the decision owner and audience.

Copy the text below and fill in the fields in square brackets. Add or remove fields as needed.

```text
Create a ready-to-use prompt for an evidence-based decision analysis.

Context:
- Decision: [choice, action, or decision not to act]
- Decision owner and audience: [who decides and who uses the analysis]
- Options: [known alternatives and the status quo]
- Objectives and criteria: [success and comparison criteria]
- Known evidence: [facts, data, research, constraints, decisions]
- Boundaries and horizon: [scope, period, geography, budget, resources, prohibitions]
- Required output format: [language, structure, length, and form]

First, assess the inputs. If critical information about the decision, options, decision owner, criteria, boundaries, or format is missing, ask no more than five clarifying questions and stop. Do not create the final prompt until the answers are provided.

If the critical information is sufficient, return only one self-contained prompt in English in a code block, with no explanation before or after it.

The prompt you create must specify:
1. the analyst's role, decision question, decision owner, audience, boundaries, and analysis horizon;
2. an explicit description of the options, including the status quo when relevant; do not create options, criteria, weights, or thresholds without input, and label missing information as questions or assumptions;
3. an explicit distinction and label for:
   - a confirmed fact with a source;
   - an observation from data;
   - an assumption;
   - a conclusion or interpretation;
   - a hypothesis that needs testing;
   - a recommendation that does not replace the decision owner's decision;
4. a method for comparing options: criteria, their definitions, data sources, units, and period; when the user supplies weights or scores, apply them transparently, and when they do not, do not invent a numerical score;
5. evidence rules: for changing external facts, search for and verify current sources online unless the task explicitly restricts sources; next to material facts, provide a direct link, title, author or organization, source type, and date; for a material, contested, comparative, or causal conclusion, compare at least two independent sources; do not present correlation as causation;
6. analysis of trade-offs, risks, dependencies, reversibility, scenarios, and sensitivity to key assumptions; separately state which facts or checks could change the recommendation;
7. this required output structure:
   - a concise answer to the decision question;
   - method, criteria, and limitations;
   - a comparison table of options;
   - evidence, assumptions, contradictions, and unknowns;
   - a conditional recommendation with rationale and alternatives;
   - next checks, without carrying out external actions;
8. constraints concerning secrets, personal data, and confidential information, plus a rule not to make the decision, publish, send data, or take external actions without separate permission.

Do not perform the decision analysis yourself and do not replace unknown inputs with assumptions.
```
