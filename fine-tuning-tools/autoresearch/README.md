---
name: "AutoResearch"
category: "Fine-tuning Tools & Techniques"
tags: ["autonomous-research", "ml-experiments", "karpathy", "self-improving-ai", "reinforcement-learning", "single-gpu"]
repo_url: "https://github.com/karpathy/autoresearch"
stars: 73800
license: "MIT"
language: "Python"
last_updated: "2026-04-17"
---

# AutoResearch — AI That Trains AI, Indefinitely

> **TL;DR:** Karpathy's autonomous ML research agent. Runs 100+ experiments overnight on a single GPU. The agent writes code, runs training, iterates, and keeps what works. You just maintain a single markdown file. 73.8K stars. MIT License.

| Metric | Value |
|--------|-------|
| **Repository** | [karpathy/autoresearch](https://github.com/karpathy/autoresearch) |
| **Author** | Andrej Karpathy (former Tesla AI Director, OpenAI founding member) |
| **Stars** | 73,800+ |
| **Forks** | 10,700+ |
| **Watchers** | 598 |
| **License** | MIT |
| **Language** | Python (83.4%), Jupyter (16.6%) |
| **Hardware** | Single NVIDIA GPU (H100 recommended) |

---

## Overview

AutoResearch is an experimental system by Andrej Karpathy that enables AI agents to conduct autonomous machine learning research without human intervention. The core idea: give an AI agent a training script, a fixed 5-minute compute budget per experiment on a single GPU, and a clear optimization metric (validation bits per byte) — then let it run 100+ experiments overnight. The agent writes code modifications, runs training, evaluates results, and iterates, keeping only improvements. Every experiment is a git commit, creating a full audit trail.

**Who built it:** Andrej Karpathy — one of the most respected names in AI
**Problem it solves:** ML research is tedious iteration. AutoResearch automates the explore-evaluate-iterate loop, running dozens of experiments while you sleep.

---

## Key Features

- **Fully Autonomous ML Loop** — Agent modifies code, trains, evaluates, iterates — zero human in the loop
- **5-Minute Budget Per Experiment** — Fixed time constraint ensures fair comparison across all runs
- **Git-Based Tracking** — Every experiment = a commit with full diff and metric
- **Single GPU Operation** — No cluster needed (tested on H100)
- **Human-Editable Strategy** — `program.md` lets you guide research direction without touching code
- **100+ Experiments Overnight** — Vastly exceeds what a human researcher could try manually
- **Clear Metric** — Validation bits per byte (lower = better)
- **Separation of Concerns** — `prepare.py` (fixed) vs `train.py` (agent-modified)
- **Community Forks** — macOS, Windows, AMD GPU adaptations

---

## Scoring

| Criteria | Score | Rationale |
|----------|-------|-----------|
| Documentation Quality | 6/10 | Thoughtful README but lacks setup guides and tutorials. "Clean code is the docs" style |
| Ease of Setup | 5/10 | Requires NVIDIA GPU (ideally H100), Python 3.10+, uv package manager |
| Community Activity | 9/10 | 73.8K stars, 10.7K forks, 130 open PRs, massive engagement |
| Production Readiness | 3/10 | Explicitly experimental. No production patterns, monitoring, or reliability features |
| Extensibility | 7/10 | Clean file separation makes adaptation easy. Extending to non-LM tasks requires work |
| Revenue Generation Potential | 7/10 | Concept has enormous commercial potential if productized |

**Overall Score: 6.2/10**

---

## Best Use Cases

- Overnight ML exploration (set it, sleep, wake up to results)
- Architecture search (discover novel model designs)
- Training recipe optimization (learning rates, schedules, optimizers)
- Educational demonstrations of autonomous AI research
- Baseline establishment on language modeling tasks
- Rapid prototyping of ML ideas
- Inspiration mining from experiment git logs

## Not Recommended For

- Production model training
- Large-scale model training (5-min budget limits scale)
- Non-language-modeling tasks (needs adaptation)
- Teams without GPU access
- Regulated environments requiring human review
- Deterministic reproducibility needs

---

## Final Verdict

AutoResearch is a genuinely innovative project that demonstrates the future of autonomous ML research. Backed by Karpathy's unmatched credibility and a 73.8K-star community, it's one of the most important conceptual contributions to AI tooling. However, it remains an experimental prototype — its value today lies in inspiration, education, and as a foundation for specialized autonomous research systems. **Highly recommended for ML researchers, AI enthusiasts, and anyone building the next generation of autonomous AI development tools.**

---

> **Deep dive:** See [deep-analysis.md](deep-analysis.md) for architecture breakdown, AutoML comparison, revenue strategies, and business ideas.
