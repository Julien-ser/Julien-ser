# Julien Serbanescu

**Computer Engineering Co-op @ University of Guelph** (GPA 3.94/4.0) · **Cloud Engineer @ Co-Operators** · AI Security Researcher

**[Portfolio](https://julien-ser.github.io/JulienSerbanescu)** · **[LinkedIn](https://linkedin.com/in/julien-serbanescu)** · **[ORCID](https://orcid.org/0009-0000-2305-0228)**

---

## Open Source Contributions

**4 merged PRs**, plus a maintainer-absorbed cross-provider fix credited via `Co-authored-by` across 3 of my PRs.

| Project | What | Status |
|---------|------|--------|
| [pydantic-ai](https://github.com/pydantic/pydantic-ai) ⭐ 10k | Fixed Cohere `tool_choice` silently dropped in v2 chat API — maintainer extended with VCR tests + named-subset handling | ✅ [Merged #5833](https://github.com/pydantic/pydantic-ai/pull/5833) |
| [mcp-atlassian](https://github.com/sooperset/mcp-atlassian) | Added Confluence permission-checking tools | ✅ [Merged #1320](https://github.com/sooperset/mcp-atlassian/pull/1320) |
| [mcp-atlassian](https://github.com/sooperset/mcp-atlassian) | Fixed Jira non-image attachments silently dropped by MCP clients (returned as rejected image blob) | ✅ [Merged #1469](https://github.com/sooperset/mcp-atlassian/pull/1469) (co-author, `Co-authored-by` credit) |
| [mcp-atlassian](https://github.com/sooperset/mcp-atlassian) | Wired up cross-request credential validation cache, closing a WAF rate-limit trap | ✅ [Merged #1481](https://github.com/sooperset/mcp-atlassian/pull/1481) (co-author, consolidated with an independently-opened fix) |
| [pydantic-ai](https://github.com/pydantic/pydantic-ai) ⭐ 10k | Cohere: implemented `request_stream` / `CohereStreamedResponse` — full streaming support where none existed | 🔄 [PR #6100](https://github.com/pydantic/pydantic-ai/pull/6100) — approved, CI green |
| [pydantic-ai](https://github.com/pydantic/pydantic-ai) ⭐ 10k | Dropped foreign `ThinkingPart`s from history by default across 5 providers (Anthropic, Bedrock, Groq, HuggingFace, xAI) to stop reasoning leaks | 🔄 [PR #5920](https://github.com/pydantic/pydantic-ai/pull/5920) (co-author, absorbs 3 of my provider-specific PRs) |
| [smolagents](https://github.com/huggingface/smolagents) ⭐ 17k | Fixed `KeyError` on `tool_calls` in `AmazonBedrockModel` with cross-region inference profiles | 🔄 [PR #2363](https://github.com/huggingface/smolagents/pull/2363) |
| [smolagents](https://github.com/huggingface/smolagents) ⭐ 17k | Fixed broken Space link in tools tutorial (Python 3.13 incompatibility) | 🔄 [PR #2364](https://github.com/huggingface/smolagents/pull/2364) |
| [crewAI](https://github.com/crewAIInc/crewAI) ⭐ 31k | Show updated agent answer before feedback prompt when `verbose=False` | 🔄 [PR #6386](https://github.com/crewAIInc/crewAI/pull/6386) |

---

## Research

| Venue | Year | Role | Paper |
|-------|------|------|-------|
| SIGIR-AP | 2025 | **First Author · Best Paper Nominee** | FalseCoTQA — Adversarial Multi-Hop QA via Knowledge-Grounded False Chains of Thought |
| CIKM | 2025 | Co-author | Uncovering the Persuasive Fingerprint of LLMs in Jailbreaking Attacks |
| Canadian AI | 2026 | Co-author | Cause-Conditioned Multi-Task Learning for Answerable Question Suggestion in MRC |
| Canadian AI | 2026 | Co-author | From Hints to Answers: Uncertainty-Aware LLM-Guided Retrieval for Multi-Hop QA |
| SIGIR-AP | 2024 | Co-author | UnAnswGen — Generating Unanswerable Questions in MRC |

---

## Featured Projects

| Project | Stack | What it is |
|---|---|---|
| [Argus](https://github.com/Julien-ser/argus) | Claude Code, SQLite, FastAPI, React/Vite | Claude Code observability platform — Pre/PostToolUse hooks trace 12+ event types; 29 sessions, 1.4M+ tokens, 198 flagged events tracked; composite trust score |
| [AgenticRobot](https://github.com/Julien-ser/AgenticRobot) | Claude Code, MCP, FastMCP, Raspberry Pi Pico W | Natural-language robot control via 15 FastMCP tools over TCP WiFi; mecanum-wheel 4WD, obstacle avoidance, servo radar |
| [FalseCoTQA](https://github.com/Julien-ser/FalseCoTQA) | Python, NLP | SIGIR-AP 2025 Best Paper Nominee — adversarial multi-hop QA benchmark, knowledge-grounded false chains of thought |
| EarningsSignal | LangChain (LCEL), LangGraph, FastMCP, SEC EDGAR | Quant-recruiting portfolio piece — LLM-structured extraction of trading signals from real 10-K/10-Q filings, backtested against forward returns with lookahead-bias discipline |
| [ResumeWorthy](https://github.com/Julien-ser/ResumeWorthy) | Next.js, TypeScript, Supabase, Vercel | AI job-application assistant — resume tailoring, job matching, recruiter finder |
| Cybersecurity Portfolio | Splunk, Kali, BurpSuite, VirtualBox | 7 job-landing security portfolio projects; AI Red-Teaming module already found a genuine prompt-injection leak |
| [AKO-Agentic-Kernel-Optimization](https://github.com/Julien-ser/AKO-Agentic-Kernel-Optimization) | Python, Agentic AI, AMD/HPC | Autonomous system that generates, profiles, and refines GPU kernels for high-performance AI inference on AMD hardware |
| PacmanRL | Python | UC Berkeley CS188 Reinforcement Learning project, full 21/21 autograder pass |

See the [portfolio](https://julien-ser.github.io/JulienSerbanescu) for the full interactive project explorer, or ask its built-in terminal a question directly.

---

## What I'm Working On

- **Co-Operators** — Azure + Splunk cloud engineering; IGA/PAM compliance; FastAPI automation across Jira/Confluence
- **Cyber Science Lab @ U of Guelph** — LLM jailbreak pipelines (97% ASR), RL-based real-time defenses, VLM adversarial vaccination
- **OSS** — contributing to AI/ML libraries (pydantic-ai, smolagents, crewAI, mcp-atlassian)

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat&logo=splunk&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)

---

## Certifications

**Anthropic (2026):** Building with Claude API · Claude Code 101 · Claude Code in Action · Intro to Subagents · Intro to Agent Skills · Introduction to MCP · MCP Advanced Topics · Claude 101 · AI Fluency Framework · Introduction to Claude Cowork

**Oracle:** Agentic AI Certified Foundations Associate

**Google Cloud:** Vertex AI ML Solutions · ML APIs · BigQuery ML · Security Command Center

**Other:** Splunk Enterprise Security · MLOps Essentials (NASBA) · Databricks GenAI

---

<sub>serbanej@uoguelph.ca · [LinkedIn](https://linkedin.com/in/julien-serbanescu) · [ORCID](https://orcid.org/0009-0000-2305-0228) · [Portfolio](https://julien-ser.github.io/JulienSerbanescu)</sub>
