---
name: "Paperclip"
category: "Agent Orchestrators"
tags: ["multi-agent", "orchestration", "zero-human-company", "agent-os", "budget-management", "audit-logs", "typescript"]
repo_url: "https://github.com/paperclipai/paperclip"
website: "https://paperclip.ing"
stars: 55300
license: "MIT"
language: "TypeScript"
last_updated: "2026-04-16"
---

# Paperclip — The Operating System for Zero-Human Companies

> **TL;DR:** Paperclip is an open-source orchestration platform that lets you run an entire company with AI agents. Org charts, budgets, reporting lines, audit logs — managed from one dashboard. 55K+ stars. MIT License.

| Metric | Value |
|--------|-------|
| **Repository** | [paperclipai/paperclip](https://github.com/paperclipai/paperclip) |
| **Website** | [paperclip.ing](https://paperclip.ing) |
| **Stars** | 55,300+ |
| **Forks** | 9,300+ |
| **Contributors** | 81 |
| **License** | MIT |
| **Language** | TypeScript (97.4%) |
| **Latest Release** | v2026.416.0 (April 16, 2026) |

---

## Overview

Paperclip is an open-source orchestration platform that treats AI agents like employees in a company. Built primarily in TypeScript, it allows organizations to assemble teams of AI agents — from Claude Code, Codex, Cursor, OpenClaw, and any HTTP-accessible agent — and manage them with real corporate structures: org charts, reporting lines, titles, budgets, and goals. Instead of having 20 Claude Code tabs open with no idea what's happening, you get one deployment, one dashboard, and your agents run the company while you sleep.

**Who built it:** The team at Paperclip AI (paperclip.ing)
**Problem it solves:** Managing multiple autonomous AI agents at scale without losing control over costs, quality, or accountability.

---

## Key Features

- **Multi-Agent Coordination** — Orchestrate agents from Claude Code, Codex, Cursor, OpenClaw, Bash, and any HTTP endpoint
- **Organizational Hierarchy** — Org charts with reporting lines, titles, and roles
- **Budget Management** — Monthly per-agent budgets with real-time cost tracking and enforcement
- **Goal Alignment** — Hierarchical goal-setting that cascades through the org chart
- **Ticketing System** — Full task management with assignment, status tracking, and prioritization
- **Immutable Audit Logs** — Tool-call tracing for every action any agent takes
- **Governance & Approval Workflows** — Critical actions require sign-off before execution
- **24/7 Heartbeat System** — Agents maintain persistent state and run continuously
- **Multi-Company Support** — Data isolation between different company/project contexts
- **Plugin System** — Extensible architecture for custom functionality
- **One-Command Setup** — `npx paperclipai onboard --yes`

---

## Scoring

| Criteria | Score | Rationale |
|----------|-------|-----------|
| Documentation Quality | 7/10 | Comprehensive README with quick-start and roadmap. Docs may lag behind rapid development pace |
| Ease of Setup | 8/10 | Single npx command for local dev. Production needs PostgreSQL |
| Community Activity | 9/10 | 55K+ stars, 81 contributors, daily releases, active Discord |
| Production Readiness | 6/10 | PostgreSQL + audit logs are solid, but missing multi-user and cloud agent hosting |
| Extensibility | 8/10 | Plugin system, agent-agnostic, skills management, org import/export |
| Revenue Generation Potential | 9/10 | "Replace entire teams" value prop is enormously compelling to businesses |

**Overall Score: 7.8/10**

---

## Best Use Cases

- Autonomous software development shops (AI agents handling full SDLC)
- Content production pipelines at scale
- Automated customer operations (support, billing, escalation)
- Research & analysis firms needing autonomous agent teams
- DevOps/infrastructure automation running 24/7
- Startup prototyping with "virtual teams"

## Not Recommended For

- Simple single-agent tasks (too much overhead)
- Latency-sensitive real-time applications
- Highly regulated industries (compliance features still maturing)
- Teams without DevOps capability
- Small personal projects

---

## Final Verdict

Paperclip is the most ambitious and fully-realized open-source platform for running autonomous AI agent organizations. Its corporate-metaphor architecture (org charts, budgets, reporting lines, audit trails) is genuinely novel and addresses the governance gap that plagues other multi-agent frameworks. With 55K+ stars and daily releases, it's the front-runner for "zero-human company" infrastructure. Best for technical teams ready to operationalize autonomous agent workforces.

---

> **Deep dive:** See [deep-analysis.md](deep-analysis.md) for architecture breakdown, comparison with alternatives, revenue strategies, and business ideas.
