# AI Security Resources

A curated list of courses, talks, labs, tools, papers, researchers, communities and references for learning AI / LLM security and red teaming.

## Table of Contents

1. [Courses](#1-courses)
2. [YouTube Videos and Recorded Talks](#2-youtube-videos-and-recorded-talks)
3. [Open-Source Labs and Practice Environments](#3-open-source-labs-and-practice-environments)
4. [Open-Source Testing Tools](#4-open-source-testing-tools)
5. [Research Papers](#5-research-papers)
6. [Security Researchers to Follow](#6-security-researchers-to-follow)
7. [Communities and Groups](#7-communities-and-groups)
8. [Articles, Blogs, and Technical References](#8-articles-blogs-and-technical-references)
9. [Very Important Repositories](#9-very-important-repositories)
10. [Personal Notes: Topics to Prioritize](#10-personal-notes-topics-to-prioritize)

---

## 1. Courses

| # | Course | Topics |
|---|--------|--------|
| 1.1 | [The Ultimate AI LLM Penetration Testing Training Course (Udemy)](https://www.udemy.com/course/the-ultimate-ai-llm-penetration-testing-training-course/?couponCode=MT261102IN) | LLM penetration testing |
| 1.2 | [Hands On AI (LLM) Red Teaming, Jitendra Chauhan (Udemy)](https://www.udemy.com/course/hands-on-ai-llm-red-teaming/) | LLM architecture, adversarial testing, jailbreaking, practical red teaming |
| 1.3 | [Hacking AI Agents: Hands-On LLM Red Teaming, Amar Massoud (Udemy)](https://www.udemy.com/course/hacking-ai-agents-hands-on-llm-red-teaming/) | Indirect prompt injection, memory poisoning, tool abuse, automated testing |
| 1.4 | [Red Teaming LLM Applications, DeepLearning.AI](https://www.deeplearning.ai/courses/red-teaming-llm-applications) | Manual and automated testing of LLM applications using Giskard. Introductory foundation before advanced practice |

---

## 2. YouTube Videos and Recorded Talks

| # | Talk | Topics |
|---|------|--------|
| 2.1 | [Using PyRIT as a Bug Hunter, Microsoft AI Red Team](https://www.youtube.com/watch?v=jq9DcEL3cHE) | AI security findings, bug bounty testing, PyRIT demonstrations |
| 2.2 | [Agentic ProbLLMs: Exploiting AI Computer-Use and Coding Agents, Johann Rehberger](https://media.ccc.de/v/39c3-agentic-probllms-exploiting-ai-computer-use-and-coding-agents) | Agent exploitation, indirect prompt injection, data exfiltration, persistence, mitigations |
| 2.3 | [PoisonedRAG, USENIX Security 2025](https://www.usenix.org/conference/usenixsecurity25/presentation/zou-poisonedrag) | Knowledge corruption attacks against retrieval-augmented generation |

---

## 3. Open-Source Labs and Practice Environments

| # | Lab | Topics |
|---|-----|--------|
| 3.1 | [Arcanum AI Security Resources](https://arcanum-sec.github.io/ai-sec-resources/) | Resource hub (no installation needed) |
| 3.2 | [PortSwigger Web Security Academy: Web LLM Attacks](https://portswigger.net/web-security/llm-attacks) | Excessive agency, indirect prompt injection, API exploitation, insecure output handling |
| 3.3 | [Microsoft AI Red Teaming Playground Labs](https://github.com/microsoft/AI-Red-Teaming-Playground-Labs) | Hands-on AI red teaming challenges and training environments |
| 3.4 | [AI Goat (dhammon)](https://github.com/dhammon/ai-goat) | Locally hosted vulnerable LLM applications and CTF challenges |
| 3.5 | [AIGoat (AI Security Consortium)](https://github.com/AISecurityConsortium/AIGoat) | Prompt injection, RAG poisoning, agent security, MCP security, defenses |
| 3.6 | [AgentDojo](https://github.com/ethz-spylab/agentdojo) | Evaluating indirect prompt injection attacks and defenses against tool-using agents |
| 3.7 | [InjecAgent](https://github.com/uiuc-kang-lab/InjecAgent) | Benchmarking indirect prompt injection against tool-integrated agents |
| 3.8 | [PoisonedRAG (Official Implementation)](https://github.com/sleeepeer/PoisonedRAG) | Reproducing knowledge database poisoning attacks against RAG systems |

---

## 4. Open-Source Testing Tools

| # | Tool | Topics |
|---|------|--------|
| 4.1 | [Microsoft PyRIT](https://github.com/microsoft/PyRIT) | Programmable red teaming, multi-turn attacks, scoring, repeatable evaluations |
| 4.2 | [Promptfoo](https://www.promptfoo.dev/docs/red-team/quickstart/) | Application security evaluations, custom tests, regression testing, CI integration |
| 4.3 | [NVIDIA garak](https://github.com/NVIDIA/garak) | Automated LLM vulnerability probing and attack detection |

---

## 5. Research Papers

| # | Paper | Research Topic |
|---|-------|----------------|
| 5.1 | [Not What You've Signed Up For: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/abs/2302.12173) | Indirect prompt injection through attacker-controlled external content |
| 5.2 | [InjecAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated LLM Agents](https://arxiv.org/abs/2403.02691) | Unauthorized actions and data theft through agent tools |
| 5.3 | [AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents](https://proceedings.neurips.cc/paper_files/paper/2024/hash/97091a5177d8dc64b1da8bf3e1f6fb54-Abstract-Datasets_and_Benchmarks_Track.html) | Realistic agent tasks, security evaluation, attack-defense comparisons |
| 5.4 | [PoisonedRAG: Knowledge Corruption Attacks to Retrieval-Augmented Generation of LLMs](https://arxiv.org/abs/2402.07867) | Manipulating RAG answers by poisoning the knowledge database |
| 5.5 | [Universal and Transferable Adversarial Attacks on Aligned Language Models](https://arxiv.org/abs/2307.15043) | Optimization-based adversarial suffixes and cross-model transferability |
| 5.6 | [Many-shot Jailbreaking](https://www.anthropic.com/research/many-shot-jailbreaking) | Long-context attacks using repeated demonstrations to influence model behavior |
| 5.7 | [Agent Security Bench: Formalizing and Benchmarking Attacks and Defenses in LLM-based Agents](https://arxiv.org/abs/2410.02644) | Agent attack surfaces, memory poisoning, systematic defense evaluation |
| 5.8 | [MCPTox: A Benchmark for Tool Poisoning Attack on Real-World MCP Servers](https://arxiv.org/abs/2508.14925) | Malicious tool descriptions and MCP-based agent manipulation |
| 5.9 | [WASP: Benchmarking Web Agent Security Against Prompt Injection Attacks](https://arxiv.org/abs/2504.18575) | Indirect prompt injection against web navigation agents |
| 5.10 | [PyRIT: A Framework for Security Risk Identification and Red Teaming in Generative AI Systems](https://arxiv.org/abs/2410.02828) | Framework design for automated generative AI red teaming |

---

## 6. Security Researchers to Follow

| # | Researcher | Focus |
|---|------------|-------|
| 6.1 | [Johann Rehberger (Embrace The Red)](https://embracethered.com/blog/) | Practical AI exploitation, prompt injection, agent security, memory persistence |
| 6.2 | [Kai Greshake](https://kai-greshake.de/) | Indirect prompt injection, trust boundaries, LLM application security |
| 6.3 | [Nicholas Carlini](https://nicholas.carlini.com/papers) | Adversarial machine learning, model privacy, rigorous security evaluation |
| 6.4 | [Simon Willison](https://simonwillison.net/) | Prompt injection, agent architecture, MCP, AI security analysis |
| 6.5 | [Microsoft AI Red Team / PyRIT Contributors](https://github.com/microsoft/PyRIT) | Practical AI red teaming methods, tooling, evaluation |

---

## 7. Communities and Groups

| # | Community | Focus |
|---|-----------|-------|
| 7.1 | [AI Village](https://aivillage.org/) | AI security research, hands-on experimentation, community events |
| 7.2 | [AI Village Discord](https://aivillage.org/discord/) | Community chat |
| 7.3 | [OWASP GenAI Security Project](https://genai.owasp.org/contribute/) | LLM and agent security guidance, research collaboration, community contributions |
| 7.4 | [OWASP AI Exchange](https://owaspai.org/connect/) | Broader AI security discussions and technical guidance |
| 7.5 | [OWASP Slack](https://owasp.org/slack/invite) | AI Exchange channel: `#project-ai-community` |

---

## 8. Articles, Blogs, and Technical References

| # | Resource | Topics |
|---|----------|--------|
| 8.1 | [Embrace The Red (Research Blog)](https://embracethered.com/blog/) | Real vulnerability disclosures, exploit chains, mitigations |
| 8.2 | [MCP Security Notification: Tool Poisoning Attacks, Invariant Labs](https://invariantlabs.ai/blog/mcp-security-notification-tool-poisoning-attacks) | Malicious tool metadata, agent manipulation, data exfiltration |
| 8.3 | [The Lethal Trifecta for AI Agents, Simon Willison](https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/) | Risks from combining private data, untrusted content, and external communication |
| 8.4 | [OWASP RAG Security Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/RAG_Security_Cheat_Sheet.html) | Document ingestion, retrieval security, access controls, RAG pipeline protections |
| 8.5 | [OWASP AI Agent Security Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/AI_Agent_Security_Cheat_Sheet.html) | Tool permissions, memory, trust boundaries, agent lifecycle security |
| 8.6 | [MITRE ATLAS](https://atlas.mitre.org/) | AI adversary tactics, techniques, mitigations, case studies |
| 8.7 | [Promptfoo Red Teaming Guide](https://www.promptfoo.dev/docs/guides/llm-redteaming/) | Automated application testing, evaluation design, security regression tests |

---

## 9. Very Important Repositories

1. [CL4R1T4S](https://github.com/elder-plinius/CL4R1T4S): collection of system prompts from every major AI model.
2. [L1B3RT4S](https://github.com/elder-plinius/L1B3RT4S): jailbreak examples for all major AI models.

---

## 10. Personal Notes: Topics to Prioritize

- [ ] Indirect prompt injection through documents, websites, emails, and tool responses
- [ ] RAG poisoning, retrieval manipulation, and cross-tenant document access
- [ ] Agent tool authorization, excessive agency, and confused deputy vulnerabilities
- [ ] MCP tool poisoning and cross-server trust boundaries
- [ ] Memory poisoning and persistent cross-session manipulation
- [ ] Insecure output handling and downstream web vulnerabilities
- [ ] Multimodal prompt injection through images, audio, and document processing
- [ ] Model extraction, training data leakage, and membership inference
- [ ] Model, dataset, dependency, and AI supply-chain security
- [ ] Evaluation methodology: attack success rate, legitimate task completion, false positives, repeatability, and defense regression testing
