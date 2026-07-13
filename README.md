<!--
DRAFT — profile README for collinbentley1/collinbentley1. The repo does NOT exist
(confirmed 404, 2026-07-07) and is NOT created tonight. Do not publish until:
(1) Collin's voice pass on every TODO(collin);
(2) WS-B secret scans (trufflehog + gitleaks + org-ref grep) complete and clean;
(3) Collin creates the repo himself.
Every claim cites a FACTS.md ID in an HTML comment. All URLs verified resolving
(HTTP 200) on 2026-07-07. Style per STYLE.md: dry, plain, exact numbers, no badges.
-->

# Collin Bentley

Product leader who ships with agent teams. <!-- A1 -->

<!-- TODO(collin): voice pass on this paragraph. It is a condensed A1 (approved frame); tighten or loosen, don't add claims. -->
I run engineering the way 2026 actually works: I direct agent teams — Claude Code,
Codex, a custom release bot — through a system I built for exactly that: isolated
worktree runtimes with their own databases and live MCP tunnels, five AI reviewers
plus mandatory human approval on every PR, contract tests and SHA-pinned CI as the
guardrails. <!-- A1 --> Claude is my #3 contributor by name, because provenance
should be auditable. <!-- A1 --> The result: three founders shipped a
contract-tested, multi-tenant in-chat commerce platform to a live operator in
31 days. <!-- A1; 31-day receipt: F4 --> My 2020 repo shows I can write every line
myself; my 2026 repos show why I usually shouldn't. <!-- A1; 2020 anchor: F9 -->

## Live right now

<!-- Table sourced from F10 (BULLETPROOF); all four URLs verified 2026-07-07.
     Row receipts:
     - cdbentley.com — F10 (932-line zero-dependency TS scroll engine, reduced-motion support)
     - medlock.ai — F10, S3 (MCP server live Jul 2025), R8 (Streamable HTTP initialize verified by live probe)
       NOTE: F10's endpoint discrepancy is RESOLVED (July 7, WS-G live probes): the citable MCP endpoint is https://medlock.ai/api/mcp; bare mcp.medlock.ai is NOT an endpoint. If an endpoint URL is ever added here, use https://medlock.ai/api/mcp. Per the same F10 note, /api/mcp has no application-level rate limit — say "origin/host allow-listing + bearer auth" for the MCP surface, not "rate-limited."
     - runsetta.com — F10 (server-side PKCE token exchange; physiological-bounds Zod contracts)
     - ycriticalhistory.org — F9 (hand-built 2020; re-platformed 2026 with tests; "six months" phrasing per F9 discrepancy note — do not print a commit count)
     Stack column: GitHub primaryLanguage per `gh repo list` metadata, verified 2026-07-07; "Bun" from runsetta's own repo description, same check. -->

| Site | What it is | Stack |
| --- | --- | --- |
| [cdbentley.com](https://cdbentley.com) | Personal site. Zero-dependency 932-line scroll engine; reduced-motion support | TypeScript |
| [medlock.ai](https://medlock.ai) | Production MCP server: Streamable HTTP, bearer auth, origin allow-listing — and an honest demo-data disclosure up front | TypeScript |
| [runsetta.com](https://runsetta.com) | Running companion: server-side PKCE token exchange, physiological-bounds Zod contracts | TypeScript · Bun |
| [ycriticalhistory.org](https://ycriticalhistory.org) | Civic-history map of Yale/New Haven activism sites. Built by hand over six months in 2020; re-platformed 2026 with tests | TypeScript |

## Timeline receipts

<!-- Receipts per spec: the four dated items below, S1–S3 only. S2 (Healthyr) is
     NEEDS-CAVEAT and deliberately omitted from this section. -->

- **Jun 2023** — public fork of Vercel's `ai-chatbot`, ~7 months after ChatGPT
  shipped, while building enterprise LLM products inside a Fortune-50 payer.
  <!-- S1 (DEFENSIBLE: fork date public; employer work internal) -->
- **Jan 2024** — LangServe app, ~3 months after LangServe's release. <!-- S1 -->
- **Jul 2025** — production MCP server live at medlock.ai, eight months after
  Anthropic shipped MCP. <!-- S3 (BULLETPROOF) -->
- **2026** — Visit Emery ChatGPT app approved by OpenAI and published to the app
  directory within ~5 months of the directory opening; withdrawn when the company
  dissolved. <!-- S3; published-then-withdrawn stated honestly per C14 -->

## How I work

Agents build; humans approve. Every PR carries mandatory human approval, and PR
descriptions include a Validation section listing the exact commands run
("139 passed"). <!-- A2 --> Deployment topology is injected into agent review
prompts ("review for issues on a min-3-replica autoscaled backend"). <!-- A2 -->
When we pivoted, it went out as 24 atomic, individually verified commits.
<!-- A2 -->

One note on the contribution graph: I ship in focused bursts around products —
132 PRs in 9.5 weeks during the last one. <!-- burst line per github_presence_plan.md 1.1; receipt: F4 (BULLETPROOF) -->

<!-- TODO(collin): optional one line on what you're looking for right now. Keep it to facts you'd say out loud in an interview. -->

## Contact

- [cdbentley.com](https://cdbentley.com) <!-- resolves 200, verified 2026-07-07 -->
- [linkedin.com/in/collinbentley](https://www.linkedin.com/in/collinbentley)
  <!-- verified from repo source (cdbentley content/site.ts:8) AND resolves 200, 2026-07-07 -->
- collin.bentley@me.com <!-- TODO(collin): confirm this is the public-facing address you want on GitHub; not sourced from FACTS.md -->
