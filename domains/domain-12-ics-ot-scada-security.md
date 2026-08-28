# ⚙️ Domain 12: ICS / OT / SCADA Security

> **Group:** OT, Automotive & Telecom  
> **Curated links:** 9  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

Your uploaded collection includes Hacking Exposed Industrial Control Systems, Hacking SCADA/Industrial Control Systems, Handbook of SCADA/Control Systems Security, EC-Council ICS/SCADA training and SANS ICS410.

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

- ⭐⭐⭐ [CISA ICS Security Resources](https://www.cisa.gov/topics/industrial-control-systems)⭐⭐⭐ [MITRE ATT&CK for ICS](https://attack.mitre.org/matrices/ics/)⭐⭐⭐ [ISA/IEC 62443](https://www.isa.org/standards-and-publications/isa-standards/isa-iec-62443-series-of-standards)MITRE ATT&CK for ICS models techniques across discovery, lateral movement, command-and-control, inhibit-response, impair-process-control and impact. ( [MITRE ATT&CK](https://attack.mitre.org/matrices/ics/))

---

## Section 02: Methodology <a name="section-02"></a>

Scope & safety 
Asset inventory 
Architecture 
Zones/conduits 
Passive discovery 
Protocol analysis 
Remote access 
Identity 
Configuration 
PLC/HMI/SCADA 
Engineering workstation 
SIS 
Segmentation 
Logging 
Recovery

---

## Section 03: Standards / Compliance <a name="section-03"></a>

- ⭐⭐⭐ IEC 62443 series ⭐⭐⭐ NIST SP 800-82 ⭐⭐ CISA ICS guidance NERC CIP · ISO 27001 · NIST CSF.

---

## Section 04: Official Documentation <a name="section-04"></a>

#### [CISA ICS Recommended Practices](https://www.cisa.gov/resources-tools/resources/ics-recommended-practices)· [MITRE ATT&CK ICS](https://attack.mitre.org/matrices/ics/)
CISA maintains guidance covering defense-in-depth, incident response, forensics, patch management and secure remote access for control systems. ( [CISA](https://www.cisa.gov/resources-tools/resources/ics-recommended-practices))

---

## Section 05: Checklists <a name="section-05"></a>

> Source combines sections 5–6: Checklists / Cheat Sheets

Cover PLCs, HMIs, historians, engineering workstations, OPC, Modbus, DNP3, IEC-104, Profinet, EtherNet/IP, remote access and Purdue-level segmentation.

---

## Section 06: Cheat Sheets <a name="section-06"></a>

> Source combines sections 5–6: Checklists / Cheat Sheets

Cover PLCs, HMIs, historians, engineering workstations, OPC, Modbus, DNP3, IEC-104, Profinet, EtherNet/IP, remote access and Purdue-level segmentation.

---

## Section 07: Tools <a name="section-07"></a>

Wireshark · Zeek · Nmap ICS NSE · GrassMarlin · Malcolm · OpenPLC · Scapy · pymodbus.

---

## Section 08: Labs / Practice <a name="section-08"></a>

[OpenPLC](https://www.openplcproject.com/)· [Conpot](https://github.com/mushorg/conpot)· ICS-focused CTFs and SANS labs.

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

Prefer safe protocol validation and configuration review over indiscriminate exploitation of live OT.

---

## Section 10: YouTube / Video <a name="section-10"></a>

S4 Conference · Dragos · CISA ICS talks · Black Hat ICS Village · DEF CON ICS Village.

---

## Section 11: Courses / Training <a name="section-11"></a>

SANS ICS410 · ICS515 · ICS612 · INL/DOE ICS training.

---

## Section 12: Certifications <a name="section-12"></a>

GICSP · GRID · GCIP; ISA/IEC 62443 certificates.

---

## Section 13: Books <a name="section-13"></a>

Industrial Network Security · Hacking Exposed ICS · Handbook of SCADA/Control Systems Security.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

> Source combines sections 14–17: Blogs / Papers / White Papers / Conferences

Dragos · Claroty Team82 · Nozomi · CISA · S4 · USENIX · NDSS · Black Hat.

---

## Section 15: Research Papers <a name="section-15"></a>

> Source combines sections 14–17: Blogs / Papers / White Papers / Conferences

Dragos · Claroty Team82 · Nozomi · CISA · S4 · USENIX · NDSS · Black Hat.

---

## Section 16: White Papers <a name="section-16"></a>

> Source combines sections 14–17: Blogs / Papers / White Papers / Conferences

Dragos · Claroty Team82 · Nozomi · CISA · S4 · USENIX · NDSS · Black Hat.

---

## Section 17: Conference Material <a name="section-17"></a>

> Source combines sections 14–17: Blogs / Papers / White Papers / Conferences

Dragos · Claroty Team82 · Nozomi · CISA · S4 · USENIX · NDSS · Black Hat.

---

## Section 18: Mind Maps <a name="section-18"></a>

OT 

```
├── PLC
```

```
├── HMI
```

```
├── SCADA
```

```
├── DCS
```

```
├── SIS
```

```
├── Historian
```

```
├── Engineering Station
```

```
├── Protocols
```

```
├── Purdue Architecture
```

```
├── Remote Access
```

```
└── Safety
```

---

## Section 19: Sample Reports <a name="section-19"></a>

> Source combines sections 19–20: Reports / Templates

Include process/safety impact separately from IT impact.

---

## Section 20: Templates <a name="section-20"></a>

> Source combines sections 19–20: Reports / Templates

Include process/safety impact separately from IT impact.

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

Stuxnet · Triton/Trisis · Industroyer · Pipedream/Incontroller · Colonial Pipeline lessons.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

Conpot · OpenPLC · Malcolm · ICSNPP protocol tooling.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

ICS PCAPs · SWaT/WADI · BATADAL · CIC industrial datasets.

---

## Section 24: Communities / Forums <a name="section-24"></a>

> Source combines sections 24–25: Communities / Vendors

S4 · ICS Village · CISA · Dragos · Nozomi · Claroty · Tenable OT.

---

## Section 25: Vendors / Products <a name="section-25"></a>

> Source combines sections 24–25: Communities / Vendors

S4 · ICS Village · CISA · Dragos · Nozomi · Claroty · Tenable OT.

---

## Section 26: Latest Developments <a name="section-26"></a>

Track ransomware-to-OT impact, insecure remote access, edge devices, IT/OT convergence and cloud-managed industrial systems.

---

## Section 27: Learning Roadmap <a name="section-27"></a>

Networking → industrial processes → Purdue model → PLC/HMI → protocols → segmentation → passive monitoring → safety-aware testing → IEC 62443 → incident response.

---

<div align="center">
<sub>⚙️ ICS / OT / SCADA Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>