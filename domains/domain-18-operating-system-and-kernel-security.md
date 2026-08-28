# 🖥️ Domain 18: Operating System & Kernel Security

> **Group:** Exploitation, RE, Malware & Systems  
> **Curated links:** 4  
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

- ⭐⭐⭐ [Linux Kernel Security Documentation](https://www.kernel.org/doc/html/latest/security/)⭐⭐⭐ [Linux Kernel Self-Protection](https://www.kernel.org/doc/html/latest/security/self-protection.html)⭐⭐⭐ Microsoft Windows Security documentation. Linux kernel security documentation currently includes LSMs, credentials, kernel keys, Landlock, IPE, TPM and kernel self-protection. ( [Kernel.org](https://www.kernel.org/doc/html/latest/security/))

---

## Section 02: Methodology <a name="section-02"></a>

Architecture → privilege model → syscall surface → kernel modules/drivers → IPC → memory → filesystem → hardening → vulnerabilities → logging.

---

## Section 03: Standards / Compliance <a name="section-03"></a>

CIS Benchmarks · DISA STIGs · NIST 800-53 · Common Criteria · Secure Boot/TPM.

---

## Section 04: Official Documentation <a name="section-04"></a>

Linux kernel docs · Microsoft Learn Windows security · Apple Platform Security.

---

## Section 05: Checklists <a name="section-05"></a>

Kernel version, patches, modules, syscall restrictions, SELinux/AppArmor, LSM, Secure Boot, driver security, kernel parameters, exploit mitigations.

---

## Section 06: Cheat Sheets <a name="section-06"></a>

sysctl · auditd · seccomp · capabilities · Windows mitigations.

---

## Section 07: Tools <a name="section-07"></a>

strace · ltrace · perf · bpftrace · eBPF · Sysinternals · WinDbg · GDB · Syzkaller · KASAN.

---

## Section 08: Labs / Practice <a name="section-08"></a>

pwn.college · kernelCTF · Linux Kernel Labs · HackSys Extreme Vulnerable Driver.

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

Driver IOCTLs, syscall validation, memory corruption, privilege boundaries, sandbox escape and hardening configuration.

---

## Section 10: YouTube / Video <a name="section-10"></a>

> Source combines sections 10–12: Training

OpenSecurityTraining2 · pwn.college · OSEE · advanced kernel exploitation courses.

---

## Section 11: Courses / Training <a name="section-11"></a>

> Source combines sections 10–12: Training

OpenSecurityTraining2 · pwn.college · OSEE · advanced kernel exploitation courses.

---

## Section 12: Certifications <a name="section-12"></a>

> Source combines sections 10–12: Training

OpenSecurityTraining2 · pwn.college · OSEE · advanced kernel exploitation courses.

---

## Section 13: Books <a name="section-13"></a>

Linux Kernel Development · Windows Internals · A Guide to Kernel Exploitation · The Linux Programming Interface.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

> Source combines sections 14–17: Research

Project Zero · Linux kernel security mailing lists · Microsoft MSRC · Black Hat · OffensiveCon · USENIX.

---

## Section 15: Research Papers <a name="section-15"></a>

> Source combines sections 14–17: Research

Project Zero · Linux kernel security mailing lists · Microsoft MSRC · Black Hat · OffensiveCon · USENIX.

---

## Section 16: White Papers <a name="section-16"></a>

> Source combines sections 14–17: Research

Project Zero · Linux kernel security mailing lists · Microsoft MSRC · Black Hat · OffensiveCon · USENIX.

---

## Section 17: Conference Material <a name="section-17"></a>

> Source combines sections 14–17: Research

Project Zero · Linux kernel security mailing lists · Microsoft MSRC · Black Hat · OffensiveCon · USENIX.

---

## Section 18: Mind Maps <a name="section-18"></a>

Userspace → syscalls → kernel → drivers → memory manager → filesystem → network stack → security subsystem.

---

## Section 19: Sample Reports <a name="section-19"></a>

> Source combines sections 19–23: Reports / Templates / CVEs / GitHub / Datasets

Syzkaller, kernelCTF, Project Zero reports, Linux CVEs, Windows driver CVEs.

---

## Section 20: Templates <a name="section-20"></a>

> Source combines sections 19–23: Reports / Templates / CVEs / GitHub / Datasets

Syzkaller, kernelCTF, Project Zero reports, Linux CVEs, Windows driver CVEs.

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

> Source combines sections 19–23: Reports / Templates / CVEs / GitHub / Datasets

Syzkaller, kernelCTF, Project Zero reports, Linux CVEs, Windows driver CVEs.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

> Source combines sections 19–23: Reports / Templates / CVEs / GitHub / Datasets

Syzkaller, kernelCTF, Project Zero reports, Linux CVEs, Windows driver CVEs.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

> Source combines sections 19–23: Reports / Templates / CVEs / GitHub / Datasets

Syzkaller, kernelCTF, Project Zero reports, Linux CVEs, Windows driver CVEs.

---

## Section 24: Communities / Forums <a name="section-24"></a>

> Source combines sections 24–25: Communities / Vendors

kernel.org · LKML · Microsoft MSRC · Project Zero.

---

## Section 25: Vendors / Products <a name="section-25"></a>

> Source combines sections 24–25: Communities / Vendors

kernel.org · LKML · Microsoft MSRC · Project Zero.

---

## Section 26: Latest Developments <a name="section-26"></a>

Modern defenses include CFI, shadow stacks, hardware-enforced stack protection, vulnerable-driver blocklists and memory-safe components. Microsoft describes kernel shadow stacks as protection against control-flow hijacking. ( [Microsoft Learn](https://learn.microsoft.com/en-us/windows-server/security/kernel-mode-hardware-stack-protection))

---

## Section 27: Learning Roadmap <a name="section-27"></a>

OS internals → C/assembly → processes/memory → syscalls → drivers → kernel debugging → mitigations → fuzzing → kernel vulnerability research.

---

<div align="center">
<sub>🖥️ Operating System & Kernel Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>