# ✈️ Domain 31: Aviation / Aerospace Security

> **Group:** Specialized & Emerging Systems  
> **Curated links:** 10  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

This domain should remain distinct from Satellite / Space Security. Here the focus is primarily civil/commercial aviation, aircraft, avionics, airports, airline infrastructure, UAS/UAVs, air-traffic systems and aviation safety.

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

- ⭐⭐⭐ [EASA Information Security / Part-IS](https://www.easa.europa.eu/en/domains/cybersecurity)⭐⭐⭐ [FAA Cybersecurity](https://www.faa.gov/about/office_org/headquarters_offices/ang/offices/tc/initiatives/cybersecurity)⭐⭐⭐ [EUROCONTROL Cybersecurity](https://www.eurocontrol.int/cybersecurity)⭐⭐ [Aviation ISAC](https://www.a-isac.com/)EASA's current regulatory framework includes Part-IS, covering management of information-security risks that can affect aviation safety. The consolidated rules were revised in December 2025, and the applicable EU requirements extend across aviation organisations and competent authorities. ( [EASA](https://www.easa.europa.eu/en/document-library/easy-access-rules/easy-access-rules-information-security-regulations-eu-2023203-and-20221645))

---

## Section 02: Methodology <a name="section-02"></a>

#### Recommended flow: 
Scope/safety → aircraft/system architecture → asset inventory → trust boundaries → avionics networks → maintenance interfaces → datalink/RF → ground systems → airport infrastructure → software/firmware → supply chain → safety-impact analysis → detection/recovery.

---

## Section 03: Standards / Compliance <a name="section-03"></a>

- ⭐⭐⭐ DO-326A / ED-202A — airborne security process 
- ⭐⭐⭐ DO-356A / ED-203A — airworthiness security methods DO-355 / ED-204 — continuing airworthiness 
DO-178C — airborne software 
DO-254 — airborne electronic hardware 
ARP4754A/B 
EASA Part-IS 
EU 2022/1645 / 2023/203 
[RTCA Standards](https://www.rtca.org/standards/)

---

## Section 04: Official Documentation <a name="section-04"></a>

[EASA Easy Access Rules for Information Security](https://www.easa.europa.eu/en/document-library/easy-access-rules/easy-access-rules-information-security-regulations-eu-2023203-and-20221645)[FAA Aircraft Certification Resources](https://www.faa.gov/aircraft/air_cert)[EUROCAE](https://www.eurocae.net/)

---

## Section 05: Checklists <a name="section-05"></a>

Cover: 
AFDX/ARINC 664 · ARINC 429 · CAN Aerospace · maintenance ports · avionics gateways · EFB · IFE · SATCOM · ACARS · ADS-B · GNSS · datalink · airport networks · ground systems · OTA/software loading · secure boot · logging

---

## Section 06: Cheat Sheets <a name="section-06"></a>

Wireshark aviation protocol filters 
ADS-B / Mode-S references 
ARINC protocol references 
MAVLink documentation for UAV crossover 
[MAVLink Security Guide](https://mavlink.io/en/guide/message_signing.html)

---

## Section 07: Tools <a name="section-07"></a>

- ⭐⭐⭐ Wireshark ⭐⭐⭐ GNU Radio ⭐⭐⭐ dump1090 / readsb ⭐⭐ Scapy ⭐⭐ SDRangel / SDR++ ⭐⭐ OpenSky tools ⭐⭐ MAVProxy / pymavlink for UAV labs

---

## Section 08: Labs / Practice <a name="section-08"></a>

ADS-B receive-only lab 
GNU Radio RF lab 
UAV simulator / SITL 
ArduPilot SITL 
PX4 SITL 
CTF-style aerospace security exercises 
Your uploaded material also includes UAV security papers, DroneSec training, DroneKit, OpenDroneID and drone-security research resources.

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

For simulation or authorized systems: 
command authentication 
maintenance interface authorization 
software-load integrity 
ADS-B trust assumptions 
GPS/GNSS resilience 
datalink authentication 
avionics segmentation 
EFB access control

---

## Section 10: YouTube / Video <a name="section-10"></a>

Aviation ISAC · DEF CON Aerospace Village · Black Hat · EUROCONTROL · DroneSec.

---

## Section 11: Courses / Training <a name="section-11"></a>

aviation cybersecurity / DO-326A training 
EASA Part-IS training 
EUROCAE/RTCA courses 
DroneSec UAV-security training

---

## Section 12: Certifications <a name="section-12"></a>

No single universal aviation pentesting credential. Useful credentials are usually DO-326A/ED-202A, Part-IS, aircraft cybersecurity engineering, or safety/security process training.

---

## Section 13: Books <a name="section-13"></a>

Aviation Cybersecurity 
Aircraft Cybersecurity 
UAV/drone security books 
avionics-network engineering references

---

## Section 14: Blogs / Articles <a name="section-14"></a>

Aviation ISAC · EUROCONTROL · EASA · Pen Test Partners aviation research · IOActive transportation research.

---

## Section 15: Research Papers <a name="section-15"></a>

IEEE Aerospace · USENIX Security · NDSS · ACM CCS · aviation cyber-safety research.

---

## Section 16: White Papers <a name="section-16"></a>

EASA Part-IS material · EUROCONTROL cybersecurity reports · Aviation ISAC guidance.

---

## Section 17: Conference Material <a name="section-17"></a>

DEF CON Aerospace Village · Aviation Cyber Initiative events · Black Hat · A-ISAC Summit.

---

## Section 18: Mind Maps <a name="section-18"></a>

Aircraft → avionics → databus → RF/datalink → navigation → EFB/IFE → maintenance → ground systems → airports → UAS → supply chain → safety.

---

## Section 19: Sample Reports <a name="section-19"></a>

Add explicit columns for: 
Safety effect · operational effect · security impact · aircraft state · affected function · compensating safety mechanism

---

## Section 20: Templates <a name="section-20"></a>

aircraft-security-test-plan.md avionics-network-review.md ground-system-review.md uas-security-checklist.md aviation-cybersecurity-report.md

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

Track aircraft communication systems, EFBs, SATCOM equipment, avionics-support equipment, airport systems and UAVs.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

dump1090 · readsb · pymavlink · ArduPilot · PX4 · OpenDroneID · DroneKit.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

OpenSky Network datasets · ADS-B captures · flight logs · UAV telemetry.

---

## Section 24: Communities / Forums <a name="section-24"></a>

Aviation ISAC · Aerospace Village · OpenSky · EUROCONTROL community.

---

## Section 25: Vendors / Products <a name="section-25"></a>

Collins Aerospace · Honeywell · Thales · Airbus Protect · Boeing security ecosystem · Keysight/Spirent avionics testing.

---

## Section 26: Latest Developments <a name="section-26"></a>

Track Part-IS implementation, software-defined avionics, connected aircraft, UAS, GNSS interference, supply-chain risk, e-enabled aircraft and increasingly cloud-connected ground systems.

---

## Section 27: Learning Roadmap <a name="section-27"></a>

Aviation fundamentals → avionics → ARINC networks → RF/GNSS → aircraft/ground architecture → DO-326A → Part-IS → UAVs → safety-aware testing.

---

<div align="center">
<sub>✈️ Aviation / Aerospace Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>