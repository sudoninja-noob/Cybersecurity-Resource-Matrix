# 🤖 Domain 20: AI / ML / LLM Security

> **Group:** AI, DevSecOps & Supply Chain  
> **Curated links:** 10  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

This one deserves a fairly large page because the field has split into ML security, GenAI/LLM security, agentic AI security and AI supply-chain security.

---

## Contents

01. [Overview / Fundamentals](#section-01)
02. [Methodology](#section-02)
03. [Standards / Compliance](#section-03)
04. [Official Documentation](#section-04)
05. [Checklists](#section-05)
06. [Cheat Sheets](#section-06)
07. [Tools](#section-07)
08. [Labs / Practice](#section-08)
09. [Payloads / Test Cases](#section-09)
10. [YouTube / Video](#section-10)
11. [Courses / Training](#section-11)
12. [Certifications](#section-12)
13. [Books](#section-13)
14. [Blogs / Articles](#section-14)
15. [Research Papers](#section-15)
16. [White Papers](#section-16)
17. [Conference Material](#section-17)
18. [Mind Maps](#section-18)
19. [Sample Reports](#section-19)
20. [Templates](#section-20)
21. [Case Studies / CVEs](#section-21)
22. [GitHub Repositories](#section-22)
23. [Datasets / PCAPs / Samples](#section-23)
24. [Communities / Forums](#section-24)
25. [Vendors / Products](#section-25)
26. [Latest Developments](#section-26)
27. [Learning Roadmap](#section-27)

---

## Section 01: Overview / Fundamentals <a name="section-01"></a>

- ⭐⭐⭐ [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)⭐⭐⭐ [OWASP GenAI Security Project](https://genai.owasp.org/)⭐⭐⭐ [MITRE ATLAS](https://atlas.mitre.org/)⭐⭐⭐ [NIST Generative AI Profile](https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence)NIST AI RMF is currently undergoing revision, and NIST has also been developing a critical-infrastructure AI RMF profile. ( [NIST](https://www.nist.gov/itl/ai-risk-management-framework))

---

## Section 02: Methodology <a name="section-02"></a>

Model/system inventory 
Threat modeling 
Training data 
Model supply chain 
Prompt interface 
RAG 
Embeddings/vector DB 
Tool use 
Agents 
MCP 
Authentication 
Authorization 
Output handling 
Secrets 
Data leakage 
Model extraction 
Adversarial testing 
Monitoring 
Governance

---

## Section 03: Standards / Compliance <a name="section-03"></a>

NIST AI RMF · NIST AI 600-1 · OWASP LLM Top 10 · OWASP Agentic Top 10 · MITRE ATLAS · ISO/IEC 42001 · ISO/IEC 23894.

---

## Section 04: Official Documentation <a name="section-04"></a>

[OWASP LLM Top 10 2026](https://genai.owasp.org/resource/owasp-genai-llm-top-10-2026/)[OWASP Agentic Security Initiative](https://genai.owasp.org/initiatives/agentic-security-initiative/)
OWASP released the LLM Top 10 2026 on August 3, 2026. ( [OWASP Gen AI Security Project](https://genai.owasp.org/resource/owasp-genai-llm-top-10-2026/))

---

## Section 05: Checklists <a name="section-05"></a>

Prompt injection 
Indirect prompt injection 
Sensitive-data disclosure 
Improper output handling 
Excessive agency 
Tool authorization 
RAG poisoning 
Vector database security 
Model theft 
Training data poisoning 
Supply chain 
Secrets 
System prompts 
MCP servers 
Plugins/tools 
Memory poisoning 
Agent identity 
Human approval 
Logging

---

## Section 06: Cheat Sheets <a name="section-06"></a>

OWASP GenAI cheat sheets · MITRE ATLAS technique pages · NIST AI RMF Playbook.

---

## Section 07: Tools <a name="section-07"></a>

Garak · PyRIT · Promptfoo · Giskard · ART (Adversarial Robustness Toolbox) · Counterfit · Inspect AI.

---

## Section 08: Labs / Practice <a name="section-08"></a>

OWASP AI/LLM security projects · Damn Vulnerable LLM Agent · Gandalf · prompt-injection labs.

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

Prompt injection, jailbreak robustness, data exfiltration, cross-user leakage, tool misuse, unsafe code execution, RAG poisoning and excessive-agent privilege.

---

## Section 10: YouTube / Video <a name="section-10"></a>

OWASP GenAI · DEF CON AI Village · Black Hat AI Summit · NIST AI events.

---

## Section 11: Courses / Training <a name="section-11"></a>

AI security/red teaming courses from SANS, OWASP community, MITRE and specialist providers.

---

## Section 12: Certifications <a name="section-12"></a>

No single dominant credential yet. AI governance/security certificates are emerging rapidly; prioritize hands-on evaluation skills.

---

## Section 13: Books <a name="section-13"></a>

Adversarial Machine Learning · Machine Learning Security Principles · current OWASP/NIST living guidance.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

Trail of Bits · Protect AI · HiddenLayer · Lakera · Microsoft AI Red Team · Google DeepMind safety/security.

---

## Section 15: Research Papers <a name="section-15"></a>

arXiv cs.CR / cs.LG · IEEE S&P · USENIX · ACM CCS · NeurIPS security/privacy workshops.

---

## Section 16: White Papers <a name="section-16"></a>

NIST AI RMF · NIST AI 600-1 · OWASP GenAI · MITRE ATLAS. 
NIST’s GenAI profile provides risk-management guidance specifically for generative-AI systems. ( [NIST](https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence))

---

## Section 17: Conference Material <a name="section-17"></a>

DEF CON AI Village · Black Hat · NeurIPS · ICML · USENIX · IEEE S&P.

---

## Section 18: Mind Maps <a name="section-18"></a>

AI SECURITY 

```
├── Data
```

```
│   ├── Poisoning
```

```
│   └── Privacy
```

```
├── Model
```

```
│   ├── Extraction
```

```
│   └── Adversarial Examples
```

```
├── LLM
```

```
│   ├── Prompt Injection
```

```
│   ├── Jailbreak
```

```
│   └── Data Leakage
```

```
├── RAG
```

```
├── Agents
```

```
│   ├── Tools
```

```
│   ├── Memory
```

```
│   └── Identity
```

```
├── MCP
```

```
├── Supply Chain
```

```
└── Governance
```

---

## Section 19: Sample Reports <a name="section-19"></a>

Include model/version, system prompt, RAG source, tool permissions, test case, observed behavior, exploitability, data impact and remediation.

---

## Section 20: Templates <a name="section-20"></a>

ai-security-test-plan.md 
llm-red-team-checklist.md 
prompt-injection-tests.md 
rag-security.md 
agent-security.md 
mcp-security.md 
model-supply-chain.md 
ai-security-report.md

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

Prompt-injection disclosures, poisoned models/datasets, malicious ML model files, RAG data leakage and agent tool-abuse incidents.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

Garak · PyRIT · Promptfoo · Giskard · MITRE ATLAS · IBM ART.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

AdvBench · HarmBench · jailbreak/prompt-injection benchmarks · adversarial ML datasets.

---

## Section 24: Communities / Forums <a name="section-24"></a>

OWASP GenAI Security · MITRE ATLAS · AI Village · ML security research communities.

---

## Section 25: Vendors / Products <a name="section-25"></a>

Protect AI · HiddenLayer · Lakera · Robust Intelligence/Cisco · Microsoft AI security tooling.

---

## Section 26: Latest Developments <a name="section-26"></a>

This category is moving extremely quickly. Current priority areas are: 
Agentic AI 
MCP security 
Agent identity 
Tool permissions 
Memory poisoning 
Cross-agent attacks 
RAG poisoning 
Prompt injection 
AI supply chain 
Model provenance 
Model serialization security 
AI-generated code security 
Autonomous cyber agents 
OWASP already has a separate Top 10 for Agentic Applications 2026, covering risks specific to autonomous agents, and its Agentic Security Initiative now publishes guidance for secure MCP server deployment and third-party MCP usage. ( [OWASP Gen AI Security Project](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/))

---

## Section 27: Learning Roadmap <a name="section-27"></a>

ML fundamentals → neural networks/transformers → AI threat modeling → adversarial ML → LLMs → prompt injection → RAG → tools/plugins → agents/MCP → AI supply chain → monitoring/governance → AI red teaming. 

#### Recommended GitHub master structure for these 10 
cybersecurity-resources/ 

```
│
```

```
├── 11-iot-security/
```

```
├── 12-ics-ot-scada-security/
```

```
├── 13-automotive-transportation-security/
```

```
├── 14-telecom-cellular-security/
```

```
├── 15-binary-exploitation-vulnerability-research/
```

```
├── 16-reverse-engineering/
```

```
├── 17-malware-analysis-development/
```

```
├── 18-os-kernel-security/
```

```
├── 19-cryptography-protocol-security/
```

```
└── 20-ai-ml-llm-security/
```
Inside each domain, I recommend keeping the exact same structure: 
README.md 
ROADMAP.md 
resources/ 

```
├── fundamentals.md
```

```
├── methodology.md
```

```
├── standards.md
```

```
├── official-docs.md
```

```
├── checklists.md
```

```
├── cheatsheets.md
```

```
├── tools.md
```

```
├── labs.md
```

```
├── test-cases.md
```

```
├── videos.md
```

```
├── courses.md
```

```
├── certifications.md
```

```
├── books.md
```

```
├── blogs.md
```

```
├── papers.md
```

```
├── whitepapers.md
```

```
├── conferences.md
```

```
├── mindmaps.md
```

```
├── reports.md
```

```
├── templates.md
```

```
├── case-studies.md
```

```
├── github-repositories.md
```

```
├── datasets.md
```

```
├── communities.md
```

```
├── vendors.md
```

```
└── latest-developments.md
```
This gets your master repository through Domain 20 while preserving the same 27-category taxonomy across every topic. 
Continuing the master repository with Domains 21–30. I’m keeping the same 27-category structure, but compact enough that you can use it as the base for your GitHub/website and expand any domain later. 
Your uploaded resources are especially useful here for secure code review, RFID/SDR, and space/satellite security. The code-review material includes the OWASP Code Review Guide, SAST, PentesterLab code-review material and vulnerable-source-code labs. Your RFID branch already contains RFID Security, Ethical RFID Hacking and SDR training references.

---

<div align="center">
<sub>🤖 AI / ML / LLM Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>