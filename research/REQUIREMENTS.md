# Research Playbook Requirements and Evaluation Baseline

This file is the standing baseline for generating and reviewing the B2B SaaS expert-research Playbook/SOP from this repository.

The stable process is [PLAYBOOK_SOP.md](PLAYBOOK_SOP.md). Run-specific synthesis belongs under `outputs/YYYY-MM-DD/` and must not be appended to the stable SOP.

## Objective

Turn the collected LinkedIn posts and YouTube transcripts into a practical, source-grounded Playbook/SOP for researching and synthesising advice from the chosen B2B SaaS influencers/business people.

The deliverable must separate:

- what a source explicitly says;
- what the analyst infers;
- what the analyst recommends as an original operating choice; and
- what cannot be concluded because the repository lacks evidence.

## Mandatory content

The Playbook/SOP must include:

1. A repeatable workflow from source collection through evidence review, synthesis, publication, and maintenance.
2. A source register with author, source type, URL, date when available, artifact path, identity confidence, and contamination/quality notes.
3. A citation for every recommendation. A recommendation without a source is a defect unless it is explicitly labelled `My original idea` and justified.
4. A section titled `Where experts disagree` with at least three examples. Each example must state Author/Source A's position, Author/Source B's position, and which side the Playbook takes and why.
5. A section titled `What I rejected and why` with at least two source-derived ideas that are excluded, plus clear reasons.
6. A section titled `My original ideas` with at least one idea not found in the collected sources and a rationale for testing it.
7. A section titled `Weaknesses of this playbook` covering untested assumptions, missing evidence, extraction errors, and likely failure modes.
8. A section titled `Who I would NOT recommend following and why`. The answer must account for all 10 names in `sources.md`; where evidence is insufficient, say so rather than inventing a judgement.
9. A final checklist that another researcher can execute without relying on undocumented context.
10. An independent judge/evaluator/validator step that reviews the result after the analyst finishes. The validator must check factual support, attribution, citation coverage, required sections, and hallucination risk, and must be allowed to fail the deliverable.
11. Run isolation: the baseline SOP remains stable; each run stores its result, source register, and validation report in a dated output folder.

## Evidence and citation rules

- Prefer the raw local artifact over a generated summary or heuristic topic/pillar output.
- Cite the original public URL and, where useful, the local artifact. Use dates in `DD.MM.YYYY` format when a source date is actually available; otherwise write `date not captured`.
- Do not attribute a source to an expert merely because a video title resembles that expert's topic. The artifact must identify the channel/author or the attribution must be explicitly marked unverified.
- Treat comments, reposts, and adjacent-page content as separate voices unless the extractor proves they are part of the author's original post.
- Quote only enough text to locate the claim; paraphrase the rest.
- Never turn a heuristic frequency count into a substantive recommendation without checking the transcript segment.
- Record uncertainty, identity conflicts, missing timestamps, missing channel names, and irrelevant sources.

## Quality gates

The analyst must not be the only person or process approving the result. A judge/evaluator/validator performs a separate pass against this file and records `PASS`, `PASS WITH WARNINGS`, or `FAIL` for each gate. A failed gate blocks publication until corrected or explicitly accepted by the project owner.

Before delivery, confirm:

- all 10 names from `sources.md` are present in the source register;
- every actionable recommendation has a nearby citation or is labelled as original;
- at least three disagreements, two rejected ideas, and one original idea are present;
- no conclusion relies on the unrelated Running Man transcript;
- unidentified YouTube videos are not presented as expert evidence;
- the Chris Walker LinkedIn capture is not silently treated as Refine Labs material;
- the Dan Martell capture is separated from apparent comments/reposts;
- the Playbook states what should be re-collected before making stronger expert-level claims;
- the final document is internally consistent and links to the repository artifacts.

The validator must specifically flag:

- claims attributed to an expert whose identity is not proven;
- recommendations without an adjacent source citation or explicit original-idea label;
- source text that appears to contain comments, reposts, or unrelated material;
- unsupported numbers, superlatives, causal claims, and outcome claims;
- required sections that are missing or do not meet their minimum counts;
- conclusions that exceed the current collection's evidence.

## What we evaluate

### Judgment

Does the Playbook make useful choices while respecting the limits of the evidence? Does it decline unsupported conclusions and explain trade-offs?

### Factual accuracy and source skepticism

Are claims traceable to the actual source text? Are identity, date, transcript quality, and extraction contamination handled explicitly?

### Creativity

Does the Playbook add at least one clearly labelled, testable idea that is not merely a restatement of a source?

### Research quality

Are sources diverse enough for the claims made? Are primary artifacts preferred, disagreements genuinely compared, and gaps identified?

### Technical execution

Are the repository pipelines and outputs used correctly? Can a researcher reproduce the workflow, audit the evidence, and detect bad inputs?

### Writing quality

Is the result clear, operational, concise, honest about uncertainty, and usable as an SOP rather than merely a collection of opinions?

### Independent validation

Did a separate judge/evaluator/validator inspect the output against this baseline, record findings, and prevent unsupported claims from being presented as facts? A polished document that fails evidence validation is not complete.
