# 🏗️ Domain 39: Security Architecture & Threat Modeling

> **Group:** Governance, Privacy & Assurance  
> **Curated links:** 4  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

This is best treated as a cross-cutting domain, because it connects almost every other domain in the repository.

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

- ⭐⭐⭐ [OWASP Threat Modeling Project](https://owasp.org/www-project-threat-modeling/)⭐⭐⭐ NIST Zero Trust Architecture ⭐⭐⭐ Threat Modeling Manifesto ⭐⭐ SABSA ⭐⭐ TOGAF security architecture OWASP recommends Shostack's technology-neutral four-question framework: what are we working on, what can go wrong, what are we going to do about it, and did we do a good job? ( [OWASP Foundation](https://owasp.org/www-project-threat-modeling/))

---

## Section 02: Methodology <a name="section-02"></a>

#### Recommended master flow: 
System Context 
→ Assets 
→ Actors 
→ Trust Boundaries 
→ Data Flows 
→ Threats 
→ Attack Paths 
→ Controls 
→ Residual Risk 
→ Security Requirements 
→ Verification

---

## Section 03: Standards / Compliance <a name="section-03"></a>

STRIDE 
PASTA 
LINDDUN 
Attack Trees 
NIST CSF 2.0 
NIST SP 800-53 
NIST SP 800-207 
SABSA 
MITRE ATT&CK 
MITRE D3FEND 
Zero Trust explicitly moves security away from implicit network-location trust toward protecting resources and continuously evaluating users/devices. ( [NIST Computer Security Resource Center](https://csrc.nist.gov/pubs/sp/800/207/final))

---

## Section 04: Official Documentation <a name="section-04"></a>

OWASP Threat Modeling · NIST ZTA · MITRE ATT&CK/D3FEND · Microsoft Threat Modeling.

---

## Section 05: Checklists <a name="section-05"></a>

assets · users · entry points · trust boundaries · data flows · secrets · dependencies · privilege · abuse cases · failure modes · mitigations · monitoring

---

## Section 06: Cheat Sheets <a name="section-06"></a>

STRIDE cheat sheet · LINDDUN cards · ATT&CK Navigator · D3FEND mappings.

---

## Section 07: Tools <a name="section-07"></a>

- ⭐⭐⭐ OWASP Threat Dragon ⭐⭐⭐ Microsoft Threat Modeling Tool ⭐⭐ pytm ⭐⭐ Threagile ⭐⭐ draw.io/PlantUML ⭐⭐ IriusRisk OWASP Threat Dragon currently supports modeling approaches including STRIDE, LINDDUN, CIA, DIE and PLOT4ai. ( [OWASP Foundation](https://owasp.org/www-project-threat-dragon/))

---

## Section 08: Labs / Practice <a name="section-08"></a>

Threat-model Juice Shop · Kubernetes · cloud architectures · sample microservices · medical/automotive architectures.

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

Misuse cases · abuse cases · trust-boundary bypass · identity compromise · dependency compromise · privilege escalation · data exposure.

---

## Section 10: YouTube / Video <a name="section-10"></a>

> Source combines sections 10–12: Video / Courses / Certs

Adam Shostack resources · OWASP threat-model talks · SABSA training · architecture-security courses.

---

## Section 11: Courses / Training <a name="section-11"></a>

> Source combines sections 10–12: Video / Courses / Certs

Adam Shostack resources · OWASP threat-model talks · SABSA training · architecture-security courses.

---

## Section 12: Certifications <a name="section-12"></a>

> Source combines sections 10–12: Video / Courses / Certs

Adam Shostack resources · OWASP threat-model talks · SABSA training · architecture-security courses.

---

## Section 13: Books <a name="section-13"></a>

- ⭐⭐⭐ Threat Modeling: Designing for Security ⭐⭐⭐ Threats: What Every Engineer Should Learn from Star Wars ⭐⭐ Security Engineering — Ross Anderson ⭐⭐ Enterprise Security Architecture

---

## Section 14: Blogs / Articles <a name="section-14"></a>

> Source combines sections 14–17: Research

OWASP · NIST · Carnegie Mellon/SEI · MITRE · IEEE Security Architecture.

---

## Section 15: Research Papers <a name="section-15"></a>

> Source combines sections 14–17: Research

OWASP · NIST · Carnegie Mellon/SEI · MITRE · IEEE Security Architecture.

---

## Section 16: White Papers <a name="section-16"></a>

> Source combines sections 14–17: Research

OWASP · NIST · Carnegie Mellon/SEI · MITRE · IEEE Security Architecture.

---

## Section 17: Conference Material <a name="section-17"></a>

> Source combines sections 14–17: Research

OWASP · NIST · Carnegie Mellon/SEI · MITRE · IEEE Security Architecture.

---

## Section 18: Mind Maps <a name="section-18"></a>

Business → assets → architecture → identities → trust boundaries → threats → controls → telemetry → resilience.

---

## Section 19: Sample Reports <a name="section-19"></a>

> Source combines sections 19–20: Reports / Templates

system-context.md data-flow-diagram.md threat-register.md security-requirements.md control-mapping.md

---

## Section 20: Templates <a name="section-20"></a>

> Source combines sections 19–20: Reports / Templates

system-context.md data-flow-diagram.md threat-register.md security-requirements.md control-mapping.md

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

Cloud architecture · microservices · automotive TARA · medical-device threat models · IoT product architecture.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

Threat Dragon · pytm · Threagile · ThreatSpec.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

Threat-model examples · ATT&CK STIX · D3FEND knowledge graph · CAPEC/CWE.

---

## Section 24: Communities / Forums <a name="section-24"></a>

> Source combines sections 24–25: Communities / Vendors

OWASP · SABSA Institute · MITRE · IriusRisk · Microsoft security architecture community.

---

## Section 25: Vendors / Products <a name="section-25"></a>

> Source combines sections 24–25: Communities / Vendors

OWASP · SABSA Institute · MITRE · IriusRisk · Microsoft security architecture community.

---

## Section 26: Latest Developments <a name="section-26"></a>

Modern architecture increasingly requires modeling: 
cloud identities, supply chain, agents/LLMs, APIs, Kubernetes, SaaS trust, machine identities and software-defined infrastructure.

---

## Section 27: Learning Roadmap <a name="section-27"></a>

Architecture fundamentals → DFDs → STRIDE → attack trees → LINDDUN → ATT&CK/D3FEND → Zero Trust → enterprise security architecture.

---

<div align="center">
<sub>🏗️ Security Architecture & Threat Modeling · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>