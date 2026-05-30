---
tags: [Anthropic, Claude, LLM, AI, 2026]
date: 2026-05-28
---

# Claude Opus 4.8 — Model Summary

**Release Date:** May 28, 2026  
**Source:** [Anthropic News](https://www.anthropic.com/news/claude-opus-4-8)  
**Developer:** Anthropic  

---

## Overview

Claude Opus 4.8 is Anthropic's latest flagship model, succeeding Opus 4.7. It brings measurable improvements in **coding, agentic tasks, honesty, and alignment** — all at the same price point as Opus 4.7. Ships with **Dynamic Workflows** (research preview) and **Effort Control** as new product features.

---

## Key Capabilities

| Domain | Highlights |
|--------|------------|
| **Coding** | Terminal-Bench 2.1 improvements; ~4× less likely to let code flaws pass unremarked |
| **Agentic Tasks** | OSWorld-Verified, Super-Agent benchmark (only model to complete every case end-to-end at parity cost) |
| **Computer Use** | Online-Mind2Web: 84% — meaningful jump over Opus 4.7 and GPT-5.5 |
| **Honesty** | ~4× less likely to allow flaws in code to pass unremarked; more likely to flag uncertainties |
| **Alignment** | Misaligned behavior rates substantially lower than Opus 4.7; comparable to Claude Mythus Preview |
| **Cost Efficiency** | Fast mode is **3× cheaper** than previous models, running at **2.5× the speed** |

---

## New Product Features

### 1. Dynamic Workflows (Research Preview)
- Available in Claude Code for Enterprise, Team, Max plans
- Allows Claude to run **hundreds of parallel subagents** in a single session
- Plans work, spawns subagents, verifies outputs before reporting
- Use case: Codebase-scale migrations across hundreds of thousands of lines with test suite as validation bar

### 2. Effort Control
- New control alongside model selector (available on all plans)
- **Low / Standard / Extra (xhigh) / Max** effort levels
- Default is high effort (best quality/experience balance)
- Increased rate limits in Claude Code for higher token usage

### 3. Messages API Update
- System entries accepted **inside the messages array**
- Update Claude's instructions mid-task (permissions, token budgets, environment context)
- No prompt cache invalidation when updating agent state mid-run

---

## Partner Benchmark Results

| Benchmark | Result | Notes |
|-----------|--------|-------|
| **Super-Agent Benchmark** | Only model to complete every case end-to-end | Beat prior Opus and GPT-5.5 at cost parity |
| **CursorBench** | Exceeds prior Opus models across every effort level | More efficient tool calling |
| **Legal Agent Benchmark** | Highest score recorded | First model to break 10% on all-pass standard |
| **Online-Mind2Web (computer use)** | **84%** | Meaningful jump over Opus 4.7 and GPT-5.5 |
| **Databricks Genie** | Step change in agentic reasoning | **61% cheaper token cost** than Opus 4.7 |
| **Hebbia (financial docs)** | Strong quality | Improved citation precision and token efficiency |

---

## Pricing

| Mode | Input | Output |
|------|-------|--------|
| **Standard** | $5 / M tokens | $25 / M tokens |
| **Fast Mode** | $10 / M tokens | $50 / M tokens |

Fast mode is **3× cheaper** and **2.5× faster** than Opus 4.7's fast mode.

---

## What's Coming

### Project Glasswing
- New class of models with intelligence **above Opus**
- **Claude Mythos Preview** in use by select organizations (cybersecurity focus)
- Expected to reach all customers **"in the coming weeks"**

### Cost Reduction
Working toward providing Opus-class capabilities at lower cost.

---

## Takeaways for Engineers

- **Honesty + reliability** are the headline improvements — ~4× less likely to let code flaws pass unremarked
- **Dynamic Workflows** changes the game for large codebase tasks — massively parallel subagent orchestration
- **Cost reduction** (3× cheaper fast mode) makes Opus 4.8 viable for higher-volume production workloads
- Claude Mythos (above-Opus intelligence) is weeks away — if you need the absolute ceiling, worth waiting for