---
tags: [OpenAI, GPT, LLM, AI, 2026]
date: 2026-05-28
---

# OpenAI GPT-5.5 — Model Summary

**Related:** [[LLM-Model-Comparison-May-2026]] (competitive context) · [[Claude-Opus-4.8-Model-Summary]] (alternative for code review) · [[Qwen-3.7-Max-Model-Summary]] (alternative for coding agent)

**Release Date:** May 28, 2026 (Instant Update); GPT-5.4 Thinking launched March 5, 2026  
**Source:** [OpenAI Help Center — Model Release Notes](https://help.openai.com/en/articles/9624314-model-release-notes)  
**Developer:** OpenAI  

---

## Overview

OpenAI's current flagship family is **GPT-5.5** (instant variant), with GPT-5.4 Thinking as the reasoning-heavy counterpart. The o-series (o3) is being retired from ChatGPT in August 2026 — OpenAI has consolidated around the GPT-5.x family. GPT-5.5 is the strongest agentic coding model OpenAI has released.

---

## Model Family Overview (Current)

| Model | Type | Status |
|-------|------|--------|
| **GPT-5.5 Instant** | General-purpose, fast | Current flagship (ChatGPT + API) |
| **GPT-5.5 Thinking** | Reasoning + coding | Current flagship reasoning (ChatGPT + API) |
| **GPT-5.4 Pro** | Top-tier reasoning + agentic | Highest capability tier |
| **GPT-5.4 Thinking** | Reasoning + coding | Mid-tier reasoning |
| **GPT-5.4 mini** | Lightweight, fast | Free-tier accessible via "Think" feature |
| o3 | Reasoning | Being retired from ChatGPT (Aug 26, 2026), remains in API |

---

## Key Capabilities

| Domain | Highlights |
|--------|------------|
| **Coding (Terminal-Bench 2.0)** | Strongest OpenAI model on complex command-line workflows |
| **Agentic Tool Use** | Best-in-class on SWE-bench Pro, OSWorld, bfcl benchmarks |
| **Benchmarks** | APEX-Agents #1 leaderboard; SWE-bench Pro: 57.7%; OSWorld: 75% (above 72.4% human expert baseline) |
| **Deep Web Research** | Improved specificity in search queries |
| **Context Maintenance** | Better handling of extended reasoning sessions |

---

## Notable Benchmarks (GPT-5.4 series)

| Benchmark | Score | Notes |
|-----------|-------|-------|
| **SWE-bench Pro** | 57.7% | Complex real-world software engineering |
| **OSWorld** | 75% | Above 72.4% human expert baseline |
| **Terminal-Bench 2.0** | State-of-the-art | Complex CLI workflows |
| **APEX-Agents** | #1 on leaderboard | OpenAI's internal agent benchmark |

---

## Canvas Deprecation

GPT-5.5 consolidates Canvas functionality directly into chat:
- **Writing blocks**: Rich inline document editing in chat
- **Code blocks**: Integrated code execution and iteration
- Canvas remains available for paid users on legacy models during sunset

---

## Recent ChatGPT Retirements (2026)

| Model | Retired Date |
|-------|-------------|
| GPT-5.1 (Instant, Thinking, Pro) | March 11, 2026 |
| GPT-4o, GPT-4.1, GPT-4.1 mini, o4-mini | February 13, 2026 |
| GPT-4.5 | June 27, 2026 |
| o3 | August 26, 2026 |

---

## API Availability

- **ChatGPT:** All plans (Plus, Pro, Team, Enterprise, Edu)
- **API:** `gpt-5.5` model string (varies by provider)
- **Free users:** GPT-5.4 mini via "Think" in composer

---

## Takeaways for Engineers

- OpenAI has fully consolidated around GPT-5.x branding — o-series is being phased out of consumer ChatGPT
- **Canvas deprecation** means inline document + code editing moves into native chat
- GPT-5.5's agentic coding improvements make it the default choice for code generation and complex CLI workflows
- If you were using o3 for heavy reasoning, migrate to GPT-5.4/GPT-5.5 Thinking before August retirement
- For production API workloads, audit deprecated model string references (GPT-4o retired Feb 2026)

---

## Cross-Note Connections

| From | To | Connection |
|------|----|-----------|
| [[OpenAI-GPT-5.5-Model-Summary]] | [[Qwen-3.7-Max-Model-Summary]] | Both compete on coding benchmarks; GPT-5.5 leads ecosystem, Qwen leads raw performance |
| [[OpenAI-GPT-5.5-Model-Summary]] | [[Claude-Opus-4.8-Model-Summary]] | Both Western flagship models; Claude leads on honesty, OpenAI leads on Codex CLI ecosystem |
| [[OpenAI-GPT-5.5-Model-Summary]] | [[DeepSeek-V3.2-Model-Summary]] | Both offer reasoning modes; DeepSeek has open weights, OpenAI has more mature API ecosystem |
| [[OpenAI-GPT-5.5-Model-Summary]] | [[LLM-Model-Comparison-May-2026]] | Decision matrix: GPT-5.5 recommended as safe general-purpose fallback + best ecosystem |