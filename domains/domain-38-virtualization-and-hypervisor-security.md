# 📦 Domain 38: Virtualization & Hypervisor Security

> **Group:** Cloud, Containers & Identity  
> **Curated links:** 3  
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

Cover: 
VMware ESXi · KVM/QEMU · Hyper-V · Xen · VirtualBox · nested virtualization · virtual TPM · confidential VMs. 

- ⭐⭐⭐ Microsoft Hyper-V Security ⭐⭐⭐ Red Hat KVM/libvirt security ⭐⭐⭐ VMware security configuration guidance [Microsoft Hyper-V Security Planning](https://learn.microsoft.com/en-us/windows-server/virtualization/hyper-v/plan/plan-hyper-v-security-in-windows-server)
Microsoft recommends securing the Hyper-V host, minimizing host attack surface and protecting VM configuration/data. ( [Microsoft Learn](https://learn.microsoft.com/en-us/windows-server/virtualization/hyper-v/plan/plan-hyper-v-security-in-windows-server))

---

## Section 02: Methodology <a name="section-02"></a>

Host → hypervisor → management plane → virtual networking → storage → VM images → device emulation → guest/host boundary → migration → snapshots → backup → confidential computing.

---

## Section 03: Standards / Compliance <a name="section-03"></a>

CIS VMware/virtualization benchmarks · NIST virtualization guidance · DISA STIGs · Common Criteria where applicable.

---

## Section 04: Official Documentation <a name="section-04"></a>

Microsoft Hyper-V · VMware vSphere Security · QEMU security · Xen Security Advisories · libvirt.

---

## Section 05: Checklists <a name="section-05"></a>

management interface · host hardening · MFA · Secure Boot · vTPM · VM isolation · virtual switches · snapshots · shared clipboard · passthrough · migration · images/templates · patching

---

## Section 06: Cheat Sheets <a name="section-06"></a>

virsh · qemu-img · ESXi CLI · PowerCLI · Hyper-V PowerShell.

---

## Section 07: Tools <a name="section-07"></a>

Prowler/host benchmarks · Lynis · CIS-CAT · CHIPSEC · QEMU fuzzing · libvirt tooling.

---

## Section 08: Labs / Practice <a name="section-08"></a>

Nested ESXi/KVM/Hyper-V lab · vulnerable QEMU builds · Xen test lab.

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

VM escape research only in isolated labs; production assessments should focus on configuration, isolation, management-plane and patch state.

---

## Section 10: YouTube / Video <a name="section-10"></a>

> Source combines sections 10–12: Videos / Training / Certs

VMware/Broadcom security · Microsoft Learn · Red Hat virtualization · OffensiveCon hypervisor talks.

---

## Section 11: Courses / Training <a name="section-11"></a>

> Source combines sections 10–12: Videos / Training / Certs

VMware/Broadcom security · Microsoft Learn · Red Hat virtualization · OffensiveCon hypervisor talks.

---

## Section 12: Certifications <a name="section-12"></a>

> Source combines sections 10–12: Videos / Training / Certs

VMware/Broadcom security · Microsoft Learn · Red Hat virtualization · OffensiveCon hypervisor talks.

---

## Section 13: Books <a name="section-13"></a>

virtualization-security references · QEMU/KVM architecture · Windows Internals.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

> Source combines sections 14–17: Research

Project Zero · Quarkslab · STAR Labs · Pwn2Own · Xen Security Advisories · QEMU security.

---

## Section 15: Research Papers <a name="section-15"></a>

> Source combines sections 14–17: Research

Project Zero · Quarkslab · STAR Labs · Pwn2Own · Xen Security Advisories · QEMU security.

---

## Section 16: White Papers <a name="section-16"></a>

> Source combines sections 14–17: Research

Project Zero · Quarkslab · STAR Labs · Pwn2Own · Xen Security Advisories · QEMU security.

---

## Section 17: Conference Material <a name="section-17"></a>

> Source combines sections 14–17: Research

Project Zero · Quarkslab · STAR Labs · Pwn2Own · Xen Security Advisories · QEMU security.

---

## Section 18: Mind Maps <a name="section-18"></a>

Hardware → hypervisor → host → VM → virtual devices → virtual network → management → storage → migration.

---

## Section 19: Sample Reports <a name="section-19"></a>

> Source combines sections 19–20: Reports / Templates

Hypervisor hardening review · virtual network assessment · VM-template security review.

---

## Section 20: Templates <a name="section-20"></a>

> Source combines sections 19–20: Reports / Templates

Hypervisor hardening review · virtual network assessment · VM-template security review.

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

VENOM · VMware escapes · QEMU device-emulation CVEs · Xen hypervisor advisories.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

QEMU · Xen · libvirt · KVM tooling · CHIPSEC.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

VM images · QEMU fuzz corpora · hypervisor CVE datasets.

---

## Section 24: Communities / Forums <a name="section-24"></a>

> Source combines sections 24–25: Communities / Vendors

QEMU · Xen Project · Microsoft · VMware/Broadcom · Red Hat.

---

## Section 25: Vendors / Products <a name="section-25"></a>

> Source combines sections 24–25: Communities / Vendors

QEMU · Xen Project · Microsoft · VMware/Broadcom · Red Hat.

---

## Section 26: Latest Developments <a name="section-26"></a>

Key themes: 
Confidential VMs · AMD SEV-SNP · Intel TDX · Arm CCA · vTPM · nested virtualization · GPU passthrough · AI workload isolation 
Hyper-V currently supports security constructs including shielded VMs, Secure Boot and virtual TPM 2.0. ( [Microsoft Learn](https://learn.microsoft.com/en-us/windows-server/virtualization/hyper-v/overview))

---

## Section 27: Learning Roadmap <a name="section-27"></a>

CPU virtualization → KVM/QEMU → Hyper-V/ESXi → virtual networking/storage → management hardening → escape research → confidential computing.

---

<div align="center">
<sub>📦 Virtualization & Hypervisor Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>