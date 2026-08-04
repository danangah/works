# Stable SOP: Source-Grounded B2B SaaS Expert Research

This file is the stable operating procedure. Do not append run-specific findings, source candidates, dates, or conclusions here. Each run writes its result under `outputs/YYYY-MM-DD/`.

This SOP is governed by the standing requirements and evaluation baseline in [REQUIREMENTS.md](REQUIREMENTS.md). The requirements define the mandatory content and quality gates; this file defines the repeatable execution procedure.

## 1. Define the research question

Record the audience, company stage, budget, channels, decision to support, and success metric before collecting sources. Keep the question narrow enough to test.

## 2. Apply the bounded collection rule

Use the time window and per-expert ceiling defined in the run request. If unspecified, use the latest three attributable public items per expert from the last 12 months. Record the rule in that run's output folder.

Collect from first-party sites, official author profiles, canonical LinkedIn posts, and canonical YouTube channels. Keep the original URL, author/channel, date, source type, retrieval date, and local artifact path.

## 3. Verify source identity and quality

For each item, record:

`identity | date | completeness | voice boundary | claim type | evidence strength | applicability | status`

Use statuses `ready`, `candidate`, `quarantine`, or `rejected`. Do not attribute an item to a named expert from a similar title alone. Separate author text from comments, reposts, interviewers, and guests. Reject irrelevant material.

Prefer raw post/transcript text over generated summaries or heuristic topic labels. Timestamps are valid only when transcript timing is reliable.

## 4. Extract claims

Create a claim ledger:

`claim_id | claim | author | public URL | local artifact | timestamp/section | claim type | confidence | counterevidence | proposed test`

Classify each claim as direct observation, personal assertion, cited evidence, analyst inference, or original idea. Flag unsupported numbers, superlatives, causal claims, and business outcomes.

## 5. Convert claims into recommendations

Every recommendation must state the action, condition, expected mechanism, success metric, and source citation. A source-free recommendation is allowed only inside a clearly labelled `My original ideas` section.

Use small, reversible tests with a baseline, one changed variable, owner, duration, and stop rule. Do not present a personal result as a universal benchmark.

## 6. Produce the run result

Write the synthesis into `outputs/YYYY-MM-DD/PLAYBOOK_RESULT.md`. It must include:

- evidence-backed recommendations;
- `Where experts disagree` — at least three examples, both positions, and the chosen side;
- `What I rejected and why` — at least two source-derived exclusions;
- `My original ideas` — at least one novel, testable idea;
- `Weaknesses of this playbook`;
- `Who I would NOT recommend following and why`;
- source register and unresolved evidence gaps.

## 7. Independent judge/evaluator/validator

The analyst does not self-approve the result. Run [validate_playbook.py](validate_playbook.py), then perform a separate human or automated review. The validator must be able to return `FAIL`.

Check coverage, citation support, identity, contamination, irrelevant inputs, hallucination risk, disagreement quality, rejected ideas, original ideas, and weaknesses. Any failure blocks release until fixed or explicitly accepted by the project owner.

Save the report in `outputs/YYYY-MM-DD/VALIDATION_REPORT.md`.

## 8. Run handoff

Keep the baseline files unchanged. Add only run-specific artifacts to the dated output folder. Update the SOP only when the process itself changes; record that change separately from any research result.
