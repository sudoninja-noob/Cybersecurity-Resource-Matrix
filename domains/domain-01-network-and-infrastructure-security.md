# 🌐 Domain 01: Network & Infrastructure Security

> **Group:** Network, Web & Application  
> **Curated links:** 181  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

This version is designed for direct reuse in a GitHub README / cybersecurity resource website. I cross-checked your uploaded Offensive Resources collection as a supplemental source. Its Infrastructure section already groups resources into books, courses and labs—including OSCP/OSEP/eCPPT, SEC560/SEC660, HTB, VulnHub and Proving Grounds—so I retained the strongest items and expanded them with current official resources. 
Legend: ⭐⭐⭐ Essential · ⭐⭐ Recommended · ⭐ Useful Type: Official · Open Source · Free · Paid · Lab · Research

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

| Resource | Type | Use |
| --- | --- | --- |
| Cisco Networking Basics [Cisco Networking](https://www.cisco.com/c/en/us/solutions/enterprise-networks/what-is-computer-networking.html) |
| Official / Free |
| Networking architecture and fundamentals |
| Cloudflare Learning Center – Networking [Cloudflare Learning Center](https://www.cloudflare.com/learning/network-layer/what-is-a-computer-network/) |
| Free |
| TCP/IP, DNS, routing, DDoS, TLS concepts |
| Practical Networking [Practical Networking](https://www.practicalnetworking.net/) |
| Free |
| Excellent TCP/IP, subnetting, ARP, VLAN and routing explanations |
| Nmap Network Scanning [Official Nmap Book](https://nmap.org/book/) |
| Official / Free |
| Network discovery and enumeration |
| Wireshark User Guide [Wireshark User Guide](https://www.wireshark.org/docs/wsug_html/) |
| Official / Free |
| Packet capture and protocol analysis |
| Beej's Guide to Network Programming [Beej Networking Guide](https://beej.us/guide/bgnet/) |
| Free |
| Socket/network-programming fundamentals |

#### Core subjects 
OSI / TCP-IP 
IPv4 / IPv6 
TCP / UDP / ICMP 
ARP / NDP 
DNS / DHCP 
HTTP / HTTPS 
SSH 
FTP / TFTP 
SMTP 
SNMP 
SMB 
LDAP 
Kerberos 
Routing 
Switching 
VLAN 
VPN 
Firewalls 
IDS / IPS 
NAT 
Proxy 
Zero Trust 
Network Segmentation 

> Priority: ⭐⭐⭐

---

## Section 02: Methodology <a name="section-02"></a>

#### Primary methodologies 

| Resource | Why use it |
| --- | --- |
| NIST SP 800-115 [Technical Guide to Information Security Testing and Assessment](https://csrc.nist.gov/pubs/sp/800/115/final) |
| Authoritative security-testing methodology |
| PTES [Penetration Testing Execution Standard](http://www.pentest-standard.org/) |
| Practical pentest lifecycle |
| OSSTMM [Open Source Security Testing Methodology Manual](https://www.isecom.org/OSSTMM.3.pdf) |
| Formal operational security-testing methodology |
| MITRE ATT&CK Enterprise [MITRE ATT&CK](https://attack.mitre.org/) |
| Map network attack techniques and adversary behavior |
| NIST Cybersecurity Framework 2.0 [NIST CSF 2.0](https://www.nist.gov/cyberframework) |
| Risk and control framework |

NIST SP 800-115 specifically covers planning assessments, executing technical tests, analyzing findings and producing mitigation recommendations. ( [NIST](https://www.nist.gov/publications/technical-guide-information-security-testing-and-assessment)) 

#### Recommended infrastructure pentest workflow 
Authorization / Scope 

→ ↓ Asset Discovery 

→ ↓ Passive Reconnaissance 

→ ↓ Host Discovery 

→ ↓ Port Scanning 

→ ↓ Service Enumeration 

→ ↓ OS / Technology Fingerprinting 

→ ↓ Vulnerability Identification 

→ ↓ Configuration Assessment 

→ ↓ Authentication Testing 

→ ↓ Controlled Exploitation 

→ ↓ Privilege Escalation 

→ ↓ Network Segmentation Testing 

→ ↓ Lateral Movement Testing 

→ ↓ Protocol Security Analysis 

→ ↓ Firewall / ACL Validation 

→ ↓ Evidence Collection 

→ ↓ Risk Rating 

→ ↓ Remediation 

→ ↓ Retest 

> Priority: ⭐⭐⭐

---

## Section 03: Standards / Compliance <a name="section-03"></a>

| Standard / Framework | Coverage |
| --- | --- |
| NIST CSF 2.0 [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework) |
| Enterprise cybersecurity framework |
| NIST SP 800-115 [Security Testing Guide](https://csrc.nist.gov/pubs/sp/800/115/final) |
| Security assessment |
| NIST SP 800-41 Rev.1 [Firewall Guidelines](https://csrc.nist.gov/pubs/sp/800/41/r1/final) |
| Firewalls and firewall policy |
| NIST SP 800-207 [Zero Trust Architecture](https://csrc.nist.gov/pubs/sp/800/207/final) |
| Zero Trust network architecture |
| NIST SP 800-53 Rev.5 [Security and Privacy Controls](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final) |
| Enterprise security controls |
| CIS Controls v8.1 [CIS Controls](https://www.cisecurity.org/controls/v8-1) |
| Prioritized security safeguards |
| CIS Benchmarks [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks) |
| Cisco, Juniper, Fortinet, Palo Alto, pfSense and OS hardening |
| PCI DSS [PCI Security Standards](https://www.pcisecuritystandards.org/standards/pci-dss/) |
| Network controls protecting payment environments |
| ISO/IEC 27001 [ISO 27001](https://www.iso.org/isoiec-27001-information-security.html) |
| ISMS |
| ISO/IEC 27002 [ISO 27002](https://www.iso.org/standard/75652.html) |
| Security controls |
| DISA STIGs [DoD Cyber Exchange STIGs](https://public.cyber.mil/stigs/) |
| Secure device/server configurations |

CIS currently provides security benchmarks covering network-device families including Cisco, Fortinet, Juniper, Palo Alto, pfSense, Sophos, Check Point and F5. ( [CIS](https://www.cisecurity.org/cis-benchmarks)) 

> Priority: ⭐⭐⭐

---

## Section 04: Official Documentation <a name="section-04"></a>

| Resource | Coverage |
| --- | --- |
| Nmap Documentation [Nmap Documentation](https://nmap.org/docs.html) |
| Discovery and scanning |
| Wireshark Documentation [Wireshark Docs](https://www.wireshark.org/docs/) |
| Packet analysis |
| Cisco Security Documentation [Cisco Security Docs](https://www.cisco.com/c/en/us/support/security/index.html) |
| Cisco security |
| Juniper Security Docs [Juniper Documentation](https://www.juniper.net/documentation/) |
| Junos/network security |
| Palo Alto Documentation [PAN Documentation](https://docs.paloaltonetworks.com/) |
| NGFW |
| Fortinet Documentation [Fortinet Docs](https://docs.fortinet.com/) |
| FortiGate/security |
| Microsoft Network Security [Microsoft Security Documentation](https://learn.microsoft.com/security/) |
| Windows infrastructure |
| CISA Cybersecurity Guidance [CISA Cybersecurity Best Practices](https://www.cisa.gov/topics/cybersecurity-best-practices) |
| Government guidance |

---

## Section 05: Checklists <a name="section-05"></a>

| Checklist | Link |
| --- | --- |
| NIST SP 800-115 Assessment Guidance |
| [NIST Assessment Guide](https://csrc.nist.gov/pubs/sp/800/115/final) |
| CIS Controls v8.1 |
| [CIS Controls](https://www.cisecurity.org/controls/v8-1) |
| CIS Network Device Benchmarks |
| [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks) |
| HackTricks Network Services Pentesting |
| [HackTricks Network Services](https://book.hacktricks.wiki/en/network-services-pentesting/index.html) |
| Red Team Notes |
| [ired.team](https://www.ired.team/) |

Your own network checklist should eventually include: 
Asset inventory 
Network diagram 
Live hosts 
TCP ports 
UDP ports 
Services 
Versions 
Default credentials 
Weak authentication 
TLS configuration 
SNMP 
SMB 
SSH 
FTP/TFTP 
DNS 
DHCP 
NTP 
Routing protocols 
VLAN segmentation 
ACLs 
Firewall rules 
VPN 
IDS/IPS 
Management interfaces 
Logging 
Unused services 
IPv6 
Lateral movement 
Patch status 
Configuration backup

---

## Section 06: Cheat Sheets <a name="section-06"></a>

| Resource | Coverage |
| --- | --- |
| Nmap Reference Guide [Nmap Reference](https://nmap.org/book/man.html) |
| Nmap commands |
| Wireshark Display Filters [Wireshark Display Filters](https://www.wireshark.org/docs/man-pages/wireshark-filter.html) |
| Packet filters |
| PacketLife Cheat Sheets [PacketLife Cheat Sheets](https://packetlife.net/library/cheat-sheets/) |
| Cisco, TCP/IP, protocols |
| SANS Cheat Sheets [SANS Cybersecurity Cheat Sheets](https://www.sans.org/posters) |
| Networking/security |
| HackTricks [HackTricks](https://book.hacktricks.wiki/) |
| Enumeration reference |
| GTFOBins [GTFOBins](https://gtfobins.github.io/) |
| Unix privilege/security reference |

---

## Section 07: Tools <a name="section-07"></a>

Discovery / scanning / enumeration 

| Tool | Purpose |
| --- | --- |
| ⭐⭐⭐ Nmap [Nmap](https://nmap.org/) |
| Host/service discovery |
| ⭐⭐⭐ Wireshark [Wireshark](https://www.wireshark.org/) |
| Packet analysis |
| ⭐⭐⭐ tcpdump [tcpdump](https://www.tcpdump.org/) |
| CLI packet capture |
| ⭐⭐ Masscan [Masscan GitHub](https://github.com/robertdavidgraham/masscan) |
| High-speed port discovery |
| ⭐⭐ Naabu [Naabu GitHub](https://github.com/projectdiscovery/naabu) |
| Fast port scanner |
| ⭐⭐ RustScan [RustScan GitHub](https://github.com/bee-san/RustScan) |
| Fast scanner + Nmap integration |

Vulnerability assessment 

| Tool | Purpose |
| --- | --- |
| ⭐⭐⭐ Nuclei [Nuclei GitHub](https://github.com/projectdiscovery/nuclei) |
| Template-driven vulnerability scanning |
| ⭐⭐⭐ OpenVAS / Greenbone [OpenVAS Community Edition](https://community.greenbone.net/getting-started/) |
| Vulnerability management |
| ⭐⭐⭐ Nessus [Tenable Nessus](https://www.tenable.com/products/nessus) |
| Commercial vulnerability scanning |
| ⭐⭐ Metasploit Framework [Metasploit](https://www.metasploit.com/) |
| Controlled vulnerability validation |

Network / protocol analysis 

| Tool | Purpose |
| --- | --- |
| Scapy [Scapy](https://scapy.net/) |
| Packet crafting |
| Impacket [Impacket GitHub](https://github.com/fortra/impacket) |
| SMB/MSRPC/Kerberos/network protocols |
| Bettercap [Bettercap](https://www.bettercap.org/) |
| Network security testing |
| Zeek [Zeek](https://zeek.org/) |
| Network security monitoring |
| Suricata [Suricata](https://suricata.io/) |
| IDS/IPS/network analysis |

---

## Section 08: Labs / Practice <a name="section-08"></a>

Your uploaded resource set already recommends HTB, VulnHub, Proving Grounds and TryHackMe for Infrastructure practice. 

| Lab | Level |
| --- | --- |
| ⭐⭐⭐ Hack The Box [Hack The Box](https://www.hackthebox.com/) |
| Beginner → Advanced |
| ⭐⭐⭐ HTB Academy Penetration Tester [HTB Penetration Tester Path](https://academy.hackthebox.com/path/preview/penetration-tester) |
| Structured |
| ⭐⭐⭐ OffSec Proving Grounds [Proving Grounds](https://www.offsec.com/labs/individual/) |
| Intermediate → Advanced |
| ⭐⭐⭐ TryHackMe Network Security [THM Network Security](https://tryhackme.com/module/network-security) |
| Beginner |
| ⭐⭐ VulnHub [VulnHub](https://www.vulnhub.com/) |
| Offline VM labs |
| ⭐⭐ Metasploitable 2 [Metasploitable Documentation](https://docs.rapid7.com/metasploit/metasploitable-2/) |
| Vulnerable network host |
| ⭐⭐ OverTheWire Bandit [OverTheWire](https://overthewire.org/wargames/bandit/) |
| Linux/network foundations |

HTB's current Penetration Tester path covers the engagement lifecycle from reconnaissance and enumeration through exploitation, documentation and reporting. ( [HTB Academy](https://academy.hackthebox.com/path/preview/penetration-tester))

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

For authorized environments: 

| Resource | Usage |
| --- | --- |
| SecLists [SecLists GitHub](https://github.com/danielmiessler/SecLists) |
| Enumeration dictionaries |
| PayloadsAllTheThings [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) |
| Security-testing references |
| Metasploit Payload Documentation [Metasploit Documentation](https://docs.metasploit.com/) |
| Lab payload framework |
| Nuclei Templates [Nuclei Templates](https://github.com/projectdiscovery/nuclei-templates) |
| Reusable vulnerability test definitions |
| FuzzDB [FuzzDB](https://github.com/fuzzdb-project/fuzzdb) |
| Fuzzing/test input corpus |

---

## Section 10: YouTube / Video <a name="section-10"></a>

| Channel | Why follow |
| --- | --- |
| David Bombal [David Bombal YouTube](https://www.youtube.com/@davidbombal) |
| Networking, packet analysis, cybersecurity |
| Chris Greer [Chris Greer YouTube](https://www.youtube.com/@ChrisGreer) |
| Wireshark/packet analysis |
| John Hammond [John Hammond YouTube](https://www.youtube.com/@_JohnHammond) |
| Security labs |
| IppSec [IppSec YouTube](https://www.youtube.com/@ippsec) |
| HTB methodology |
| Black Hat [Black Hat YouTube](https://www.youtube.com/@BlackHatOfficialYT) |
| Advanced security talks |
| DEF CON [DEF CON YouTube](https://www.youtube.com/@DEFCONConference) |
| Security research |
| SANS [SANS YouTube](https://www.youtube.com/@SANSInstitute) |
| Enterprise security |

---

## Section 11: Courses / Training <a name="section-11"></a>

Your original resource map includes OSCP, OSEP, eCPPT, eCPTX, SEC560 and SEC660 as Infrastructure training resources. 

| Course | Level |
| --- | --- |
| ⭐⭐⭐ OffSec PEN-200 [PEN-200 / OSCP](https://www.offsec.com/courses/pen-200/) |
| Intermediate |
| ⭐⭐⭐ OffSec PEN-300 [PEN-300 / OSEP](https://www.offsec.com/courses/pen-300/) |
| Advanced |
| ⭐⭐⭐ SANS SEC560 [Enterprise Penetration Testing](https://www.sans.org/cyber-security-courses/enterprise-penetration-testing/) |
| Intermediate |
| ⭐⭐⭐ HTB Penetration Tester Path [HTB Academy](https://academy.hackthebox.com/path/preview/penetration-tester) |
| Hands-on |
| ⭐⭐ INE Penetration Testing Professional [INE Security](https://security.ine.com/) |
| Intermediate |
| ⭐⭐ TCM Practical Ethical Hacking [TCM Academy](https://academy.tcm-sec.com/) |
| Beginner → Intermediate |
| ⭐⭐ TryHackMe Network Security [THM Network & System Security](https://tryhackme.com/module/network-and-system-security) |
| Beginner |

---

## Section 12: Certifications <a name="section-12"></a>

| Certification | Focus |
| --- | --- |
| ⭐⭐⭐ OSCP [OffSec OSCP](https://www.offsec.com/courses/pen-200/) |
| Practical penetration testing |
| ⭐⭐⭐ OSEP [OffSec OSEP](https://www.offsec.com/courses/pen-300/) |
| Advanced enterprise attacks |
| ⭐⭐⭐ GPEN [GIAC GPEN](https://www.giac.org/certifications/penetration-tester-gpen?trk=public_profile_certification-title) |
| Professional penetration testing |
| ⭐⭐ eCPPT [INE eCPPT](https://security.ine.com/certifications/ecppt-certification/) |
| Practical pentesting |
| ⭐⭐ PNPT [TCM PNPT](https://certifications.tcm-sec.com/pnpt/) |
| Network/enterprise pentesting |
| ⭐⭐ HTB CPTS [HTB CPTS](https://academy.hackthebox.com/preview/certifications/htb-certified-penetration-testing-specialist) |
| Practical infrastructure testing |

GIAC describes GPEN as validating reconnaissance, exploitation and process-oriented penetration-testing skills. ( [GIAC Certifications](https://www.giac.org/certifications/penetration-tester-gpen?trk=public_profile_certification-title))

---

## Section 13: Books <a name="section-13"></a>

Several of these were also present in your uploaded Infrastructure resource map. 

| Book | Focus |
| --- | --- |
| ⭐⭐⭐ Nmap Network Scanning [Official Nmap Book](https://nmap.org/book/) |
| Network discovery |
| ⭐⭐⭐ The Art of Network Penetration Testing [Manning Book](https://www.manning.com/books/the-art-of-network-penetration-testing) |
| Network pentesting |
| ⭐⭐⭐ Penetration Testing: A Hands-On Introduction to Hacking [No Starch Press](https://nostarch.com/pentesting) |
| Pentest foundations |
| ⭐⭐ The Hacker Playbook 3 [Hacker Playbook](https://securepla.net/hacker-playbook/) |
| Red-team methodology |
| ⭐⭐ RTFM: Red Team Field Manual [No Starch / Author information](https://www.amazon.com/dp/1494295504) |
| Command reference |
| ⭐⭐ Practical Packet Analysis [No Starch Press](https://nostarch.com/packetanalysis3) |
| Wireshark/network analysis |
| ⭐⭐ Attacking Network Protocols [No Starch Press](https://nostarch.com/networkprotocols) |
| Network protocol security |

---

## Section 14: Blogs / Articles <a name="section-14"></a>

| Resource | Specialty |
| --- | --- |
| ⭐⭐⭐ HackTricks [HackTricks](https://book.hacktricks.wiki/) |
| Pentesting techniques |
| ⭐⭐⭐ ProjectDiscovery Blog [ProjectDiscovery Blog](https://projectdiscovery.io/blog) |
| Recon/scanning |
| ⭐⭐ Cisco Talos [Cisco Talos Blog](https://blog.talosintelligence.com/) |
| Network threats |
| ⭐⭐ Cloudflare Blog [Cloudflare Blog](https://blog.cloudflare.com/) |
| Internet/DDoS/network security |
| ⭐⭐ SANS Internet Storm Center [ISC](https://isc.sans.edu/) |
| Network threat monitoring |
| ⭐⭐ Palo Alto Unit 42 [Unit 42 Research](https://unit42.paloaltonetworks.com/) |
| Threat research |
| ⭐⭐ Mandiant Blog [Google Cloud Threat Intelligence](https://cloud.google.com/blog/topics/threat-intelligence) |
| Incident/adversary research |

---

## Section 15: Research Papers <a name="section-15"></a>

| Source | Resources |
| --- | --- |
| USENIX Security [USENIX Security Symposium](https://www.usenix.org/conferences/byname/108) |
| Peer-reviewed security research |
| IEEE Security & Privacy [IEEE S&P](https://www.ieee-security.org/TC/SP-Index.html) |
| Security research |
| NDSS Symposium [NDSS Papers](https://www.ndss-symposium.org/ndss-paper/) |
| Network/distributed security |
| ACM CCS [ACM CCS](https://www.sigsac.org/ccs.html) |
| Computer/network security |
| Google Scholar [Network Security Research](https://scholar.google.com/scholar?q=network+security+penetration+testing) |
| Academic search |
| arXiv Cryptography & Security [arXiv Security](https://arxiv.org/list/cs.CR/recent) |
| Current research |

---

## Section 16: White Papers <a name="section-16"></a>

| Resource | Focus |
| --- | --- |
| NIST SP 800-115 [NIST SP 800-115](https://csrc.nist.gov/pubs/sp/800/115/final) |
| Assessment |
| NIST SP 800-207 [Zero Trust Architecture](https://csrc.nist.gov/pubs/sp/800/207/final) |
| Modern network architecture |
| NIST SP 800-41 Rev.1 [Firewall Guidelines](https://csrc.nist.gov/pubs/sp/800/41/r1/final) |
| Firewall policy |
| CIS Controls v8.1 [CIS Controls](https://www.cisecurity.org/controls/v8-1) |
| Cyber defense |
| NSA Cybersecurity Publications [NSA Cybersecurity Guidance](https://www.nsa.gov/Press-Room/Cybersecurity-Advisories-Guidance/) |
| Network/device hardening |
| CISA Cyber Guidance [CISA Resources](https://www.cisa.gov/resources-tools) |
| Infrastructure defense |

---

## Section 17: Conference Material <a name="section-17"></a>

| Conference | Why useful |
| --- | --- |
| ⭐⭐⭐ Black Hat [Black Hat](https://www.blackhat.com/) |
| Network exploitation/research |
| ⭐⭐⭐ DEF CON [DEF CON](https://defcon.org/) |
| Offensive research |
| ⭐⭐⭐ USENIX Security [USENIX Security](https://www.usenix.org/conference/usenixsecurity) |
| Academic/industry |
| ⭐⭐⭐ NDSS [NDSS Symposium](https://www.ndss-symposium.org/) |
| Network/distributed systems |
| ⭐⭐ TROOPERS [TROOPERS](https://troopers.de/) |
| Infrastructure security |
| ⭐⭐ BSides [Security BSides](https://bsides.org/) |
| Community research |
| ⭐⭐ RSA Conference [RSAC](https://www.rsaconference.com/) |
| Enterprise security |

---

## Section 18: Mind Maps <a name="section-18"></a>

Your uploaded Offensive Resources V3 is useful here because it visually organizes Infrastructure into Books, Courses and Labs before branching into other offensive-security domains. 
For your website, I recommend this hierarchy: 
NETWORK & INFRASTRUCTURE SECURITY 

```
│
```

```
├── Networking Fundamentals
```

```
│   ├── TCP/IP
```

```
│   ├── IPv4/IPv6
```

```
│   ├── Routing
```

```
│   ├── Switching
```

```
│   └── VLAN
```

```
│
```

```
├── Discovery
```

```
│   ├── Passive Recon
```

```
│   ├── Host Discovery
```

```
│   └── Port Scanning
```

```
│
```

```
├── Enumeration
```

```
│   ├── DNS
```

```
│   ├── SMB
```

```
│   ├── SNMP
```

```
│   ├── LDAP
```

```
│   ├── SSH
```

```
│   └── Network Services
```

```
│
```

```
├── Vulnerability Assessment
```

```
│
```

```
├── Protocol Security
```

```
│
```

```
├── Segmentation
```

```
│
```

```
├── Firewall / ACL
```

```
│
```

```
├── VPN
```

```
│
```

```
├── Network Authentication
```

```
│
```

```
├── Controlled Exploitation
```

```
│
```

```
├── Detection
```

```
│   ├── IDS
```

```
│   ├── IPS
```

```
│   ├── Zeek
```

```
│   └── Suricata
```

```
│
```

```
└── Standards
```

```
    ├── NIST
```

```
    ├── CIS
```

```
    ├── ISO
```

```
    └── PCI DSS
```

---

## Section 19: Sample Reports <a name="section-19"></a>

| Resource | Use |
| --- | --- |
| OffSec Reporting Guidance [OffSec Reporting](https://help.offsec.com/hc/en-us/categories/360002666252-PEN-200-FAQ) |
| Pentest reporting concepts |
| TCM Security Sample Report [TCM Security Resources](https://tcm-sec.com/) |
| Professional pentest style |
| Pentest Reports [Public Pentest Reports GitHub](https://github.com/juliocesarfort/public-pentesting-reports) |
| Public report examples |
| CISA Cybersecurity Assessments [CISA Assessments](https://www.cisa.gov/resources-tools/services/cybersecurity-assessments) |
| Assessment reference |

#### Recommended report structure: 
Executive Summary 
Scope 
Rules of Engagement 
Network Architecture 
Methodology 
Attack Surface 
Host Discovery 
Port & Service Enumeration 
Vulnerability Assessment 
Configuration Assessment 
Segmentation Testing 
Findings 
Risk Rating 
Evidence 
Remediation 
Compliance Mapping 
Retest 
Conclusion

---

## Section 20: Templates <a name="section-20"></a>

For your own repository: 
/templates/network-security/ 

```
│
```

```
├── network-security-test-plan.md
```

```
├── network-pentest-checklist.md
```

```
├── network-test-cases.md
```

```
├── firewall-review-checklist.md
```

```
├── vlan-segmentation-test.md
```

```
├── router-security-checklist.md
```

```
├── switch-security-checklist.md
```

```
├── vpn-security-checklist.md
```

```
├── evidence-template.md
```

```
├── vulnerability-report.md
```

```
└── compliance-matrix.md
```

#### Recommended test-case fields: 
Test ID 
Test Name 
Asset 
IP Address 
Protocol 
Port 
Objective 
Precondition 
Tool 
Procedure 
Expected Result 
Actual Result 
Evidence 
Severity 
CVE 
CWE 
CVSS 
Standard Mapping 
Status

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

| Database | Purpose |
| --- | --- |
| ⭐⭐⭐ CVE.org [CVE Database](https://www.cve.org/) |
| CVE records |
| ⭐⭐⭐ NIST NVD [NVD](https://nvd.nist.gov/) |
| Vulnerability metadata |
| ⭐⭐⭐ CISA KEV [Known Exploited Vulnerabilities](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) |
| Exploited vulnerabilities |
| ⭐⭐⭐ MITRE CWE [CWE](https://cwe.mitre.org/) |
| Weakness classification |
| ⭐⭐ Exploit Database [Exploit-DB](https://www.exploit-db.com/) |
| Historical public exploit research |
| ⭐⭐ Packet Storm [Packet Storm Security](https://packetstormsecurity.com/) |
| Advisories/research |

For infrastructure, particularly track vulnerabilities in: 
Routers 
Switches 
VPN gateways 
Firewalls 
Load balancers 
DNS servers 
SSH servers 
SMB 
SNMP 
Remote management systems 
Network appliances

---

## Section 22: GitHub Repositories <a name="section-22"></a>

This should be a major section on your website. 

| Repository | Purpose |
| --- | --- |
| ⭐⭐⭐ Nmap [Nmap GitHub](https://github.com/nmap/nmap) |
| Network scanning |
| ⭐⭐⭐ Nuclei [ProjectDiscovery Nuclei](https://github.com/projectdiscovery/nuclei) |
| Vulnerability scanning |
| ⭐⭐⭐ Nuclei Templates [Nuclei Templates](https://github.com/projectdiscovery/nuclei-templates) |
| Security test templates |
| ⭐⭐⭐ Impacket [Fortra Impacket](https://github.com/fortra/impacket) |
| Network protocol toolkit |
| ⭐⭐ Masscan [Masscan](https://github.com/robertdavidgraham/masscan) |
| High-speed scanning |
| ⭐⭐ Naabu [Naabu](https://github.com/projectdiscovery/naabu) |
| Port discovery |
| ⭐⭐ RustScan [RustScan](https://github.com/bee-san/RustScan) |
| Fast scanning |
| ⭐⭐ SecLists [SecLists](https://github.com/danielmiessler/SecLists) |
| Security wordlists |
| ⭐⭐ Scapy [Scapy GitHub](https://github.com/secdev/scapy) |
| Packet manipulation |
| ⭐⭐ Zeek [Zeek GitHub](https://github.com/zeek/zeek) |
| Network monitoring |
| ⭐⭐ Suricata [Suricata GitHub](https://github.com/OISF/suricata) |
| IDS/IPS |

ProjectDiscovery's current toolkit includes Nuclei, Naabu, Subfinder, httpx and related assessment utilities. ( [GitHub](https://github.com/projectdiscovery))

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

| Resource | Content |
| --- | --- |
| ⭐⭐⭐ Wireshark Sample Captures [Wireshark SampleCaptures Wiki](https://wiki.wireshark.org/SampleCaptures) |
| Protocol PCAPs |
| ⭐⭐⭐ Malware Traffic Analysis [Malware Traffic Analysis](https://www.malware-traffic-analysis.net/) |
| Malicious traffic PCAP exercises |
| ⭐⭐ NETRESEC PCAP Files [NETRESEC PCAP Resources](https://www.netresec.com/?page=PcapFiles) |
| Network captures |
| ⭐⭐ Stratosphere IPS Dataset [Stratosphere Dataset](https://www.stratosphereips.org/datasets-overview) |
| Malicious network datasets |
| ⭐⭐ CIC Datasets [Canadian Institute for Cybersecurity Datasets](https://www.unb.ca/cic/datasets/index.html) |
| IDS/network datasets |

Excellent for: 
Wireshark practice 
IDS testing 
Traffic analysis 
Threat hunting 
Protocol learning 
Detection-rule development

---

## Section 24: Communities / Forums <a name="section-24"></a>

| Community | Focus |
| --- | --- |
| Network Engineering Stack Exchange [Network Engineering SE](https://networkengineering.stackexchange.com/) |
| Networking |
| Security Stack Exchange [Information Security SE](https://security.stackexchange.com/) |
| Security |
| r/netsec [Reddit netsec](https://www.reddit.com/r/netsec/) |
| Security research |
| r/networking [Reddit Networking](https://www.reddit.com/r/networking/) |
| Enterprise networking |
| Nmap Dev [Nmap Community](https://nmap.org/mailman/) |
| Nmap |
| Wireshark Community [Wireshark Q&A](https://ask.wireshark.org/) |
| Packet analysis |

---

## Section 25: Vendors / Products <a name="section-25"></a>

For awareness and lab/compliance coverage: 

| Area | Important Vendors |
| --- | --- |
| Network infrastructure |
| Cisco, Juniper, Arista |
| NGFW |
| Palo Alto, Fortinet, Check Point |
| Load balancer / ADC |
| F5 |
| Vulnerability Management |
| Tenable, Qualys, Rapid7, Greenbone |
| IDS/IPS |
| Suricata, Snort |
| Network Detection |
| Zeek, Corelight |
| NAC |
| Cisco ISE, Forescout, Aruba ClearPass |
| VPN / ZTNA |
| Palo Alto, Fortinet, Cisco, Zscaler, Cloudflare |
| Packet analysis |
| Wireshark, NETSCOUT |

For security testing, avoid becoming vendor-specific; learn the underlying protocols and controls.

---

## Section 26: Latest Developments <a name="section-26"></a>

For this category, link to continuously updated sources rather than static news articles. 

| Feed | What to monitor |
| --- | --- |
| CISA Advisories [CISA Cybersecurity Advisories](https://www.cisa.gov/news-events/cybersecurity-advisories) |
| Network appliance vulnerabilities |
| CISA KEV [CISA KEV Catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) |
| Actively exploited CVEs |
| Cisco PSIRT [Cisco Security Advisories](https://sec.cloudapps.cisco.com/security/center/publicationListing.x) |
| Cisco vulnerabilities |
| Juniper Security Advisories [Juniper Security Advisories](https://supportportal.juniper.net/s/global-search/%40uri?language=en_US) |
| Juniper vulnerabilities |
| Fortinet PSIRT [FortiGuard PSIRT](https://www.fortiguard.com/psirt) |
| Fortinet vulnerabilities |
| Palo Alto Security Advisories [PAN Security Advisories](https://security.paloaltonetworks.com/) |
| PAN vulnerabilities |
| NIST NVD [NVD Recent Vulnerabilities](https://nvd.nist.gov/vuln/search) |
| CVE monitoring |

Also track modern infrastructure-security trends such as Zero Trust, SASE, ZTNA, microsegmentation, encrypted traffic visibility, IPv6 security, SD-WAN security, network automation and AI-assisted network defense. NIST SP 800-207 remains the core authoritative Zero Trust architecture reference. ( [NIST Computer Security Resource Center](https://csrc.nist.gov/pubs/sp/800/207/final))

---

## Section 27: Learning Roadmap <a name="section-27"></a>

```
LEVEL 1 — Networking Fundamentals
```
OSI 
TCP/IP 
IPv4 / IPv6 
Subnetting 
ARP 
DNS 
DHCP 
TCP / UDP 
Routing 
Switching 
VLAN 

→ ↓ 
```
LEVEL 2 — Linux & Windows Networking
```
ip 
ss 
netstat 
route 
arp 
nslookup 
dig 
ping 
traceroute 
PowerShell networking 

→ ↓ 
```
LEVEL 3 — Packet Analysis
```
Wireshark 
tcpdump 
TShark 
PCAP 
TCP handshake 
DNS 
TLS 
HTTP 
SMB 

→ ↓ 
```
LEVEL 4 — Network Discovery
```
Nmap 
Masscan 
Naabu 
Host discovery 
Port scanning 
OS detection 

→ ↓ 
```
LEVEL 5 — Service Enumeration
```
SSH 
FTP 
DNS 
SNMP 
SMB 
LDAP 
NFS 
SMTP 
Databases 
Remote management 

→ ↓ 
```
LEVEL 6 — Vulnerability Assessment
```
Nuclei 
OpenVAS 
Nessus 
CVE 
CWE 
CVSS 
CISA KEV 

→ ↓ 
```
LEVEL 7 — Network Infrastructure
```
Router 
Switch 
Firewall 
ACL 
VPN 
Proxy 
Load balancer 
NAC 
IDS / IPS 

→ ↓ 
```
LEVEL 8 — Enterprise Security
```
Segmentation 
DMZ 
Internal networks 
Remote access 
Authentication 
Logging 
Monitoring 

→ ↓ 
```
LEVEL 9 — Advanced Network Testing
```
Scapy 
Impacket 
Packet crafting 
Protocol analysis 
IPv6 
Routing protocol security 
Segmentation validation 

→ ↓ 
```
LEVEL 10 — Defense
```
Wireshark 
Zeek 
Suricata 
Snort 
SIEM 
Network Detection 
Threat Hunting 

→ ↓ 
```
LEVEL 11 — Architecture
```
Zero Trust 
Microsegmentation 
SASE 
ZTNA 
Network access control 

→ ↓ 
```
LEVEL 12 — Compliance
```
NIST SP 800-115 
NIST SP 800-41 
NIST SP 800-207 
CIS Controls 
CIS Benchmarks 
ISO 27001 
PCI DSS 
DISA STIG 

- ⭐ Network & Infrastructure Security — Top 15 
| Rank | Resource | Purpose |
| --- | --- | --- |
| 1 |
| [NIST SP 800-115](https://csrc.nist.gov/pubs/sp/800/115/final) |
| Assessment methodology |
| 2 |
| [Nmap](https://nmap.org/) |
| Discovery/enumeration |
| 3 |
| [Wireshark](https://www.wireshark.org/) |
| Packet analysis |
| 4 |
| [HackTricks](https://book.hacktricks.wiki/) |
| Pentesting reference |
| 5 |
| [HTB Penetration Tester Path](https://academy.hackthebox.com/path/preview/penetration-tester) |
| Hands-on methodology |
| 6 |
| [Nuclei](https://github.com/projectdiscovery/nuclei) |
| Vulnerability validation |
| 7 |
| [Impacket](https://github.com/fortra/impacket) |
| Network protocols |
| 8 |
| [OpenVAS](https://community.greenbone.net/getting-started/) |
| Vulnerability assessment |
| 9 |
| [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks) |
| Hardening |
| 10 |
| [NIST Zero Trust Architecture](https://csrc.nist.gov/pubs/sp/800/207/final) |
| Modern architecture |
| 11 |
| [Zeek](https://zeek.org/) |
| Network monitoring |
| 12 |
| [Suricata](https://suricata.io/) |
| IDS/IPS |
| 13 |
| [SecLists](https://github.com/danielmiessler/SecLists) |
| Enumeration datasets |
| 14 |
| [OffSec PEN-200](https://www.offsec.com/courses/pen-200/) |
| Professional training |
| 15 |
| [CISA KEV](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) |
| Exploited-vulnerability tracking |

#### Recommended practical stack 
Networking fundamentals → Nmap → Wireshark → tcpdump → NIST/PTES methodology → service enumeration → Nuclei/OpenVAS/Nessus → firewall/VLAN/segmentation assessment → Impacket/Scapy → Zeek/Suricata → Zero Trust → CIS/NIST compliance → professional reporting. 
This is the level of refinement I’ll use for each of the remaining domains: multiple curated hyperlinks under all 27 categories, official sources where possible, GitHub repos, labs, methodology, standards, reports, videos, books and learning roadmap, while also extracting good resources from your uploaded Offensive Resources material when relevant.

---

<div align="center">
<sub>🌐 Network & Infrastructure Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>