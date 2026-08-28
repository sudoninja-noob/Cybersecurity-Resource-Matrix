# 🏥 Domain 33: Medical Device Security

> **Group:** Specialized & Emerging Systems  
> **Curated links:** 4  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

Your uploaded resources already contain MITRE/FDA threat-modeling material, FDA guidance, IoMT risk frameworks, medical-device hacking research and several training resources. 
One refinement is important: your uploaded list references the June 2025 FDA guidance, but FDA issued a newer final guidance in February 2026, which supersedes that version. ( [U.S. Food and Drug Administration](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/cybersecurity-medical-devices-quality-management-system-considerations-and-content-premarket))

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

- ⭐⭐⭐ [FDA Cybersecurity in Medical Devices — 2026 Final Guidance](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/cybersecurity-medical-devices-quality-management-system-considerations-and-content-premarket)⭐⭐⭐ [HSCC MedTech Joint Security Plan 2](https://healthsectorcouncil.org/JSP2/)⭐⭐⭐ IEC 81001-5-1 ⭐⭐⭐ AAMI TIR57 / TIR97 The HSCC JSP2 uses a total-product-lifecycle, secure-by-design and secure-by-default approach. ( [Health Sector Council](https://healthsectorcouncil.org/JSP2/))

---

## Section 02: Methodology <a name="section-02"></a>

Intended use → safety analysis → threat model → architecture → interfaces → firmware/software → wireless → cloud/backend → mobile app → update → SBOM → vulnerability management → coordinated disclosure → postmarket monitoring.

---

## Section 03: Standards / Compliance <a name="section-03"></a>

FDA 524B cyber-device requirements 
IEC 81001-5-1 
IEC 62304 
ISO 14971 
IEC 60601-1 where applicable 
AAMI TIR57 
AAMI TIR97 
UL 2900 
ISO/IEC 27001 
EU MDR cybersecurity guidance

---

## Section 04: Official Documentation <a name="section-04"></a>

FDA CDRH · CISA healthcare guidance · HSCC JSP2 · MITRE medical-device threat-modeling material.

---

## Section 05: Checklists <a name="section-05"></a>

device identity · authentication · authorization · secure boot · firmware update · SBOM · crypto · wireless · Bluetooth · Wi-Fi · USB · debug interfaces · cloud API · patient data · audit logs · recovery · vulnerability disclosure

---

## Section 06: Cheat Sheets <a name="section-06"></a>

MITRE/FDA medical-device threat modeling · FDA premarket guidance · AAMI security references.

---

## Section 07: Tools <a name="section-07"></a>

Binwalk · EMBA · Ghidra · MobSF · Burp · Wireshark · BLE sniffers · Proxmark3 · Syft · Grype · Trivy.

---

## Section 08: Labs / Practice <a name="section-08"></a>

Use simulated/retired devices and IoMT labs—not operational clinical equipment.

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

Secure-update failure, authentication, access control, hard-coded credentials, wireless security, sensitive-data exposure, rollback and recovery.

---

## Section 10: YouTube / Video <a name="section-10"></a>

> Source combines sections 10–12: Videos / Courses / Certifications

TÜV SÜD medical-device security · FDA webinars · AAMI training · MedCrypt/HSCC workshops. Your uploads already list TÜV SÜD and IoMT/security training options.

---

## Section 11: Courses / Training <a name="section-11"></a>

> Source combines sections 10–12: Videos / Courses / Certifications

TÜV SÜD medical-device security · FDA webinars · AAMI training · MedCrypt/HSCC workshops. Your uploads already list TÜV SÜD and IoMT/security training options.

---

## Section 12: Certifications <a name="section-12"></a>

> Source combines sections 10–12: Videos / Courses / Certifications

TÜV SÜD medical-device security · FDA webinars · AAMI training · MedCrypt/HSCC workshops. Your uploads already list TÜV SÜD and IoMT/security training options.

---

## Section 13: Books <a name="section-13"></a>

Medical Device Cybersecurity · Security and Privacy Issues in IoMT · medical IoT engineering references.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

> Source combines sections 14–17: Research

FDA · MITRE · NCC Group · MedCrypt · CISA · Black Hat · USENIX HealthSec.

---

## Section 15: Research Papers <a name="section-15"></a>

> Source combines sections 14–17: Research

FDA · MITRE · NCC Group · MedCrypt · CISA · Black Hat · USENIX HealthSec.

---

## Section 16: White Papers <a name="section-16"></a>

> Source combines sections 14–17: Research

FDA · MITRE · NCC Group · MedCrypt · CISA · Black Hat · USENIX HealthSec.

---

## Section 17: Conference Material <a name="section-17"></a>

> Source combines sections 14–17: Research

FDA · MITRE · NCC Group · MedCrypt · CISA · Black Hat · USENIX HealthSec.

---

## Section 18: Mind Maps <a name="section-18"></a>

Device → hardware → firmware → network → wireless → cloud → app → patient data → updates → SBOM → postmarket.

---

## Section 19: Sample Reports <a name="section-19"></a>

> Source combines sections 19–20: Reports / Templates

Add: 
Patient safety impact · clinical workflow impact · exploit prerequisites · detectability · updateability · compensating controls

---

## Section 20: Templates <a name="section-20"></a>

> Source combines sections 19–20: Reports / Templates

Add: 
Patient safety impact · clinical workflow impact · exploit prerequisites · detectability · updateability · compensating controls

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

Infusion pumps · pacemakers · insulin pumps · imaging systems · hospital IoMT.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

MedSec/IoMT academic projects · Binwalk · EMBA · MobSF · Syft.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

Firmware samples · DICOM data · simulated device telemetry · IoMT research datasets.

---

## Section 24: Communities / Forums <a name="section-24"></a>

> Source combines sections 24–25: Communities / Vendors

AAMI · HSCC · FDA · MedCrypt · Health-ISAC · CISA.

---

## Section 25: Vendors / Products <a name="section-25"></a>

> Source combines sections 24–25: Communities / Vendors

AAMI · HSCC · FDA · MedCrypt · Health-ISAC · CISA.

---

## Section 26: Latest Developments <a name="section-26"></a>

The February 2026 FDA final guidance is now the priority regulatory reference for U.S. premarket medical-device cybersecurity. ( [U.S. Food and Drug Administration](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/cybersecurity-medical-devices-quality-management-system-considerations-and-content-premarket))

---

## Section 27: Learning Roadmap <a name="section-27"></a>

Medical-device lifecycle → risk management → embedded/firmware → wireless/API → threat modeling → SBOM/update → FDA/IEC 81001-5-1 → clinical-safety reporting.

---

<div align="center">
<sub>🏥 Medical Device Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>