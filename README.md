# I make enterprise codebases agent-friendly — and rewire how teams ship software around coding agents.

AI agents that operate Adobe Experience Manager — not as demos, but as production systems running across 100+ markets and serving millions of users.

**1,300+ GitHub stars · 3 Adobe-distributed SDKs · 57 MCP tools · 78 AI skills**

## What I actually do

I embed with engineering teams and make their codebases agent-friendly — building the rules, skills, and MCP servers that let AI coding agents actually work in large, complex enterprise codebases. Then I redesign the SDLC around them: finding where delivery breaks when you add agents (QA bottlenecks, poorly scoped requirements, review debt) and rewiring it — and bringing the whole team up, not just the engineers already excited.

Under that sits the tooling I've built for the constraints enterprises actually have — governance, multi-environment deployments, team-scale coordination:

- the **protocol layer** (MCP servers),
- the **orchestration layer** (multi-agent workflows),
- the **autonomous execution layer** (24/7 pipeline agents).

My systems handle the full development lifecycle autonomously: requirements analysis → implementation planning → code generation → multi-phase verification → PR creation. One command. No re-explaining the project each session.

## Production usage

This isn't research or prototyping:

- **Daily in production on a Fortune 500 account** — a 13-agent requirements-to-PR platform (KAI) running every day, escalated to COO
- **100+ market AEM platform** — agentic workflows operating across a multi-market content platform
- **Millions of users** — systems deployed in high-traffic enterprise environments
- **Autonomous pipeline agents** — AI agents running 24/7 as Azure DevOps pipelines, triggered by webhooks, producing verified PRs without human intervention
- **Multi-agent orchestration** — Opus for deep review, Sonnet for execution, Haiku for lookups — tiered by task complexity

## What I build

Years of open source and internal enterprise tooling — from UI components and developer utilities to deployment automation and platform SDKs. Recently shifted focus to agentic workflows:

### [AEM MCP Server](https://github.com/easingthemes/aem-mcp-server)
The protocol layer. 57 MCP tools that give AI agents direct access to AEM — JCR content, components, dialogs, page operations. The interface between LLMs and enterprise CMS. One of the first full MCP servers for AEM.

### [dx-aem-flow](https://github.com/easingthemes/dx-aem-flow)
The orchestration layer. 78 skills, 13 agents, 4 plugins running identically across Claude Code, GitHub Copilot CLI, and VS Code Chat. Full development lifecycle from ticket to PR — config-driven, never hardcoded. Includes autonomous agents for DoR/DoD validation, code review, bug fixing, and QA. Shipped ~6 months before Salesforce productized the "Agentic Engineering" category.

### [ki-bundestag](https://github.com/easingthemes/ki-bundestag)
AI parliament simulation. 6 autonomous agents model German political parties using Claude + Grok. Multi-provider orchestration, circuit breakers, and coalition negotiation running a full 4-year parliamentary term for ~$44. This is the project that got me found — a recruiter discovered it via GitHub search and reached out directly (June 2026).

### [ssh-deploy](https://github.com/easingthemes/ssh-deploy)
GitHub Action for SSH deployments. 1,300+ stars, 162 forks, 57 releases. Used across thousands of CI/CD pipelines.

### [Mocker](https://github.com/easingthemes/mocker)
Zero-config Node.js mock API server with web GUI. File-based endpoint management, dynamic path parameters, response variations. Built to unblock frontend teams waiting on backend APIs.

### [fe-build](https://github.com/Netcentric/fe-build)
All-in-one frontend toolchain for AEM projects. Standardized build processes adopted across Netcentric, setting company-wide frontend standards.

### [@adobe/aem-headless-client-js](https://github.com/adobe/aem-headless-client-js)
Lead contributor to Adobe's official AEM Headless SDK for JavaScript/Node.js.

## Technical focus

- **Making codebases agent-friendly** — rules files, custom skills, MCP servers; context engineering for large, complex repos
- **SDLC redesign & enablement** — rewiring delivery around coding agents, evals/LLMOps, bringing whole teams up
- **Agentic workflows** — LLM + tools + structured execution, not chatbots
- **MCP (Model Context Protocol)** — building the interface layer between AI agents and enterprise systems
- **Enterprise AI constraints** — governance, verification gates, multi-environment deployments, team coordination
- **AEM platform engineering** — deep specialization in making Adobe Experience Manager AI-operable

## Speaking & writing

- **[adaptTo() 2023](https://adapt.to/speakers/dragan-filipovic)** — "AEM Headless: A Glimpse of Developer Tools" (Europe's leading AEM conference)
- **[Frontend Coffee Break](https://frontend.coffee)** — Podcast Episode #25: "Open Sourcing Our FE Build"
- **[Netcentric Blog](https://www.netcentric.biz)** — "AI-Driven Code Generation: AEM Component Development from Figma" (2025)
- **Multiple internal/client talks** — AI-enabled development, AEM headless, frontend architecture (audiences up to 200+)

## Direction

Expanding the surface area of what AI agents can operate in enterprise environments. More MCP servers, deeper orchestration, more autonomous pipelines. The goal: enterprise development workflows where AI agents handle execution end-to-end, with humans setting direction and reviewing output.

---

**Berlin** · [@draganfill](https://twitter.com/draganfill) · [LinkedIn](https://www.linkedin.com/in/draganfilipovic/) · [frontenddot.com](https://frontenddot.com)
