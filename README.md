# 👋 Hi, I'm Rene Turcios


AI product builder and founder of **Clipwise** and **Xod**, based in San Francisco. Replit Ambassador since January 2026. I ship full-stack products solo with AI coding tools (React frontends, Python backends, MCP servers, agent pipelines), then teach other people to do the same: 200+ hackathons, hands-on workshops across the Bay Area, and mentoring non-technical founders.


## ⭐ Flagship projects

<table>
<tr>
<td width="50%" valign="top">

### [🌙 Xod](https://github.com/CloudCorpRecords/xod)

**A private AI that works on your Mac.** It researches, works with your files, runs jobs in the background, and asks before it acts. Runs locally with no account and no telemetry.

<a href="https://github.com/CloudCorpRecords/xod"><img src="https://github.com/CloudCorpRecords/xod/raw/main/docs/media/moon.gif" width="160" alt="Xod's moon companion"></a>

[**Download for Mac**](https://github.com/CloudCorpRecords/xod/releases/latest) · [Contribute](https://github.com/CloudCorpRecords/xod/blob/main/.github/CONTRIBUTING.md) · [Discussions](https://github.com/CloudCorpRecords/xod/discussions) · [Roadmap](https://github.com/CloudCorpRecords/xod/blob/main/docs/ROADMAP.md)

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

### [🟢 Greenlight](https://github.com/CloudCorpRecords/greenlight)

**Pre-flight checks for open-source contributions.** Point it at any GitHub issue and it tells you if the issue is actually landable: verdicts (GO / RISKY / TAKEN / GATED / STALE), repo friction scores, and scan mode that ranks a repo's good first issues. Ships as a CLI and an MCP server, born from vetting real issues by hand, then automated end to end. 163 tests, CI green on Node 20 and 24.

[**Release v0.3.0**](https://github.com/CloudCorpRecords/greenlight/releases/tag/v0.3.0)

Since v0.2 it also runs the pipeline after the verdict: `claim`, `prep` and `pr` commands (plus MCP tools) with dry-run-by-default writes, gate-aware claim comments, repo conventions learned into a prep checklist, and DCO verification before a PR opens. v0.3 added house-rules gates from AGENTS.md files and detection for issues that already shipped in part.

`TypeScript` `MCP` `CLI` `GitHub API`

Greenlight is one of four tools I built out of a single day of real open-source contribution work, one per stage of the lifecycle:

- **[prwatch](https://github.com/CloudCorpRecords/prwatch)**: after you submit. Ranks your open PRs by what needs attention (changes requested, unresolved threads, real failing checks, conflicts, reviewer silence), with external blockers like Vercel authorization classified separately
- **[claimcheck](https://github.com/CloudCorpRecords/claimcheck)**: while you work. Finds stale issue claims aging with no PR, and parked fixes: finished work on fork branches that never became a PR
- **[gatefile](https://github.com/CloudCorpRecords/gatefile)**: for maintainers. Extracts a repo's hidden contribution gates from its docs into a machine-readable contribution-gates.json, with a drift validator for CI



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

- **IBM ContextForge** — [#181](https://github.com/contextforge-org/contextforge-web-ui/pull/181) (merged): moved prompt/resource argument forms onto the shared accessible `Field` component, with the tests and i18n cleanup that go with it
- **Sage** — [#302](https://github.com/ZHangZHengEric/Sage/pull/302) (merged): extended the docs link checker to cover the knowledge hub, with regression tests; the maintainer independently re-verified it
- **pdfcn (shadcn-labs)** — six registry blocks and components in review, each claimed, built and review-fixed the same day: [Business Letter](https://github.com/shadcn-labs/pdfcn/pull/92), [Resume](https://github.com/shadcn-labs/pdfcn/pull/93), [Cover Letter](https://github.com/shadcn-labs/pdfcn/pull/94), [Project Proposal](https://github.com/shadcn-labs/pdfcn/pull/95), [Quarterly Report](https://github.com/shadcn-labs/pdfcn/pull/96), [Addresses](https://github.com/shadcn-labs/pdfcn/pull/97)
- **Reticle** — [#1620](https://github.com/reticlehq/reticle/pull/1620) (in review): fixed the destructive-action guard judging selectable items by their whole text, with red-first regression tests and a changelog entry per the repo's house rules
- **Squidbrake** — [#91](https://github.com/batrapulkit/squidbrake/pull/91) (in review): added a taint signal so approvers see when an agent edits its own setup right after reading outside content
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
