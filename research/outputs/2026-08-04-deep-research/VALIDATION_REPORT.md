# Independent validation report

Run date: 04.08.2026  
Command: `python3 validate_playbook.py --output-dir outputs/2026-08-04-deep-research`

## Automated decision

**PASS WITH WARNINGS** — 17 checks passed, 0 failed.

Passed gates:

- required sections are present;
- at least three disagreement entries are present;
- at least two rejected ideas are present;
- the original idea is labelled and justified;
- ten distinct experts are present in the fresh source register;
- public LinkedIn and YouTube links are present;
- no expert exceeds the three-source ceiling;
- date window, candidate status, quarantine, and identity uncertainty are documented;
- irrelevant or weak material is explicitly rejected/quarantined;
- the blocking validator policy is present.

## Human-review warnings

1. Dave Gerhardt and Devin Reed remain candidate-only because the captured material does not preserve enough full post text and voice boundary.
2. SaaStr entries are editorial/company sources; they should not be silently treated as Jason Lemkin's individual words.
3. Several claims are expert assertions, predictions, interviews, surveys, or anecdotes rather than independent causal evidence.
4. The ten-interview threshold, 30-day schedule, evidence-debt budget, and other operating constraints are analyst-designed tests, not source-proven benchmarks.
5. Before publication to an external audience, manually open every cited page and verify the cited claim, date, and speaker identity.

## Release decision

Release for bounded internal experimentation only. Do not present the result as proof that any expert's tactic will produce a particular business outcome. Re-run the validator after any edit to the result or source register.
