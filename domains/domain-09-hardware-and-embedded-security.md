# 🔧 Domain 09: Hardware & Embedded Security

> **Group:** Wireless, Hardware & Embedded  
> **Curated links:** 108  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

This is the GitHub/website-ready Hardware & Embedded Security resource set, using the same 27-category structure. 
Your uploaded Offensive Resources already contains a useful IoT & Hardware branch with Practical IoT Hacking, The IoT Hacker's Handbook, The Hardware Hacking Handbook, Practical Hardware Pentesting, SEC556, Offensive IoT Exploitation and the Applied Physical Attacks series. I’ve expanded that significantly toward actual hardware/embedded security: PCB analysis, UART/JTAG/SWD, SPI/I²C, flash, debug/test interfaces, secure elements, TPM, TrustZone, Root of Trust, side-channel analysis, fault injection, secure MCUs, hardware lifecycle, and hardware-assisted memory safety. 
Boundary with your other domains: deep firmware extraction/reversing belongs under Firmware Security, while Wi-Fi/BLE/RF belongs under Wireless & RF Security. Here the main focus is the physical device, processor, buses, debug interfaces, silicon security, and hardware roots of trust. 

#### Legend: ⭐⭐⭐ Essential · ⭐⭐ Recommended · ⭐ Useful

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

| Resource | Type | Main Value |
| --- | --- | --- |
| The Hardware Hacking Handbook |
| Book |
| Best broad practical introduction |
| OWASP IoT Security Guidance |
| Free |
| Device-level security concepts |
| MITRE CWE Hardware Design View |
| Official |
| Hardware weakness taxonomy |
| Arm Platform Security Architecture |
| Official |
| Embedded security architecture |
| OpenTitan Security Model |
| Open Source |
| Real Root-of-Trust architecture |
| ChipWhisperer Documentation |
| Open Source / Lab |
| Side-channel and fault injection |
| TCG TPM 2.0 |
| Official |
| Hardware-backed trust |
| GlobalPlatform SESIP |
| Standard / Free |
| Secure MCU/IoT platform evaluation |

[MITRE CWE Hardware Design View](https://cwe.mitre.org/data/definitions/1194.html)[Arm Security Architecture Resources](https://www.arm.com/architecture/security-features)[OpenTitan Security Documentation](https://opentitan.org/book/doc/security/)[ChipWhisperer Documentation](https://chipwhisperer.readthedocs.io/)[TCG TPM 2.0 Library](https://trustedcomputinggroup.org/resource/tpm-library-specification/)[GlobalPlatform SESIP](https://globalplatform.org/sesip/)
MITRE's current Hardware Design view is particularly useful because it organizes weaknesses around manufacturing/lifecycle, security flows, SoC integration, memory/storage, interfaces and buses, cryptographic hardware, power/clock/reset, and debug/test interfaces. ( [CWE](https://cwe.mitre.org/data/definitions/1194.html)) 

#### Core subjects 
Electronics fundamentals 
PCB architecture 
MCU / MPU / SoC 
CPU architectures 
ARM / RISC-V / MIPS 
Flash / EEPROM / eMMC / NAND 
UART 
JTAG 
SWD 
SPI 
I²C 
USB 
GPIO 
Debug interfaces 
Boundary scan 
Boot ROM 
Bootloader 
Memory protection 
TrustZone 
Secure Element 
TPM 
Hardware Root of Trust 
Device identity 
Attestation 
PUF 
TRNG 
Secure storage 
Hardware cryptography 
Side-channel analysis 
Power analysis 
EM analysis 
Fault injection 
Voltage glitching 
Clock glitching 
EMFI 
Debug locking 
Lifecycle states 
Anti-tamper 
Hardware memory safety

---

## Section 02: Methodology <a name="section-02"></a>

There is no single universal hardware-pentest standard. A strong methodology combines: 
Hardware threat modeling 
Physical inspection 
Interface discovery 
component identification 
bus analysis 
debug security 
memory extraction 
secure boot/Root-of-Trust assessment 
side-channel/fault resistance where applicable 
lifecycle/provisioning review 

#### Recommended Hardware Security Assessment Workflow 
Authorization / Scope 

→ ↓ Device Documentation Review 

→ ↓ Threat Modeling 

→ ↓ External Physical Inspection 

→ ↓ Device Disassembly 

→ ↓ PCB Mapping 

→ ↓ Component Identification 

→ ↓ Datasheet Collection 

→ ↓ Test Point Discovery 

→ ↓ Voltage / Ground Mapping 

→ ↓ UART Discovery 

→ ↓ JTAG / SWD Discovery 

→ ↓ SPI / I²C / Flash Analysis 

→ ↓ Debug Lock Verification 

→ ↓ Memory / Storage Security 

→ ↓ Secure Boot / Root of Trust 

→ ↓ Key / Secret Storage 

→ ↓ Hardware Isolation 

→ ↓ Secure Element / TPM 

→ ↓ Side-Channel Assessment 

→ ↓ Fault Injection Assessment 

→ ↓ Anti-Tamper / Physical Security 

→ ↓ Lifecycle / Provisioning 

→ ↓ Evidence 

→ ↓ Risk / Standards Mapping 

→ ↓ Remediation 

→ ↓ Retest 
A useful professional methodology source is Applied Physical Attacks 2, which explicitly structures hardware pentesting around pre-engagement, intelligence gathering, threat modeling, vulnerability analysis, exploitation, post-exploitation, and reporting. ( [Securing Hardware](https://securinghardware.com/training/pentesting/))

---

## Section 03: Standards / Compliance <a name="section-03"></a>

| Standard / Framework | Coverage |
| --- | --- |
| ⭐⭐⭐ MITRE CWE Hardware Design |
| Hardware weakness taxonomy |
| ⭐⭐⭐ GlobalPlatform SESIP |
| IoT/embedded platform evaluation |
| ⭐⭐⭐ SESIP Secure MCU/MPU Profile |
| Secure microcontrollers |
| ⭐⭐⭐ Arm PSA / PSA Certified |
| Embedded Root-of-Trust architecture |
| ⭐⭐⭐ TCG TPM 2.0 |
| Trusted hardware |
| ISO/IEC 15408 – Common Criteria |
| Security evaluation |
| FIPS 140-3 |
| Cryptographic modules |
| IEC 62443-4-2 |
| Industrial component security |
| NISTIR 8259A |
| Device cybersecurity baseline |
| NISTIR 8259 Rev.1 |
| Product-manufacturer cybersecurity activities |
| NIST SP 800-193 |
| Platform firmware resilience |
| IEEE 1149.1 |
| JTAG/boundary scan |

[GlobalPlatform SESIP Methodology](https://globalplatform.org/specs-library/sesip-methodology/)[SESIP Secure MCU/MPU Profile](https://globalplatform.org/specs-library/globalplatform-technology-sesip-profile-for-secure-mcus-and-mpus-gpt_spe_150/)[NISTIR 8259A](https://csrc.nist.gov/pubs/ir/8259/a/final)[NISTIR 8259 Rev.1](https://csrc.nist.gov/pubs/ir/8259/r1/final)[NIST SP 800-193](https://csrc.nist.gov/pubs/sp/800/193/final)
GlobalPlatform's SESIP Secure MCUs and MPUs v1.1 was published in May 2025 and is specifically designed for evaluating MCU and MPU security using SESIP. ( [GlobalPlatform](https://globalplatform.org/specs-library/globalplatform-technology-sesip-profile-for-secure-mcus-and-mpus-gpt_spe_150/))

---

## Section 04: Official Documentation <a name="section-04"></a>

Hardware roots of trust 
[OpenTitan Documentation](https://opentitan.org/book/)[OpenTitan Security Model](https://opentitan.org/book/doc/security/)[Trusted Computing Group TPM](https://trustedcomputinggroup.org/work-groups/trusted-platform-module/)
OpenTitan is especially valuable because its public security model covers attestation, provisioning, secure boot, lifecycle management, identity, ownership transfer and firmware update. ( [OpenTitan](https://opentitan.org/book/doc/security/)) 
ARM 
[Arm CPU Architecture Security Features](https://www.arm.com/architecture/security-features)[Arm Platform Security Resources](https://developer.arm.com/architectures/security-architectures/platform-security-architecture)[PSA Certified](https://www.psacertified.org/)
Arm's platform model combines threat models, hardware/firmware architecture, reference implementations and security evaluation. ( [Arm Documentation Service](https://documentation-service.arm.com/static/6554c33bd29a2e2f75bb464e?token=)) 
Debugging 
[OpenOCD Documentation](https://openocd.org/doc/html/index.html)[pyOCD Documentation](https://pyocd.io/)
OpenOCD supports both JTAG and ARM-specific SWD transports, making it one of the central tools for embedded debug-interface analysis. ( [Open On-Chip Debugger](https://openocd.org/doc/html/Debug-Adapter-Configuration.html))

---

## Section 05: Checklists <a name="section-05"></a>

Hardware/Embedded Security Checklist 
Device model / revision 
PCB revision 
SoC / MCU identification 
Memory chips 
Secure element 
TPM 
External flash 
Test points 
Debug headers 
UART 
JTAG 
SWD 
SPI 
I²C 
USB 
GPIO 
Debug lock status 
Production debug disabled 
Boundary scan exposure 
Boot mode pins 
Recovery mode 
ROM bootloader 
Flash read protection 
Memory encryption 
Secure storage 
Key storage 
OTP / eFuse 
Lifecycle configuration 
Secure Boot 
Root of Trust 
Boot chain 
Anti-rollback 
Attestation 
Device identity 
TrustZone / isolation 
MPU / PMP 
Privilege separation 
TRNG quality 
Hardware crypto 
Key generation 
Side-channel leakage 
Timing leakage 
Power leakage 
EM leakage 
Voltage glitch resistance 
Clock glitch resistance 
EM fault resistance 
Tamper detection 
Enclosure security 
Sensors 
Debug port physical protection 
Manufacturing provisioning 
Factory credentials 
RMA lifecycle 
Ownership transfer 
Secure decommissioning

---

## Section 06: Cheat Sheets <a name="section-06"></a>

Interface quick reference 

| Interface | Typical Signals |
| --- | --- |
| UART |
| TX, RX, GND, VCC |
| JTAG |
| TCK, TMS, TDI, TDO, TRST |
| SWD |
| SWDIO, SWCLK, GND |
| SPI |
| MOSI, MISO, CLK, CS |
| I²C |
| SDA, SCL |
| SWO |
| SWO / trace output |

Useful references: 
[OpenOCD JTAG/SWD Configuration](https://openocd.org/doc/html/Debug-Adapter-Configuration.html)[PulseView / sigrok](https://sigrok.org/wiki/PulseView)[ChipWhisperer Getting Started](https://chipwhisperer.readthedocs.io/en/latest/getting-started.html)[Bus Pirate Documentation](https://docs.buspirate.com/)

---

## Section 07: Tools <a name="section-07"></a>

PCB / Interface Discovery 

| Tool | Purpose |
| --- | --- |
| ⭐⭐⭐ Multimeter |
| Voltage/GND/continuity |
| ⭐⭐⭐ Logic Analyzer |
| Digital bus analysis |
| ⭐⭐⭐ Oscilloscope |
| Electrical/timing analysis |
| ⭐⭐⭐ JTAGulator |
| Debug interface discovery |
| ⭐⭐⭐ Bus Pirate |
| UART/SPI/I²C interaction |
| ⭐⭐ Glasgow Interface Explorer |
| Multi-protocol hardware interface |
| ⭐⭐ Tigard |
| Hardware interface tool |
| ⭐⭐ GreatFET |
| USB/SPI/I²C/UART experimentation |

[JTAGulator GitHub](https://github.com/grandideastudio/jtagulator)[Glasgow Interface Explorer](https://github.com/GlasgowEmbedded/glasgow)[Tigard](https://github.com/tigard-tools/tigard)[GreatFET](https://greatfet.readthedocs.io/)
JTAGulator is specifically designed to discover on-chip debug interfaces from test points, vias and component pads. ( [GitHub](https://github.com/grandideastudio/jtagulator)) 
Digital Analysis 

- ⭐⭐⭐ PulseView 
- ⭐⭐⭐ sigrok-cli Saleae Logic 
DSView 
[sigrok / PulseView](https://sigrok.org/)
PulseView provides logic-analyzer visualization plus protocol-decoder support. ( [sigrok.org](https://sigrok.org/wiki/PulseView)) 
Debugging / Programming 

- ⭐⭐⭐ OpenOCD pyOCD 
J-Link tools 
ST-Link 
Black Magic Probe 
[OpenOCD](https://openocd.org/)[Black Magic Probe](https://black-magic.org/)
Memory / Flash 

- ⭐⭐⭐ flashrom flashprog 
Bus Pirate 
CH341A tooling 
SPI programmers 
[flashrom](https://flashrom.org/)
Side Channel / Fault Injection 

| Tool | Purpose |
| --- | --- |
| ⭐⭐⭐ ChipWhisperer |
| Power analysis + glitching |
| ⭐⭐⭐ ChipWhisperer Husky |
| Advanced SCA/FI |
| ⭐⭐ ChipSHOUTER |
| EM fault injection |
| ⭐⭐ PicoEMP |
| Accessible EMFI experimentation |
| Riscure Inspector |
| Commercial evaluation platform |

[ChipWhisperer](https://chipwhisperer.io/)[ChipWhisperer Documentation](https://chipwhisperer.readthedocs.io/)[PicoEMP](https://github.com/newaetech/picoemp)
ChipWhisperer is a complete open-source toolchain specifically built for power side-channel analysis and voltage/clock fault injection, with Jupyter-based labs. ( [chipwhisperer.readthedocs.io](https://chipwhisperer.readthedocs.io/en/latest/getting-started.html)) 
Platform Security 
CHIPSEC 
tpm2-tools 
TPM2 software stack 
OpenTitan 
[CHIPSEC](https://github.com/chipsec/chipsec)[tpm2-tools](https://github.com/tpm2-software/tpm2-tools)

---

## Section 08: Labs / Practice <a name="section-08"></a>

| Lab | Area |
| --- | --- |
| ⭐⭐⭐ ChipWhisperer Labs |
| SCA / fault injection |
| ⭐⭐⭐ Microcorruption |
| Embedded reversing |
| ⭐⭐⭐ Securing Hardware Workshops |
| UART/JTAG/SPI |
| ⭐⭐⭐ Applied Physical Attacks |
| Hardware pentesting |
| ⭐⭐ OpenTitan |
| Root-of-Trust architecture |
| ⭐⭐ CHERIoT simulator |
| Secure embedded architecture |
| ⭐⭐ Raspberry Pi Hardware Hacking Workshop |
| Beginner hardware lab |

[ChipWhisperer Tutorials](https://chipwhisperer.readthedocs.io/en/latest/getting-started.html)[Microcorruption](https://microcorruption.com/)[Securing Hardware Workshops](https://securinghardware.com/training/formats/workshops/)[OpenTitan](https://opentitan.org/)[CHERIoT Platform](https://cheriot.org/)
SecuringHardware publishes free workshops in addition to its professional courses, including material around Raspberry Pi hardware attacks and JTAG/OpenOCD. ( [Securing Hardware](https://securinghardware.com/training/courses/))

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

For devices you own or are authorized to assess, maintain test cases rather than generic offensive payloads. 
Debug interfaces 
UART console exposure 
UART unauthenticated shell 
Bootloader interruption 
JTAG enabled in production 
SWD enabled in production 
Debug authentication 
Debug fuse configuration 
Boundary scan access 
Storage 
External flash readable 
Flash protection bypass 
Secrets in EEPROM 
Unencrypted eMMC 
Sensitive OTP values 
Key extraction feasibility 
Hardware security 
Secure Boot validation 
Root-of-Trust verification 
Anti-rollback 
Debug lifecycle transition 
TrustZone isolation 
Secure/non-secure peripheral separation 
Secure element authentication 
TPM access controls 
Physical robustness 
Power side-channel leakage 
Timing leakage 
EM leakage 
Voltage glitch response 
Clock glitch response 
Reset glitch response 
EMFI response 
Tamper detection

---

## Section 10: YouTube / Video <a name="section-10"></a>

#### Recommended: 

| Resource | Focus |
| --- | --- |
| ⭐⭐⭐ Hardwear.io |
| Hardware-security research |
| ⭐⭐⭐ NewAE / ChipWhisperer |
| SCA/FI |
| ⭐⭐⭐ Joe Grand |
| Hardware hacking |
| ⭐⭐⭐ DEF CON Hardware Hacking Village |
| Hardware research |
| ⭐⭐⭐ Black Hat |
| Advanced embedded research |
| ⭐⭐ Great Scott Gadgets |
| Electronics/RF/hardware |
| ⭐⭐ EEVblog |
| Electronics foundations |
| ⭐⭐ Low Level Learning |
| low-level systems |

[Hardwear.io Videos](https://www.youtube.com/@hardweario)[NewAE / ChipWhisperer](https://www.youtube.com/@NewAETechnology)[DEF CON](https://www.youtube.com/@DEFCONConference)[Black Hat](https://www.youtube.com/@BlackHatOfficialYT)

---

## Section 11: Courses / Training <a name="section-11"></a>

Your uploaded resource material already recommends Offensive IoT Exploitation, SANS SEC556 and Applied Physical Attacks for IoT/hardware study. 

#### Recommended refined list: 

| Training | Focus |
| --- | --- |
| ⭐⭐⭐ Applied Physical Attacks 1 |
| UART/JTAG/SPI/embedded |
| ⭐⭐⭐ Applied Physical Attacks 2 |
| Hardware pentesting workflow |
| ⭐⭐⭐ Attify Offensive IoT Exploitation |
| Hardware + firmware + IoT |
| ⭐⭐⭐ ChipWhisperer Tutorials |
| SCA/FI |
| ⭐⭐ Hardwear.io Training |
| Advanced physical security |
| ⭐⭐ SANS SEC556 |
| IoT/embedded penetration testing |

[Applied Physical Attacks Courses](https://securinghardware.com/training/courses/)[Attify Offensive IoT Exploitation](https://www.attify.com/iot-security-exploitation-training)[ChipWhisperer Training Material](https://chipwhisperer.readthedocs.io/)[Hardwear.io Training](https://hardwear.io/trainings/)
Applied Physical Attacks 1 covers UART, JTAG, SPI, flash and embedded-device workflows; APA2 then extends this into a structured hardware penetration-testing process. ( [Securing Hardware](https://securinghardware.com/training/embedded/))

---

## Section 12: Certifications <a name="section-12"></a>

Hardware security does not have one dominant OSCP-style certification. 
Useful adjacent credentials: 

| Credential | Relevance |
| --- | --- |
| GlobalPlatform SESIP ecosystem |
| Product/platform evaluation |
| Common Criteria evaluator knowledge |
| Security evaluation |
| PSA Certified ecosystem |
| Embedded security assurance |
| GIAC GICSP |
| Useful for embedded/industrial crossover |
| Offensive IoT / hardware course certificates |
| Practical training evidence |

For this domain, demonstrable lab capability and research portfolio are generally more valuable than certification alone.

---

## Section 13: Books <a name="section-13"></a>

Your uploaded material provides a strong base here. 

#### Essential 

- ⭐⭐⭐ The Hardware Hacking Handbook — Jasper van Woudenberg & Colin O'Flynn 
- ⭐⭐⭐ Practical Hardware Pentesting 
- ⭐⭐⭐ The IoT Hacker's Handbook 
- ⭐⭐⭐ Practical IoT Hacking 
- ⭐⭐ Hardware Security: A Hands-On Learning Approach 
- ⭐⭐ The Hardware Security Handbook 
- ⭐⭐ Practical Electronics for Inventors 
- ⭐⭐ The Art of Electronics [The Hardware Hacking Handbook – No Starch Press](https://nostarch.com/hardwarehacking)
Your resource files specifically identify The Hardware Hacking Handbook and Practical Hardware Pentesting as core IoT/hardware texts.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

Follow: 

- ⭐⭐⭐ NewAE / ChipWhisperer 
- ⭐⭐⭐ Hardwear.io 
- ⭐⭐⭐ NCC Group Research 
- ⭐⭐⭐ Quarkslab 
- ⭐⭐⭐ Trail of Bits 
- ⭐⭐⭐ Riscure 
- ⭐⭐ Interrupt / Memfault 
- ⭐⭐ SecuringHardware 
- ⭐⭐ OpenTitan 
- ⭐⭐ lowRISC [ChipWhisperer Documentation & Research](https://chipwhisperer.readthedocs.io/)[Hardwear.io](https://hardwear.io/)[NCC Group Research](https://www.nccgroup.com/research-blog/)[Quarkslab Blog](https://blog.quarkslab.com/)[Trail of Bits Blog](https://blog.trailofbits.com/)[Interrupt by Memfault](https://interrupt.memfault.com/)[SecuringHardware.com](https://securinghardware.com/)

---

## Section 15: Research Papers <a name="section-15"></a>

#### Recommended publication sources: 
USENIX Security 
IEEE Security & Privacy 
ACM CCS 
CHES 
HOST 
NDSS 
WOOT 
Hardwear.io 
Black Hat 
[USENIX Security](https://www.usenix.org/conferences/byname/108)[IEEE Symposium on Security and Privacy](https://www.ieee-security.org/TC/SP-Index.html)[IACR CHES](https://ches.iacr.org/)[IEEE HOST](https://www.hostsymposium.org/)[NDSS Symposium](https://www.ndss-symposium.org/)

#### Research topics 
Side-channel analysis 
Differential power analysis 
Correlation power analysis 
EM analysis 
Fault injection 
Laser fault injection 
Voltage glitching 
Clock glitching 
EMFI 
Rowhammer 
PUFs 
TRNG attacks 
Hardware Trojans 
Secure elements 
Root of Trust 
Trusted execution 
Hardware memory safety 
Transient execution 
Chiplet security 
Supply-chain integrity

---

## Section 16: White Papers <a name="section-16"></a>

#### Recommended: 
Arm PSA Security Model 
OpenTitan Security Model 
TCG TPM architecture 
GlobalPlatform SESIP 
NISTIR 8259A 
NIST SP 800-193 
PSA Certified resources 
CHERIoT architecture 
[OpenTitan Security Model](https://opentitan.org/book/doc/security/)[TCG TPM 2.0 Specification](https://trustedcomputinggroup.org/resource/tpm-library-specification/)[GlobalPlatform SESIP](https://globalplatform.org/sesip/)[CHERIoT Architecture and Publications](https://cheriot.org/publications.html)

---

## Section 17: Conference Material <a name="section-17"></a>

| Conference | Importance |
| --- | --- |
| ⭐⭐⭐ Hardwear.io |
| Dedicated hardware security |
| ⭐⭐⭐ CHES |
| Cryptographic hardware |
| ⭐⭐⭐ IEEE HOST |
| Hardware-oriented security |
| ⭐⭐⭐ Black Hat |
| Applied hardware attacks |
| ⭐⭐⭐ DEF CON Hardware Hacking Village |
| Practical research |
| ⭐⭐ REcon |
| Low-level/reversing |
| ⭐⭐ TROOPERS |
| Embedded/product security |
| ⭐⭐ USENIX Security |
| Academic research |
| ⭐⭐ CCC |
| Hardware/embedded talks |

[Hardwear.io](https://hardwear.io/)[CHES](https://ches.iacr.org/)[IEEE HOST](https://www.hostsymposium.org/)[Black Hat](https://www.blackhat.com/)[DEF CON](https://defcon.org/)

---

## Section 18: Mind Maps <a name="section-18"></a>

#### Recommended hierarchy for your site: 
HARDWARE & EMBEDDED SECURITY 

```
│
```

```
├── Electronics Fundamentals
```

```
│   ├── Voltage / Current
```

```
│   ├── Digital Logic
```

```
│   └── Oscilloscope / Logic Analyzer
```

```
│
```

```
├── Device Architecture
```

```
│   ├── MCU
```

```
│   ├── MPU
```

```
│   ├── SoC
```

```
│   └── FPGA
```

```
│
```

```
├── Memory
```

```
│   ├── NOR
```

```
│   ├── NAND
```

```
│   ├── EEPROM
```

```
│   ├── eMMC
```

```
│   └── OTP / eFuse
```

```
│
```

```
├── Interfaces
```

```
│   ├── UART
```

```
│   ├── JTAG
```

```
│   ├── SWD
```

```
│   ├── SPI
```

```
│   ├── I²C
```

```
│   └── USB
```

```
│
```

```
├── Hardware Isolation
```

```
│   ├── TrustZone
```

```
│   ├── MPU
```

```
│   ├── PMP
```

```
│   └── TEE
```

```
│
```

```
├── Root of Trust
```

```
│   ├── TPM
```

```
│   ├── Secure Element
```

```
│   ├── OpenTitan
```

```
│   └── Attestation
```

```
│
```

```
├── Physical Attacks
```

```
│   ├── Power Analysis
```

```
│   ├── EM Analysis
```

```
│   ├── Voltage Glitch
```

```
│   ├── Clock Glitch
```

```
│   └── EMFI
```

```
│
```

```
├── Anti-Tamper
```

```
│
```

```
├── Manufacturing / Provisioning
```

```
│
```

```
├── Hardware Supply Chain
```

```
│
```

```
└── Standards
```

```
    ├── SESIP
```

```
    ├── PSA
```

```
    ├── Common Criteria
```

```
    └── CWE Hardware
```

---

## Section 19: Sample Reports <a name="section-19"></a>

#### Recommended report structure: 
Executive Summary 
Scope 
Device Identification 
Hardware Architecture 
PCB Analysis 
Component Inventory 
Debug Interfaces 
UART 
JTAG / SWD 
SPI / I²C 
Memory / Storage 
Boot Architecture 
Root of Trust 
Secure Element / TPM 
TrustZone / Isolation 
Cryptographic Hardware 
Side-Channel Assessment 
Fault-Injection Assessment 
Tamper Protection 
Manufacturing / Lifecycle 
Findings 
Evidence 
CWE Mapping 
SESIP / PSA Mapping 
Risk Rating 
Remediation 
Retest 
Conclusion

---

## Section 20: Templates <a name="section-20"></a>

#### Recommended repository structure: 
/templates/hardware-embedded-security/ 

```
├── hardware-security-test-plan.md
```

```
├── device-inventory.md
```

```
├── pcb-analysis-checklist.md
```

```
├── component-identification.md
```

```
├── uart-testing.md
```

```
├── jtag-swd-testing.md
```

```
├── spi-i2c-testing.md
```

```
├── memory-security-testing.md
```

```
├── debug-security-review.md
```

```
├── trustzone-review.md
```

```
├── secure-element-review.md
```

```
├── tpm-review.md
```

```
├── side-channel-test-plan.md
```

```
├── fault-injection-test-plan.md
```

```
├── lifecycle-security.md
```

```
├── evidence-template.md
```

```
└── hardware-security-report.md
```
Suggested test-case fields: 
Test ID 
Hardware Revision 
Component 
Interface 
Test Point 
Voltage 
Objective 
Prerequisite 
Equipment 
Procedure 
Expected Result 
Actual Result 
Evidence 
CWE 
Standard 
Severity 
Status

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

#### Primary resources: 
[MITRE CWE Hardware Design View](https://cwe.mitre.org/data/definitions/1194.html)[CVE.org](https://www.cve.org/)[NIST NVD](https://nvd.nist.gov/)[Google Project Zero](https://googleprojectzero.blogspot.com/)
Track case studies around: 
JTAG left enabled 
Unauthenticated UART 
Weak debug authentication 
Boot-ROM vulnerabilities 
Secure Boot bypass 
eFuse misconfiguration 
TrustZone escapes 
Secure element attacks 
TPM vulnerabilities 
Side-channel key recovery 
Fault-injection bypass 
Rowhammer 
Spectre-class hardware issues 
Hardware Trojans 
Supply-chain modification 
Weak TRNG 
Rollback protections 
MITRE's current hardware taxonomy alone contains over a hundred hardware-design weaknesses across areas such as debug/test, memory, cryptography, security flows and power/clock/reset. ( [CWE](https://cwe.mitre.org/data/definitions/1194.html))

---

## Section 22: GitHub Repositories <a name="section-22"></a>

#### Essential hardware tooling 

| Repository | Purpose |
| --- | --- |
| ⭐⭐⭐ ChipWhisperer |
| SCA / fault injection |
| ⭐⭐⭐ OpenOCD |
| JTAG/SWD |
| ⭐⭐⭐ JTAGulator |
| Debug discovery |
| ⭐⭐⭐ sigrok |
| Logic analysis |
| ⭐⭐⭐ flashrom |
| Flash access |
| ⭐⭐⭐ OpenTitan |
| Hardware Root of Trust |
| ⭐⭐ Glasgow |
| Interface exploration |
| ⭐⭐ GreatFET |
| Hardware experimentation |
| ⭐⭐ Tigard |
| UART/JTAG/SPI/I²C |
| ⭐⭐ CHIPSEC |
| Platform security |

[ChipWhisperer GitHub](https://github.com/newaetech/chipwhisperer)[OpenOCD GitHub](https://github.com/openocd-org/openocd)[JTAGulator GitHub](https://github.com/grandideastudio/jtagulator)[sigrok GitHub Organization](https://github.com/sigrokproject)[OpenTitan GitHub](https://github.com/lowRISC/opentitan)[Glasgow GitHub](https://github.com/GlasgowEmbedded/glasgow)[CHIPSEC GitHub](https://github.com/chipsec/chipsec)

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

Hardware security needs different datasets from normal pentesting. 
Useful material includes: 
Power traces 
EM traces 
Fault-injection results 
Logic-analyzer captures 
SPI captures 
I²C captures 
UART logs 
JTAG traces 
Oscilloscope captures 
Flash dumps 
EEPROM dumps 
PCB images 
Chip photographs 
Datasheets 
Schematic files 
FPGA bitstreams 

#### Useful sources 
[ChipWhisperer Tutorials and Traces](https://chipwhisperer.readthedocs.io/)[OpenTitan Hardware Repository](https://github.com/lowRISC/opentitan)[CHERIoT Platform](https://cheriot.org/)
ChipWhisperer training resources include purpose-built target boards and trace-based side-channel exercises across MCU and FPGA targets. ( [chipwhisperer.readthedocs.io](https://chipwhisperer.readthedocs.io/en/latest/Targets/index.html))

---

## Section 24: Communities / Forums <a name="section-24"></a>

#### Recommended: 
NewAE Forum 
Hardwear.io community 
EEVblog forum 
OpenTitan community 
lowRISC 
CHERIoT 
RISC-V community 
Reverse Engineering Stack Exchange 
r/embedded 
r/hardwarehacking 
r/ReverseEngineering 
[NewAE Forum](https://forum.newae.com/)[EEVblog Forum](https://www.eevblog.com/forum/)[OpenTitan](https://opentitan.org/)[Reverse Engineering Stack Exchange](https://reverseengineering.stackexchange.com/)

---

## Section 25: Vendors / Products <a name="section-25"></a>

| Category | Important Examples |
| --- | --- |
| Side-channel / FI |
| NewAE ChipWhisperer, Riscure |
| Debug |
| Segger J-Link, Lauterbach, ST-Link |
| Logic analysis |
| Saleae, DreamSourceLab |
| Oscilloscope |
| Keysight, Tektronix, Rohde & Schwarz |
| Hardware interface |
| Bus Pirate, Tigard, Glasgow, GreatFET |
| Debug discovery |
| JTAGulator |
| Secure elements |
| NXP, Infineon, Microchip, ST |
| TPM |
| Infineon, Nuvoton, ST |
| Secure MCU |
| NXP, ST, Microchip, Renesas |
| Root of Trust |
| OpenTitan ecosystem |

For your website, separate testing equipment from security components. Otherwise the vendor section becomes confusing.

---

## Section 26: Latest Developments <a name="section-26"></a>

Several developments are particularly important for your repository in 2026. 
TPM 2.0 continues evolving 
The Trusted Computing Group lists TPM 2.0 Library Specification Version 185, March 2026, with newer errata updates during August 2026. ( [Trusted Computing Group](https://trustedcomputinggroup.org/resource/tpm-library-specification/)) 
Open-source silicon Root of Trust is becoming production-grade 
OpenTitan describes itself as an open-source silicon Root of Trust and now reports OpenTitan silicon shipping in Chromebooks. ( [OpenTitan](https://opentitan.org/)) 
Its security framework also includes an automated penetration-testing framework for side-channel and fault-injection validation. ( [OpenTitan](https://opentitan.org/book/doc/security/)) 
Hardware-assisted memory safety: CHERIoT 
This is worth creating a dedicated subsection in your repository. 
CHERIoT 1.0 was released in November 2025, and in March 2026 the project announced its first CHERIoT silicon. The architecture brings capability-based memory safety and fine-grained compartmentalization to embedded-class RISC-V systems. ( [CHERIoT Platform](https://cheriot.org/sail/specification/release/2025/11/03/cheriot-1.0.html)) 
[CHERIoT Platform](https://cheriot.org/)
IoT manufacturer guidance updated 
NIST published NIST IR 8259 Rev.1 in April 2026, updating foundational cybersecurity activities for IoT product manufacturers. ( [NIST Computer Security Resource Center](https://csrc.nist.gov/pubs/ir/8259/r1/final)) 
Important topics to track 
Open-source silicon Root of Trust 
OpenTitan 
Hardware attestation 
TPM 2.0 
DICE 
Secure elements 
PSA Certified 
SESIP 
CHERI / CHERIoT 
Hardware-assisted memory safety 
Secure MCUs 
RISC-V security 
Post-quantum cryptography on MCUs 
PQC hardware acceleration 
Chiplet security 
PUFs 
Hardware supply-chain assurance 
Side-channel countermeasures 
Fault-injection countermeasures 
Secure lifecycle management 
Confidential computing 
AI accelerator security 
GPU/NPU hardware security

---

## Section 27: Learning Roadmap <a name="section-27"></a>

```
LEVEL 1 — Electronics Fundamentals
```
Voltage 
Current 
Resistance 
Digital logic 
Multimeter 
Oscilloscope 
Logic analyzer 

→ ↓ 
```
LEVEL 2 — Embedded Fundamentals
```
MCU 
MPU 
SoC 
ARM 
RISC-V 
Memory map 
GPIO 
Boot process 

→ ↓ 
```
LEVEL 3 — PCB Analysis
```
Components 
Datasheets 
Test points 
Tracing 
Ground 
Voltage rails 

→ ↓ 
```
LEVEL 4 — UART
```
Identify pins 
Baud rate 
Serial console 
Boot logs 

→ ↓ 
```
LEVEL 5 — SPI / I²C
```
Bus architecture 
Logic capture 
Protocol decoding 
External flash 

→ ↓ 
```
LEVEL 6 — JTAG / SWD
```
TAP 
Boundary scan 
Debug access 
OpenOCD 
JTAGulator 

→ ↓ 
```
LEVEL 7 — Memory Security
```
NOR 
NAND 
EEPROM 
eMMC 
OTP 
eFuse 

→ ↓ 
```
LEVEL 8 — Embedded Architecture
```
Boot ROM 
Bootloader 
MPU 
PMP 
Trust boundaries 

→ ↓ 
```
LEVEL 9 — Hardware Roots of Trust
```
Secure Boot 
TPM 
Secure Element 
OpenTitan 
Attestation 
Device identity 

→ ↓ 
```
LEVEL 10 — TrustZone / TEE
```
Secure world 
Non-secure world 
Secure peripherals 
Isolation 

→ ↓ 
```
LEVEL 11 — Cryptographic Hardware
```
AES accelerators 
TRNG 
PUF 
Key storage 

→ ↓ 
```
LEVEL 12 — Side-Channel Analysis
```
Timing 
Power 
SPA 
DPA 
CPA 
EM 

→ ↓ 
```
LEVEL 13 — Fault Injection
```
Voltage glitch 
Clock glitch 
Reset glitch 
EMFI 

→ ↓ 
```
LEVEL 14 — Physical Security
```
Tamper detection 
Tamper response 
Enclosure 
Sensors 

→ ↓ 
```
LEVEL 15 — Hardware Lifecycle
```
Manufacturing 
Provisioning 
Lifecycle states 
RMA 
Ownership transfer 
Decommissioning 

→ ↓ 
```
LEVEL 16 — Advanced Architecture
```
OpenTitan 
PSA 
SESIP 
CHERI / CHERIoT 
Hardware memory safety 

→ ↓ 
```
LEVEL 17 — Standards
```
CWE Hardware 
SESIP 
PSA Certified 
TPM 
Common Criteria 
NIST 

→ ↓ 
```
LEVEL 18 — Reporting
```
PCB evidence 
Interface captures 
Logic traces 
Oscilloscope traces 
CWE mapping 
Risk 
Remediation 
Retest 

- ⭐ Hardware & Embedded Security — Top 20 
| Rank | Resource | Purpose |
| --- | --- | --- |
| 1 |
| The Hardware Hacking Handbook |
| Practical foundation |
| 2 |
| ChipWhisperer |
| Side-channel / FI |
| 3 |
| OpenOCD |
| JTAG / SWD |
| 4 |
| JTAGulator |
| Debug discovery |
| 5 |
| sigrok / PulseView |
| Bus analysis |
| 6 |
| Bus Pirate |
| Hardware interfaces |
| 7 |
| MITRE CWE Hardware Design |
| Weakness taxonomy |
| 8 |
| OpenTitan |
| Root-of-Trust architecture |
| 9 |
| Arm PSA / TrustZone |
| Embedded architecture |
| 10 |
| TCG TPM 2.0 |
| Hardware trust |
| 11 |
| GlobalPlatform SESIP |
| Security evaluation |
| 12 |
| Applied Physical Attacks |
| Hardware training |
| 13 |
| Hardwear.io |
| Research/training |
| 14 |
| Microcorruption |
| Embedded practice |
| 15 |
| CHIPSEC |
| Platform hardware security |
| 16 |
| GreatFET |
| Hardware experimentation |
| 17 |
| Glasgow |
| Interface exploration |
| 18 |
| flashrom |
| Flash analysis |
| 19 |
| CHERIoT |
| Hardware memory safety |
| 20 |
| NISTIR 8259 |
| Device-security baseline |

#### Recommended practical stack 
Electronics → PCB analysis → datasheets → multimeter/logic analyzer → UART → SPI/I²C → JTAG/SWD + OpenOCD/JTAGulator → memory/flash → TrustZone/MPU → secure elements/TPM → Root of Trust/OpenTitan → ChipWhisperer side channels → fault injection → lifecycle/provisioning → SESIP/PSA/CWE → professional hardware security reporting.

---

<div align="center">
<sub>🔧 Hardware & Embedded Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>