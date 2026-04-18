---
name: "Open Agents"
category: "AI Agent Frameworks"
tags: ["vercel", "coding-agent", "cloud-agent", "sandbox", "typescript", "nextjs", "durable-workflows"]
repo_url: "https://github.com/vercel-labs/open-agents"
stars: 3500
license: "MIT"
language: "TypeScript"
last_updated: "2026-04-17"
---

# Open Agents — Cloud Coding Agents by Vercel

> **TL;DR:** Open-source reference app for building cloud-based coding agents on Vercel. Chat-driven code changes, isolated sandbox VMs, durable workflows, automated PRs. Replaces $200/mo agent platforms. 3.5K stars. MIT.

| Metric | Value |
|--------|-------|
| **Repository** | [vercel-labs/open-agents](https://github.com/vercel-labs/open-agents) |
| **Stars** | ~3,500 |
| **Forks** | ~381 |
| **Commits** | 924 |
| **License** | MIT |
| **Language** | TypeScript (99.3%) |
| **Framework** | Next.js + Turborepo + Bun |

---

## Overview

Open Agents is an open-source reference application by Vercel Labs for building and running cloud-based coding agents. Submit natural language prompts → the agent writes code, runs shell commands, manages git, and creates pull requests — all in isolated cloud sandboxes. Positioned as a free, self-hostable alternative to paid platforms like Devin ($200+/mo). Built with Next.js, TypeScript, and Vercel's Workflow SDK.

**Who built it:** Vercel Labs (experimental arm of Vercel)
**Problem it solves:** Autonomous coding agents need isolated execution environments, durable workflows, and git integration — this provides all three as a deployable reference architecture.

---

## Key Features

- **Chat-Driven Coding** — Natural language → file edits, shell commands, git operations, PRs
- **Durable Multi-Step Execution** — Vercel Workflow SDK for long-running tasks with streaming
- **Isolated Sandbox VMs** — Each session gets its own filesystem, shell, git, dev servers
- **Snapshot Hibernation** — Sandboxes hibernate and resume without losing state (saves compute)
- **Automated Git Workflow** — Auto-commit, auto-push, automated PR creation
- **Session Sharing** — Read-only links for team collaboration
- **Skills System** — Extensible agent capabilities with metadata caching
- **GitHub App Integration** — Full OAuth, webhooks, GitHub App installation
- **Voice Input** — Optional ElevenLabs voice transcription

---

## Scoring

| Criteria | Score | Rationale |
|----------|-------|-----------|
| Documentation Quality | 6/10 | Solid README for setup but lacks extension guides |
| Ease of Setup | 5/10 | Needs PostgreSQL, OAuth configs, encryption keys, Vercel infra |
| Community Activity | 7/10 | 3.5K stars, 924 commits, Vercel Labs credibility |
| Production Readiness | 6/10 | Production-grade architecture but "reference app" status |
| Extensibility | 7/10 | Clean monorepo, skills system. Vercel coupling limits flexibility |
| Revenue Generation Potential | 7/10 | Hot market, open-source + Vercel backing |

**Overall Score: 6.3/10**

---

## Best Use Cases

- Solo devs/small teams wanting self-hosted AI coding assistant
- Vercel-centric organizations wanting tight infrastructure integration
- Internal developer tools teams building custom AI dev workflows
- Open-source maintainers wanting automated PR/issue resolution
- Educational reference for production-grade agent architecture

## Not Recommended For

- Non-coding use cases (support, data pipelines, content)
- Organizations not on Vercel (deep infrastructure coupling)
- Teams needing multi-model flexibility
- Enterprise requiring RBAC, audit trails, SOC2
- Low-resource / free-tier environments

---

## Final Verdict

Open Agents is a technically impressive reference architecture for cloud coding agents. Its three-layer design (web/agent/sandbox), durable workflows, and snapshot hibernation are genuinely innovative. However, deep Vercel coupling limits broader adoption. **Best for Vercel-native teams who want to self-host a coding agent on a well-designed, opinionated foundation.**

---

> **Deep dive:** See [deep-analysis.md](deep-analysis.md) for architecture breakdown, Devin/Cursor comparison, and revenue strategies.
