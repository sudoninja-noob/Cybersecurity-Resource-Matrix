# 💾 Domain 10: Firmware Security

> **Group:** Wireless, Hardware & Embedded  
> **Curated links:** 119  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

This is the GitHub/website-ready Firmware Security resource set, using the same 27-category structure. 
Your uploaded Offensive Resources collection does not have a separate Firmware Security branch, but it contains highly relevant material under IoT & Hardware, including Practical IoT Hacking, The IoT Hacker's Handbook, The Hardware Hacking Handbook, Practical Hardware Pentesting, SEC556 and Offensive IoT Exploitation. It also contains the reverse-engineering foundation—The Ghidra Book, Practical Reverse Engineering, reverse-engineering courses and labs—that becomes important after firmware extraction. 
Legend: ⭐⭐⭐ Essential · ⭐⭐ Recommended · ⭐ Useful Type: Official · Free · Open Source · Paid · Lab · Research

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

Firmware security sits between software, hardware, embedded Linux, reverse engineering and product security. 

| Resource | Type | Main Value |
| --- | --- | --- |
| ⭐⭐⭐ OWASP Firmware Security Testing Methodology (FSTM) |
| Free / Methodology |
| End-to-end firmware assessment |
| ⭐⭐⭐ NIST SP 800-193 |
| Official |
| Firmware protection, detection and recovery |
| ⭐⭐⭐ NIST IR 8259 Rev.1 |
| Official |
| Product/IoT cybersecurity lifecycle |
| ⭐⭐⭐ UEFI Specifications |
| Official |
| PC/platform firmware |
| ⭐⭐⭐ EMBA |
| Open Source |
| Automated firmware security analysis |
| ⭐⭐⭐ Binwalk |
| Open Source |
| Firmware identification/extraction |
| ⭐⭐ FACT |
| Open Source |
| Automated firmware analysis/comparison |
| ⭐⭐ OWASP IoT Project |
| Free |
| Firmware + device security context |

[OWASP Internet of Things / FSTM](https://owasp.org/www-project-internet-of-things/)[NIST SP 800-193](https://csrc.nist.gov/pubs/sp/800/193/final)[NIST IR 8259 Rev.1](https://csrc.nist.gov/pubs/ir/8259/r1/final)[UEFI Specifications](https://uefi.org/specifications)[EMBA](https://github.com/e-m-b-a/emba)[Binwalk](https://github.com/ReFirmLabs/binwalk)[FACT Core](https://github.com/fkie-cad/fact_core)
NIST SP 800-193 provides the useful firmware-resiliency model of protecting firmware from unauthorized change, detecting unauthorized change, and recovering securely. ( [NIST Computer Security Resource Center](https://csrc.nist.gov/pubs/sp/800/193/final)) 

#### Core subjects 
Firmware architecture 
MCU / MPU firmware 
Embedded Linux 
RTOS firmware 
UEFI / BIOS 
Bootloader 
Boot ROM 
Device Tree 
Kernel 
Root filesystem 
SquashFS 
JFFS2 
UBIFS / UBI 
CRAMFS 
YAFFS 
CramFS 
initramfs 
ELF binaries 
ARM / ARM64 
MIPS 
RISC-V 
x86 
Firmware extraction 
Entropy analysis 
Static analysis 
Binary analysis 
Dynamic analysis 
Firmware emulation 
SBOM 
Secrets discovery 
CVE mapping 
Secure Boot 
Measured Boot 
Root of Trust 
Firmware signing 
OTA updates 
Anti-rollback 
Recovery 
Firmware supply chain

---

## Section 02: Methodology <a name="section-02"></a>

The strongest starting methodology is OWASP FSTM. 
OWASP defines nine firmware security testing stages: 
Information gathering and reconnaissance 
Obtaining firmware 
Analyzing firmware 
Extracting the filesystem 
Analyzing filesystem contents 
Emulating firmware 
Dynamic analysis 
Runtime analysis 
Binary exploitation 
( [GitHub](https://github.com/OWASP/www-project-internet-of-things/blob/master/tab_validate_and_test.md)) 

#### Recommended practical workflow 
Authorization / Scope 

→ ↓ Device / Firmware Identification 

→ ↓ Documentation Collection 

→ ↓ Firmware Acquisition 

→ ↓ Hash / Version Recording 

→ ↓ File-Type Identification 

→ ↓ Entropy Analysis 

→ ↓ Firmware Extraction 

→ ↓ Filesystem Identification 

→ ↓ Filesystem Extraction 

→ ↓ Static Analysis 

→ ↓ Configuration Analysis 

→ ↓ Secrets / Credentials Analysis 

→ ↓ Software Component Inventory 

→ ↓ SBOM Generation 

→ ↓ CVE / CWE Mapping 

→ ↓ Binary Hardening Review 

→ ↓ Binary Reverse Engineering 

→ ↓ Firmware Emulation 

→ ↓ Service / Web / API Testing 

→ ↓ Runtime Analysis 

→ ↓ Secure Boot Review 

→ ↓ Firmware Update Review 

→ ↓ Signature Verification 

→ ↓ Anti-Rollback Review 

→ ↓ Recovery Review 

→ ↓ Evidence / Reporting 

→ ↓ Remediation / Retest 

> Priority: ⭐⭐⭐

---

## Section 03: Standards / Compliance <a name="section-03"></a>

| Standard / Framework | Firmware Relevance |
| --- | --- |
| ⭐⭐⭐ NIST SP 800-193 |
| Firmware resiliency |
| ⭐⭐⭐ NIST IR 8259 Rev.1 |
| Product cybersecurity lifecycle |
| ⭐⭐⭐ ETSI EN 303 645 |
| Consumer IoT secure-update requirements |
| ⭐⭐⭐ EU Cyber Resilience Act |
| Secure updates, vulnerability handling |
| IEC 62443-4-1 |
| Secure product development |
| IEC 62443-4-2 |
| Component security |
| GlobalPlatform SESIP |
| Embedded platform security evaluation |
| PSA Certified |
| MCU/embedded security |
| ISO/SAE 21434 |
| Automotive firmware/software cybersecurity |
| UNECE R156 |
| Automotive software update management |
| Common Criteria |
| Security evaluation |
| FIPS 140-3 |
| Crypto module security |
| TCG TPM / DICE |
| Trust/attestation |

[ETSI EN 303 645](https://www.etsi.org/technologies/consumer-iot-security)[EU Cyber Resilience Act](https://eur-lex.europa.eu/eli/reg/2024/2847/oj/eng)[GlobalPlatform SESIP](https://globalplatform.org/sesip/)[PSA Certified](https://www.psacertified.org/)[UNECE R156](https://unece.org/transport/documents/2021/03/standards/un-regulation-no-156-software-update-and-software-update)
ETSI EN 303 645 explicitly requires software components that are not intentionally immutable to be securely updateable and calls for secure update mechanisms, authenticity/integrity verification and measures such as anti-rollback where appropriate. ( [ETSI](https://www.etsi.org/deliver/etsi_en/303600_303699/303645/03.01.02_20/en_303645v030102a.pdf))

---

## Section 04: Official Documentation <a name="section-04"></a>

NIST 
[NIST SP 800-193 — Platform Firmware Resiliency](https://csrc.nist.gov/pubs/sp/800/193/final)[NIST IR 8259 Rev.1](https://csrc.nist.gov/pubs/ir/8259/r1/final)[NIST IR 8259A](https://csrc.nist.gov/pubs/ir/8259/a/final)
UEFI / Platform Firmware 
[UEFI Specifications](https://uefi.org/specifications)[UEFI Secure Boot specification section](https://uefi.org/specs/UEFI/2.10/32_Secure_Boot_and_Driver_Signing.html)
UEFI currently lists UEFI Specification 2.11, released in December 2024. ( [uefi.org](https://uefi.org/specifications)) 
Linux Firmware Updates 
[fwupd](https://fwupd.org/)[LVFS Security Documentation](https://lvfs.readthedocs.io/en/latest/security.html)
LVFS/fwupd uses signed metadata and vendor/device identity checks to reduce the risk of firmware being delivered to unintended hardware. ( [lvfs.readthedocs.io](https://lvfs.readthedocs.io/en/latest/security.html))

---

## Section 05: Checklists <a name="section-05"></a>

Firmware Acquisition 
Firmware source identified 
Version identified 
Build date identified 
Vendor hash obtained 
Local hash generated 
Firmware signature identified 
Encrypted/unencrypted status 
Compression identified 
Filesystem 
Filesystem type 
Root filesystem extracted 
/etc 
/bin 
/sbin 
/usr/bin 
/usr/sbin 
/www 
/var 
/home 
/root 
/init 
Startup scripts 
Configuration files 
Web files 
Certificates 
Keys 
Secrets 
Hard-coded usernames 
Passwords 
API keys 
Cloud credentials 
Private keys 
SSH keys 
TLS keys 
Wi-Fi credentials 
Database credentials 
Debug credentials 
Default credentials 
Tokens 
Certificates 
Binary Security 
Architecture 
ELF properties 
NX 
PIE 
RELRO 
Stack canary 
FORTIFY 
RPATH/RUNPATH 
Stripped symbols 
Dangerous functions 
Setuid binaries 
Custom daemons 
Update Security 
Authenticated update 
Firmware signature 
Integrity verification 
TLS 
Certificate validation 
Version checking 
Anti-rollback 
Recovery image 
A/B partitioning 
Failure recovery 
Key rotation 
Revocation

---

## Section 06: Cheat Sheets <a name="section-06"></a>

#### Recommended: 
[Binwalk README/Wiki](https://github.com/ReFirmLabs/binwalk)[Ghidra Documentation](https://ghidra-sre.org/)[HackTricks Firmware / IoT material](https://book.hacktricks.wiki/)[QEMU Documentation](https://www.qemu.org/docs/master/)[Radare2 Book](https://book.rada.re/)[EMBA Wiki](https://github.com/e-m-b-a/emba/wiki)
Useful command/tool index: 
file 
strings 
xxd 
hexdump 
binwalk 
unsquashfs 
sasquatch 
jefferson 
ubi_reader 
readelf 
objdump 
nm 
checksec 
grep 
ripgrep 
yara 
qemu 
gdb-multiarch 
strace 
ltrace 
ghidra 
radare2 
rizin

---

## Section 07: Tools <a name="section-07"></a>

Firmware Identification / Extraction 

| Tool | Use |
| --- | --- |
| ⭐⭐⭐ Binwalk v3 |
| Signatures, extraction, entropy |
| ⭐⭐⭐ EMBA |
| End-to-end analysis |
| ⭐⭐⭐ FACT |
| Automated analysis/comparison |
| ⭐⭐ unblob |
| Firmware extraction |
| ⭐⭐ Jefferson |
| JFFS2 extraction |
| ⭐⭐ ubi_reader |
| UBI/UBIFS |
| ⭐⭐ SquashFS Tools |
| SquashFS extraction |

[Binwalk](https://github.com/ReFirmLabs/binwalk)[EMBA](https://github.com/e-m-b-a/emba)[FACT Core](https://github.com/fkie-cad/fact_core)[unblob](https://github.com/onekey-sec/unblob)[Jefferson](https://github.com/sviehb/jefferson)[ubi_reader](https://github.com/onekey-sec/ubi_reader)[SquashFS Tools](https://github.com/plougher/squashfs-tools)
Binwalk has now moved to Binwalk v3, rewritten in Rust and still focused on identifying/extracting embedded data plus entropy-based analysis. ( [GitHub](https://github.com/refirmlabs/binwalk)) 
EMBA integrates extraction, static analysis, emulation-based dynamic analysis, SBOM generation and web reporting. ( [GitHub](https://github.com/e-m-b-a/emba)) 
Binary Analysis 

- ⭐⭐⭐ Ghidra 
- ⭐⭐⭐ IDA 
- ⭐⭐⭐ Radare2 
- ⭐⭐⭐ Rizin/Cutter 
- ⭐⭐ Binary Ninja 
- ⭐⭐ angr 
- ⭐⭐ GDB [Ghidra GitHub](https://github.com/NationalSecurityAgency/ghidra)[Radare2](https://github.com/radareorg/radare2)[Rizin](https://rizin.re/)[Cutter](https://cutter.re/)[angr](https://github.com/angr/angr)
Security / Hardening 
[checksec](https://github.com/slimm609/checksec)[YARA](https://github.com/VirusTotal/yara)
UEFI / BIOS 
CHIPSEC 
UEFITool 
UEFIExtract 
fwupd 
chipsec_util 
[CHIPSEC](https://github.com/chipsec/chipsec)[UEFITool](https://github.com/LongSoft/UEFITool)

---

## Section 08: Labs / Practice <a name="section-08"></a>

| Lab / Project | Focus |
| --- | --- |
| ⭐⭐⭐ EMBA |
| Full firmware workflow |
| ⭐⭐⭐ FirmAE |
| Firmware emulation |
| ⭐⭐⭐ Firmadyne |
| Linux firmware emulation |
| ⭐⭐⭐ IoTVulBench |
| Vulnerable firmware benchmark |
| ⭐⭐⭐ RealworldFirmware |
| Research dataset |
| ⭐⭐ pwn.college |
| Low-level/binary skills |
| ⭐⭐ Microcorruption |
| Embedded reversing |
| ⭐⭐ OWASP IoTGoat |
| IoT/firmware practice |

[FirmAE](https://github.com/pr0v3rbs/FirmAE)[Firmadyne](https://github.com/firmadyne/firmadyne)[IoTVulBench](https://github.com/a101e-lab/IoTVulBench)[RealworldFirmware](https://github.com/MCUSec/RealworldFirmware)[pwn.college](https://pwn.college/)[Microcorruption](https://microcorruption.com/)
IoTVulBench is specifically designed as an open-source benchmark containing firmware vulnerabilities plus tooling for building emulations and verifying them. ( [GitHub](https://github.com/a101e-lab/IoTVulBench))

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

For authorized firmware assessments, organize this as test cases, not simply exploit payload collections. 
Secrets 
Search for password= 
passwd 
secret 
token 
apikey 
api_key 
BEGIN PRIVATE KEY 
BEGIN RSA PRIVATE KEY 
AWS_ACCESS_KEY 
ssh-rsa 
Binary tests 
Stack protection 
NX 
PIE 
RELRO 
FORTIFY 
Dangerous functions 
Command execution 
Unsafe temporary files 
Setuid/setgid 
Weak permissions 
Update tests 
Unsigned update rejection 
Modified-image rejection 
Wrong-device image rejection 
Older-version rejection 
Invalid certificate rejection 
Corrupted-image recovery 
Interrupted-update recovery 
Useful corpora 
[SecLists](https://github.com/danielmiessler/SecLists)[FuzzDB](https://github.com/fuzzdb-project/fuzzdb)[AFL++](https://github.com/AFLplusplus/AFLplusplus)[boofuzz](https://github.com/jtpereyda/boofuzz)[libFuzzer Documentation](https://llvm.org/docs/LibFuzzer.html)

---

## Section 10: YouTube / Video <a name="section-10"></a>

#### Recommended channels: 

- ⭐⭐⭐ Hardwear.io 
- ⭐⭐⭐ DEF CON 
- ⭐⭐⭐ Black Hat 
- ⭐⭐⭐ OpenSecurityTraining 
- ⭐⭐⭐ LiveOverflow 
- ⭐⭐⭐ Ghidra 
- ⭐⭐ NewAE / ChipWhisperer 
- ⭐⭐ Attify talks 
- ⭐⭐ ONEKEY research talks [Hardwear.io YouTube](https://www.youtube.com/@hardweario)[DEF CON YouTube](https://www.youtube.com/@DEFCONConference)[Black Hat YouTube](https://www.youtube.com/@BlackHatOfficialYT)[OpenSecurityTraining2](https://p.ost2.fyi/)[LiveOverflow](https://www.youtube.com/@LiveOverflow)
Search topics: 
Firmware extraction 
Binwalk 
Firmware emulation 
FirmAE 
Ghidra ARM 
MIPS reversing 
Embedded Linux security 
UEFI security 
Secure Boot 
Firmware update security 
Firmware fuzzing

---

## Section 11: Courses / Training <a name="section-11"></a>

Your uploaded materials already recommend Offensive IoT Exploitation, SEC556 and Applied Physical Attacks, all of which have substantial firmware crossover. 

#### Recommended: 

| Training | Focus |
| --- | --- |
| ⭐⭐⭐ Attify Offensive IoT Exploitation |
| Hardware + firmware + IoT |
| ⭐⭐⭐ OpenSecurityTraining2 |
| Architecture/reversing |
| ⭐⭐⭐ SANS SEC556 |
| IoT/product security |
| ⭐⭐ Hardwear.io Training |
| Embedded/hardware/firmware |
| ⭐⭐ pwn.college |
| Binary/reversing |
| ⭐⭐ Applied Physical Attacks |
| Firmware acquisition crossover |

[Attify Offensive IoT Exploitation](https://www.attify.com/training/offensive-iot-exploitation)[OpenSecurityTraining2](https://p.ost2.fyi/)[SANS SEC556](https://www.sans.org/cyber-security-courses/iot-penetration-testing/)[pwn.college](https://pwn.college/)

---

## Section 12: Certifications <a name="section-12"></a>

There is no universally dominant dedicated Firmware Security certification. 
Most useful adjacent paths: 

| Certification / Training | Relevance |
| --- | --- |
| GIAC GICSP |
| Embedded/industrial crossover |
| eCRE-style reversing credentials |
| Reverse engineering |
| OffSec OSED/OSEE |
| Binary exploitation |
| IoT/Hardware training certificates |
| Device security |
| SESIP evaluator/product knowledge |
| Product assurance |
| Common Criteria knowledge |
| Security evaluation |

For firmware specialists, a portfolio of firmware analyses, CVEs, emulation labs and reverse-engineering work is generally more useful than chasing a generic certification.

---

## Section 13: Books <a name="section-13"></a>

Your uploaded material already includes highly useful books for this domain. 

#### Essential 

- ⭐⭐⭐ The IoT Hacker's Handbook 
- ⭐⭐⭐ Practical IoT Hacking 
- ⭐⭐⭐ The Hardware Hacking Handbook 
- ⭐⭐⭐ Practical Hardware Pentesting 
- ⭐⭐⭐ The Ghidra Book 
- ⭐⭐⭐ Practical Reverse Engineering 
- ⭐⭐ Reversing: Secrets of Reverse Engineering 
- ⭐⭐ The IDA Pro Book 
- ⭐⭐ Practical Binary Analysis 
- ⭐⭐ Attacking Network Protocols Your reverse-engineering source set specifically includes Reversing, Mastering Reverse Engineering, The Ghidra Book, The IDA Pro Book and Practical Reverse Engineering.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

High-value sources: 

| Resource | Focus |
| --- | --- |
| ⭐⭐⭐ Binarly Research |
| UEFI/firmware supply chain |
| ⭐⭐⭐ Eclypsium Research |
| Firmware/platform security |
| ⭐⭐⭐ ONEKEY Research |
| IoT/embedded firmware |
| ⭐⭐⭐ EMBA Wiki/Blog |
| Firmware automation |
| ⭐⭐ NCC Group Research |
| Embedded/firmware |
| ⭐⭐ Quarkslab |
| Firmware/reversing |
| ⭐⭐ Trail of Bits |
| Low-level security |
| ⭐⭐ Interrupt/Memfault |
| Embedded systems |

[Binarly Research](https://www.binarly.io/research)[Eclypsium Research](https://eclypsium.com/research/)[ONEKEY Blog](https://www.onekey.com/resource/blog)[EMBA Wiki](https://github.com/e-m-b-a/emba/wiki)[NCC Group Research](https://www.nccgroup.com/research-blog/)[Quarkslab Blog](https://blog.quarkslab.com/)

---

## Section 15: Research Papers <a name="section-15"></a>

Follow: 
USENIX Security 
NDSS 
IEEE S&P 
ACM CCS 
ACSAC 
WOOT 
RAID 
Hardwear.io research 
[USENIX Security](https://www.usenix.org/conferences/byname/108)[NDSS Symposium](https://www.ndss-symposium.org/)[IEEE Security & Privacy](https://www.ieee-security.org/TC/SP-Index.html)[ACM CCS](https://www.sigsac.org/ccs.html)
Important firmware papers/projects 
Firmadyne — automated dynamic analysis of Linux embedded firmware. Its original study analyzed 23,035 firmware images and successfully extracted 9,486. ( [GitHub](https://github.com/firmadyne/firmadyne)) 
FirmAE — improved automated firmware emulation and reported a substantially higher emulation success rate on its evaluated dataset. ( [GitHub](https://github.com/pr0v3rbs/FirmAE)) 
RealworldFirmware accompanies the USENIX Security 2024 paper Unveiling IoT Security in Reality: A Firmware-Centric Journey. ( [GitHub](https://github.com/MCUSec/RealworldFirmware))

---

## Section 16: White Papers <a name="section-16"></a>

#### Recommended: 
NIST SP 800-193 
NIST IR 8259 Rev.1 
NIST IR 8259A 
ETSI EN 303 645 
UEFI Secure Boot material 
GlobalPlatform SESIP 
PSA Certified security model 
TCG DICE / TPM 
[NIST SP 800-193](https://csrc.nist.gov/pubs/sp/800/193/final)[NIST IoT Cybersecurity Program](https://www.nist.gov/itl/applied-cybersecurity/nist-cybersecurity-iot-program)[UEFI Forum](https://uefi.org/)[Trusted Computing Group Resources](https://trustedcomputinggroup.org/resources/)

---

## Section 17: Conference Material <a name="section-17"></a>

| Conference | Firmware Relevance |
| --- | --- |
| ⭐⭐⭐ Hardwear.io |
| Embedded/firmware/hardware |
| ⭐⭐⭐ Black Hat |
| UEFI, firmware, IoT |
| ⭐⭐⭐ DEF CON |
| Embedded/product security |
| ⭐⭐⭐ USENIX Security |
| Firmware research |
| ⭐⭐⭐ NDSS |
| Firmware/emulation research |
| ⭐⭐ TROOPERS |
| Product security |
| ⭐⭐ REcon |
| Reverse engineering |
| ⭐⭐ OffensiveCon |
| Low-level security |
| ⭐⭐ CCC |
| Embedded research |

[Hardwear.io](https://hardwear.io/)[Black Hat](https://www.blackhat.com/)[DEF CON](https://defcon.org/)[REcon](https://recon.cx/)

---

## Section 18: Mind Maps <a name="section-18"></a>

#### Recommended hierarchy: 
FIRMWARE SECURITY 

```
│
```

```
├── Firmware Acquisition
```

```
│   ├── Vendor download
```

```
│   ├── OTA capture
```

```
│   ├── Flash extraction
```

```
│   └── Debug interface
```

```
│
```

```
├── Initial Analysis
```

```
│   ├── file
```

```
│   ├── strings
```

```
│   ├── entropy
```

```
│   └── Binwalk
```

```
│
```

```
├── Filesystems
```

```
│   ├── SquashFS
```

```
│   ├── JFFS2
```

```
│   ├── UBIFS
```

```
│   ├── CramFS
```

```
│   └── initramfs
```

```
│
```

```
├── Static Analysis
```

```
│   ├── Credentials
```

```
│   ├── Keys
```

```
│   ├── Config
```

```
│   ├── Scripts
```

```
│   └── Web files
```

```
│
```

```
├── Components
```

```
│   ├── Libraries
```

```
│   ├── Versions
```

```
│   ├── SBOM
```

```
│   └── CVEs
```

```
│
```

```
├── Binary Analysis
```

```
│   ├── ARM
```

```
│   ├── MIPS
```

```
│   ├── RISC-V
```

```
│   ├── Ghidra
```

```
│   └── GDB
```

```
│
```

```
├── Emulation
```

```
│   ├── QEMU
```

```
│   ├── FirmAE
```

```
│   ├── Firmadyne
```

```
│   └── EMBA
```

```
│
```

```
├── Dynamic Analysis
```

```
│
```

```
├── Firmware Update
```

```
│   ├── Signing
```

```
│   ├── Verification
```

```
│   ├── Anti-rollback
```

```
│   └── Recovery
```

```
│
```

```
├── Secure Boot
```

```
│
```

```
├── UEFI / BIOS
```

```
│
```

```
├── Supply Chain
```

```
│   ├── SBOM
```

```
│   ├── Provenance
```

```
│   └── Third-party components
```

```
│
```

```
└── Compliance
```

---

## Section 19: Sample Reports <a name="section-19"></a>

#### Recommended report structure: 
Executive Summary 
Scope 
Product / Firmware Identification 
Firmware Acquisition Method 
Firmware Version / Hash 
Architecture 
Extraction Results 
Filesystem Analysis 
Secrets / Credentials 
Cryptographic Material 
Configuration Review 
Software Components 
SBOM 
CVE Analysis 
Binary Security 
Reverse Engineering 
Emulation 
Dynamic Testing 
Network Services 
Web/API Interfaces 
Secure Boot 
Firmware Update Mechanism 
Signature Verification 
Anti-Rollback 
Recovery 
Supply Chain 
Findings 
Evidence 
CWE / CVE / CVSS 
Standards Mapping 
Remediation 
Retest 
Conclusion 
Useful public-report sources: 
[Binarly Research & Advisories](https://www.binarly.io/research)[CERT/CC Vulnerability Notes](https://kb.cert.org/vuls/)[Public Pentesting Reports Repository](https://github.com/juliocesarfort/public-pentesting-reports)

---

## Section 20: Templates <a name="section-20"></a>

#### Recommended repository structure: 
/templates/firmware-security/ 

```
├── firmware-security-test-plan.md
```

```
├── firmware-acquisition.md
```

```
├── firmware-extraction-checklist.md
```

```
├── filesystem-analysis.md
```

```
├── secrets-analysis.md
```

```
├── binary-security-review.md
```

```
├── sbom-template.md
```

```
├── firmware-emulation.md
```

```
├── secure-boot-review.md
```

```
├── firmware-update-review.md
```

```
├── anti-rollback-testing.md
```

```
├── recovery-testing.md
```

```
├── evidence-template.md
```

```
├── firmware-pentest-report.md
```

```
└── compliance-matrix.md
```

#### Recommended test-case fields 
Test ID 
Firmware Version 
Firmware Hash 
Architecture 
Component 
Objective 
Precondition 
Tool 
Procedure 
Expected Result 
Actual Result 
Evidence 
CWE 
CVE 
CVSS 
Standard Mapping 
Severity 
Status

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

Primary sources: 
[CVE.org](https://www.cve.org/)[NIST NVD](https://nvd.nist.gov/)[CISA KEV](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)[MITRE CWE](https://cwe.mitre.org/)[Binarly Advisories](https://www.binarly.io/advisories)
Track especially: 
Hard-coded credentials 
Private keys in firmware 
Outdated libraries 
Command injection 
Memory corruption 
Authentication bypass 
Debug services 
Unsigned firmware 
Firmware downgrade 
Secure Boot bypass 
UEFI vulnerabilities 
Bootloader vulnerabilities 
Update-server compromise 
Supply-chain compromise 
Relevant CWE examples include: 
CWE-798  Hard-coded Credentials 
CWE-259  Hard-coded Password 
CWE-494  Download of Code Without Integrity Check 
CWE-347  Improper Verification of Cryptographic Signature 
CWE-327  Broken/Risky Crypto 
CWE-119  Memory Corruption family

---

## Section 22: GitHub Repositories <a name="section-22"></a>

This should be one of the strongest sections of your Firmware Security page. 

| Repository | Purpose |
| --- | --- |
| ⭐⭐⭐ EMBA |
| Full firmware analysis |
| ⭐⭐⭐ Binwalk |
| Extraction |
| ⭐⭐⭐ FACT Core |
| Firmware analysis/comparison |
| ⭐⭐⭐ FirmAE |
| Emulation/dynamic analysis |
| ⭐⭐⭐ Firmadyne |
| Embedded Linux emulation |
| ⭐⭐⭐ Ghidra |
| Reverse engineering |
| ⭐⭐⭐ QEMU |
| Emulation |
| ⭐⭐ unblob |
| Extraction |
| ⭐⭐ ubi_reader |
| UBI/UBIFS |
| ⭐⭐ Jefferson |
| JFFS2 |
| ⭐⭐ UEFITool |
| UEFI analysis |
| ⭐⭐ CHIPSEC |
| Platform/UEFI security |
| ⭐⭐ IoTVulBench |
| Firmware benchmark |
| ⭐⭐ RealworldFirmware |
| Research dataset |
| ⭐⭐ FirmWire |
| Baseband firmware |

[EMBA GitHub](https://github.com/e-m-b-a/emba)[Binwalk GitHub](https://github.com/ReFirmLabs/binwalk)[FACT Core GitHub](https://github.com/fkie-cad/fact_core)[FirmAE GitHub](https://github.com/pr0v3rbs/FirmAE)[Firmadyne GitHub](https://github.com/firmadyne/firmadyne)[Ghidra GitHub](https://github.com/NationalSecurityAgency/ghidra)[UEFITool GitHub](https://github.com/LongSoft/UEFITool)[IoTVulBench GitHub](https://github.com/a101e-lab/IoTVulBench)[FirmWire GitHub](https://github.com/FirmWire/FirmWire)
FirmWire is especially useful as a specialized example: it provides full-system analysis, fuzzing and debugging for supported smartphone baseband firmware. ( [GitHub](https://github.com/firmwire/firmwire))

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

Firmware analysis benefits greatly from curated firmware datasets. 

#### Recommended 

| Resource | Content |
| --- | --- |
| ⭐⭐⭐ IoTVulBench |
| Known vulnerable firmware |
| ⭐⭐⭐ RealworldFirmware |
| Research corpus |
| ⭐⭐ FirmAE sample images |
| Emulation targets |
| ⭐⭐ Firmadyne datasets |
| Router/embedded research |
| ⭐⭐ Vendor firmware portals |
| Real public firmware |

[IoTVulBench](https://github.com/a101e-lab/IoTVulBench)[RealworldFirmware](https://github.com/MCUSec/RealworldFirmware)[FirmAE](https://github.com/pr0v3rbs/FirmAE)
Suggested repository structure: 
datasets/ 

```
├── firmware-images/
```

```
│   ├── routers/
```

```
│   ├── cameras/
```

```
│   ├── gateways/
```

```
│   └── iot/
```

```
│
```

```
├── extracted-filesystems/
```

```
├── sbom/
```

```
├── binaries/
```

```
├── pcaps/
```

```
├── vulnerability-mapping/
```

```
└── hashes/
```

---

## Section 24: Communities / Forums <a name="section-24"></a>

#### Recommended: 
EMBA community 
Ghidra community 
Binwalk GitHub 
Hardwear.io 
Reverse Engineering Stack Exchange 
IoT Village 
OpenSecurityTraining 
r/ReverseEngineering 
r/embedded 
r/netsec 
[Reverse Engineering Stack Exchange](https://reverseengineering.stackexchange.com/)[Information Security Stack Exchange](https://security.stackexchange.com/)[IoT Village](https://www.iotvillage.org/)[Hardwear.io](https://hardwear.io/)

---

## Section 25: Vendors / Products <a name="section-25"></a>

| Area | Examples |
| --- | --- |
| Firmware analysis |
| ONEKEY, Finite State |
| UEFI/platform security |
| Binarly, Eclypsium |
| Static analysis |
| GrammaTech, Synopsys |
| SBOM/SCA |
| Syft, Black Duck, Snyk |
| Firmware updating |
| LVFS/fwupd |
| Product security |
| ONEKEY, Finite State, Binarly |
| Reverse engineering |
| Hex-Rays, Binary Ninja |

For your GitHub site, place open-source tools and official standards first, then commercial vendors as optional enterprise solutions.

---

## Section 26: Latest Developments <a name="section-26"></a>

This is one of the categories where your resource directory should be actively maintained. 
NIST IR 8259 Rev.1 — April 2026 
NIST published Revision 1 in April 2026. It updates manufacturer cybersecurity activities across the product lifecycle and broadens attention to product maintenance, support and end-of-life. ( [NIST Computer Security Resource Center](https://csrc.nist.gov/pubs/ir/8259/r1/final)) 
Binwalk v3 
Binwalk's current generation is v3, rewritten in Rust for speed and accuracy while maintaining firmware file/data identification, extraction and entropy analysis. ( [GitHub](https://github.com/refirmlabs/binwalk)) 
EMBA continues expanding 
EMBA's current tooling combines: 
Extraction 
Static analysis 
Dynamic emulation 
SBOM 
Vulnerability identification 
Web reporting 
( [GitHub](https://github.com/e-m-b-a/emba)) 
UEFI 
The current UEFI specifications page lists UEFI 2.11 as the current released specification. ( [uefi.org](https://uefi.org/specifications)) 
Major research themes to track 
Firmware SBOM 
VEX 
Firmware supply chain 
Secure update frameworks 
Reproducible firmware builds 
Firmware provenance 
Signed firmware 
Key rotation 
Remote attestation 
DICE 
Measured Boot 
UEFI security 
Bootkit detection 
Baseboard / BMC firmware security 
NVMe firmware security 
SSD firmware 
Network adapter firmware 
GPU firmware 
Baseband firmware 
Automotive ECU firmware 
PQC firmware signing 
AI-assisted firmware analysis 
Large-scale firmware emulation 
Firmware fuzzing

---

## Section 27: Learning Roadmap <a name="section-27"></a>

```
LEVEL 1 — Embedded Fundamentals
```
Linux 
Embedded Linux 
MCU / MPU 
ARM / MIPS / RISC-V 
Boot process 
Memory 

→ ↓ 
```
LEVEL 2 — Firmware Fundamentals
```
Firmware image 
Bootloader 
Kernel 
Root filesystem 
Device Tree 
Init system 

→ ↓ 
```
LEVEL 3 — File / Binary Inspection
```
file 
strings 
xxd 
hexdump 
entropy 

→ ↓ 
```
LEVEL 4 — Firmware Extraction
```
Binwalk 
SquashFS 
JFFS2 
UBIFS 
unblob 
Jefferson 
ubi_reader 

→ ↓ 
```
LEVEL 5 — Filesystem Analysis
```
/etc 
startup scripts 
services 
web files 
configuration 
permissions 

→ ↓ 
```
LEVEL 6 — Secrets
```
Passwords 
API keys 
SSH keys 
TLS keys 
Cloud credentials 
Tokens 

→ ↓ 
```
LEVEL 7 — Component Analysis
```
Libraries 
Versions 
SBOM 
CVE 
CWE 

→ ↓ 
```
LEVEL 8 — Binary Security
```
ELF 
NX 
PIE 
RELRO 
Canary 
FORTIFY 
checksec 

→ ↓ 
```
LEVEL 9 — Reverse Engineering
```
ARM 
MIPS 
Assembly 
Ghidra 
Radare2 
GDB 

→ ↓ 
```
LEVEL 10 — Firmware Emulation
```
QEMU 
Firmadyne 
FirmAE 
EMBA 

→ ↓ 
```
LEVEL 11 — Dynamic Analysis
```
Network services 
Web interfaces 
APIs 
Authentication 
Runtime behavior 

→ ↓ 
```
LEVEL 12 — Fuzzing
```
AFL++ 
libFuzzer 
boofuzz 
Protocol fuzzing 
Binary fuzzing 

→ ↓ 
```
LEVEL 13 — Boot Security
```
Boot ROM 
Bootloader 
Secure Boot 
Measured Boot 
Root of Trust 

→ ↓ 
```
LEVEL 14 — Firmware Update Security
```
Signing 
Verification 
TLS 
OTA 
Version checks 
Anti-rollback 

→ ↓ 
```
LEVEL 15 — Recovery
```
A/B partitions 
Recovery image 
Failed update 
Factory recovery 

→ ↓ 
```
LEVEL 16 — Platform Firmware
```
UEFI 
BIOS 
CHIPSEC 
UEFITool 
fwupd 

→ ↓ 
```
LEVEL 17 — Supply Chain
```
SBOM 
VEX 
Provenance 
Third-party components 
Reproducible builds 

→ ↓ 
```
LEVEL 18 — Standards
```
NIST SP 800-193 
NIST IR 8259 
ETSI EN 303 645 
EU CRA 
IEC 62443 
SESIP 

→ ↓ 
```
LEVEL 19 — Reporting
```
Hashes 
Evidence 
SBOM 
CVE/CWE/CVSS 
Standards mapping 
Remediation 
Retest 

- ⭐ Firmware Security — Top 20 Resources 
| Rank | Resource | Purpose |
| --- | --- | --- |
| 1 |
| OWASP Firmware Security Testing Methodology |
| Methodology |
| 2 |
| NIST SP 800-193 |
| Firmware resiliency |
| 3 |
| EMBA |
| Complete firmware analyzer |
| 4 |
| Binwalk |
| Extraction |
| 5 |
| Ghidra |
| Reverse engineering |
| 6 |
| FACT Core |
| Automated analysis |
| 7 |
| FirmAE |
| Emulation |
| 8 |
| QEMU |
| General emulation |
| 9 |
| Firmadyne |
| Linux firmware emulation |
| 10 |
| NIST IR 8259 Rev.1 |
| Product lifecycle |
| 11 |
| ETSI EN 303 645 |
| Secure-update requirements |
| 12 |
| UEFI Specifications |
| Platform firmware |
| 13 |
| CHIPSEC |
| UEFI/platform assessment |
| 14 |
| UEFITool |
| UEFI analysis |
| 15 |
| IoTVulBench |
| Vulnerable firmware dataset |
| 16 |
| RealworldFirmware |
| Research corpus |
| 17 |
| Syft / SBOM tooling |
| Component inventory |
| 18 |
| checksec |
| Binary hardening |
| 19 |
| Hardwear.io |
| Research/training |
| 20 |
| Attify Offensive IoT Exploitation |
| Structured training |

#### Recommended practical stack 
Embedded Linux → firmware architecture → file/strings/entropy → Binwalk/unblob → filesystem analysis → credentials/secrets → SBOM/CVE analysis → checksec → Ghidra → QEMU/FirmAE/EMBA → dynamic service testing → Secure Boot → firmware signing/update → anti-rollback/recovery → NIST/ETSI/CRA mapping → professional firmware-security report. 
For the repository architecture, I would make these subfolders under Firmware Security: 
firmware-security/ 

```
├── acquisition/
```

```
├── extraction/
```

```
├── filesystems/
```

```
├── static-analysis/
```

```
├── secrets/
```

```
├── sbom/
```

```
├── binary-analysis/
```

```
├── reverse-engineering/
```

```
├── emulation/
```

```
├── dynamic-analysis/
```

```
├── fuzzing/
```

```
├── secure-boot/
```

```
├── firmware-update/
```

```
├── anti-rollback/
```

```
├── recovery/
```

```
├── uefi-bios/
```

```
├── supply-chain/
```

```
├── standards/
```

```
├── labs/
```

```
├── reports/
```

```
└── datasets/
```
That separation will also prevent duplication when you later create the dedicated IoT Security, Reverse Engineering, Binary Exploitation, and Hardware & Embedded Security resource pages. 
Below are the next 10 cybersecurity domains in the same GitHub/website-ready structure. Because putting ten full-length directories at the same depth as the previous pages would become extremely large, I’ve kept all 27 resource categories for every domain, but made each category more compact. These can later be expanded individually. 
Your uploaded Offensive Resources are useful for several of these areas: they already contain IoT/hardware material, ICS/SCADA books and training, exploit-development resources, reverse-engineering material, telecom references, and malware-development resources. 

#### Legend: ⭐⭐⭐ Essential · ⭐⭐ Recommended · ⭐ Reference

---

<div align="center">
<sub>💾 Firmware Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>