# Output Result — Source-Grounded B2B SaaS Expert Research

Run date: 04.08.2026. Baseline: [SOP](../../PLAYBOOK_SOP.md) and [requirements](../../REQUIREMENTS.md).

## Evidence-backed recommendations

- Start an AI agent on a repetitive, rules-based task with a clear return on time; define the outcome, narrow scope, and increase autonomy gradually (source: Dan Martell, [AI agent guide](https://www.danmartell.com/how-to-build-your-first-ai-agent/), 20.07.2026).
- Keep a shared system of record and human-facing controls when multiple agents operate on revenue data (source: Jason Lemkin, [SaaStr article](https://www.saastr.com/3-humans-20-ai-agents-and-yes-we-still-need-real-b2b-software/), 21.07.2026).
- Measure AI visibility through downstream actions and conversions, not mentions alone (source: Ahrefs, [AI Search Trends](https://ahrefs.com/blog/ai-search-trends/), 24.07.2026).
- Treat attribution as incomplete in fragmented buyer journeys and combine channel evidence with audience research (source: Rand Fishkin, [Pinball Buyer Journeys](https://sparktoro.com/blog/the-7-marketing-problems-pinball-shaped-buyer-journeys-create/), 30.11.2025).
- During rollout, make corrections reusable rules and keep a human copied on sensitive outbound actions (source: Jason Lemkin, [AI VP of Finance](https://www.saastr.com/our-new-ai-vp-of-finance-closes-the-deal-sends-the-invoice-and-chases-the-cash-it-took-4-deals-to-train-it/), 26.07.2026).

## Where experts disagree

### 1. AI-first drafting vs human-first thinking

- Dan Martell: use AI for research, drafts, process analysis, and options; humans decide (source: Dan Martell, [LinkedIn post](https://www.linkedin.com/posts/dmartell_a-few-weeks-ago-i-told-my-team-that-ai-needs-activity-7403156286651002880-AbXr); local [capture](../../linkedin-posts/research_output/dmartell-a-few-weeks-ago-i-told-my-team-that-ai-needs-activity-7403156286651002880-abxr/post_research.md)).
- Captured commenter: think and understand the problem first, then use AI to accelerate it (source: same [capture](../../linkedin-posts/research_output/dmartell-a-few-weeks-ago-i-told-my-team-that-ai-needs-activity-7403156286651002880-abxr/post_research.md)).
- Decision: use a staged middle position—human defines the question and rubric, AI accelerates, human approves.

### 2. Raw database vs shared system of record

- Jason Lemkin's source argues for shared systems, workflow controls, permissions, and audit trails when agents operate on business data (source: [SaaStr article](https://www.saastr.com/3-humans-20-ai-agents-and-yes-we-still-need-real-b2b-software/)).
- The opposing position is the “agents plus raw Postgres” approach described and rejected in that same article (source: same [SaaStr article](https://www.saastr.com/3-humans-20-ai-agents-and-yes-we-still-need-real-b2b-software/)).
- Decision: keep a controlled system of record unless a bounded test proves the simpler architecture is safe.

### 3. Citation volume vs business impact

- Ahrefs reports that citation/visibility volume can rise without meaningful business impact (source: [Ahrefs AI Search Trends](https://ahrefs.com/blog/ai-search-trends/)).
- The competing approach is to optimize for AI/search mentions as the main success metric (source: [Ahrefs AI Search Trends](https://ahrefs.com/blog/ai-search-trends/), presented as the industry trend being questioned).
- Decision: use mentions as a diagnostic metric, but judge success by qualified actions and conversions.

## What I rejected and why

1. I rejected Dan Martell's “92% of work” figure as a target because the source does not define the denominator, quality bar, or independent validation (source: [Dan Martell AI agent guide](https://www.danmartell.com/how-to-build-your-first-ai-agent/)).
2. I rejected the old Chris Walker LinkedIn capture as Refine Labs evidence because its text identifies an animation studio and does not prove the listed affiliation (sources: [old capture](../../linkedin-posts/research_output/chris-walker-4850aa14-tuesday-however-the-show-must-go-on-activity-7475111805082796032-rtv/post_research.md); [Refine Labs profile](https://www.refinelabs.com/chris-walker)).
3. I rejected the generated numeric YouTube “pillars” because they are frequency artifacts, not validated themes (source: [YouTube index](../../youtube-transcript/research_output/index.json)).

## My original ideas

Create a claim-quarantine queue between extraction and synthesis. Claims with missing identity, mixed voices, malformed transcripts, or unsupported superlatives cannot become recommendations until verified or downgraded to hypotheses. This idea is not stated in the collected sources; it responds to the repository's concrete extraction failures and is a testable process control, not an expert claim. It could work by making uncertainty visible before it enters the synthesis.

## Who I would NOT recommend following and why

I would not follow any of the 10 people as an unqualified authority. Chris Walker's old capture has an identity conflict; Dan Martell's numerical claims need validation; the other experts now have promising recent candidates but not yet enough locally normalized evidence for a personality-level ranking. Follow claims, not personalities.

## Weaknesses of this playbook

- Many refreshed candidates remain web candidates rather than local raw artifacts.
- Eight source rows use collection pages or profiles and still need exact item URLs.
- Several numbers are self-reported company results, not independent benchmarks.
- The current dataset is too small for causal conclusions about pipeline or revenue.
- Expert disagreement is still partly methodological rather than three fully independent, locally extracted debates.

The unrelated [Running Man YouTube transcript](https://www.youtube.com/watch?v=5iLNKj0qd_0) remains rejected and is not used as evidence. The distribution transcript is also retained only as an unidentified, low-confidence source because its channel name is blank.

## Source and validation records

- [Source refresh](SOURCE_REFRESH.md)
- [Source audit](SOURCE_AUDIT.md)
- [Validation report](VALIDATION_REPORT.md)
