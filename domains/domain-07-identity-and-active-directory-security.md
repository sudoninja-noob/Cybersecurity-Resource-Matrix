# 🔐 Domain 07: Identity & Active Directory Security

> **Group:** Cloud, Containers & Identity  
> **Curated links:** 86  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

This is the GitHub/website-ready Identity & Active Directory Security resource set using the same 27-category structure. 
This domain should cover both traditional Active Directory (AD DS) and modern identity platforms such as Microsoft Entra ID, because real enterprise identity environments are usually hybrid now. 
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

| Resource | Type | Why Use It |
| --- | --- | --- |
| Microsoft Active Directory Security Best Practices |
| Official / Free |
| Core AD hardening |
| Microsoft Entra Security Documentation |
| Official / Free |
| Cloud identity security |
| MITRE ATT&CK – Credential Access / AD Techniques |
| Official / Free |
| Adversary identity techniques |
| CIS Windows Server Benchmarks |
| Industry / Free |
| AD/Windows hardening |
| SpecterOps BloodHound |
| Open Source / Research |
| AD attack-path analysis |
| ADSecurity.org |
| Free / Research |
| Deep Active Directory security knowledge |

[Microsoft AD Security Best Practices](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/plan/security-best-practices/best-practices-for-securing-active-directory)[Microsoft Entra Security](https://learn.microsoft.com/en-us/entra/fundamentals/security-operations-introduction)[MITRE ATT&CK Enterprise Techniques](https://attack.mitre.org/techniques/enterprise/)[CIS Windows Server Benchmarks](https://www.cisecurity.org/benchmark/microsoft_windows_server)[ADSecurity.org](https://adsecurity.org/)
Microsoft’s current AD guidance emphasizes least privilege, limiting membership in highly privileged groups, using secure administrative hosts, securing domain controllers, and monitoring sensitive AD objects. ( [Microsoft Learn](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/plan/security-best-practices/best-practices-for-securing-active-directory)) 
Core topics 
Active Directory Domain Services 
Domain Controllers 
Forests / Domains / Trees 
Users / Groups / Computers 
Organizational Units 
Group Policy 
Kerberos 
NTLM 
LDAP / LDAPS 
DNS 
Trusts 
ACLs / ACEs 
SPNs 
Service Accounts 
gMSA 
AD CS 
AD FS 
LAPS 
Privileged Access 
Tiering 
Entra ID 
Hybrid Identity 
Azure AD Connect / Entra Connect 
OAuth / OIDC 
SAML 
Conditional Access 
MFA 
PIM 
Workload Identities

---

## Section 02: Methodology <a name="section-02"></a>

Use a combination of: 
Microsoft AD security guidance 
MITRE ATT&CK 
CIS Windows Server Benchmark 
BloodHound attack-path methodology 
PingCastle risk model 
NIST identity guidance 

#### Recommended Identity / AD Assessment Workflow 
Authorization / Scope 

→ ↓ Forest / Domain Discovery 

→ ↓ Domain Controller Inventory 

→ ↓ User / Group / Computer Enumeration 

→ ↓ Trust Mapping 

→ ↓ Privileged Group Review 

→ ↓ ACL / Delegation Review 

→ ↓ Kerberos Configuration 

→ ↓ NTLM Usage 

→ ↓ Service Account Review 

→ ↓ GPO Review 

→ ↓ Password / Authentication Policies 

→ ↓ LAPS / gMSA Review 

→ ↓ AD CS Review 

→ ↓ DNS / LDAP Security 

→ ↓ Attack Path Analysis 

→ ↓ Hybrid Identity Review 

→ ↓ Entra ID Roles / Applications 

→ ↓ Conditional Access / MFA 

→ ↓ PIM / Privileged Identity 

→ ↓ Logging / Detection 

→ ↓ Recovery / Backup 

→ ↓ Risk Rating 

→ ↓ Remediation 

→ ↓ Retest 

> Priority: ⭐⭐⭐

---

## Section 03: Standards / Compliance <a name="section-03"></a>

| Standard / Framework | Coverage |
| --- | --- |
| ⭐⭐⭐ Microsoft AD Security Best Practices |
| AD hardening |
| ⭐⭐⭐ CIS Windows Server Benchmarks |
| Windows/AD baseline |
| MITRE ATT&CK |
| Identity attack techniques |
| NIST SP 800-63 |
| Digital identity |
| NIST SP 800-53 |
| Access control/authentication |
| NIST Zero Trust Architecture |
| Identity-centric access |
| DISA STIG Windows Server |
| Hardened Windows/AD configuration |
| Microsoft Security Baselines |
| Windows/domain security |
| ISO/IEC 27001 |
| Identity/access governance |

CIS currently lists Windows Server 2025 Benchmark 2.1.0, Server 2022 5.1.0, and Server 2019 5.0.0, along with STIG variants. ( [CIS](https://www.cisecurity.org/benchmark/microsoft_windows_server)) 
[NIST Digital Identity Guidelines](https://pages.nist.gov/800-63-4/)[NIST SP 800-53](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)[NIST Zero Trust Architecture](https://csrc.nist.gov/pubs/sp/800/207/final)[Microsoft Security Baselines](https://learn.microsoft.com/en-us/windows/security/operating-system-security/device-management/windows-security-configuration-framework/windows-security-baselines)

---

## Section 04: Official Documentation <a name="section-04"></a>

Active Directory 
[Active Directory Domain Services Docs](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/active-directory-domain-services)[AD Security Best Practices](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/plan/security-best-practices/best-practices-for-securing-active-directory)[Group Policy Documentation](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/manage/group-policy/group-policy-overview)[Kerberos Authentication Overview](https://learn.microsoft.com/en-us/windows-server/security/kerberos/kerberos-authentication-overview)[Windows LAPS Documentation](https://learn.microsoft.com/en-us/windows-server/identity/laps/laps-overview)
Entra ID 
[Microsoft Entra Documentation](https://learn.microsoft.com/en-us/entra/)[Conditional Access](https://learn.microsoft.com/en-us/entra/identity/conditional-access/overview)[Privileged Identity Management](https://learn.microsoft.com/en-us/entra/id-governance/privileged-identity-management/pim-configure)[Entra Identity Protection](https://learn.microsoft.com/en-us/entra/id-protection/overview-identity-protection)

---

## Section 05: Checklists <a name="section-05"></a>

#### Recommended sources: 
Microsoft AD Best Practices 
CIS Windows Server Benchmark 
PingCastle 
BloodHound 
Purple Knight 
DISA STIG 

#### Recommended Identity / AD Security Checklist 
Domain controllers 
Forest/domain functional level 
Privileged groups 
Enterprise Admins 
Domain Admins 
Administrators 
Schema Admins 
Account Operators 
Backup Operators 
Service accounts 
Dormant accounts 
Password policies 
MFA 
Kerberos 
NTLM 
LM hashes 
SPNs 
Delegation 
Unconstrained delegation 
Constrained delegation 
Resource-based constrained delegation 
GPO permissions 
ACLs 
AdminSDHolder 
SIDHistory 
Trusts 
LAPS 
gMSA 
AD CS 
LDAP signing 
LDAP channel binding 
SMB signing 
DNS 
KRBTGT rotation 
DC backups 
Secure admin workstations 
Tiering model 
Windows auditing 
Entra admin roles 
Conditional Access 
PIM 
Enterprise applications 
App registrations 
Service principals 
Guest users 
Hybrid identity

---

## Section 06: Cheat Sheets <a name="section-06"></a>

Useful references: 
[HackTricks Active Directory](https://book.hacktricks.wiki/en/windows-hardening/active-directory-methodology/index.html)[MITRE ATT&CK Credential Access](https://attack.mitre.org/tactics/TA0006/)[MITRE ATT&CK Privilege Escalation](https://attack.mitre.org/tactics/TA0004/)[BloodHound Documentation](https://bloodhound.specterops.io/)[Microsoft Kerberos Documentation](https://learn.microsoft.com/en-us/windows-server/security/kerberos/kerberos-authentication-overview)
Useful command/reference areas: 
whoami 
whoami /groups 
net user 
net group 
nltest 
dsquery 
setspn 
klist 
gpresult 
Get-ADUser 
Get-ADGroup 
Get-ADComputer 
Get-ADTrust 
Get-GPO 
Get-ACL 
Get-ADObject

---

## Section 07: Tools <a name="section-07"></a>

AD Security Assessment 

| Tool | Purpose |
| --- | --- |
| ⭐⭐⭐ BloodHound |
| Attack-path analysis |
| ⭐⭐⭐ PingCastle |
| AD security posture/risk assessment |
| ⭐⭐⭐ Purple Knight |
| AD/Entra security assessment |
| ⭐⭐ ADRecon |
| AD reconnaissance/reporting |
| ⭐⭐ Forest Druid |
| AD attack-path review |

[BloodHound](https://github.com/SpecterOps/BloodHound)[PingCastle GitHub](https://github.com/netwrix/pingcastle)[Purple Knight](https://www.semperis.com/purple-knight/)[ADRecon](https://github.com/adrecon/ADRecon)
PingCastle currently supports AD health checks, Entra ID scoring, inter-domain mapping, consolidation, workstation scanning, and export functions. ( [GitHub](https://github.com/netwrix/pingcastle)) 
Kerberos / Protocol Analysis 
Rubeus 
Impacket 
Kerbrute 
ldapsearch 
Wireshark 
[Rubeus](https://github.com/GhostPack/Rubeus)[Impacket](https://github.com/fortra/impacket)[Kerbrute](https://github.com/ropnop/kerbrute)
Entra / Hybrid Identity 
AzureHound 
ROADtools 
GraphRunner 
AADInternals 
Monkey365 
[AzureHound](https://github.com/SpecterOps/AzureHound)[ROADtools](https://github.com/dirkjanm/ROADtools)[GraphRunner](https://github.com/dafthack/GraphRunner)[AADInternals](https://github.com/Gerenios/AADInternals)[Monkey365](https://github.com/silverhack/monkey365)

---

## Section 08: Labs / Practice <a name="section-08"></a>

| Lab | Level |
| --- | --- |
| ⭐⭐⭐ GOAD – Game of Active Directory |
| Intermediate → Advanced |
| ⭐⭐⭐ Hack The Box AD Labs |
| Intermediate |
| ⭐⭐⭐ HTB Academy Active Directory |
| Structured |
| ⭐⭐⭐ TryHackMe Attacktive Directory |
| Beginner |
| ⭐⭐ DetectionLab |
| AD + defensive lab |
| ⭐⭐ Vulnerable-AD |
| Build vulnerable AD |
| ⭐⭐ PurpleCloud |
| Azure/AD lab |

[GOAD GitHub](https://github.com/Orange-Cyberdefense/GOAD)[Vulnerable-AD](https://github.com/WazeHell/vulnerable-AD)[DetectionLab](https://github.com/clong/DetectionLab)[PurpleCloud](https://github.com/iknowjason/PurpleCloud)

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

For authorized labs, prioritize identity configuration and attack-path test cases rather than generic payloads. 

#### Recommended test categories 
Weak password policy 
Privileged group membership 
Dormant admin accounts 
Kerberoastable service accounts 
AS-REP roastable users 
Unconstrained delegation 
Constrained delegation 
RBCD 
Excessive ACL permissions 
AdminSDHolder exposure 
SIDHistory misuse 
Weak GPO permissions 
NTLM fallback 
LDAP signing disabled 
LDAP channel binding disabled 
SMB signing disabled 
LAPS missing 
Weak service account management 
AD CS misconfiguration 
Trust abuse 
Kerberos configuration weaknesses 
MFA gaps 
Conditional Access gaps 
Overprivileged Entra roles 
App registration permissions 
Service principal privileges 
Guest access 
Hybrid sync privilege 
MITRE currently models many AD behaviors including domain-account abuse, NTDS credential access, LSA secrets, Kerberos/NTLM-related credential activity, and AD object access. ( [MITRE ATT&CK](https://attack.mitre.org/techniques/))

---

## Section 10: YouTube / Video <a name="section-10"></a>

#### Recommended channels/resources: 
SpecterOps 
Black Hat 
DEF CON 
Microsoft Security 
John Hammond 
IppSec 
SANS 
DerbyCon archives 
ADSecurity / Sean Metcalf talks 
[SpecterOps YouTube](https://www.youtube.com/@SpecterOps)[Microsoft Security YouTube](https://www.youtube.com/@MicrosoftSecurity)[Black Hat YouTube](https://www.youtube.com/@BlackHatOfficialYT)[DEF CON YouTube](https://www.youtube.com/@DEFCONConference)
Search topics: 
Active Directory attack paths 
BloodHound 
Kerberos security 
AD CS 
Delegation 
NTLM 
Kerberoasting 
ACL abuse 
Tiered administration 
Hybrid identity 
Entra Conditional Access 
Identity threat detection

---

## Section 11: Courses / Training <a name="section-11"></a>

| Course | Level |
| --- | --- |
| ⭐⭐⭐ Altered Security CRTP |
| Intermediate |
| ⭐⭐⭐ Altered Security CRTE |
| Advanced |
| ⭐⭐⭐ Altered Security CARTP |
| Azure/Entra |
| ⭐⭐⭐ HTB Active Directory paths |
| Hands-on |
| ⭐⭐ SANS SEC560/660 |
| Enterprise offensive |
| ⭐⭐ OffSec PEN-200/300 |
| AD crossover |
| ⭐⭐ SpecterOps training |
| Advanced identity/security |

[Altered Security Training](https://www.alteredsecurity.com/)[Hack The Box Academy](https://academy.hackthebox.com/)[SpecterOps Training](https://specterops.io/training/)

---

## Section 12: Certifications <a name="section-12"></a>

| Certification | Focus |
| --- | --- |
| ⭐⭐⭐ CRTP |
| AD penetration testing |
| ⭐⭐⭐ CRTE |
| Advanced AD red teaming |
| ⭐⭐⭐ CARTP |
| Azure/Entra red teaming |
| ⭐⭐ CRTO |
| Enterprise red-team identity skills |
| ⭐⭐ OSCP |
| General AD pentesting |
| ⭐⭐ OSEP |
| Advanced enterprise AD attacks |
| ⭐⭐ HTB CPTS |
| Practical AD |
| ⭐⭐ SC-300 |
| Microsoft Identity and Access Administrator |

[Microsoft SC-300](https://learn.microsoft.com/en-us/credentials/certifications/identity-and-access-administrator/)

---

## Section 13: Books <a name="section-13"></a>

#### Recommended: 

- ⭐⭐⭐ Active Directory Security 
- ⭐⭐⭐ Penetration Testing Active Directory 
- ⭐⭐⭐ Mastering Active Directory 
- ⭐⭐⭐ Windows Internals 
- ⭐⭐ Learn Active Directory Management in a Month of Lunches 
- ⭐⭐ The Definitive Guide to Active Directory Troubleshooting and Auditing 
- ⭐⭐ Microsoft identity/security documentation as a living reference For practical AD security, combine printed references with BloodHound, SpecterOps research, and Microsoft documentation because identity attack techniques change rapidly.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

High-value sources: 

- ⭐⭐⭐ ADSecurity.org 
- ⭐⭐⭐ SpecterOps Blog 
- ⭐⭐⭐ Microsoft Security Blog 
- ⭐⭐⭐ Semperis Blog 
- ⭐⭐⭐ NetSPI Technical Blog 
- ⭐⭐ TrustedSec 
- ⭐⭐ MDSec 
- ⭐⭐ Orange Cyberdefense 
- ⭐⭐ WithSecure Labs 
- ⭐⭐ Dirk-jan Mollema research [ADSecurity.org](https://adsecurity.org/)[SpecterOps Blog](https://specterops.io/blog/)[Microsoft Security Blog](https://www.microsoft.com/en-us/security/blog/)[Semperis Blog](https://www.semperis.com/blog/)[Dirk-jan Mollema Blog](https://dirkjanm.io/)

---

## Section 15: Research Papers <a name="section-15"></a>

Track research from: 
USENIX Security 
IEEE Security & Privacy 
ACM CCS 
NDSS 
Black Hat 
SpecterOps 
Microsoft security research 

#### Important research topics: 
Kerberos attacks 
NTLM relay 
Credential Guard 
AD CS abuse 
Delegation 
Attack-path graphs 
Hybrid identity 
OAuth abuse 
Entra service principals 
Conditional Access bypass 
Passwordless identity 
Passkeys 
Identity persistence 
Machine identities 
[USENIX Security](https://www.usenix.org/conferences/byname/108)[IEEE Security & Privacy](https://www.ieee-security.org/TC/SP-Index.html)[NDSS Symposium](https://www.ndss-symposium.org/)

---

## Section 16: White Papers <a name="section-16"></a>

#### Recommended: 
Microsoft AD Security Best Practices 
Microsoft Securing Privileged Access guidance 
Microsoft Zero Trust identity guidance 
NIST SP 800-63 
NIST SP 800-207 
MITRE ATT&CK 
CIS Windows Server Benchmark 
SpecterOps identity research 
[Microsoft Privileged Access Strategy](https://learn.microsoft.com/en-us/security/privileged-access-workstations/privileged-access-strategy)[Microsoft Zero Trust Identity](https://learn.microsoft.com/en-us/security/zero-trust/deploy/identity)

---

## Section 17: Conference Material <a name="section-17"></a>

| Conference | Focus |
| --- | --- |
| ⭐⭐⭐ Black Hat |
| AD / identity attacks |
| ⭐⭐⭐ DEF CON |
| Offensive identity |
| ⭐⭐⭐ SpecterOps SO-CON |
| Identity attack paths |
| ⭐⭐⭐ BSides |
| AD research |
| ⭐⭐ TROOPERS |
| Enterprise identity |
| ⭐⭐ Microsoft Ignite |
| Identity/security |
| ⭐⭐ USENIX Security |
| Academic research |

[Black Hat](https://www.blackhat.com/)[DEF CON](https://defcon.org/)[SpecterOps Events](https://specterops.io/events/)

---

## Section 18: Mind Maps <a name="section-18"></a>

#### Recommended website structure: 
IDENTITY & ACTIVE DIRECTORY SECURITY 

```
│
```

```
├── AD Architecture
```

```
│   ├── Forest
```

```
│   ├── Domain
```

```
│   ├── Domain Controller
```

```
│   └── Trusts
```

```
│
```

```
├── Authentication
```

```
│   ├── Kerberos
```

```
│   ├── NTLM
```

```
│   ├── LDAP
```

```
│   └── MFA
```

```
│
```

```
├── Authorization
```

```
│   ├── Groups
```

```
│   ├── ACL
```

```
│   ├── ACE
```

```
│   └── Delegation
```

```
│
```

```
├── Privileged Access
```

```
│   ├── Domain Admin
```

```
│   ├── Enterprise Admin
```

```
│   ├── Tiering
```

```
│   ├── PAW
```

```
│   └── PIM
```

```
│
```

```
├── Credentials
```

```
│   ├── Passwords
```

```
│   ├── Service Accounts
```

```
│   ├── gMSA
```

```
│   ├── LAPS
```

```
│   └── Tokens
```

```
│
```

```
├── Kerberos
```

```
│   ├── SPNs
```

```
│   ├── Delegation
```

```
│   └── Tickets
```

```
│
```

```
├── AD CS
```

```
│
```

```
├── Group Policy
```

```
│
```

```
├── Hybrid Identity
```

```
│   ├── Entra ID
```

```
│   ├── Entra Connect
```

```
│   ├── Conditional Access
```

```
│   ├── OAuth/OIDC
```

```
│   └── Enterprise Apps
```

```
│
```

```
├── Attack Paths
```

```
│   └── BloodHound
```

```
│
```

```
└── Detection / Recovery
```

---

## Section 19: Sample Reports <a name="section-19"></a>

Useful reporting sources: 
PingCastle reports 
Purple Knight reports 
BloodHound attack-path reports 
ADRecon 
CIS Benchmark assessments 

#### Recommended report structure: 
Executive Summary 
Scope 
Forest / Domain Architecture 
Domain Controllers 
Privileged Accounts 
Authentication 
Kerberos 
NTLM 
LDAP 
Group Policy 
ACL / Delegation 
Service Accounts 
LAPS / gMSA 
Trusts 
AD CS 
Attack Paths 
Hybrid Identity 
Entra Roles 
Conditional Access 
Applications / Service Principals 
Logging / Detection 
Backup / Recovery 
Findings 
Evidence 
MITRE ATT&CK Mapping 
CIS Mapping 
Remediation 
Retest 
Conclusion

---

## Section 20: Templates <a name="section-20"></a>

#### Recommended GitHub structure: 
/templates/identity-ad-security/ 

```
├── ad-security-test-plan.md
```

```
├── ad-security-checklist.md
```

```
├── domain-controller-review.md
```

```
├── privileged-group-review.md
```

```
├── kerberos-review.md
```

```
├── ntlm-review.md
```

```
├── acl-review.md
```

```
├── gpo-review.md
```

```
├── adcs-review.md
```

```
├── service-account-review.md
```

```
├── laps-review.md
```

```
├── entra-id-review.md
```

```
├── conditional-access-review.md
```

```
├── attack-path-review.md
```

```
├── evidence-template.md
```

```
└── identity-security-report.md
```

#### Recommended test-case columns: 
Test ID 
Forest 
Domain 
Object 
Account / Group 
Control 
Objective 
Precondition 
Tool 
Procedure 
Expected Result 
Actual Result 
Evidence 
MITRE Technique 
CIS Control 
Severity 
Status

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

Track both CVEs and configuration-driven identity compromises. 
Primary sources: 
[CVE.org](https://www.cve.org/)[NIST NVD](https://nvd.nist.gov/)[CISA KEV](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)[MITRE ATT&CK](https://attack.mitre.org/)
Important case-study areas: 
Kerberoasting 
AS-REP roasting 
NTLM relay 
Pass-the-Hash 
Pass-the-Ticket 
Golden Ticket 
Silver Ticket 
Delegation abuse 
DCSync 
DCShadow 
ACL abuse 
GPO abuse 
AD CS abuse 
Trust abuse 
Password spraying 
Token theft 
OAuth consent abuse 
Service principal compromise 
Hybrid identity compromise 
MITRE explicitly tracks Active Directory Configuration as mitigation M1015, emphasizing account configuration, interactive-logon restrictions, group policies, and attack-surface reduction. ( [MITRE ATT&CK](https://attack.mitre.org/mitigations/M1015/))

---

## Section 22: GitHub Repositories <a name="section-22"></a>

#### Essential 

- ⭐⭐⭐ BloodHound 
- ⭐⭐⭐ PingCastle 
- ⭐⭐⭐ Impacket 
- ⭐⭐⭐ Rubeus 
- ⭐⭐⭐ GOAD 
- ⭐⭐⭐ ROADtools 
- ⭐⭐⭐ AzureHound 
- ⭐⭐ ADRecon 
- ⭐⭐ Kerbrute 
- ⭐⭐ AADInternals 
- ⭐⭐ GraphRunner 
- ⭐⭐ PurpleCloud 
- ⭐⭐ Vulnerable-AD [BloodHound GitHub](https://github.com/SpecterOps/BloodHound)[PingCastle GitHub](https://github.com/netwrix/pingcastle)[Impacket GitHub](https://github.com/fortra/impacket)[Rubeus GitHub](https://github.com/GhostPack/Rubeus)[GOAD GitHub](https://github.com/Orange-Cyberdefense/GOAD)[ROADtools GitHub](https://github.com/dirkjanm/ROADtools)[AzureHound GitHub](https://github.com/SpecterOps/AzureHound)
PingCastle’s current GitHub project identifies itself as an AD security-risk assessment and maturity tool, with support for both Active Directory and Entra ID scoring. ( [GitHub](https://github.com/netwrix/pingcastle))

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

For identity security, useful datasets are mostly Windows event logs, AD objects, Kerberos traffic, and BloodHound-style graphs. 
Useful data: 
Windows Security Event Logs 
Domain Controller logs 
Kerberos events 
NTLM events 
LDAP logs 
PowerShell logs 
Sysmon 
Entra sign-in logs 
Entra audit logs 
Identity Protection alerts 
Conditional Access logs 
BloodHound JSON 
PingCastle reports 
GPO exports 
AD CS configuration 
MITRE ATT&CK’s current data components include specific identity telemetry such as Active Directory Credential Request, AD Object Access, AD Object Creation, and AD Object Deletion. ( [MITRE ATT&CK](https://attack.mitre.org/datacomponents/))

---

## Section 24: Communities / Forums <a name="section-24"></a>

#### Recommended: 
SpecterOps community 
Microsoft Security community 
Microsoft Q&A 
BloodHound community 
Netwrix/PingCastle community 
r/activedirectory 
r/sysadmin 
r/netsec 
Security Stack Exchange 
[Microsoft Security Community](https://techcommunity.microsoft.com/category/security-compliance-and-identity)[Security Stack Exchange](https://security.stackexchange.com/)

---

## Section 25: Vendors / Products <a name="section-25"></a>

| Category | Examples |
| --- | --- |
| Identity Provider |
| Microsoft Entra ID, Okta, Ping Identity |
| AD Security Posture |
| Semperis, Netwrix PingCastle, Tenable Identity Exposure |
| Attack Path Management |
| BloodHound Enterprise |
| PAM |
| CyberArk, Delinea, BeyondTrust |
| ITDR |
| Microsoft Defender for Identity, CrowdStrike, Semperis |
| IGA |
| SailPoint, Saviynt |
| MFA / Passwordless |
| Entra, Okta, Duo |
| Secrets / Machine Identity |
| HashiCorp Vault, CyberArk |

For your repository, keep Microsoft, MITRE, CIS, BloodHound, PingCastle and open-source resources above vendor marketing content.

---

## Section 26: Latest Developments <a name="section-26"></a>

Use living sources: 
[Microsoft Security Blog](https://www.microsoft.com/en-us/security/blog/)[SpecterOps Blog](https://specterops.io/blog/)[Semperis Blog](https://www.semperis.com/blog/)[MITRE ATT&CK Enterprise](https://attack.mitre.org/matrices/enterprise/)[Microsoft Entra Blog](https://techcommunity.microsoft.com/category/microsoft-entra-blog)

#### Important current topics: 
Identity Threat Detection and Response (ITDR) 
Attack Path Management 
Hybrid Identity 
Passwordless Authentication 
Passkeys 
Phishing-resistant MFA 
FIDO2 
Conditional Access 
Continuous Access Evaluation 
Privileged Identity Management 
Machine identities 
Workload identities 
OAuth application abuse 
Service principal security 
AD CS security 
LDAP hardening 
NTLM reduction 
Kerberos hardening 
Tier-0 protection 
Identity recovery 
Ransomware resilience 
A notable modern shift is that AD security is no longer only about domain admins and password policy; attack-path analysis and hybrid identity have become central, with tools such as PingCastle now including Entra ID scoring alongside traditional domain assessment. ( [GitHub](https://github.com/netwrix/pingcastle))

---

## Section 27: Learning Roadmap <a name="section-27"></a>

```
LEVEL 1 — Windows Fundamentals
```
Users 
Groups 
Services 
Registry 
NTFS 
PowerShell 

→ ↓ 
```
LEVEL 2 — Active Directory Fundamentals
```
Forest 
Domain 
DC 
OU 
Users 
Groups 
Computers 
DNS 
GPO 

→ ↓ 
```
LEVEL 3 — Authentication
```
Kerberos 
NTLM 
LDAP 
Tickets 
Hashes 
SPNs 

→ ↓ 
```
LEVEL 4 — Authorization
```
ACL 
ACE 
Groups 
Privileges 
Delegation 

→ ↓ 
```
LEVEL 5 — Administration Security
```
Domain Admins 
Enterprise Admins 
Tiering 
PAW 
LAPS 
gMSA 

→ ↓ 
```
LEVEL 6 — Enumeration / Assessment
```
ADRecon 
PingCastle 
BloodHound 
PowerShell 

→ ↓ 
```
LEVEL 7 — Kerberos Security
```
SPNs 
Delegation 
Ticket security 
Service accounts 

→ ↓ 
```
LEVEL 8 — Identity Attack Paths
```
BloodHound 
ACL paths 
Delegation 
Trusts 
GPO 

→ ↓ 
```
LEVEL 9 — AD CS
```
Certificate templates 
Enrollment 
PKI trust 
Certificate authentication 

→ ↓ 
```
LEVEL 10 — Hybrid Identity
```
Entra ID 
Entra Connect 
Federation 
SSO 
OAuth 
OIDC 

→ ↓ 
```
LEVEL 11 — Entra Security
```
Conditional Access 
MFA 
PIM 
Enterprise Apps 
Service Principals 
Guests 

→ ↓ 
```
LEVEL 12 — Detection
```
Windows event logs 
Defender for Identity 
Sysmon 
SIEM 
MITRE ATT&CK 

→ ↓ 
```
LEVEL 13 — Recovery
```
DC backup 
Forest recovery 
KRBTGT reset 
Tier-0 recovery 
Identity incident response 

→ ↓ 
```
LEVEL 14 — Standards
```
Microsoft Best Practices 
CIS 
NIST 
MITRE ATT&CK 
Zero Trust 

→ ↓ 
```
LEVEL 15 — Advanced
```
Attack Path Management 
Machine identities 
Workload identities 
ITDR 
Passkeys 
Passwordless 
Hybrid attack paths 

- ⭐ Identity & Active Directory Security — Top 15 
| Rank | Resource | Purpose |
| --- | --- | --- |
| 1 |
| Microsoft AD Security Best Practices |
| Official hardening |
| 2 |
| BloodHound |
| Attack-path analysis |
| 3 |
| PingCastle |
| AD posture assessment |
| 4 |
| CIS Windows Server Benchmark |
| Hardening baseline |
| 5 |
| MITRE ATT&CK |
| Identity attacker TTPs |
| 6 |
| ADSecurity.org |
| Deep AD knowledge |
| 7 |
| GOAD |
| Hands-on lab |
| 8 |
| Impacket |
| Protocol/security testing |
| 9 |
| Rubeus |
| Kerberos analysis |
| 10 |
| AzureHound |
| Entra attack paths |
| 11 |
| ROADtools |
| Entra research |
| 12 |
| Purple Knight |
| AD/Entra assessment |
| 13 |
| Microsoft Entra Documentation |
| Cloud identity |
| 14 |
| NIST SP 800-63 |
| Digital identity |
| 15 |
| CRTP/CRTE training |
| Structured practical learning |

#### Recommended practical stack 
Windows fundamentals → AD architecture → Kerberos/NTLM/LDAP → privileged groups → ACLs/GPO/delegation → BloodHound/PingCastle → LAPS/gMSA → AD CS → trusts → logging/detection → Entra ID/Conditional Access/PIM → hybrid identity → ITDR/attack-path management → CIS/Microsoft/NIST mapping → professional identity security report.

---

<div align="center">
<sub>🔐 Identity & Active Directory Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>