---
name: "Claude-Mem"
category: "Memory Management for AI"
tags: ["claude-code", "memory", "compression", "vector-search", "sqlite", "mcp", "session-persistence"]
repo_url: "https://github.com/thedotmack/claude-mem"
website: "https://docs.claude-mem.ai"
stars: 61300
license: "AGPL-3.0"
language: "TypeScript"
last_updated: "2026-04-16"
---

# Claude-Mem — Persistent Memory Compression for Claude Code

> **TL;DR:** Auto-captures everything Claude does across sessions, compresses via AI, injects relevant context into future sessions. 3-layer retrieval saves 10x tokens. Local-only storage. 61.3K stars. 231 releases.

| Metric | Value |
|--------|-------|
| **Repository** | [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) |
| **Docs** | [docs.claude-mem.ai](https://docs.claude-mem.ai) |
| **Stars** | 61,300+ |
| **Forks** | 5,100+ |
| **License** | AGPL-3.0 (core), PolyForm Noncommercial (Ragtime) |
| **Language** | TypeScript (83%) |
| **Releases** | 231 (latest v12.1.6) |

---

## Overview

Claude-Mem is a persistent memory compression system for Claude Code that automatically captures everything Claude does across sessions — tool calls, observations, decisions — compresses them via AI summarization, stores in local SQLite + Chroma vector database, and injects relevant context into future sessions. The 3-layer progressive retrieval pattern claims 10x token savings by filtering before fetching details.

**Who built it:** Alex Newman (@thedotmack)
**Problem it solves:** Context loss between Claude Code sessions. You shouldn't have to re-explain your codebase every time.

---

## Key Features

- **Automatic Session Capture** — 5 lifecycle hooks intercept Claude's activity
- **AI-Powered Compression** — Semantic summaries reduce storage and retrieval cost
- **3-Layer Retrieval** — Compact index → timeline → full details (10x token savings)
- **Hybrid Search** — SQLite FTS5 + Chroma vector database
- **4 MCP Search Tools** — Token-efficient retrieval within Claude sessions
- **Privacy Controls** — `<private>` tags exclude sensitive data
- **Web Viewer UI** — Local dashboard at localhost:37777
- **Multi-IDE** — Claude Code, Gemini CLI, OpenCode
- **Citations** — Every injected memory references its source observation

---

## Scoring

| Criteria | Score | Rationale |
|----------|-------|-----------|
| Documentation Quality | 8/10 | Dedicated docs site, multi-language support |
| Ease of Setup | 7/10 | One-line NPX install. Multi-runtime deps add hidden complexity |
| Community Activity | 9/10 | 61.3K stars, 5.1K forks, 231 releases, active Discord |
| Production Readiness | 7/10 | v12.1.6 with 231 releases. 141 open issues temper confidence |
| Extensibility | 8/10 | MCP tools, plugin marketplace, multi-IDE, configurable |
| Revenue Generation Potential | 7/10 | Massive user base. Dual licensing path available |

**Overall Score: 7.7/10**

---

## Best Use Cases

- Long-running development projects with daily Claude Code usage
- Complex codebases where re-explaining architecture wastes tokens
- Multi-session refactoring/migration projects
- Privacy-conscious developers (local-only storage)
- Power users wanting a "second brain" for their AI assistant

## Not Recommended For

- Enterprise with strict AGPL concerns
- Casual/infrequent Claude Code users
- Resource-constrained machines (SQLite + Chroma + Bun overhead)
- Deterministic context needs (AI compression loses some detail)

---

## Final Verdict

Claude-Mem is the **clear market leader** in persistent memory for AI coding agents. The 3-layer progressive retrieval, hybrid search, and AI compression are genuine engineering sophistication. With 61.3K stars and 231 releases, it has extraordinary traction. **If you use Claude Code regularly, this is essential. For enterprise adoption, evaluate the AGPL license carefully.**

---

> **Deep dive:** See [deep-analysis.md](deep-analysis.md) for architecture, Mem0/Zep comparison, and revenue strategies.
