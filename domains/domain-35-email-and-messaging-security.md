# 📧 Domain 35: Email & Messaging Security

> **Group:** Network, Web & Application  
> **Curated links:** 6  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

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

Core protocols: 
SMTP 
MIME 
SPF 
DKIM 
DMARC 
ARC 
MTA-STS 
TLS-RPT 
S/MIME 
OpenPGP 

- ⭐⭐⭐ [RFC 7208 — SPF](https://www.rfc-editor.org/rfc/rfc7208.html)⭐⭐⭐ [RFC 6376 — DKIM](https://www.rfc-editor.org/rfc/rfc6376.html)⭐⭐⭐ [RFC 7489 — DMARC](https://www.rfc-editor.org/rfc/rfc7489.html)SPF allows a domain to explicitly authorize hosts permitted to use its domain in SMTP identity fields. ( [RFC Editor](https://www.rfc-editor.org/info/rfc7208/))

---

## Section 02: Methodology <a name="section-02"></a>

DNS/domain → inbound mail path → outbound mail → authentication → transport encryption → anti-spam/phishing → attachments/URLs → mailbox identity → forwarding → reporting → incident response.

---

## Section 03: Standards / Compliance <a name="section-03"></a>

RFC 7208 SPF · RFC 6376 DKIM · RFC 7489 DMARC · RFC 8461 MTA-STS · RFC 8460 TLS-RPT · S/MIME · OpenPGP.

---

## Section 04: Official Documentation <a name="section-04"></a>

[RFC 8461 — MTA-STS](https://www.rfc-editor.org/rfc/rfc8461.html)[RFC 8460 — SMTP TLS Reporting](https://www.rfc-editor.org/rfc/rfc8460.html)

---

## Section 05: Checklists <a name="section-05"></a>

SPF · DKIM · DMARC · DNS alignment · TLS · MTA-STS · TLS-RPT · anti-spoofing · forwarding · BEC protection · mailbox MFA · OAuth apps · attachment sandboxing · URL rewriting

---

## Section 06: Cheat Sheets <a name="section-06"></a>

DMARC alignment cheat sheets · SMTP response codes · MIME structure · Exchange mail-flow references.

---

## Section 07: Tools <a name="section-07"></a>

dig · nslookup · OpenSSL · swaks · testssl.sh · MXToolbox · dmarcian · Thunderbird header analysis · Wireshark.

---

## Section 08: Labs / Practice <a name="section-08"></a>

Local Postfix/Dovecot lab · MailHog/Mailpit · Microsoft 365 test tenant · Google Workspace test domain.

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

Spoofing resistance · domain alignment · DKIM signing · forwarding behavior · TLS enforcement · malicious attachment handling.

---

## Section 10: YouTube / Video <a name="section-10"></a>

> Source combines sections 10–12: Video / Courses / Certifications

Microsoft 365 security · Google Workspace security · SANS SEC401/450 crossover · email-authentication workshops.

---

## Section 11: Courses / Training <a name="section-11"></a>

> Source combines sections 10–12: Video / Courses / Certifications

Microsoft 365 security · Google Workspace security · SANS SEC401/450 crossover · email-authentication workshops.

---

## Section 12: Certifications <a name="section-12"></a>

> Source combines sections 10–12: Video / Courses / Certifications

Microsoft 365 security · Google Workspace security · SANS SEC401/450 crossover · email-authentication workshops.

---

## Section 13: Books <a name="section-13"></a>

Email architecture/SMTP books · phishing-defense references · Microsoft 365 security books.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

> Source combines sections 14–17: Research

M3AAWG · APWG · Google Security · Microsoft Threat Intelligence · Proofpoint research · Mimecast research.

---

## Section 15: Research Papers <a name="section-15"></a>

> Source combines sections 14–17: Research

M3AAWG · APWG · Google Security · Microsoft Threat Intelligence · Proofpoint research · Mimecast research.

---

## Section 16: White Papers <a name="section-16"></a>

> Source combines sections 14–17: Research

M3AAWG · APWG · Google Security · Microsoft Threat Intelligence · Proofpoint research · Mimecast research.

---

## Section 17: Conference Material <a name="section-17"></a>

> Source combines sections 14–17: Research

M3AAWG · APWG · Google Security · Microsoft Threat Intelligence · Proofpoint research · Mimecast research.

---

## Section 18: Mind Maps <a name="section-18"></a>

SMTP → DNS → SPF → DKIM → DMARC → transport TLS → mailbox → phishing/BEC → messaging apps.

---

## Section 19: Sample Reports <a name="section-19"></a>

> Source combines sections 19–20: Reports / Templates

email-security-review.md · dmarc-assessment.md · mail-flow-diagram.md · phishing-readiness-report.md

---

## Section 20: Templates <a name="section-20"></a>

> Source combines sections 19–20: Reports / Templates

email-security-review.md · dmarc-assessment.md · mail-flow-diagram.md · phishing-readiness-report.md

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

BEC · OAuth-consent abuse · domain spoofing · malicious attachment campaigns.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

MailHog/Mailpit · parsedmarc · checkdmarc · mail-security automation.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

SpamAssassin corpus · phishing-email datasets · Enron email dataset · malicious-email corpora.

---

## Section 24: Communities / Forums <a name="section-24"></a>

> Source combines sections 24–25: Communities / Vendors

M3AAWG · APWG · Microsoft · Google · Proofpoint · Mimecast · Abnormal Security.

---

## Section 25: Vendors / Products <a name="section-25"></a>

> Source combines sections 24–25: Communities / Vendors

M3AAWG · APWG · Microsoft · Google · Proofpoint · Mimecast · Abnormal Security.

---

## Section 26: Latest Developments <a name="section-26"></a>

Track DMARC modernization, BIMI/VMC/CMC, phishing-resistant authentication, OAuth mailbox compromise and AI-generated BEC/social-engineering content.

---

## Section 27: Learning Roadmap <a name="section-27"></a>

SMTP/MIME → DNS → SPF/DKIM/DMARC → TLS → phishing/BEC → M365/Workspace → secure messaging → detection/IR.

---

<div align="center">
<sub>📧 Email & Messaging Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>