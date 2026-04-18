---
name: "Multica Deep Analysis"
category: "Agent Orchestrators"
tags: ["managed-agents", "issue-tracker", "multi-agent"]
repo_url: "https://github.com/multica-ai/multica"
---

# Multica — Deep Technical Analysis

## Architecture

| Layer | Technology |
|-------|-----------|
| Frontend | Next.js 16 (App Router), TypeScript |
| Backend | Go, Chi router, sqlc (type-safe SQL), gorilla/websocket |
| Database | PostgreSQL 17 + pgvector |
| Agent Runtime | Local daemon executing supported CLI agents |

### How It Works
1. User creates issue and assigns to an AI agent
2. Go backend dispatches work to local agent daemon
3. Daemon (persistent process with UUID) claims task from queue
4. Agent executes work (writes code, runs tests)
5. Agent reports blockers, updates status via WebSocket
6. Completed solutions become reusable skills via pgvector

## Multica vs Paperclip

| Feature | Multica | Paperclip |
|---------|---------|-----------|
| **Mental Model** | Issue tracker with AI assignees | Corporate org chart for agents |
| **Agent Providers** | 8+ (vendor-neutral) | Claude Code, Codex, Cursor, HTTP |
| **Governance** | Lightweight issues/labels | Heavy budgets, approval chains |
| **Skills** | Composable, compounding | Not yet shipping |
| **Focus** | Team coding workflow | Zero-human company OS |
| **Stars** | 15.3K | 55.3K |
| **Maturity** | v0.2.5 | v2026.416.0 |

## Revenue Ideas

| Idea | Model | Revenue |
|------|-------|---------|
| **Managed Cloud SaaS** | Per-agent-seat or per-execution-minute | Freemium → $50-200/seat/mo |
| **Enterprise Self-Hosted** | Annual license + SLA + SSO/SAML | $10K-100K/year |
| **Agent Skill Store** | Third-party skills with revenue share | Marketplace commissions |
| **Compute-as-a-Service** | Managed cloud runtimes for agents | Margin on cloud costs |

## Final Assessment

**For whom:** Engineering teams wanting to manage AI agents through familiar issue-tracker workflows.

**Skip if:** Solo developer, need stability today, or non-coding use cases.

**Bottom line:** The most intuitive approach to "AI agent management" — assigning issues to AI like you'd assign to a human. The skills compounding system is the sleeper feature that will define long-term value.
