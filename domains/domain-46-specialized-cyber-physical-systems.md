# 🏭 Domain 46: Specialized Cyber-Physical Systems

> **Group:** Specialized & Emerging Systems  
> **Curated links:** 4  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

This is best used as the umbrella for cyber-physical domains that do not justify another full top-level category. 
NIST defines CPS as interacting digital, analog, physical and human components, with examples including smart transportation, healthcare, intelligent buildings, robots and unmanned systems. ( [NIST](https://www.nist.gov/publications/framework-cyber-physical-systems-volume-1-overview)) 

#### Recommended Scope 
Robotics 
Drones / UAV 
Industrial Robots 
Autonomous Robots 
Smart Buildings 
Building Management Systems 
Elevators 
Access-Control Systems 
Smart Appliances 
Vending Machines 
Kiosks 
Smart Cities 
Emergency Systems 
Rail Systems 
Autonomous Machines 
Warehouse Robots 
AGVs / AMRs 
Physical Access Systems 
Your uploaded corpus also contains a substantial UAV/drone subsection with academic papers, DroneSec training and test/research projects, which fits well under this umbrella.

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

- ⭐⭐⭐ [NIST Cyber-Physical Systems Public Working Group](https://pages.nist.gov/cpspwg/)⭐⭐⭐ [NIST CPS Framework Volume 1](https://www.nist.gov/publications/framework-cyber-physical-systems-volume-1-overview)⭐⭐⭐ [NIST CPS Framework Volume 2](https://www.nist.gov/publications/framework-cyber-physical-systems-volume-2-working-group-reports)The NIST CPS Framework specifically models concerns such as trustworthiness, timing, data, composition, boundaries and lifecycle. ( [NIST](https://www.nist.gov/publications/framework-cyber-physical-systems-volume-2-working-group-reports))

---

## Section 02: Methodology <a name="section-02"></a>

Mission / Physical Function 
→ Safety Analysis 
→ Architecture 
→ Sensors 
→ Actuators 
→ Controllers 
→ Networks 
→ Wireless 
→ Firmware 
→ Cloud 
→ Human-Machine Interface 
→ Physical Effects 
→ Recovery / Fail-Safe

---

## Section 03: Standards / Compliance <a name="section-03"></a>

NIST CPS Framework · IEC 62443 · IEC 61508 · NIST CSF · sector-specific safety/security standards.

---

## Section 04: Official Documentation <a name="section-04"></a>

NIST CPS PWG · ROS 2 security · vendor protocol documentation · IEC/ISO sector standards.

---

## Section 05: Checklists <a name="section-05"></a>

Sensors 
Actuators 
Controllers 
Safety state 
Physical override 
Authentication 
Authorization 
Firmware 
Secure Boot 
Updates 
Wireless 
Cloud 
Remote access 
Fail-safe 
Logging 
Time synchronization 
Physical tamper

---

## Section 06: Cheat Sheets <a name="section-06"></a>

ROS 2 security · MQTT · CAN · Modbus · BACnet · MAVLink references according to system type.

---

## Section 07: Tools <a name="section-07"></a>

Wireshark · Nmap · Scapy · GNU Radio · ROS 2 tools · Gazebo · can-utils · MQTT tooling · BACnet utilities.

---

## Section 08: Labs / Practice <a name="section-08"></a>

- ⭐⭐⭐ ROS 2 + Gazebo ⭐⭐ ArduPilot/PX4 SITL ⭐⭐ OpenPLC ⭐⭐ smart-building/BACnet simulation ⭐⭐ custom Raspberry Pi/MCU CPS lab

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

Sensor spoofing resistance · actuator authorization · unsafe-state prevention · command replay · network segmentation · fail-safe behavior · firmware integrity.

---

## Section 10: YouTube / Video <a name="section-10"></a>

NIST CPS · ROSCon · DEF CON ICS/Aerospace villages · Hardwear.io · robotics-security talks.

---

## Section 11: Courses / Training <a name="section-11"></a>

Robotics security · embedded security · industrial security · drone security · functional-safety courses.

---

## Section 12: Certifications <a name="section-12"></a>

Usually sector-specific rather than CPS-wide: IEC 62443 · functional safety · IoT/product security.

---

## Section 13: Books <a name="section-13"></a>

Cyber-physical systems engineering · robotics security · IoT security · industrial-system security.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

NIST CPS · ROS security · CISA · industrial/product-security researchers.

---

## Section 15: Research Papers <a name="section-15"></a>

Robotics security · sensor spoofing · actuator attacks · autonomous systems · CPS resilience · safety/security co-engineering.

---

## Section 16: White Papers <a name="section-16"></a>

NIST CPS Framework · IEC 62443 guidance · sector-specific security/safety reports.

---

## Section 17: Conference Material <a name="section-17"></a>

IEEE CPS-Sec · ACM/IEEE ICCPS · USENIX Security · NDSS · CPS-IoT Week.

---

## Section 18: Mind Maps <a name="section-18"></a>

Cyber-Physical Systems 

```
├── Computation
```

```
├── Network
```

```
├── Sensors
```

```
├── Actuators
```

```
├── Physical Process
```

```
├── Human Operator
```

```
├── Timing
```

```
├── Safety
```

```
├── Security
```

```
└── Resilience
```

---

## Section 19: Sample Reports <a name="section-19"></a>

Include both: 
Cyber Impact 
+ 
Physical Impact 
+ 
Safety Impact 
+ 
Operational Impact

---

## Section 20: Templates <a name="section-20"></a>

cps-threat-model.md 
sensor-security-review.md 
actuator-security-review.md 
physical-impact-analysis.md 
cps-test-plan.md 
cps-security-report.md

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

Drone hijacking research · robot command manipulation · smart-building compromises · safety-system incidents · GPS/GNSS spoofing.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

ROS 2 · Gazebo · ArduPilot · PX4 · OpenPLC · DroneKit · OpenDroneID.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

Robot telemetry · UAV flight logs · sensor datasets · actuator events · GNSS/IMU data · smart-building datasets.

---

## Section 24: Communities / Forums <a name="section-24"></a>

ROS · NIST CPS PWG · CPS-IoT Week · Open Robotics · industrial-security communities.

---

## Section 25: Vendors / Products <a name="section-25"></a>

ABB · Siemens · Schneider Electric · Rockwell · Honeywell · Boston Dynamics · Universal Robots · DJI · smart-building vendors.

---

## Section 26: Latest Developments <a name="section-26"></a>

The main areas to track are: 
Autonomous robots 
AI-controlled physical systems 
Warehouse AMRs 
Drone autonomy 
Computer vision 
Smart buildings 
Digital twins 
Edge AI 
5G-connected CPS 
GNSS resilience 
Safety + cybersecurity co-engineering

---

## Section 27: Learning Roadmap <a name="section-27"></a>

Embedded systems → sensors/actuators → networking → safety → robotics/physical process → threat modeling → protocol testing → resilience → CPS security engineering. 
Repository Structure — Domains 40–46 
cybersecurity-resources/ 

```
│
```

```
├── 40-vulnerability-exposure-management/
```

```
├── 41-privacy-engineering-data-security/
```

```
├── 42-security-testing-standards-compliance/
```

```
├── 43-quantum-post-quantum-security/
```

```
├── 44-game-anti-cheat-security/
```

```
├── 45-mainframe-legacy-security/
```

```
└── 46-specialized-cyber-physical-systems/
```
Use the same common structure under every domain: 
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
├── sample-reports.md
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

---

<div align="center">
<sub>🏭 Specialized Cyber-Physical Systems · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>