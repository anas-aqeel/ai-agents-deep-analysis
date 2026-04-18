---
name: "NullClaw"
category: "Agent Operating Systems"
tags: ["zig", "minimal", "agent-platform", "edge", "iot", "security", "multi-channel"]
repo_url: "https://github.com/nullclaw/nullclaw"
stars: 7200
license: "MIT"
language: "Zig"
last_updated: "2026-04-09"
---

# NullClaw — Ultra-Minimal Agent Infrastructure in Zig

> **TL;DR:** AI agent platform in 678KB binary, ~1MB RAM, <2ms startup. 50+ AI providers, 19 channels, 35+ tools, 10 memory engines. Written in Zig. Zero external dependencies. 5,300+ tests. 7.2K stars.

| Metric | Value |
|--------|-------|
| **Repository** | [nullclaw/nullclaw](https://github.com/nullclaw/nullclaw) |
| **Stars** | 7,200+ |
| **Forks** | 849 |
| **License** | MIT |
| **Language** | Zig |
| **Binary Size** | 678 KB |
| **Memory** | ~1 MB RSS |
| **Startup** | <2ms |

## Overview

NullClaw is a minimal AI assistant infrastructure written in Zig, engineered for extreme resource efficiency. With 678KB binary, ~1MB memory, and <2ms startup, it runs on everything from ARM embedded devices to standard servers. Despite the tiny footprint: 50+ AI providers, 19 communication channels, 35+ tools, and 10 memory engines including SQLite with hybrid FTS5 + vector search. ChaCha20-Poly1305 encryption and multi-layer sandboxing (Landlock, Firejail, Bubblewrap, Docker).

## Key Features

- **50+ AI Providers** — OpenRouter, Anthropic, Ollama, and more
- **19 Channels** — Telegram, Discord, Signal, Slack, WhatsApp, Matrix
- **35+ Tools** — Pluggable vtable-based architecture
- **10 Memory Engines** — Including SQLite with hybrid FTS5 vector search
- **678KB Binary** — Zero external dependencies beyond libc
- **Multi-Layer Security** — ChaCha20-Poly1305, Landlock, Firejail, Bubblewrap
- **A2A Protocol v0.3.0** — Agent-to-agent communication
- **5,300+ Tests** — Rigorous engineering

## Scoring

| Criteria | Score |
|----------|-------|
| Documentation Quality | 8/10 |
| Ease of Setup | 7/10 |
| Community Activity | 7/10 |
| Production Readiness | 7/10 |
| Extensibility | 8/10 |
| Revenue Generation Potential | 6/10 |

**Overall: 8.0/10**

## Final Verdict

NullClaw pushes the boundaries of what a tiny binary can do. If you need an agent platform for edge/IoT deployments or environments with strict security requirements, nothing else comes close to this efficiency. **The Zig niche limits the contributor pool, but the engineering quality is exceptional.**
