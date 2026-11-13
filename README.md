# 👋 Hi, I'm Rene Turcios


**Vibe coder. Agent-native dev.** SF AI product builder and founder of **Xod**, **Clipwise**, and **[Internet of Things](https://github.com/CloudCorpRecords/internet-of-things)**: 1,000 open source tools, rebuilt from scratch as one verifiable tool layer for agents. I take an idea from prompt to shipped, tested, published software — solo, fast, in whatever lane the problem is in: full-stack product, MCP servers and agents, dev tools, security tooling, local/Mac AI, fine-tuning, data indexes, interactive demos.

Agent-native is my discipline, not a shortcut: agents build with me, but nothing carries my name until it is tested, verified against the real thing, and shipped. The proof is below — every number is checkable.

Replit Ambassador since September 2025 (top 1% Replit user). I also teach this way of building: 200+ hackathons, hands-on workshops across the Bay Area, 48 events hosted, and mentoring for non-technical founders.

## 📈 The proof (Nov 12, 2026)

- **192 open-source PRs authored into other people's projects, 59 merged, 103 open** — every one vetted by my own tool first, every number checkable from [my pull requests](https://github.com/pulls?q=is%3Apr+author%3ACloudCorpRecords)
- **Internet of Things: 1,003 tools built and parity-validated, 51 published and verified live** on GitHub, npm, GHCR and the MCP Registry (scoreboard as of Nov 1, 2026 — built and published are separate numbers on purpose, and the published count moves only on verified read-back)
- **689 public repos** on this profile: the tool fleet, products, indexes, and prototypes I built to prove a point before an interview ever asked
- **Greenlight: 1,268 tests, 33 MCP tools**, plus an [Agent Policy Index](https://cloudcorprecords.github.io/greenlight/policy.html) mapping how repos gate or ban agent contributions
- **Xod v1.1.3** shipped and verified; **Greenlight v0.26.0** is the current release

**Try the flagship in one command:** `npx @reneturcios/greenlight` — or `docker run --rm -i ghcr.io/cloudcorprecords/greenlight mcp`

**Hiring:** I'm open to Forward Deployed Engineer, Applied AI, DevRel, and Software Engineer (full-stack / product / dev tools) roles — US remote or San Francisco. My hireable flag is on. Reach me on [LinkedIn](https://www.linkedin.com/in/reneturcios) or follow the search live on my **[Job Search Tracker](https://cloudcorprecords.github.io/job-search-tracker/)**.

**If you try something here:** [follow me on GitHub](https://github.com/CloudCorpRecords) for the next tool, and star [Greenlight](https://github.com/CloudCorpRecords/greenlight) if it saved you a weekend — stars are how this work gets found.


## Already ready

Before interviews and take-homes, I build the thing: independent prototypes against the public APIs, docs, and problems of the companies I want to work for. Each one is original code, test-verified, and labeled independent and unaffiliated in its own repo.

- [adyen-payments-demo](https://github.com/CloudCorpRecords/adyen-payments-demo) - DevRel prototype of an Adyen-style payments flow, simulated payments from public docs
- [context-budget-analyzer](https://github.com/CloudCorpRecords/context-budget-analyzer) - scans a codebase and estimates what each file costs an AI coding agent in context
- [healthcare-doc-pipeline](https://github.com/CloudCorpRecords/healthcare-doc-pipeline) - synthetic discharge notes in, redacted validated structured JSON out
- [lab-experiment-console](https://github.com/CloudCorpRecords/lab-experiment-console) - console for tracking autonomous lab experiment runs, simulated data
- [agent-eval-harness](https://github.com/CloudCorpRecords/agent-eval-harness) - deterministic agent eval harness with experiment tracking, simulated agents
- [identity-admin-kit](https://github.com/CloudCorpRecords/identity-admin-kit) - enterprise identity admin patterns: SSO setup flow, directory sync, audit log
- [restaurant-api-devex-kit](https://github.com/CloudCorpRecords/restaurant-api-devex-kit) - simulated restaurant ordering API with a tested quickstart and error guide
- [video-job-console](https://github.com/CloudCorpRecords/video-job-console) - generative video job queue console with simulated worker and credit costing
- [video-evidence-search](https://github.com/CloudCorpRecords/video-evidence-search) - video evidence search and grounded QA over timestamped segments, synthetic corpus
- [anthropic-perf-takehome-attempt](https://github.com/CloudCorpRecords/anthropic-perf-takehome-attempt) - Anthropic's publicly released retired performance take-home: 147,734 down to 2,819 cycles (52.4x), correctness verified with their harness

More pre-built work is held privately for take-home stages.

### Live interview demos

Solutions built live during technical interviews, AI-assisted with the use disclosed, then cleaned up and test-verified.

- [password-validation](https://github.com/CloudCorpRecords/password-validation) - HackerRank live interview problem, solved in TypeScript, Python, C++, Go, Java, Rust and Ruby: per-language unit tests, 8 shared golden cases, CI-recorded video proof


## 📊 My job search, live

I track every application and every open-source PR in public. The **[Job Search Tracker](https://cloudcorprecords.github.io/job-search-tracker/)** streams straight from my tracking sheets, with searchable tables, status breakdowns and daily activity. ([source](https://github.com/CloudCorpRecords/job-search-tracker))

## ⭐ Flagship projects

<table>
<tr>
<td width="50%" valign="top">

### [🌙 Xod](https://github.com/CloudCorpRecords/xod)

**A private AI that works on your Mac.** It researches, works with your files, runs jobs in the background, and asks before it acts. Runs locally with no account and no telemetry.

<a href="https://github.com/CloudCorpRecords/xod"><img src="https://github.com/CloudCorpRecords/xod/raw/main/docs/media/moon.gif" width="160" alt="Xod's moon companion"></a>

[**Download for Mac**](https://github.com/CloudCorpRecords/xod/releases/latest) (current release: [v1.1.3](https://github.com/CloudCorpRecords/xod/releases/tag/v1.1.3)) · [Contribute](https://github.com/CloudCorpRecords/xod/blob/main/.github/CONTRIBUTING.md) · [Discussions](https://github.com/CloudCorpRecords/xod/discussions) · [Roadmap](https://github.com/CloudCorpRecords/xod/blob/main/docs/ROADMAP.md)

`Python` `Electron` `MCP` `MLX` `Ollama`

</td>
<td width="50%" valign="top">

### [🚂 TrainerBoi](https://github.com/CloudCorpRecords/trainerboi)

**Train your own AI on your own computer.** A no-code desktop studio for fine-tuning LLMs on your NVIDIA GPU: guided training, a data doctor, SFT / LoRA / DPO / GRPO and more, no cloud needed.

<a href="https://github.com/CloudCorpRecords/trainerboi"><img src="https://github.com/CloudCorpRecords/trainerboi/raw/main/desktop/assets/icon.png" width="96" alt="TrainerBoi icon"></a>

[**Get started**](https://github.com/CloudCorpRecords/trainerboi#install) · [Contribute](https://github.com/CloudCorpRecords/trainerboi/blob/main/CONTRIBUTING.md) · [Discussions](https://github.com/CloudCorpRecords/trainerboi/discussions) · [Good first issues](https://github.com/CloudCorpRecords/trainerboi/labels/good%20first%20issue)

`PyTorch` `Transformers` `TRL` `React` `Electron`

</td>
</tr>
</table>

### [🌐 Internet of Things](https://github.com/CloudCorpRecords/internet-of-things)

**1,000 open tools, one builder, all verifiable.** Agents do their work through tools written by other people, and every tool is a door. I rebuilt that layer from scratch: one source of truth, one standard, everything open source, and every release verified against public surfaces I do not control (GitHub, npm, GHCR, the MCP Registry) before it counts. 1,003 tools built and parity-validated; 51 published and verified live as of the Nov 1, 2026 [public scoreboard](https://github.com/CloudCorpRecords/internet-of-things/blob/main/scoreboard.md), with the publish train still running. The claim is never trust me. The claim is verify it yourself: start with the [verification one-pager](https://github.com/CloudCorpRecords/internet-of-things/blob/main/verification-one-pager.md).

`MCP` `TypeScript` `Python` `npm` `GHCR` `Supply Chain Security`

### [🟢 Greenlight](https://github.com/CloudCorpRecords/greenlight)

**The pre-flight and coordination layer for open-source contribution.** It answers the questions no other tool answers: is this issue secretly taken, does this repo's policy allow your PR, who else is racing you. Timeline X-Ray deep-verifies issues against their timelines; friction scores and an Agent Policy Index decode each repo's gates; PR Radar clusters duplicate and competing PRs across a repo's whole queue; PR Brief writes an evidence-verified review brief for any PR. Racecheck searches open PRs by problem words, so a competing PR does not stay hidden just because it never linked the issue. Ships as a CLI and an MCP server with 33 tools, born from vetting real issues by hand, then automated end to end. 1,268 tests, CI green on Node 20 and 24.

[**Release v0.26.0**](https://github.com/CloudCorpRecords/greenlight/releases/tag/v0.26.0)

**Set up your agent in one command:** `npx @reneturcios/greenlight init --agent claude-code` (also Cursor, Copilot, Windsurf, Cline). Prefer containers? All five tools ship as images: `docker run --rm -i ghcr.io/cloudcorprecords/greenlight:0.26.0 mcp`. The toolkit packages are on npm under `@reneturcios/` and listed in the [official MCP Registry](https://registry.modelcontextprotocol.io) as io.github.CloudCorpRecords/greenlight, prwatch, claimcheck, gatefile, shipcheck, cidiff and reprocheck.

It also runs the pipeline after the verdict: claim comments with repo conventions baked in, CI pre-flight that runs a repo's checks locally before you push, CI failure triage (yours vs pre-existing), review-response triage (real findings vs bot noise, drafts only), a maintainer guard Action with opt-in Autopilot labels, repo digests that arbitrate duplicate-PR races, a PR babysitter that watches your open PRs, honest base-vs-head test verification, and evidence packs that cite every claim they make.

Newest: **PR Radar**, which clusters a repo's open PRs into duplicate and competing sets with a labeled keep heuristic (its first live run found two PRs closing the same issue that nobody had connected), and **PR Brief**, a one-screen verified brief for any PR: change shape, CI base-vs-head, findings classified against evidence. Plus the **Claim Protocol**, an open spec for claiming issues with expiring leases and a public queue, with a live [Claim Ledger](https://cloudcorprecords.github.io/claim-ledger/) and a [hosted pre-flight API](https://claim-api-wine.vercel.app). And optional **AI claim detection**: with a Fireworks key set, a cheap model reads the comments the patterns cannot parse and flags hidden claims with the quote as evidence (it can only ever make a verdict more careful, never more confident). Field data lives on the [Contribution Friction Index](https://cloudcorprecords.github.io/greenlight/) and the [Agent Policy Index](https://cloudcorprecords.github.io/greenlight/policy.html).

Greenlight runs my own contribution campaign: 192 PRs authored into other people's projects so far, 59 merged, every one of them vetted by the tool first.

`TypeScript` `MCP` `CLI` `GitHub API`

Greenlight is one of four tools I built out of a single day of real open-source contribution work, one per stage of the lifecycle:

- **[prwatch](https://github.com/CloudCorpRecords/prwatch)**: after you submit. Ranks your open PRs by what needs attention (changes requested, unresolved threads, real failing checks, conflicts, reviewer silence), with external blockers like Vercel authorization classified separately
- **[claimcheck](https://github.com/CloudCorpRecords/claimcheck)**: while you work. Finds stale issue claims aging with no PR, and parked fixes: finished work on fork branches that never became a PR
- **[gatefile](https://github.com/CloudCorpRecords/gatefile)**: for maintainers. Extracts a repo's hidden contribution gates from its docs into a machine-readable contribution-gates.json, with a drift validator for CI

Three more tools joined the family in October 2026, each an npm package and MCP server too:

- **[shipcheck](https://github.com/CloudCorpRecords/shipcheck)**: release verification. Git tag, GitHub release, npm, MCP Registry and GHCR must all agree on the same version, or it is a NO-GO
- **[cidiff](https://github.com/CloudCorpRecords/cidiff)**: base-vs-head CI differ for PRs. Sorts failing checks into introduced by you, pre-existing, external, or fixed by you
- **[reprocheck](https://github.com/CloudCorpRecords/reprocheck)**: red-first repro verifier. A fix only counts when the repro fails on the base code and passes on the fix

Adjacent to the toolkit: **[pkgverdict](https://github.com/CloudCorpRecords/pkgverdict)** — pre-install verdicts for npm packages (GO / RISKY / FAKE / MISSING), built for humans and AI agents.



### [🛡️ Security Wave](https://github.com/CloudCorpRecords/security-wave)

**Local security checks for the repos an AI agent is about to trust.** Greenlight checks if an agent may contribute. The Security Wave checks if the repo an agent touches is trying to rob it. Each tool is one small deterministic CLI and MCP server in a single binary, on npm under `@reneturcios/` and in the official MCP Registry.

- **[hookcheck](https://github.com/CloudCorpRecords/hookcheck)** (v0.1.16): audits install hooks and agent autostart persistence in a repo (postinstall scripts, .claude hooks, .vscode tasks) for supply-chain backdoors
- **[actionpin](https://github.com/CloudCorpRecords/actionpin)** (v0.1.6): audits GitHub Actions for mutable refs and pins them to full SHAs, so a moved tag cannot change what your CI runs
- **[injectcheck](https://github.com/CloudCorpRecords/injectcheck)** (v0.1.13): scans issues, PRs, docs and files an agent will read for prompt injection before the agent sees them
- **[tracewatch](https://github.com/CloudCorpRecords/tracewatch)** (v0.1.0): tracks security scans over time, diffs findings, blames the commit that introduced each one, and watches repos with measured time-to-detect
- **[mcpvet](https://github.com/CloudCorpRecords/mcpvet)** (v0.1.0): vets MCP servers and agent skills before you install them, auditing server and client configs, autostart entries, declared capabilities and bundled scripts for credential stealers, droppers and persistence shapes
- **[depguard](https://github.com/CloudCorpRecords/depguard)** (v0.1.0): dependency early warning at PR time: diffs package.json and lockfiles and flags new dependencies, newly added install scripts and typosquat-shaped names before the change merges
- **[flowcheck](https://github.com/CloudCorpRecords/flowcheck)** (v0.1.0): GitHub Actions least-privilege audit covering missing or write-all permissions, pull_request_target shapes, and secrets exposed to fork contexts

Validated in the open: the wave closed Round 4 SOLID with zero problems open and a 223-check regression corpus passing on the published binaries. Live proof, updated by the tools themselves every 15 minutes: the [Live Danger Board](https://cloudcorprecords.github.io/security-wave/).

`TypeScript` `MCP` `CLI` `GitHub Actions` `Supply Chain Security`


## 🤝 Join in

Both flagship projects are MIT-licensed and open to contributors of every level, including first-timers.

- ⭐ **Star or watch** [Xod](https://github.com/CloudCorpRecords/xod) and [TrainerBoi](https://github.com/CloudCorpRecords/trainerboi) to follow along, and **follow me** here on GitHub for new builds.
- 🐣 **Make your first PR** by picking a [good first issue in Xod](https://github.com/CloudCorpRecords/xod/labels/good%20first%20issue) or [in TrainerBoi](https://github.com/CloudCorpRecords/trainerboi/labels/good%20first%20issue). Comment on it and I'll help you get set up.
- 💬 **Ask, share or suggest** in [Xod Discussions](https://github.com/CloudCorpRecords/xod/discussions) or [TrainerBoi Discussions](https://github.com/CloudCorpRecords/trainerboi/discussions).
- 🐛 **Found a bug?** Open an issue on [Xod](https://github.com/CloudCorpRecords/xod/issues/new/choose) or [TrainerBoi](https://github.com/CloudCorpRecords/trainerboi/issues/new/choose).


## More builds

- **[Clipwise](https://github.com/CloudCorpRecords/cliqwise)** — MCP-first AI video clipping: submit a long video, get captioned vertical clips back, each moment scored for hook, story and payoff. Agents can drive the whole pipeline over MCP. Live: [clipwise.replit.app](https://clipwise.replit.app)
- **[SudoHired](https://github.com/CloudCorpRecords/sudohired)** — AI platform for automated technology recruiting
- **TaskCato** — an accessible agent harness that lets everyday users run AI agents on projects and workflow automation
- **Agentcies** — an AI agent platform for small businesses, with infrastructure for agent-to-agent communication
- **[mcp-directory](https://github.com/CloudCorpRecords/mcp-directory)** — searchable directory of MCP servers with a live in-browser playground: connect to any server and call its tools, no install needed
- **[agent-evals](https://github.com/CloudCorpRecords/agent-evals)** — open eval harness + leaderboard: point it at any AI agent, get scored on tool-use, accuracy, and latency
- **[mcp-job-tracker](https://github.com/CloudCorpRecords/mcp-job-tracker)** — MCP server over a job-application tracker: ask Claude about your pipeline, find stale leads, check reply status
- **[resume-sync](https://github.com/CloudCorpRecords/resume-sync)** — CLI that regenerates your resume's Projects section from GitHub pinned repos, as Markdown or DOCX
- **[AI-Course-Creator](https://github.com/CloudCorpRecords/AI-Course-Creator)** — a complete course on building software with AI, the same material I teach in workshops
- **[system-monitor](https://github.com/CloudCorpRecords/system-monitor)** — macOS system monitor with a built-in agentic AI assistant (Ollama), live CPU, memory, disk, network and battery views


## Open source contributions

- **IBM ContextForge**: [#180](https://github.com/contextforge-org/contextforge-web-ui/pull/180), [#181](https://github.com/contextforge-org/contextforge-web-ui/pull/181), [#191](https://github.com/contextforge-org/contextforge-web-ui/pull/191), [#194](https://github.com/contextforge-org/contextforge-web-ui/pull/194) (all merged): moved the server test panel, the prompt and resource argument forms, and the auth screens onto the shared accessible `Field` component, with the tests and i18n cleanup that go with it; fixed the CF icon flicker on the Servers page with a targeted single-server patch
- **Sage**: [#302](https://github.com/ZHangZHengEric/Sage/pull/302) (merged): extended the docs link checker to cover the knowledge hub, with regression tests; the maintainer independently re-verified it
- **pdfcn (shadcn-labs)**: six registry blocks and components in review, each claimed, built and review-fixed the same day: [Business Letter](https://github.com/shadcn-labs/pdfcn/pull/92), [Resume](https://github.com/shadcn-labs/pdfcn/pull/93), [Cover Letter](https://github.com/shadcn-labs/pdfcn/pull/94), [Project Proposal](https://github.com/shadcn-labs/pdfcn/pull/95), [Quarterly Report](https://github.com/shadcn-labs/pdfcn/pull/96), [Addresses](https://github.com/shadcn-labs/pdfcn/pull/97)
- **Reticle**: [#1634](https://github.com/reticlehq/reticle/pull/1634), [#1636](https://github.com/reticlehq/reticle/pull/1636), [#1726](https://github.com/reticlehq/reticle/pull/1726), [#2096](https://github.com/reticlehq/reticle/pull/2096) (merged): a pre-writable selector in the split-text hint, a failed browser launch naming the exact Chromium path it checked, design tokens declared inside `@layer` blocks are now found, and theme tokens resolve on the inspected element, not the body
- **Reticle**: [#1620](https://github.com/reticlehq/reticle/pull/1620) (merged): fixed the destructive-action guard judging selectable items by their whole text, with red-first regression tests and a changelog entry per the repo's house rules
- **Reticle**: [#1633](https://github.com/reticlehq/reticle/pull/1633), [#1635](https://github.com/reticlehq/reticle/pull/1635) (in review): upload through hidden dropzone inputs, and geometry assertions (fully in viewport, overlap, clipped text) for element predicates
- **Forge (git-pkgs)**: [#172](https://github.com/git-pkgs/forge/pull/172), [#180](https://github.com/git-pkgs/forge/pull/180), [#181](https://github.com/git-pkgs/forge/pull/181), [#179](https://github.com/git-pkgs/forge/pull/179), [#190](https://github.com/git-pkgs/forge/pull/190) (all merged): release upload gained `--tag` parity and non-nil upload options, the Gitea and Forgejo `pr list` now applies the `--head` filter client-side, a `pr checks` command with CI-aware exit codes, and draft releases can be targeted by release ID on GitHub
- **Firecrawl**: [#5141](https://github.com/firecrawl/firecrawl/pull/5141) (in review): fixed the map and extract search builders corrupting URLs by stripping `www.` from anywhere in the string instead of only the hostname, with a shared helper and unit tests for the corrupted cases
- **Firecrawl**: [#5164](https://github.com/firecrawl/firecrawl/pull/5164) (in review): made the crawler's JS link-filter fallback enforce the same host scoping as the native filter, so crawls cannot silently wander off-site when the native filter fails
- **Squidbrake**: [#91](https://github.com/batrapulkit/squidbrake/pull/91), [#131](https://github.com/batrapulkit/squidbrake/pull/131) (all merged): added a taint signal so approvers see when an agent edits its own setup right after reading outside content; hardened the shell guard to inspect what `make`, `npm run`, and `bash x.sh` execute underneath, with 26 tests
- **LegalQuants lq-ai**: [#720](https://github.com/LegalQuants/lq-ai/pull/720) (merged): passage retrieval now matches on any playbook keyword
- **doc-scraper (Sriram-PR)**: [#31](https://github.com/Sriram-PR/doc-scraper/pull/31), [#53](https://github.com/Sriram-PR/doc-scraper/pull/53) (all merged): incremental `crawl_site` jobs now resume and skip unchanged pages; search results dedupe to one chunk per page
- **GENesis-AGI (WingedGuardian)**: [#3307](https://github.com/WingedGuardian/GENesis-AGI/pull/3307), [#3931](https://github.com/WingedGuardian/GENesis-AGI/pull/3931) (all merged): made the live approval-gate memory test able to fail, so it actually verifies the gate it covers; a preferences set now round-trips every unmentioned field in the outreach tests
- **sqlalchemy-cubrid (cubrid-lab)**: [#973](https://github.com/cubrid-lab/sqlalchemy-cubrid/pull/973), [#978](https://github.com/cubrid-lab/sqlalchemy-cubrid/pull/978), [#977](https://github.com/cubrid-lab/sqlalchemy-cubrid/pull/977), [#979](https://github.com/cubrid-lab/sqlalchemy-cubrid/pull/979), [#981](https://github.com/cubrid-lab/sqlalchemy-cubrid/pull/981), [#1113](https://github.com/cubrid-lab/sqlalchemy-cubrid/pull/1113) (all merged): corrected the namespace of reflected timezone types, test coverage for escaped and reserved identifier quoting, the reflection probe engine now disposes on every exit path, preflight sync engine disposal pinned on success and errors, the reflection_probe report shape pinned with a fake inspector, and the build now requires setuptools 77 or newer for the SPDX license string
- **Gophenberg (gopherium)**: [#432](https://github.com/gopherium/gophenberg/pull/432), [#521](https://github.com/gopherium/gophenberg/pull/521), [#645](https://github.com/gopherium/gophenberg/pull/645) (all merged): slugs now strip accents the way WordPress does; named the label or item blocking a root hand-over; exported types are compared by key in the resume test
- **sloptotal (pablocaeg)**: [#138](https://github.com/pablocaeg/sloptotal/pull/138), [#139](https://github.com/pablocaeg/sloptotal/pull/139) (merged): enabled ruff import sorting and the pyupgrade rules for Python 3.10, fixing everything they reported
- **statewave-openrouter (smaramwbc)**: [#5](https://github.com/smaramwbc/statewave-openrouter/pull/5) (merged): a failed compile after a turn is now logged instead of silently dropped
- **Composio**: [#4946](https://github.com/ComposioHQ/composio/pull/4946) (merged): the CLI `connections list` command now shows account id, alias, and display name
- **razer-ctl (sqmagellan)**: [#11](https://github.com/sqmagellan/razer-ctl/pull/11) (merged): added the Razer Blade 17 (2022), PID 0x028b, USB device descriptor
- **Umami**: [#4631](https://github.com/umami-software/umami/pull/4631) (merged): the heatmap overlay stays composited above the iframe snapshot in Safari
- **Docusaurus OpenAPI Docs (PaloAltoNetworks)**: [#1707](https://github.com/PaloAltoNetworks/docusaurus-openapi-docs/pull/1707) (merged): an auth scheme reused by OR security alternatives is deduped in the theme instead of rendered twice
- **Framework (gopherium)**: [#135](https://github.com/gopherium/framework/pull/135) (merged): the gottext check now names a translation whose tags differ from its message
- **Avenx-JS**: [#1632](https://github.com/Avenx-JS/avenx-js/pull/1632), [#1638](https://github.com/Avenx-JS/avenx-js/pull/1638), [#1639](https://github.com/Avenx-JS/avenx-js/pull/1639) (all merged): `warnings` keys that name no warning code are reported, a compiled template that cannot be prepared names the AVX_R37 environment error, and `avenx explain` catalogues every AVX code
- **Crosstl (CrossGL)**: [#3872](https://github.com/CrossGL/crosstl/pull/3872), [#4018](https://github.com/CrossGL/crosstl/pull/4018) (all merged): SPIR-V input tests cover Restrict on a storage buffer variable, and Slang writes nonuniformEXT(k) as NonUniformResourceIndex(k)
- **JSPrismarine**: [#2880](https://github.com/JSPrismarine/JSPrismarine/pull/2880), [#2883](https://github.com/JSPrismarine/JSPrismarine/pull/2883) (all merged): mcfunction code fences are highlighted in the docs, and `/clear` with a max count of 0 reports its count
- **Invoicerr**: [#924](https://github.com/invoicerr-app/invoicerr/pull/924) (merged): documents show what is still owed due this month as the current month expected
- **Vedo (marcomusy)**: [#1317](https://github.com/marcomusy/vedo/pull/1317) (merged): fixed a merge() AttributeError when the first input is a raw vtkPolyData
- **Ludusavi manifest (mtkennerly)**: [#85](https://github.com/mtkennerly/ludusavi-manifest/pull/85) (merged): manifest overrides can create new entries
- **Soundcraft (storytold)**: [#1026](https://github.com/storytold/soundcraft/pull/1026) (merged): deleting a track keeps a folder's input bus when surviving tracks route through it
- **Obsidian Outliner (vslinko)**: [#616](https://github.com/vslinko/obsidian-outliner/pull/616) (merged): fixed the last bullet point left over when closing a list
- **CUGA (cuga-project)**: [#965](https://github.com/cuga-project/cuga-agent/pull/965) (merged): the unit suite runs without an OpenAI key or the evolve extra
- Plus more in review across Go, Python and TypeScript projects: [all my pull requests](https://github.com/pulls?q=is%3Apr+author%3ACloudCorpRecords)

## What I do


- 🏗️ **Build** — full-stack TypeScript/Python apps, MCP servers, AI agent systems, local-first AI apps
- 🎓 **Teach** — hands-on workshops on building with Replit, Cursor, and Claude; AI course creator
- 🤝 **Mentor** — help non-technical builders ship with AI


## Recognition


- 🏆 **2024 NAB Show Product of the Year** (AI/ML category), as a builder on ARwall's ARFX XR/AI Filmmaking Suite
- 📰 Profiled in *The San Francisco Standard* (July 2025) for AI-assisted building and San Francisco's hackathon community


## Stack


`TypeScript` `React` `Python` `FastAPI` `MCP` `MLX` `PyTorch` `Electron` `Stripe` `Claude` `OpenAI` `Cursor` `Replit`


## Find me


- 🌐 Portfolio: [reneturcios.replit.app](https://reneturcios.replit.app)
- 💼 LinkedIn: [linkedin.com/in/reneturcios](https://linkedin.com/in/reneturcios)
- ✉️ Email: [cloudtheboy@gmail.com](mailto:cloudtheboy@gmail.com)
- 📍 San Francisco, CA — available now for Forward Deployed, Applied AI and DevRel roles, and for freelance AI builds
