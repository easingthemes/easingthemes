# I build AI developer platforms: coding agents that take real tickets to reviewed pull requests in large enterprise codebases.

Agentic engineering and AI enablement for engineering teams, running daily in production on a Fortune-500-scale program, not as demos.

## What I actually do

I make enterprise codebases agent-friendly — the rules, skills, MCP servers and guardrails that let AI coding agents work in large, complex repositories. Then I redesign delivery around them: find where it breaks when agents arrive (QA bottlenecks, poorly scoped requirements, review debt), fix it, and bring the whole team along, not just the engineers already excited.

Under that sits tooling built for the constraints enterprises actually have — governance, multi-environment deployments, team-scale coordination:

- the **protocol layer** (MCP servers),
- the **orchestration layer** (skills, agents and plugins shared across Claude Code, Copilot CLI and VS Code Chat),
- the **execution layer** (agents running as CI pipelines, triggered from the ticket),
- the **measurement layer** (evals with known-answer fixtures).

## In production

- **Issue-to-PR agents** — requirements, readiness checks, bug fixing, development, QA, docs; each triggered by a comment on the ticket and running in CI. A third of all work items are delivered through this spec-to-PR workflow.
- **Autonomous AI PR review** — hundreds of pull requests reviewed in daily delivery, at about $5 per review.
- **5 enterprise repositories made agent-ready** — skills, agents, rules files, guardrails (policy-as-code, token budgets, secret-blocking hooks).
- **Evals that changed decisions** — an LLM judge passed a report its own rubric marked as a fail; the deterministic grader caught it, so deterministic graders now run first.
- **Model tiering** — Opus for deep review, Sonnet for execution, Haiku for lookups.
- **Scale** — a multi-brand AEM platform with 500+ components and hundreds of country/language sites, 4+ market teams.

## What I build

### [dx-aem-flow](https://github.com/easingthemes/dx-aem-flow)
The orchestration layer. 75+ skills, 13 agents, 4 plugins running identically across Claude Code, GitHub Copilot CLI and VS Code Chat. Ticket to PR, autonomous CI agents, AI PR review, eval layer. Config-driven, never hardcoded.

### [kai-hausmeister](https://github.com/easingthemes/kai-hausmeister)
A self-hosted n8n agent that triages every new GitHub issue on a public repo: reads the code and past issues, posts a code-aware triage comment, labels and possible duplicates. About one cent per issue; 8 security layers against prompt injection on public input; GitOps deploy.

### [AEM MCP Server](https://github.com/easingthemes/aem-mcp-server)
The protocol layer. 57 MCP tools that give AI agents direct access to AEM — JCR content, components, dialogs, page operations. One of the first comprehensive MCP servers for AEM. Listed on PulseMCP.

### [ki-bundestag](https://github.com/easingthemes/ki-bundestag)
AI parliament simulation. 6 autonomous agents model German political parties using Claude + Grok and the Vercel AI SDK. Multi-provider orchestration, circuit breakers and coalition negotiation, running a full 4-year parliamentary term for ~$44.

### [ssh-deploy](https://github.com/easingthemes/ssh-deploy)
GitHub Action for SSH deployments. 1.3k+ stars, used in CI/CD pipelines worldwide.

### [@adobe/aem-headless-client-js](https://github.com/adobe/aem-headless-client-js) · [fe-build](https://github.com/Netcentric/fe-build) · [Mocker](https://github.com/easingthemes/mocker)
Lead contributor to Adobe's official AEM Headless SDK (one of 3 Adobe-distributed SDKs I delivered) · the frontend toolchain adopted across Netcentric · a zero-config mock API server.

## Technical focus

- **AI developer platforms** — agents for engineers: skills, subagents, hooks, plugins, MCP
- **Context engineering** — rules files, AGENTS.md, skills for large, complex repos
- **Agent safety** — policy-as-code, token budgets, review gates, prompt-injection defense
- **Evals / LLMOps** — known-answer fixtures, deterministic graders before LLM judges
- **AEM platform engineering** — 16+ years in enterprise platforms; AEM is the depth

## Speaking & writing

- **[adaptTo() 2023](https://adapt.to/speakers/dragan-filipovic)** — "AEM Headless: A Glimpse of Developer Tools"
- **[Frontend Coffee Break](https://frontend.coffee)** — Episode #25: "Open Sourcing Our FE Build"
- **[Netcentric Blog](https://www.netcentric.biz)** — "AI-Driven Code Generation: AEM Component Development from Figma" (2025)
- **ThoughtWorks Berlin 2019** — ML prototype turning hand-drawn wireframes into rendered web components
- Company-wide talks on AI-enabled development (audiences up to 200+)

---

**Berlin** · [LinkedIn](https://www.linkedin.com/in/draganfilipovic/) · [@draganfill](https://twitter.com/draganfill)
