# 💰 Domain 34: Payment / POS / ATM Security

> **Group:** Specialized & Emerging Systems  
> **Curated links:** 6  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

Your uploaded set includes deep ATM resources on XFS, ATM replay, jackpotting, Black Hat/DEF CON research and dedicated ATM-security training.

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

- ⭐⭐⭐ [PCI DSS](https://www.pcisecuritystandards.org/standards/pci-dss/)⭐⭐⭐ [PCI PTS POI](https://www.pcisecuritystandards.org/standards/pts-point-of-interaction-poi/)⭐⭐⭐ [EMVCo Specifications](https://www.emvco.com/about-us/what-are-emv-specifications/)PCI SSC currently lists PCI DSS v4.0.1 and PTS POI v7.0 in its document library. ( [PCI Security Standards Council](https://www.pcisecuritystandards.org/document_library/?class=pcidss&doc=pci_dss))

---

## Section 02: Methodology <a name="section-02"></a>

Cardholder-data flow → terminal → PED/PIN → POS application → merchant network → acquirer → payment gateway → HSM → ATM components → physical security → backend.

---

## Section 03: Standards / Compliance <a name="section-03"></a>

PCI DSS 4.0.1 
PCI PTS POI 
PCI PIN Security 
PCI Secure Software 
PCI 3DS 
EMV Contact / Contactless 
EMV 3-D Secure 
ISO 9564 PIN management 
EMV specifications are global technical requirements intended to enable interoperable and secure payment products. ( [EMVCo](https://www.emvco.com/about-us/what-are-emv-specifications/))

---

## Section 04: Official Documentation <a name="section-04"></a>

PCI SSC document library · EMVCo · payment-network security guidance.

---

## Section 05: Checklists <a name="section-05"></a>

PAN storage · PIN · PED · skimming · terminal tamper · key loading · HSM · EMV · contactless · POS malware · ATM XFS · dispenser · kiosk OS · remote admin · network segmentation

---

## Section 06: Cheat Sheets <a name="section-06"></a>

EMV APDU references · ISO 8583 references · XFS architecture · PCI DSS requirement map.

---

## Section 07: Tools <a name="section-07"></a>

Wireshark · PC/SC tools · EMV smart-card tools · Proxmark3 · YARA/capa for payment malware · Sysinternals.

---

## Section 08: Labs / Practice <a name="section-08"></a>

Payment-card simulators · test EMV cards · isolated POS environments · ATM software simulators.

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

Use authorized test infrastructure for: 
PIN protection 
terminal tamper controls 
cardholder-data exposure 
application integrity 
payment-network segmentation 
software/update controls

---

## Section 10: YouTube / Video <a name="section-10"></a>

> Source combines sections 10–12: Videos / Courses / Certifications

PCI Professional programs · ATMIA training · PCI ISA/QSA paths · EMVCo educational resources.

---

## Section 11: Courses / Training <a name="section-11"></a>

> Source combines sections 10–12: Videos / Courses / Certifications

PCI Professional programs · ATMIA training · PCI ISA/QSA paths · EMVCo educational resources.

---

## Section 12: Certifications <a name="section-12"></a>

> Source combines sections 10–12: Videos / Courses / Certifications

PCI Professional programs · ATMIA training · PCI ISA/QSA paths · EMVCo educational resources.

---

## Section 13: Books <a name="section-13"></a>

Hacking Point of Sale · Payment Card Industry Data Security Standard Handbook · EMV technical references.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

> Source combines sections 14–17: Research

Group-IB · Kaspersky · Positive Technologies · Black Hat · DEF CON · ATMIA.

---

## Section 15: Research Papers <a name="section-15"></a>

> Source combines sections 14–17: Research

Group-IB · Kaspersky · Positive Technologies · Black Hat · DEF CON · ATMIA.

---

## Section 16: White Papers <a name="section-16"></a>

> Source combines sections 14–17: Research

Group-IB · Kaspersky · Positive Technologies · Black Hat · DEF CON · ATMIA.

---

## Section 17: Conference Material <a name="section-17"></a>

> Source combines sections 14–17: Research

Group-IB · Kaspersky · Positive Technologies · Black Hat · DEF CON · ATMIA.

---

## Section 18: Mind Maps <a name="section-18"></a>

Card → terminal → POS → merchant → gateway → acquirer → HSM → ATM → payment network.

---

## Section 19: Sample Reports <a name="section-19"></a>

> Source combines sections 19–20: Reports / Templates

PCI mapping · terminal assessment · ATM hardening review · payment-app assessment.

---

## Section 20: Templates <a name="section-20"></a>

> Source combines sections 19–20: Reports / Templates

PCI mapping · terminal assessment · ATM hardening review · payment-app assessment.

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

Tyupkin · Ploutus · Cutlet Maker · Black Box ATM attacks · POS malware families.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

EMV tooling · smart-card tools · ISO8583 parsers · malware-analysis tooling.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

Payment malware samples, EMV test vectors, synthetic ISO8583 data.

---

## Section 24: Communities / Forums <a name="section-24"></a>

> Source combines sections 24–25: Communities / Vendors

PCI SSC · EMVCo · ATMIA · Visa/Mastercard security ecosystems · NCR Atleos · Diebold Nixdorf.

---

## Section 25: Vendors / Products <a name="section-25"></a>

> Source combines sections 24–25: Communities / Vendors

PCI SSC · EMVCo · ATMIA · Visa/Mastercard security ecosystems · NCR Atleos · Diebold Nixdorf.

---

## Section 26: Latest Developments <a name="section-26"></a>

Important areas: contactless payments, mobile acceptance, software PIN, COTS acceptance, tokenization, 3-D Secure and increasingly software-defined POS devices. EMVCo currently documents 3-D Secure v2.3.1.x. ( [EMVCo](https://www.emvco.com/whitepapers/emv-3-d-secure-whitepaper/3-d-secure-documentation/3-d-secure-specification/))

---

## Section 27: Learning Roadmap <a name="section-27"></a>

Payment flow → EMV → PCI DSS → smart cards → POS → HSM/PIN → ATM/XFS → payment malware → mobile/contactless.

---

<div align="center">
<sub>💰 Payment / POS / ATM Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>