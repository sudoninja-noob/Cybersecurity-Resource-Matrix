# 🛡️ Domain 22: Application Security & Secure Code Review

> **Group:** Network, Web & Application  
> **Curated links:** 4  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

Your uploaded source already contains a useful dedicated code-review set: secure software development, vulnerability-detection tools, OWASP Code Review Guide v2, SAST, PentesterLab Code Review and vulnerable-source-code labs.

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

[OWASP Application Security Verification Standard](https://owasp.org/www-project-application-security-verification-standard/)[OWASP Secure Code Review Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Secure_Code_Review_Cheat_Sheet.html)[OWASP Code Review Guide](https://owasp.org/www-project-code-review-guide/)
Secure code review focuses on logic and data-flow issues that automated tools may miss. ( [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/cheatsheets/Secure_Code_Review_Cheat_Sheet.html))

---

## Section 02: Methodology <a name="section-02"></a>

Architecture 
→ Entry Points 
→ Trust Boundaries 
→ Data Flow 
→ Authentication 
→ Authorization 
→ Validation 
→ Crypto 
→ Secrets 
→ File Handling 
→ Serialization 
→ Business Logic 
→ Error Handling 
→ Logging

---

## Section 03: Standards / Compliance <a name="section-03"></a>

OWASP ASVS · CWE · CERT Secure Coding · SEI CERT C/C++ · NIST SSDF · MISRA where applicable.

---

## Section 04: Official Documentation <a name="section-04"></a>

OWASP ASVS · OWASP Code Review Guide · CWE · language secure-coding guides.

---

## Section 05: Checklists <a name="section-05"></a>

Auth · access control · input handling · SQL/NoSQL · command execution · SSRF · deserialization · crypto · secrets · logging · race conditions · memory safety.

---

## Section 06: Cheat Sheets <a name="section-06"></a>

OWASP Cheat Sheet Series · CERT coding rules.

---

## Section 07: Tools <a name="section-07"></a>

- ⭐⭐⭐ Semgrep · CodeQL · SonarQube · Bandit · Brakeman · SpotBugs · ESLint security plugins · Clang Static Analyzer · Coverity.

---

## Section 08: Labs / Practice <a name="section-08"></a>

PentesterLab Code Review · Secure Code Warrior · Damn Vulnerable Source Code · CodeQL CTFs.

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

Injection · authorization logic · tainted data flow · unsafe deserialization · command execution · path traversal · integer/memory errors.

---

## Section 10: YouTube / Video <a name="section-10"></a>

OWASP · GitHub Security Lab · Trail of Bits · LiveOverflow.

---

## Section 11: Courses / Training <a name="section-11"></a>

PentesterLab · Secure Code Warrior · SANS SEC522/SEC540 · language-specific secure coding.

---

## Section 12: Certifications <a name="section-12"></a>

CSSLP · OSWE · BSCP · GIAC GWEB.

---

## Section 13: Books <a name="section-13"></a>

Secure Coding in C and C++ · The Art of Software Security Assessment · Writing Secure Code.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

Trail of Bits · GitHub Security Lab · SonarSource · Project Zero · Assetnote. 
15. Papers 
USENIX · IEEE S&P · ACM CCS · static-analysis research.

---

## Section 15: Research Papers <a name="section-15"></a>

No separate source block was available for this section.

---

## Section 16: White Papers <a name="section-16"></a>

OWASP ASVS · NIST SSDF · CERT Secure Coding.

---

## Section 17: Conference Material <a name="section-17"></a>

OWASP Global AppSec · Black Hat · USENIX · CodeQL workshops.

---

## Section 18: Mind Maps <a name="section-18"></a>

Secure Code Review 

```
├── Architecture
```

```
├── Input
```

```
├── AuthN
```

```
├── AuthZ
```

```
├── Data Flow
```

```
├── Crypto
```

```
├── Files
```

```
├── Serialization
```

```
├── Concurrency
```

```
└── Business Logic
```

---

## Section 19: Sample Reports <a name="section-19"></a>

> Source combines sections 19–20: Reports / Templates

secure-code-review-report.md, data-flow-review.md, source-code-checklist.md.

---

## Section 20: Templates <a name="section-20"></a>

> Source combines sections 19–20: Reports / Templates

secure-code-review-report.md, data-flow-review.md, source-code-checklist.md.

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

GitHub Security Lab advisories · Project Zero · OSS vulnerability disclosures.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

Semgrep · CodeQL · Bandit · Brakeman · SpotBugs.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

Juliet Test Suite · SVCP datasets · CodeQL challenge repositories.

---

## Section 24: Communities / Forums <a name="section-24"></a>

> Source combines sections 24–25: Communities / Vendors

OWASP · GitHub Security Lab · Semgrep · Sonar · Checkmarx · Fortify.

---

## Section 25: Vendors / Products <a name="section-25"></a>

> Source combines sections 24–25: Communities / Vendors

OWASP · GitHub Security Lab · Semgrep · Sonar · Checkmarx · Fortify.

---

## Section 26: Latest Developments <a name="section-26"></a>

Important topics: AI-generated code review, dependency-aware analysis, variant analysis and memory-safety migration.

---

## Section 27: Learning Roadmap <a name="section-27"></a>

Programming → secure coding → CWE → manual review → SAST → data flow → business logic → advanced variant analysis.

---

<div align="center">
<sub>🛡️ Application Security & Secure Code Review · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>