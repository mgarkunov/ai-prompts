# Brief and Requirements Prompt

## Context fields

- **Task or problem** — the need, change, or question to address, and why it matters; do not replace the problem with a presumed solution.
- **Desired outcome** — the verifiable effect or artifact the work should produce.
- **Users and stakeholders** — direct users, affected parties, and the approval owner if known.
- **Scope and boundaries** — the objects, processes, or work outputs, plus explicit inclusions and exclusions.
- **Known requirements and evidence** — confirmed conditions, decisions, documents, and data with a source or owner; leave anything unknown as a question or assumption.
- **Definition of done** — observable acceptance conditions and how to check them.
- **Constraints and dependencies** — mandatory limits on time, budget, resources, technology, and rules, plus risks and external dependencies.
- **Required output format** — the language, structure, length, and form of the brief or requirements that suit the intended audience.

Copy the text below and fill in the fields in square brackets. Add or remove fields as needed.

```text
Create a ready-to-use prompt for preparing a task brief and requirements.

Context:
- Task or problem: [need, change, or question]
- Desired outcome: [effect or artifact]
- Users and stakeholders: [users, affected parties, approval owner]
- Scope and boundaries: [objects, inclusions, and exclusions]
- Known requirements and evidence: [confirmed conditions, decisions, documents, data]
- Definition of done: [acceptance conditions and check]
- Constraints and dependencies: [time, budget, resources, technology, rules, risks]
- Required output format: [language, structure, length, and form]

First, assess the inputs. If critical information about the problem, outcome, users, boundaries, approval owner, or format is missing, ask no more than five clarifying questions and stop. Do not create the final prompt until the answers are provided.

If the critical information is sufficient, return only one self-contained prompt in English in a code block, with no explanation before or after it.

The prompt you create must specify:
1. the role of an analyst or facilitator, the objective of the brief, audience, scope, and boundaries of the work;
2. an input structure covering the problem and context, desired outcome, users and scenarios, stakeholders and approval owner, and known requirements and evidence;
3. an explicit distinction between:
   - a confirmed input requirement with a source or owner;
   - an assumption that needs validation;
   - an open question;
   - a decision that a specific owner must make;
   - a risk, dependency, or constraint;
4. this required output structure:
   - a concise brief: problem, objective, and desired outcome;
   - users, audiences, and key scenarios;
   - scope and non-goals;
   - a requirements table: requirement, type, priority, evidence or source, acceptance criterion, and limitation;
   - applicable functional and non-functional requirements;
   - definition of done and verification method;
   - constraints, dependencies, risks, contradictions, and unknowns;
   - questions for owners and the next safe step;
5. quality requirements: write requirements so they are testable and unambiguous; do not invent users, stakeholders, deadlines, budget, technical choices, priorities, or acceptance criteria; when evidence is absent, label the item as a question or assumption;
6. a rule to preserve the boundary between a brief, requirements, recommendations, and the owner's decision; do not turn an assumption into a mandatory requirement;
7. constraints concerning secrets, personal data, and confidential information, plus a rule not to approve, publish, send data, or take external actions without separate permission.

Do not prepare the brief or requirements yourself and do not replace unknown inputs with assumptions.
```
