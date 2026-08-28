# 🖧 Domain 45: Mainframe & Legacy System Security

> **Group:** Specialized & Emerging Systems  
> **Curated links:** 15  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

This should not be just “old systems.” Mainframes remain high-value modern enterprise systems running z/OS, RACF, CICS, IMS, Db2, JES, TSO/ISPF, USS and increasingly REST/API workloads.

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

- ⭐⭐⭐ [IBM z/OS Security Server RACF Documentation](https://www.ibm.com/docs/en/zos/3.2.0?topic=zos-security-server-racf)⭐⭐⭐ [IBM RACF Overview](https://www.ibm.com/products/resource-access-control-facility)⭐⭐⭐ [IBM zSecure](https://www.ibm.com/products/zsecure)⭐⭐ [IBM Z Xplore](https://www.ibm.com/products/z/resources/zxplore)IBM's z/OS 3.2 RACF documentation was actively updated throughout 2026, including administrator, auditor, command and programming references. ( [IBM](https://www.ibm.com/docs/en/zos/3.2.0?topic=zos-security-server-racf))

---

## Section 02: Methodology <a name="section-02"></a>

Platform Inventory 
→ LPAR 
→ z/OS 
→ RACF / ACF2 / Top Secret 
→ Users & Privileges 
→ Data Sets 
→ JES 
→ TSO 
→ CICS 
→ IMS 
→ Db2 
→ USS 
→ Network 
→ TLS/Certificates 
→ SMF Logging 
→ APIs / z/OSMF 
→ Encryption

---

## Section 03: Standards / Compliance <a name="section-03"></a>

NIST 800-53 · ISO 27001 · PCI DSS · STIG-based mainframe policies · RACF best practices · organizational security baselines.

---

## Section 04: Official Documentation <a name="section-04"></a>

[IBM RACF Auditor's and Administration Guides](https://www.ibm.com/docs/en/zos/3.2.0?topic=zos-security-server-racf)[IBM z/OSMF](https://www.ibm.com/products/zos/management-facility)

---

## Section 05: Checklists <a name="section-05"></a>

RACF SPECIAL 
OPERATIONS 
AUDITOR 
Dataset profiles 
Generic profiles 
JES 
Started tasks 
SURROGAT 
APF libraries 
USS UID 0 
SSH 
FTP/Telnet 
TLS 
AT-TLS 
Certificates 
CICS 
IMS 
Db2 
SMF 
z/OSMF 
REST APIs 
Encryption

---

## Section 06: Cheat Sheets <a name="section-06"></a>

TSO/ISPF basics · RACF commands · JCL basics · z/OS UNIX commands · SMF record references.

---

## Section 07: Tools <a name="section-07"></a>

- ⭐⭐⭐ IBM zSecure Audit ⭐⭐⭐ IBM zSecure Alert/Detection ⭐⭐ RACF reports ⭐⭐ SMF analytics ⭐⭐ z/OSMF Security Configuration Assistant ⭐⭐ enterprise SIEM integrations IBM zSecure provides audit, alerting, RACF administration, reporting and SIEM integration for IBM Z. ( [IBM](https://www.ibm.com/products/zsecure))

---

## Section 08: Labs / Practice <a name="section-08"></a>

- ⭐⭐⭐ [IBM Z Xplore](https://www.ibm.com/products/z/resources/zxplore)⭐⭐ [Hercules Hyperion Emulator](https://github.com/hercules-390/hyperion)IBM Z Xplore provides no-cost challenge-based hands-on mainframe training covering JCL, USS, COBOL, Db2 and security fundamentals. ( [IBM](https://www.ibm.com/products/z/resources/zxplore))

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

Privilege review · RACF resource coverage · excessive dataset access · weak authentication · network plaintext · TLS configuration · REST API authorization · audit completeness.

---

## Section 10: YouTube / Video <a name="section-10"></a>

IBM Z · SHARE conference · IBM TechXchange · mainframe security webinars.

---

## Section 11: Courses / Training <a name="section-11"></a>

IBM Z Xplore · IBM RACF courses · Broadcom ACF2/TSS training · mainframe security training.

---

## Section 12: Certifications <a name="section-12"></a>

IBM Z / z/OS credentials · RACF administration · mainframe cybersecurity courses.

---

## Section 13: Books <a name="section-13"></a>

IBM Redbooks on z/OS security · RACF administration · mainframe networking · CICS security. 
[IBM Redbooks — Securing the IBM Mainframe](https://www.redbooks.ibm.com/Redbooks.nsf/5193609f3941e9cf85256bc300724cfc/3d07c246447f428e85257e00005686c5)

---

## Section 14: Blogs / Articles <a name="section-14"></a>

IBM Z Security · SHARE · Broadcom Mainframe Software · BMC Mainframe security.

---

## Section 15: Research Papers <a name="section-15"></a>

Mainframe identity · cryptography · security modernization · transaction security · anomaly detection.

---

## Section 16: White Papers <a name="section-16"></a>

IBM Z security architecture · pervasive encryption · RACF security architecture.

---

## Section 17: Conference Material <a name="section-17"></a>

SHARE · IBM TechXchange · RSA/Black Hat mainframe-specific talks.

---

## Section 18: Mind Maps <a name="section-18"></a>

Mainframe Security 

```
├── z/OS
```

```
├── RACF
```

```
├── JES
```

```
├── TSO
```

```
├── Data Sets
```

```
├── CICS
```

```
├── IMS
```

```
├── Db2
```

```
├── USS
```

```
├── Network
```

```
├── Cryptography
```

```
└── SMF
```

---

## Section 19: Sample Reports <a name="section-19"></a>

RACF audit · privileged-access report · dataset exposure report · network/crypto review · z/OSMF security assessment.

---

## Section 20: Templates <a name="section-20"></a>

racf-audit.md 
zos-hardening-checklist.md 
cics-security-review.md 
db2-security-review.md 
zos-network-review.md 
mainframe-security-report.md

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

RACF misconfiguration · weak legacy protocols · excessive privileged IDs · legacy application modernization risks.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

Hercules · z/OSMF community samples · Z Open Automation Utilities projects.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

SMF records · RACF audit outputs · synthetic JCL/data sets · mainframe transaction logs.

---

## Section 24: Communities / Forums <a name="section-24"></a>

IBM Z Community · SHARE · Open Mainframe Project.

---

## Section 25: Vendors / Products <a name="section-25"></a>

IBM · Broadcom ACF2/Top Secret · BMC · Precisely · Kyndryl · mainframe security specialists.

---

## Section 26: Latest Developments <a name="section-26"></a>

Two useful 2026 developments: 
z/OS 3.2 introduced expanded RACF/SAF secrets-management capabilities for applications. ( [IBM](https://www.ibm.com/docs/en/zos/3.2.0?topic=sc-summary-changes-zos-32-159)) 
IBM introduced zSecure Detection in June 2026 for threat monitoring and response on z/OS. ( [IBM](https://www.ibm.com/new/announcements/introducing-ibm-zsecure-detection)) 
Modern z/OS also supports TLS, SSH, RACF-controlled access and hardware-backed cryptographic services. ( [IBM](https://www.ibm.com/docs/en/zos/3.2.0?topic=25-zos-security-functions))

---

## Section 27: Learning Roadmap <a name="section-27"></a>

Mainframe architecture → JCL/TSO/ISPF → RACF → datasets/JES → CICS/IMS/Db2 → USS/network → SMF → crypto → z/OSMF/API security.

---

<div align="center">
<sub>🖧 Mainframe & Legacy System Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>