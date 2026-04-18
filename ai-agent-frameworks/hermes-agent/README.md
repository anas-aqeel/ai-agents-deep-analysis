---
name: "Hermes Agent"
category: "AI Agent Frameworks"
tags: ["self-improving", "nous-research", "multi-platform", "skills", "memory", "messaging-gateway"]
repo_url: "https://github.com/nousresearch/hermes-agent"
stars: 96500
license: "MIT"
language: "Python"
last_updated: "2026-04-16"
---

# Hermes Agent — Self-Improving AI Agent by Nous Research

> **TL;DR:** Open-source AI agent that learns from every interaction, building reusable skills over time. 16+ messaging platforms, 10+ LLM providers, 25+ skill domains. By Nous Research. 96.5K stars. MIT.

| Metric | Value |
|--------|-------|
| **Repository** | [nousresearch/hermes-agent](https://github.com/nousresearch/hermes-agent) |
| **Stars** | 96,500+ |
| **Forks** | 13,600+ |
| **License** | MIT |
| **Language** | Python (93.6%) |
| **First Release** | March 23, 2026 |
| **Latest Release** | v0.10.0 (April 16, 2026) |

---

## Overview

Hermes Agent is a self-improving, open-source AI agent framework by Nous Research. Its core innovation: a built-in learning loop where the agent autonomously creates skills from experience and refines them during subsequent use. It provides persistent memory, smart model routing across 10+ LLM providers, and a unified messaging gateway spanning 16+ platforms (Telegram, Discord, Slack, WhatsApp, Signal, iMessage, WeChat, and more).

**Who built it:** Nous Research (creators of Hermes model series)
**Problem it solves:** Agents that start from scratch every session. Hermes remembers, learns, and gets better with use.

---

## Key Features

- **Self-Improving Skills** — Agent creates, stores, and refines skills from interactions. 25+ domain categories
- **Persistent Memory** — Cross-session memory with pluggable providers (Honcho integration)
- **10+ LLM Providers** — Nous Portal, OpenRouter, OpenAI, Anthropic, Gemini, Bedrock, Mistral, Ollama
- **16+ Messaging Platforms** — Telegram, Discord, Slack, WhatsApp, Signal, iMessage, WeChat, DingTalk, Matrix
- **Smart Model Routing** — Auto-selects optimal model based on task, cost, and latency
- **Provider Failover** — Ordered fallback chains with credential rotation
- **Rich Tools** — Browser automation (anti-detection), code execution, TTS, image gen, Home Assistant, MCP
- **Subagent Spawning** — Parallel task execution via spawned subagents
- **Multiple Deployments** — Local, Docker, SSH, Daytona, Modal (serverless with hibernation), Nix
- **OpenAI-Compatible API** — Drop-in `/v1/chat/completions` endpoint
- **Security** — Tirith module, skills guard, URL safety, injection tracking

---

## Scoring

| Criteria | Score | Rationale |
|----------|-------|-----------|
| Documentation Quality | 5/10 | External docs site exists but in-repo docs thin |
| Ease of Setup | 7/10 | One-line curl installer. Complexity grows with features |
| Community Activity | 9/10 | 96.5K stars, 13.6K forks, hundreds of PRs per release |
| Production Readiness | 4/10 | Less than 1 month old, 1.8K open issues, rapid API churn |
| Extensibility | 9/10 | Plugin system, hooks, 25+ skill categories, MCP, multi-provider |
| Revenue Generation Potential | 7/10 | Nous Portal monetizes. Enterprise + marketplace opportunities |

**Overall Score: 6.8/10**

---

## Best Use Cases

- Personal AI assistant with persistent memory across platforms
- DevOps automation (cron, terminal, Docker, webhooks)
- Multi-platform bot deployment (one agent, 16+ channels)
- Research and experimentation with multi-model routing
- Team knowledge management with compounding skills

## Not Recommended For

- Enterprise production today (< 1 month old, unstable APIs)
- Minimal/lightweight agent needs (massive feature surface)
- Highly regulated environments (unclear security model)
- Offline/air-gapped deployments
- Stable API consumers (expect frequent breaking changes)

---

## Makes Money?

Partially. Hermes Agent is free (MIT). Nous Research monetizes through **Nous Portal** — paid subscription for premium tools (web search, image gen, TTS, browser). Classic open-core/freemium model.

## Revenue Ideas

| Idea | Model | Revenue |
|------|-------|---------|
| Managed Hermes Cloud | Hosted service with SLA | Per-seat/usage pricing |
| Enterprise Skill Marketplace | Organizations sell skill packs | Platform fee on transactions |
| White-Label Bot Platform | License gateway for customer service bots | B2B licensing |
| Skill Analytics SaaS | Usage tracking, cost optimization, recommendations | Analytics subscription |

---

## Final Verdict

Hermes Agent is the most ambitious open-source AI agent project of 2026 — self-improving skills, 16+ platforms, 10+ providers, all from a respected AI research lab. The 96.5K stars in under a month signal extraordinary interest. However, it's brand new (first release March 23, 2026) and moving at breakneck speed. **For developers and power users: adopt now and ride the wave. For production teams: watch for v1.0.**

---

> **Deep dive:** See [deep-analysis.md](deep-analysis.md) for architecture, comparison with AutoGPT/CrewAI, and detailed revenue strategies.
