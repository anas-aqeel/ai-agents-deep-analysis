---
name: "Symphony"
category: "AI Agent Frameworks"
tags: ["openai", "codex", "orchestrator", "elixir", "linear", "autonomous-coding"]
repo_url: "https://github.com/openai/symphony"
stars: 15200
license: "Apache-2.0"
language: "Elixir"
last_updated: "2026-04-14"
---

# Symphony — OpenAI's Autonomous Coding Agent Orchestrator

> **TL;DR:** OpenAI's spec-first orchestrator that polls Linear issues, creates isolated workspaces, and dispatches Codex agents to resolve them autonomously. Built in Elixir/OTP. Engineering preview. 15.2K stars.

| Metric | Value |
|--------|-------|
| **Repository** | [openai/symphony](https://github.com/openai/symphony) |
| **Stars** | 15,200+ |
| **Forks** | 1,300+ |
| **License** | Apache 2.0 |
| **Language** | Elixir (95.4%) |
| **Status** | Engineering Preview |

## Overview

Symphony is an automation service by OpenAI that orchestrates Codex agents to autonomously resolve Linear issues at scale. It creates isolated per-issue workspaces, dispatches agents, handles CI failure retry loops, and supports multi-turn resolution. Built in Elixir/OTP for fault-tolerant concurrency. Configured via a single WORKFLOW.md file with hot-reload. No persistent database — recovers entirely from polling.

## Key Features

- **Autonomous Issue Resolution** — Polls Linear, dispatches Codex agents per issue
- **Isolated Workspaces** — Sandboxed per-issue filesystems with lifecycle hooks
- **Continuation Turns** — Agents re-check tracker and continue across turns
- **WORKFLOW.md Config** — All behavior in one hot-reloadable markdown file
- **Reconciliation Engine** — Detects stalls, terminates terminal-state work, cleans up
- **Zero External State** — No database; recovers from polling on restart
- **Exponential Backoff** — Configurable retry with backoff capped at 5 minutes
- **LiveView Dashboard** — Phoenix-based real-time monitoring

## Scoring

| Criteria | Score |
|----------|-------|
| Documentation Quality | 8/10 |
| Ease of Setup | 4/10 |
| Community Activity | 3/10 |
| Production Readiness | 3/10 |
| Extensibility | 6/10 |
| Revenue Generation Potential | 5/10 |

**Overall: 6.5/10**

## Final Verdict

Architecturally brilliant, practically constrained. The SPEC.md is one of the best in open source — study it. But Linear-only, Codex-only, and Elixir-only narrows the audience severely. **Best as a reference architecture for autonomous agent orchestration, not a daily-driver tool.**
