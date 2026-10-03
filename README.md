<picture>
  <source media="(max-width: 600px)" srcset="assets/soukyu-console-mobile.svg">
  <img src="assets/soukyu-console.svg" width="100%" alt="Soukyu — AI Engineer. 30 public repos including this profile, 249 commits, 46 pull requests and 355 contributions. Snapshot 2026-09-30 08:49 UTC.">
</picture>

<picture>
  <source media="(max-width: 600px)" srcset="assets/soukyu-activity-mobile.svg">
  <img src="assets/soukyu-activity.svg" width="100%" alt="GitHub activity and language shares. Snapshot 2026-09-28. Public language bytes, excluding forks, not skill ratings.">
</picture>

<a href="https://github.com/ducanhnguyen223/opsdesk">
<picture>
  <source media="(max-width: 600px)" srcset="assets/soukyu-opsdesk-mobile.svg">
  <img src="assets/soukyu-opsdesk.svg" width="100%" alt="OpsDesk: Turns shipment exceptions into sourced next actions an operator can review. PUBLIC / DEMO. Open repository.">
</picture>
</a>

<a href="https://github.com/ducanhnguyen223/llm-reliability-bench">
<picture>
  <source media="(max-width: 600px)" srcset="assets/soukyu-bench-mobile.svg">
  <img src="assets/soukyu-bench.svg" width="100%" alt="LLM Reliability &amp; Cache Bench: Tests whether a cached answer is still safe after its context or permissions change. PUBLIC / OFFLINE. Open repository.">
</picture>
</a>

<picture>
  <source media="(max-width: 600px)" srcset="assets/soukyu-vanban-mobile.svg">
  <img src="assets/soukyu-vanban.svg" width="100%" alt="VanBanAI: Brings source retrieval, structured drafting and Word/PDF export into one review flow. Private, in development.">
</picture>

<p align="center"><a href="mailto:ducanhtq88@gmail.com">GET IN TOUCH ↗</a> · <a href="https://github.com/ducanhnguyen223?tab=repositories">EXPLORE REPOSITORIES ↗</a></p>

<details>
<summary>Profile as text · evidence & links</summary>

## Soukyu / AI Engineer

I build LLM applications around business context, tools and human review.

**Focus:** RAG and retrieval, structured outputs, MCP and scoped tools, evaluation and caching.

**Stack:** Python · TypeScript · Node.js · FastAPI · PostgreSQL · SQLite · Docker · GitHub Actions · Git · Linux.

**Evidence tooling:** [GitHub Profile Audit](https://github.com/ducanhnguyen223/github-profile-audit) — read-only checks for public repository and profile-README consistency, with tests and CI.

**Selected open upstream PRs (checked 2026-10-03 UTC; none are merged claims):** [LlamaIndex #23299](https://github.com/run-llama/llama_index/pull/23299) validates non-positive workflow iteration budgets; [NanoCoder #1528](https://github.com/Nano-Collective/nanocoder/pull/1528) makes an LLM-summary fallback visible; [Pydantic AI #8955](https://github.com/pydantic/pydantic-ai/pull/8955) clarifies agent persistence and sandbox docs; [Clinical Deep Research #91](https://github.com/BlueRingsLabs/Clinical-Deep-Research_CDR/pull/91) uses structured logs, surfaces run IDs and failed checks at appropriate levels, and adds a regression assertion; [Chroma #7848](https://github.com/chroma-core/chroma/pull/7848) clarifies embedding-dimension mismatch guidance without assuming the cause; [Jev RAG #9](https://github.com/aifabrice/jev-rag/pull/9) adds Windows CLI smoke coverage (maintainer changes requested). These are selected open submissions, not merged contributions.

Haystack [#12986](https://github.com/deepset-ai/haystack/pull/12986) is not listed as open: the maintainer closed it without merge on 2026-10-01 because it duplicated #13009.

**Merged upstream:** [mcp-memory-service #1334](https://github.com/doobidoo/mcp-memory-service/pull/1334), [#1343](https://github.com/doobidoo/mcp-memory-service/pull/1343) and [#1344](https://github.com/doobidoo/mcp-memory-service/pull/1344), all merged into `main` with maintainer merge commits; [Clinical Deep Research #90](https://github.com/BlueRingsLabs/Clinical-Deep-Research_CDR/pull/90) adds offline regression coverage for long ClinicalTrials.gov query sanitization, [#92](https://github.com/BlueRingsLabs/Clinical-Deep-Research_CDR/pull/92) aligns critique output with the current schema, and [#118](https://github.com/BlueRingsLabs/Clinical-Deep-Research_CDR/pull/118) uses the `SpanStatus.ERROR` enum for Risk of Bias 2 error spans (all merged 2026-09-30 UTC).

The #92 validation also surfaced an invalid mypy override; the separate [CDR #95](https://github.com/BlueRingsLabs/Clinical-Deep-Research_CDR/pull/95) fix corrected it and credits the report from #92.

**Technical discussions:** [Haystack #12969](https://github.com/deepset-ai/haystack/discussions/12969#discussioncomment-18623580) proposes a fail-closed context-budget guard for RAG; [Jev RAG #5](https://github.com/aifabrice/jev-rag/issues/5#issuecomment-5855272663) proposes an opt-in OCR adapter with page-aware citations and explicit privacy boundaries; [mcp-memory-service #1345](https://github.com/doobidoo/mcp-memory-service/issues/1345#issuecomment-5855848041) proposes idempotent event-log sync and embedding-consistency invariants. RFC author `filhocf` confirmed the invariants were incorporated into the [v0.3 draft](https://github.com/filhocf/mcp-memory-service/blob/doc/rfc-delta-sync-invariants/docs/rfc/rfc-delta-sync.md) (design-only). These discussions are proposals, not merged implementations.

**Latest GitHub snapshot (GraphQL, 2026-10-03 19:25 UTC):** 31 public repos including this profile; 251 commit contributions, 46 pull-request contributions, 2 reviews, 2 issues and 359 total contributions in the trailing year. These are GitHub activity counters, not a count of merged PRs or a skills score.

The console artwork above is a separately dated 2026-09-30 snapshot (30 public repos, 249 commits, 46 pull requests and 355 contributions); the activity/language panel is a 2026-09-28 snapshot. Language shares use bytes from public owned repos, excluding forks and this profile, and are not proficiency scores.

### [OpsDesk](https://github.com/ducanhnguyen223/opsdesk)

Turns shipment exceptions into sourced next actions an operator can review.

Python · FastAPI · SQLite · MCP. Simulated operations · scoped access · human approval.

The separate Agent Gym prototype checks evidence-grounded tool-use proposals against synthetic cases, including policy citations, tenant scope and forbidden-action attempts. It is offline and does not claim live-model quality. [Implementation and limits](https://github.com/ducanhnguyen223/opsdesk/blob/main/docs/AGENT_GYM.md).

### [LLM Reliability & Cache Bench](https://github.com/ducanhnguyen223/llm-reliability-bench)

Tests whether a cached answer is still safe after its context or permissions change.

Python · Evaluation · Cache invalidation. Reproducible cases · exact / semantic / dependency-aware.

### VanBanAI

Brings source retrieval, structured drafting and Word/PDF export into one review flow.

TypeScript · Node.js · Zod · RAG. In development · legal-source validation remains ongoing.

[Email](mailto:ducanhtq88@gmail.com) · [Repositories](https://github.com/ducanhnguyen223?tab=repositories)

</details>
