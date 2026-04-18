---
name: "Open Deep Research"
category: "Domain-Specific Agents"
tags: ["research-agent", "vercel", "nextjs", "together-ai", "exa", "report-generation"]
repo_url: "https://github.com/Nutlope/open-deep-research"
stars: 391
license: "MIT"
language: "TypeScript"
last_updated: "2026-04-17"
---

# Open Deep Research — AI-Powered Research Report Generator

> **TL;DR:** Submit a question, get a comprehensive sourced research report. Multi-step agentic pipeline with Together.ai + Exa search. Full-stack Next.js app deployed at opendeepresearch.dev. 391 stars. MIT.

| Metric | Value |
|--------|-------|
| **Repository** | [Nutlope/open-deep-research](https://github.com/Nutlope/open-deep-research) |
| **Stars** | ~391 |
| **License** | MIT |
| **Language** | TypeScript (97.7%) |
| **Live Site** | opendeepresearch.dev |

## Overview

Full-stack Next.js research agent that plans searches, iteratively queries the web via Exa, summarizes with Together.ai LLMs, and compiles sourced reports. Uses Upstash QStash for async workflow orchestration (solving serverless timeouts). Clerk auth, Neon DB, S3 storage.

## Scoring: 5.2/10

## Final Verdict

Well-crafted reference architecture for building agentic web apps on Vercel's stack. Greatest value is the **QStash async pipeline pattern**, not the research quality itself. For actual research, use GPT Researcher (15K+ stars) or Perplexity. **Study the architecture, reference the patterns.**
