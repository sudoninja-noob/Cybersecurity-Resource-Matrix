# 🔌 Domain 11: IoT Security

> **Group:** Wireless, Hardware & Embedded  
> **Curated links:** 19  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

Your uploaded resources already include Practical IoT Hacking, The IoT Hacker's Handbook, IoT Penetration Testing Cookbook, The Hardware Hacking Handbook, SEC556 and Offensive IoT Exploitation.

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

- ⭐⭐⭐ [NIST IoT Cybersecurity Program](https://www.nist.gov/itl/applied-cybersecurity/nist-cybersecurity-iot-program)⭐⭐⭐ [NISTIR 8259 Series](https://www.nist.gov/itl/applied-cybersecurity/nist-cybersecurity-iot-program/nistir-8259-series)⭐⭐⭐ [OWASP Internet of Things Project](https://owasp.org/www-project-internet-of-things/)⭐⭐ [ETSI Consumer IoT Security](https://www.etsi.org/technologies/consumer-iot-security)NISTIR 8259 Rev.1 was published in April 2026 and extends manufacturer guidance across pre-market and post-market activities, including maintenance, support and end-of-life. ( [NIST Computer Security Resource Center](https://csrc.nist.gov/pubs/ir/8259/r1/final))

---

## Section 02: Methodology <a name="section-02"></a>

Use asset discovery → interfaces → hardware → firmware → network → application/API → cloud/mobile companion → authentication → crypto → update mechanism → privacy → lifecycle. 
Resources: [OWASP IoT Security Testing Guide](https://owasp.org/www-project-iot-security-testing-guide/)· [NISTIR 8259 Rev.1](https://csrc.nist.gov/pubs/ir/8259/r1/final)

---

## Section 03: Standards / Compliance <a name="section-03"></a>

NISTIR 8259/8259A/8259B 
ETSI EN 303 645 
IEC 62443 
EU Cyber Resilience Act 
ISO/IEC 27400 
NIST Cybersecurity Framework 
[EU Cyber Resilience Act](https://eur-lex.europa.eu/eli/reg/2024/2847/oj/eng)

---

## Section 04: Official Documentation <a name="section-04"></a>

[NISTIR 8259A](https://csrc.nist.gov/pubs/ir/8259/a/final)· [NISTIR 8259B](https://csrc.nist.gov/pubs/ir/8259/b/final)· [ETSI EN 303 645](https://www.etsi.org/technologies/consumer-iot-security)

---

## Section 05: Checklists <a name="section-05"></a>

Cover: 
Unique credentials 
Authentication 
Authorization 
Network services 
Debug interfaces 
Firmware 
Secure Boot 
OTA updates 
Cryptography 
Cloud APIs 
Mobile app 
Privacy 
Logging 
Physical interfaces 
Lifecycle / EOL

---

## Section 06: Cheat Sheets <a name="section-06"></a>

[OWASP IoT Guidance](https://owasp.org/www-project-internet-of-things/)· [HackTricks IoT/Hardware](https://book.hacktricks.wiki/)

---

## Section 07: Tools <a name="section-07"></a>

- ⭐⭐⭐ Binwalk · EMBA · Ghidra · Wireshark · Burp Suite · Nmap · FirmAE · QEMU · MobSF · Frida · OpenOCD · ChipWhisperer.

---

## Section 08: Labs / Practice <a name="section-08"></a>

- ⭐⭐⭐ [OWASP IoTGoat](https://github.com/OWASP/IoTGoat)⭐⭐⭐ [IoTVulnBench](https://github.com/a101e-lab/IoTVulBench)⭐⭐ [Microcorruption](https://microcorruption.com/)

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

Test default credentials, exposed services, weak authorization, plaintext protocols, insecure firmware, update rollback, hard-coded secrets, cloud API authorization and debug interfaces.

---

## Section 10: YouTube / Video <a name="section-10"></a>

[IoT Village](https://www.iotvillage.org/)· [Hardwear.io](https://hardwear.io/)· DEF CON / Black Hat embedded-security talks.

---

## Section 11: Courses / Training <a name="section-11"></a>

SEC556, Attify Offensive IoT Exploitation, Applied Physical Attacks. Your source explicitly includes these.

---

## Section 12: Certifications <a name="section-12"></a>

No dominant IoT-only credential. Relevant: GICSP, embedded-security training certificates, SESIP/PSA evaluation knowledge.

---

## Section 13: Books <a name="section-13"></a>

- ⭐⭐⭐ Practical IoT Hacking ⭐⭐⭐ The IoT Hacker's Handbook ⭐⭐⭐ IoT Penetration Testing Cookbook ⭐⭐ The Hardware Hacking Handbook

---

## Section 14: Blogs / Articles <a name="section-14"></a>

NCC Group Research · ONEKEY · Quarkslab · Trail of Bits · IoT Village.

---

## Section 15: Research Papers <a name="section-15"></a>

USENIX Security · NDSS · IEEE S&P · ACM CCS · ACM SenSys.

---

## Section 16: White Papers <a name="section-16"></a>

NISTIR 8259 series · ETSI EN 303 645 · CSA IoT guidance.

---

## Section 17: Conference Material <a name="section-17"></a>

IoT Village · Hardwear.io · Black Hat · DEF CON · USENIX Security.

---

## Section 18: Mind Maps <a name="section-18"></a>

IoT 

```
├── Device
```

```
├── Hardware
```

```
├── Firmware
```

```
├── Network
```

```
├── Wireless
```

```
├── Mobile
```

```
├── Cloud/API
```

```
├── Identity
```

```
├── Updates
```

```
├── Privacy
```

```
└── Lifecycle
```

---

## Section 19: Sample Reports <a name="section-19"></a>

Structure findings against device → firmware → communication → backend → companion application → update → privacy.

---

## Section 20: Templates <a name="section-20"></a>

iot-test-plan.md 
device-checklist.md 
firmware-review.md 
network-review.md 
cloud-api-review.md 
update-security.md 
iot-report.md

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

CVE.org · NVD · CISA KEV · router/camera/smart-device vendor advisories.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

IoTGoat · EMBA · FirmAE · Firmadyne · IoTVulnBench · Binwalk · Ghidra.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

IoTVulnBench · RealworldFirmware · vendor firmware images · Wireshark PCAP collections.

---

## Section 24: Communities / Forums <a name="section-24"></a>

IoT Village · OWASP · Hardwear.io · embedded-security communities.

---

## Section 25: Vendors / Products <a name="section-25"></a>

IoT security testing: ONEKEY, Finite State, Binarly; device security: PSA Certified, SESIP ecosystems.

---

## Section 26: Latest Developments <a name="section-26"></a>

Key 2026 themes: full-product security rather than device-only security, SBOM, EU CRA, secure updates, product EOL, device identity and attestation. ( [NIST](https://www.nist.gov/itl/applied-cybersecurity/nist-cybersecurity-iot-program/nistir-8259-series))

---

## Section 27: Learning Roadmap <a name="section-27"></a>

Networking → embedded Linux → hardware → firmware → protocols → APIs/mobile/cloud → OTA → secure boot → IoT standards → complete product assessment.

---

<div align="center">
<sub>🔌 IoT Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>