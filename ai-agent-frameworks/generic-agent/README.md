---
name: "GenericAgent"
category: "AI Agent Frameworks"
tags: ["self-evolving", "skill-tree", "minimal", "token-efficient", "multi-provider"]
repo_url: "https://github.com/lsdefine/GenericAgent"
stars: 3500
license: "MIT"
language: "Python"
last_updated: "2026-04-11"
---

# GenericAgent — Self-Evolving Agent with Skill Tree (~3K Lines)

> **TL;DR:** Minimal autonomous agent (~3K lines) that grows a skill tree from every task it completes. 6x less token consumption than standard agents. 9 atomic tools + 5-layer memory system. Multi-LLM support. 3.5K stars. MIT.

| Metric | Value |
|--------|-------|
| **Repository** | [lsdefine/GenericAgent](https://github.com/lsdefine/GenericAgent) |
| **Stars** | ~3,500 |
| **Forks** | 374 |
| **License** | MIT |
| **Language** | Python (95.4%) |
| **Core Code** | ~3,000 lines |
| **Token Usage** | 6x less than standard agents |

## Overview

GenericAgent achieves system-level control of a local computer through just 9 atomic tools and ~100 lines of agent loop. Its innovation: every solved task automatically becomes a reusable SOP (skill) in a growing skill tree. Claims to be "entirely built by the agent itself — the author never opened a terminal." Supports Claude, Gemini, Kimi, MiniMax with fallback chains. 5-layer memory system (L0-L4).

## Key Features

- **Self-Evolving Skill Tree** — Every task creates a reusable SOP stored in `memory/`
- **9 Atomic Tools** — code_run, file_read, file_write, file_patch, web_scan, web_execute_js, ask_user + 2 memory tools
- **5-Layer Memory** — L0: meta-rules, L1: insight indices, L2: global facts, L3: task skills, L4: raw archives
- **6x Token Efficiency** — Context stays under 30K tokens (vs 200K-1M typical)
- **Multi-Provider** — Claude, Gemini, Kimi, MiniMax with MixinSession fallback chains
- **Rich Frontends** — Streamlit, Qt desktop, desktop pet, WeChat/QQ/Telegram bots
- **Self-Bootstrapping** — Agent installs its own dependencies

## Scoring

| Criteria | Score |
|----------|-------|
| Documentation Quality | 5/10 |
| Ease of Setup | 7/10 |
| Community Activity | 6/10 |
| Production Readiness | 3/10 |
| Extensibility | 8/10 |
| Revenue Generation Potential | 5/10 |

**Overall: 5.7/10**

## Final Verdict

Intellectually fascinating — the skill tree concept is genuinely novel. The ~3K line codebase is a masterclass in minimalism. However, security gaps, no CI/CD, and Chinese-centric ecosystem limit practical adoption. **Best for enthusiasts, researchers, and personal automation. Watch for the concept; don't deploy in production yet.**
