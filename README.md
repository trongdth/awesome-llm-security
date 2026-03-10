# Awesome LLM Security 2025 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

A curated list of awesome resources for Large Language Model (LLM) Security, including papers, tools, benchmarks, and best practices for building secure AI systems.

Special focus on **Agentic AI**, **RAG Security**, and **Model Context Protocol (MCP)**.

---

## Contents

- [Core Frameworks & Standards](#core-frameworks--standards)
- [Vulnerabilities & Attack Vectors](#vulnerabilities--attack-vectors)
- [Security Tools](#security-tools)
- [Benchmarks & Evaluation](#benchmarks--evaluation)
- [Agentic & MCP Security](#agentic--mcp-security)
- [Best Practices & Blueprints](#best-practices--blueprints)

---

## Core Frameworks & Standards

- [OWASP Top 10 for LLM Applications 2025](https://genai.owasp.org/llm-top-10/) - The gold standard for modern LLM application risks.
- [OWASP Top 10 for Agentic Applications 2026](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/) - Focuses on risks in autonomous AI agents (ASI01-ASI10).
- [NIST AI Risk Management Framework](https://www.nist.gov/artificial-intelligence/ai-risk-management-framework) - Comprehensive AI-RMF from the US government, updated for Model Manipulation vulnerabilities.
- [Google SAIF](https://saif.google/) - Google's Secure AI Framework, offering practical guidance for securing AI Agents.

_For detailed operation guides and blueprints, see the [Guidelines](guidelines/README.md) directory._

## Vulnerabilities & Attack Vectors

### Prompt Injection

- [Indirect Prompt Injection](https://arxiv.org/abs/2302.12173) - Exploiting untrusted input data (e.g., websites, emails) to compromise LLMs.
- [Universal and Transferable Adversarial Attacks](https://arxiv.org/abs/2307.15043) - Automated techniques to generate jailbreak sequences.

### RAG & Training Data Poisoning

- [PoisonedRAG](https://github.com/sleeepeer/PoisonedRAG) - Manipulating retrieval results by poisoning vector databases.
- [Backdoor Threats Survey](https://arxiv.org/abs/2502.05224) - A deep dive into backdoor injection techniques during model fine-tuning.

## Security Tools

### Vulnerability Scanners (Red Teaming)

- [garak](https://github.com/leondz/garak) - (NVIDIA) Vulnerability scanner for LLMs covering hallucinations, data leakage, and injections.
- [promptfoo](https://github.com/promptfoo/promptfoo) - The most powerful framework for testing, evaluating, and red teaming LLM applications.
- [PyRIT](https://github.com/microsoft/pyrit) - (Microsoft) Python Risk Identification Tool for Generative AI.

### Guardrails & Runtime Protection

- [LLM Guard](https://github.com/protectai/llm-guard) - Toolkit for actively protecting LLM interactions in real-time.
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) - NVIDIA's framework for ensuring safe and controlled conversational AI flows.
- [ClawMoat](https://github.com/openclaw/clawmoat) - (2026) Host-level security layer for AI Agents preventing unauthorized file access.

## Benchmarks & Evaluation

- [JailbreakBench](https://jailbreakbench.github.io/) - A unified leaderboard tracking the jailbreak resistance of State-Of-The-Art (SOTA) models.
- [ZeroDayBench](https://arxiv.org/abs/2603.02297v1) - Evaluates an AI Agent's capability to discover and patch vulnerabilities in real-world source code.
- [Existential Threats Benchmark](https://arxiv.org/abs/2601.19970v1) - A benchmark assessing potential existential threats posed by powerful AI models.

_A deeper exploration can be found in the [Benchmarks](benchmarks/README.md) directory._

## Agentic & MCP Security

- [MSB (MCP Security Bench)](https://openreview.net/forum?id=irxxkFMrry) - The first benchmark designed to evaluate the security of the Model Context Protocol.
- [AgentLeak](https://arxiv.org/abs/2602.11510v1) - (2026) Evaluating privacy leakage in multi-agent systems.
- [Agentic Radar](https://github.com/splx-ai/agentic-radar) - A dedicated CLI scanner mapping out vulnerabilities in agentic workflows.

## Best Practices & Blueprints

- [42 Security Checkpoints for Agents](https://gist.github.com/afrexai-cto/aac533fcc126a5b1aeb79b8bf1d81302) - Practical security guidelines and checkpoints for enterprise AI Agents.
- [Identity Propagation in MCP](https://github.com/OWASP/CheatSheetSeries/issues/2000) - Guidelines for transmitting user identification transparently across the entire AI execution layer.

---

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.
