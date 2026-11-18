# Hi, I'm Deniz 👋

**Software & AI engineer in Budapest. I test what AI actually does on real hardware, and publish the numbers, including when it fails.**

By day I build data products and MCP servers. Before that: motor-control software, camera inspection,
sensor calibration and test rigs. That's why I trust a measurement more than a demo.

---

## 🔥 What I'm building

### [Prometheus](https://github.com/nilusitechtigris/Prometheus): bring the fire home

A native Mac app for running open AI models locally, with a **harness** that helps small models do more: sandboxed
code, trusted search, checks in code, a 3-agent council and a coding agent. No account, no cloud.

> Same 1.7B model, same 100 questions: **24 → 62** with the harness switched on.

<a href="https://github.com/nilusitechtigris/Prometheus"><img src="https://github.com/nilusitechtigris/Prometheus/raw/main/docs/screenshots/side-by-side.png" width="640" alt="The same question asked twice: the plain model answers 14, the harness answers 36, and code confirms 36"></a>

### [Silicon AI News](https://siliconainews.com): AI news with the evidence attached

Every story links its sources, company claims are labelled as claims, and corrections are public.
Also available to AI assistants as a free [MCP server](https://github.com/nilusitechtigris/silicon-ai-news-mcp).

---

## 🧪 Lab notes

One question per experiment. Every result comes with its raw data and a way to reproduce it.

| When | Question | Answer | Data |
|---|---|---|---|
| Nov 2026 | How hard is my 100-task benchmark for a 27B 4-bit model? | Qwen3.8-27B passed **79 of 100** tasks, all graded by code (no LLM judge). Ready for Qwen4. | [Qwen3.8_VS_Qwen4](https://github.com/nilusitechtigris/Qwen3.8_VS_Qwen4) |
| Nov 2026 | How fast are 20 open LLMs on a 24 GB Mac mini M4 Pro? | **tokens/s ≈ 220 ÷ model size in GB.** MoE wins: gpt-oss:20b runs at 52.5 tok/s. | [benchmark](https://github.com/nilusitechtigris/MACMINIM4PRO_12CPU_16GPU_24RAM_512SSD) |
| Nov 2026 | Can a better harness beat a bigger model? | Yes: a 1.7B model went from 24 to 62 / 100 and beat a model twice its size. | [Prometheus](https://github.com/nilusitechtigris/Prometheus) |
| May 2026 | Does training a 1.7B base on DeepSeek R1 traces make it reason better? | **No.** GSM8K fell 79% → 67% and answers got 4–8× slower. It learned the *style* of reasoning, not the skill. | [tiny-reasoning-qwen3](https://github.com/nilusitechtigris/tiny-reasoning-qwen3) |

<a href="https://github.com/nilusitechtigris/MACMINIM4PRO_12CPU_16GPU_24RAM_512SSD"><img src="https://github.com/nilusitechtigris/MACMINIM4PRO_12CPU_16GPU_24RAM_512SSD/raw/main/charts/speed_vs_memory.svg" width="640" alt="Generation speed versus memory use for 20 local LLMs on a Mac mini M4 Pro"></a>

---

## 🏆 Hackathons

- **1st place**: recipe-to-cart assistant for ALDI International IT Services (AI Klub hackathon)
- **2nd place**: zero-token knowledge graph for ABAP developers (SAP hackathon, Budapest)

## 🛠️ Stack

Python · TypeScript · Swift · ABAP · LangChain / LangGraph · MCP · Ollama · MLX · llama.cpp · SAP BTP & Joule Studio

## 📫 Elsewhere

[LinkedIn](https://www.linkedin.com/in/deniz-daniel-yetik-engineer/) · [Silicon AI News](https://siliconainews.com) ·
Happy to talk about local LLMs, agent harnesses and honest benchmarks.
