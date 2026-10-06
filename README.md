<picture>
  <source media="(max-width: 600px)" srcset="assets/soukyu-console-mobile.svg">
  <img src="assets/soukyu-console.svg" width="100%" alt="Soukyu — AI Engineer. 32 owned public repositories total: 15 non-fork repositories including this profile, plus 17 forks; 253 commits, 53 pull requests and 377 contributions. Snapshot 2026-10-07 05:00 ICT (UTC+7).">
</picture>

<p align="center"><sub>Repository count: 15 non-fork public repositories (including this profile) + 17 forks = 32 total.</sub></p>

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

**Selected open upstream work, checked 2026-10-07 05:00 ICT (UTC+7)** — status is shown so open work is not mistaken for merged contributions.

| Project / PR | Focus | Live status |
| --- | --- | --- |
| [LlamaIndex #23299](https://github.com/run-llama/llama_index/pull/23299) | Reject non-positive workflow iteration budgets | Open · review required · no checks reported |
| [NanoCoder #1528](https://github.com/Nano-Collective/nanocoder/pull/1528) | Disclose when LLM summarization falls back | Open · checks passing · review required |
| [Clinical Deep Research #91](https://github.com/BlueRingsLabs/Clinical-Deep-Research_CDR/pull/91) | Structured logs, run IDs, failure levels and regression coverage | Open · 7/7 checks passing · review required |
| [smolagents #2900](https://github.com/huggingface/smolagents/pull/2900) | Review: safe serialization fallback for non-JSON NumPy arrays, including remote-executor coverage | Open · Soukyu submitted APPROVED review at `6287979`; overall review still required · no CI checks; 4 focused local tests and Ruff pass |
| [Tokenizers #2462](https://github.com/huggingface/tokenizers/pull/2462) | Preserve ByteLevel `add_prefix_space` during canonicalization | Open · maintainer said they will review · no CI checks on current head; earlier failure was on an older commit |
| [Chroma #7848](https://github.com/chroma-core/chroma/pull/7848) | Explain embedding-dimension mismatch without assuming its cause | Open · reviewer comment says “Approving at `f1159af`” and reports focused Rust/Python tests pass; formal review decision is blank and no code-test CI is reported |
| [LangChain #41023](https://github.com/langchain-ai/langchain/pull/41023) | Review: prevent `JumpToToolsMiddleware` from bypassing human approval | Open · latest head `b844c7a`; 55 checks passed, 2 skipped; no current issue-link check is reported · maintainer reproduced the issue and committed an execution-time fix; formal review decision pending |
| [Jev RAG #9](https://github.com/aifabrice/jev-rag/pull/9) | Add Windows CLI smoke coverage | Open · changes requested · no checks reported |

Haystack [#12986](https://github.com/deepset-ai/haystack/pull/12986) is not listed as open: the maintainer closed it without merge on 2026-10-01 because it duplicated #13009.

**Merged upstream:** [mcp-memory-service #1334](https://github.com/doobidoo/mcp-memory-service/pull/1334), [#1343](https://github.com/doobidoo/mcp-memory-service/pull/1343) and [#1344](https://github.com/doobidoo/mcp-memory-service/pull/1344), all merged into `main` with maintainer merge commits; [Clinical Deep Research #90](https://github.com/BlueRingsLabs/Clinical-Deep-Research_CDR/pull/90) adds offline regression coverage for long ClinicalTrials.gov query sanitization, [#92](https://github.com/BlueRingsLabs/Clinical-Deep-Research_CDR/pull/92) aligns critique output with the current schema, and [#118](https://github.com/BlueRingsLabs/Clinical-Deep-Research_CDR/pull/118) uses the `SpanStatus.ERROR` enum for Risk of Bias 2 error spans (all merged 2026-09-30 UTC).

**Review feedback incorporated in upstream work:** In [mcp-memory-service #1449](https://github.com/doobidoo/mcp-memory-service/pull/1449), I flagged that prior search queries could reach the LLM provider and response snapshot; the author added allow-listed fields and regression coverage, and the maintainer merged it. In [Semantic Kernel #14532](https://github.com/microsoft/semantic-kernel/pull/14532), the author adopted my feedback on URL-only `ImageContent` and inferred MIME types in `7a5b3eb` and `727e1a7`; after my follow-up about unsupported SVG/BMP types, the author added explicit rejection and two regression tests in `dfe3f5f9`. These are review contributions, not code I authored; #14532 remains open, review-required and behind its base, with only label and CLA checks reported. In [LangChain #41023](https://github.com/langchain-ai/langchain/pull/41023), I reported that `JumpToToolsMiddleware` could execute a tool call before human review when middleware order was reversed. The maintainer reproduced it and added execution-time gating plus regression coverage in `be32874`; this is review feedback, not code I authored, and the upstream PR remains open. In [smolagents #2900](https://github.com/huggingface/smolagents/pull/2900), the author added the requested NumPy dtype, safe-only and `RemotePythonExecutor` regression tests in `6287979`. I independently ran the four focused regressions on Python 3.12 and Ruff lint/format on the four changed files; they passed locally, and I submitted an APPROVED review for that head. GitHub still reports no CI checks, the full suite was not run, and the PR remains open and review-required.

The #92 validation also surfaced an invalid mypy override; the separate [CDR #95](https://github.com/BlueRingsLabs/Clinical-Deep-Research_CDR/pull/95) fix corrected it and credits the report from #92.

**Technical discussions and design work:** [Haystack #12969](https://github.com/deepset-ai/haystack/discussions/12969#discussioncomment-18623580) proposes a fail-closed context-budget guard for RAG; [Jev RAG #5](https://github.com/aifabrice/jev-rag/issues/5#issuecomment-5855272663) proposes an opt-in OCR adapter with page-aware citations and explicit privacy boundaries; [mcp-memory-service #1345](https://github.com/doobidoo/mcp-memory-service/issues/1345#issuecomment-5855848041) proposes idempotent event-log sync and embedding-consistency invariants. RFC author `filhocf` confirmed the invariants were incorporated into the [v0.3 draft](https://github.com/filhocf/mcp-memory-service/blob/doc/rfc-delta-sync-invariants/docs/rfc/rfc-delta-sync.md) (design-only). In the maintainer's [#1304 phased delivery plan](https://github.com/doobidoo/mcp-memory-service/issues/1304#issuecomment-6020517402), the event-log work in #1345 is explicitly gated until the self-hosted secondary contract is integrated; the maintainer plans to open Phase 1 first. The follow-on [RFC PR #4](https://github.com/filhocf/mcp-memory-service/pull/4) on `filhocf`'s fork details alternatives, migration rules, backend scope and the first-PR boundary; the maintainer reopened it after an accidental closure, praised the revision and said they would like to land it. It remains open on that fork and is not merged into upstream `doobidoo/mcp-memory-service`.

**GitHub contribution snapshot (GraphQL, rechecked 2026-10-07 05:00 ICT / 2026-10-06 22:00 UTC):** 32 owned public repositories total: 15 non-fork repositories including this profile, plus 17 forks; 377 contributions in the exact preceding 365 days, including 253 commits, 53 pull-request contributions, 8 reviews and 2 issues. These are GitHub activity counters, not a count of merged PRs or a skills score. The values match the artwork snapshot below.

The console artwork above reflects the 2026-10-07 05:00 ICT snapshot: 31 other owned public repositories besides this profile, including 17 forks; 253 commits, 53 pull requests and 377 contributions. The activity/language panel remains a historical 2026-09-28 snapshot. Language shares use bytes from public owned repos, excluding forks and this profile, and are not proficiency scores.

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
