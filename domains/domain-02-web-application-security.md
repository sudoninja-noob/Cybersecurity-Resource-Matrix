# 🕸️ Domain 02: Web Application Security

> **Group:** Network, Web & Application  
> **Curated links:** 155  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

This is the GitHub/website-ready Web Application Security resource set, organized in the same 27-category structure. 
Your uploaded Offensive Resources collection already includes strong web-security foundations such as The Web Application Hacker’s Handbook, PortSwigger learning materials, OWASP Web Security Testing Guide, Real-World Bug Hunting, PortSwigger Labs, OWASP Juice Shop, PentesterLab, root-me, OSWE, eWAPT/eWAPTX, SEC542 and SEC642. I’ve kept those where they are still valuable and added newer official and maintained resources. 
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
| OWASP Web Security Testing Guide |
| Official / Free |
| Primary web-security testing methodology |
| OWASP Top 10:2025 |
| Official / Free |
| Current high-level web application risk awareness |
| PortSwigger Web Security Academy |
| Free / Lab |
| Best practical web-security learning platform |
| OWASP ASVS |
| Official / Free |
| Application security verification requirements |
| MDN Web Docs |
| Official-quality / Free |
| Understand HTTP, cookies, CORS, browser behavior |
| HTTP Semantics — RFC 9110 |
| Standard / Free |
| Core HTTP protocol reference |

[OWASP WSTG](https://owasp.org/www-project-web-security-testing-guide/)[OWASP Top 10:2025](https://owasp.org/www-project-top-ten/)[PortSwigger Web Security Academy](https://portswigger.net/web-security)[OWASP ASVS](https://owasp.org/www-project-application-security-verification-standard/)[MDN Web Docs](https://developer.mozilla.org/)[RFC 9110 HTTP Semantics](https://www.rfc-editor.org/rfc/rfc9110)
OWASP’s current released Top 10 is 2025, with Broken Access Control, Security Misconfiguration, Software Supply Chain Failures, Cryptographic Failures and Injection among the current categories. ( [OWASP Foundation](https://owasp.org/www-project-top-ten/))

---

## Section 02: Methodology <a name="section-02"></a>

Primary methodology sources 
OWASP WSTG Stable 
OWASP WSTG Latest / v5 development 
OWASP ASVS 
PTES 
NIST SP 800-115 
[OWASP WSTG Stable](https://owasp.org/www-project-web-security-testing-guide/stable/)[OWASP WSTG Latest](https://owasp.org/www-project-web-security-testing-guide/latest/)[OWASP ASVS](https://owasp.org/www-project-application-security-verification-standard/)[PTES](http://www.pentest-standard.org/)[NIST SP 800-115](https://csrc.nist.gov/pubs/sp/800/115/final)
OWASP WSTG organizes testing around information gathering, configuration/deployment, identity, authentication, authorization, session management, input validation, error handling, cryptography, business logic and client-side testing; the latest development content also includes API testing. ( [OWASP Foundation](https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/)) 

#### Recommended Web Pentest Workflow 
Authorization / Scope 

→ ↓ Reconnaissance 

→ ↓ Application Mapping 

→ ↓ Technology Fingerprinting 

→ ↓ Endpoint Discovery 

→ ↓ Authentication Testing 

→ ↓ Authorization Testing 

→ ↓ Session Management 

→ ↓ Input Validation 

→ ↓ Injection Testing 

→ ↓ Business Logic Testing 

→ ↓ Client-Side Testing 

→ ↓ File Upload / Parser Testing 

→ ↓ Server-Side Testing 

→ ↓ API / WebSocket Testing 

→ ↓ Configuration Review 

→ ↓ Dependency Review 

→ ↓ Vulnerability Validation 

→ ↓ Risk Rating 

→ ↓ Reporting 

→ ↓ Retest 

> Priority: ⭐⭐⭐

---

## Section 03: Standards / Compliance <a name="section-03"></a>

| Standard / Framework | Coverage |
| --- | --- |
| OWASP ASVS |
| Web application verification requirements |
| OWASP Top 10:2025 |
| Web risk awareness |
| OWASP WSTG |
| Security testing methodology |
| OWASP Cheat Sheet Series |
| Secure implementation guidance |
| CWE Top 25 |
| Dangerous software weaknesses |
| PCI DSS 4.x |
| Web/payment security requirements |
| NIST SSDF SP 800-218 |
| Secure software development |
| ISO/IEC 27001 |
| Information security management |
| ISO/IEC 27034 |
| Application security |
| CIS Controls |
| Security safeguards |

[OWASP ASVS](https://owasp.org/www-project-application-security-verification-standard/)[OWASP Top 10](https://owasp.org/www-project-top-ten/)[OWASP Cheat Sheets](https://cheatsheetseries.owasp.org/)[MITRE CWE Top 25](https://cwe.mitre.org/top25/)[PCI DSS](https://www.pcisecuritystandards.org/standards/pci-dss/)[NIST SSDF SP 800-218](https://csrc.nist.gov/pubs/sp/800/218/final)[ISO/IEC 27001](https://www.iso.org/isoiec-27001-information-security.html)
The 2025 CWE Top 25 ranks XSS, SQL injection, CSRF, missing authorization, path traversal and OS command injection among the highest-risk weaknesses. ( [CWE](https://cwe.mitre.org/top25/archive/2025/2025_cwe_top25.html))

---

## Section 04: Official Documentation <a name="section-04"></a>

OWASP 
OWASP WSTG 
OWASP ASVS 
OWASP Top 10 
OWASP Cheat Sheet Series 
OWASP Juice Shop 
OWASP WebGoat 
[OWASP Projects](https://owasp.org/projects/)[OWASP WSTG](https://wstg.owasp.org/)[OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/)
PortSwigger 
Web Security Academy 
Burp Suite documentation 
Burp extensions documentation 
Research 
[Web Security Academy](https://portswigger.net/web-security)[Burp Suite Documentation](https://portswigger.net/burp/documentation)[PortSwigger Research](https://portswigger.net/research)
Browser/Web Platform 
MDN 
WHATWG 
RFC Editor 
[MDN Web Security](https://developer.mozilla.org/en-US/docs/Web/Security)[WHATWG HTML Standard](https://html.spec.whatwg.org/)[RFC Editor](https://www.rfc-editor.org/)

---

## Section 05: Checklists <a name="section-05"></a>

| Resource | Purpose |
| --- | --- |
| OWASP WSTG |
| Full pentest checklist |
| OWASP ASVS |
| Security verification checklist |
| OWASP Cheat Sheets |
| Implementation checklist |
| HackTricks Web Pentesting |
| Operational pentest notes |
| PayloadsAllTheThings |
| Testing reference |
| OWASP Testing Checklist |
| Web assessment baseline |

[OWASP WSTG](https://owasp.org/www-project-web-security-testing-guide/stable/)[OWASP ASVS](https://owasp.org/www-project-application-security-verification-standard/)[OWASP Cheat Sheets](https://cheatsheetseries.owasp.org/)[HackTricks Web Pentesting](https://book.hacktricks.wiki/en/network-services-pentesting/pentesting-web/index.html)[PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)

#### Recommended internal checklist 
Recon 
Subdomains 
Virtual hosts 
Technology stack 
HTTP methods 
Headers 
Cookies 
Authentication 
MFA 
Password reset 
Authorization 
IDOR/BOLA 
Session handling 
CSRF 
CORS 
XSS 
SQLi 
NoSQLi 
Command injection 
SSTI 
XXE 
SSRF 
Path traversal 
LFI/RFI 
File upload 
Deserialization 
Request smuggling 
Web cache poisoning 
Web cache deception 
Open redirect 
Clickjacking 
WebSockets 
OAuth/OIDC 
JWT 
Business logic 
Race conditions 
Rate limiting 
Error handling 
Cryptography 
TLS 
Dependencies 
Logging

---

## Section 06: Cheat Sheets <a name="section-06"></a>

- ⭐⭐⭐ Best collection: OWASP Cheat Sheet Series. It covers authentication, authorization, CSP, CSRF, XSS, SQL injection prevention, file upload, SSRF, JWT, WebSocket security, OAuth, TLS and many other web topics. ( [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/)) 
[OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/)[HackTricks](https://book.hacktricks.wiki/)[PortSwigger Web Security Academy Topics](https://portswigger.net/web-security/all-topics)[PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)[Pentest Book](https://pentestbook.six2dez.com/)

---

## Section 07: Tools <a name="section-07"></a>

Proxy / Interception 

| Tool | Purpose |
| --- | --- |
| ⭐⭐⭐ Burp Suite |
| Main web-security proxy |
| ⭐⭐⭐ OWASP ZAP |
| Open-source proxy/scanner |
| ⭐⭐ Caido |
| Modern web proxy |
| ⭐⭐ mitmproxy |
| Scriptable HTTP proxy |

[Burp Suite](https://portswigger.net/burp)[OWASP ZAP](https://www.zaproxy.org/)[Caido](https://caido.io/)[mitmproxy](https://mitmproxy.org/)
Recon / Discovery 
httpx 
Katana 
gau 
waybackurls 
ffuf 
Feroxbuster 
Gobuster 
[httpx](https://github.com/projectdiscovery/httpx)[Katana](https://github.com/projectdiscovery/katana)[gau](https://github.com/lc/gau)[waybackurls](https://github.com/tomnomnom/waybackurls)[ffuf](https://github.com/ffuf/ffuf)[Feroxbuster](https://github.com/epi052/feroxbuster)[Gobuster](https://github.com/OJ/gobuster)
Vulnerability Discovery 
Nuclei 
Nikto 
sqlmap 
Dalfox 
XSStrike 
Commix 
Arjun 
[Nuclei](https://github.com/projectdiscovery/nuclei)[Nikto](https://github.com/sullo/nikto)[sqlmap](https://github.com/sqlmapproject/sqlmap)[Dalfox](https://github.com/hahwul/dalfox)[XSStrike](https://github.com/s0md3v/XSStrike)[Commix](https://github.com/commixproject/commix)[Arjun](https://github.com/s0md3v/Arjun)

---

## Section 08: Labs / Practice <a name="section-08"></a>

Your uploaded collection already includes PortSwigger Labs, OWASP Juice Shop, OWASP Broken Web Apps, PentesterLab and root-me as web-security labs. 

| Lab | Level |
| --- | --- |
| ⭐⭐⭐ PortSwigger Web Security Academy |
| Beginner → Expert |
| ⭐⭐⭐ OWASP Juice Shop |
| Beginner → Advanced |
| ⭐⭐⭐ OWASP WebGoat |
| Beginner → Intermediate |
| ⭐⭐⭐ PentesterLab |
| Intermediate → Advanced |
| ⭐⭐⭐ Hack The Box Academy Web Pentester |
| Beginner → Advanced |
| ⭐⭐ DVWA |
| Beginner |
| ⭐⭐ bWAPP |
| Beginner |
| ⭐⭐ Root-Me Web Challenges |
| Intermediate |

[PortSwigger Academy Labs](https://portswigger.net/web-security/all-labs)[OWASP Juice Shop](https://owasp.org/www-project-juice-shop/)[OWASP WebGoat](https://owasp.org/www-project-webgoat/)[PentesterLab](https://pentesterlab.com/)[HTB Web Penetration Tester Path](https://academy.hackthebox.com/path/preview/web-penetration-tester)[DVWA](https://github.com/digininja/DVWA)[Root-Me Web Challenges](https://www.root-me.org/en/Challenges/Web-Server/)
PortSwigger Academy currently includes interactive labs across SQL injection, XSS, CSRF, XXE, request smuggling, cache attacks, Web LLM attacks, API testing, NoSQL injection and more. ( [PortSwigger](https://portswigger.net/web-security))

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

Use only in authorized testing environments. 
PayloadsAllTheThings 
SecLists 
FuzzDB 
PortSwigger payload/reference material 
OWASP WSTG fuzz vectors 
Nuclei Templates 
[PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)[SecLists](https://github.com/danielmiessler/SecLists)[FuzzDB](https://github.com/fuzzdb-project/fuzzdb)[Nuclei Templates](https://github.com/projectdiscovery/nuclei-templates)[OWASP WSTG Fuzzing](https://owasp.org/www-project-web-security-testing-guide/latest/Appendices/Fuzzing/)

---

## Section 10: YouTube / Video <a name="section-10"></a>

| Channel | Focus |
| --- | --- |
| ⭐⭐⭐ PortSwigger |
| Web vulnerability research |
| ⭐⭐⭐ LiveOverflow |
| Web exploitation concepts |
| ⭐⭐⭐ IppSec |
| Web/HTB walkthroughs |
| ⭐⭐⭐ John Hammond |
| Web security labs |
| ⭐⭐ NahamSec |
| Bug bounty / recon |
| ⭐⭐ STÖK |
| Bug bounty methodology |
| ⭐⭐ DEF CON |
| Advanced research |
| ⭐⭐ Black Hat |
| Research / AppSec talks |

[PortSwigger YouTube](https://www.youtube.com/@PortSwigger)[LiveOverflow](https://www.youtube.com/@LiveOverflow)[IppSec](https://www.youtube.com/@ippsec)[John Hammond](https://www.youtube.com/@_JohnHammond)[NahamSec](https://www.youtube.com/@NahamSec)[STÖK](https://www.youtube.com/@STOKfredrik)[DEF CON](https://www.youtube.com/@DEFCONConference)[Black Hat](https://www.youtube.com/@BlackHatOfficialYT)

---

## Section 11: Courses / Training <a name="section-11"></a>

Your uploaded source already lists OSWE, eWAPT, eWAPTX, SEC542 and SEC642 for Web Applications. 

| Course | Level |
| --- | --- |
| ⭐⭐⭐ PortSwigger Web Security Academy |
| All levels |
| ⭐⭐⭐ HTB Web Penetration Tester |
| Beginner → Intermediate |
| ⭐⭐⭐ HTB Senior Web Penetration Tester |
| Advanced |
| ⭐⭐⭐ OffSec WEB-200 |
| Intermediate |
| ⭐⭐⭐ OffSec WEB-300 / OSWE |
| Advanced |
| ⭐⭐⭐ SANS SEC542 |
| Intermediate |
| ⭐⭐ SANS SEC642 |
| Advanced |
| ⭐⭐ INE eWPT/eWPTX tracks |
| Intermediate/Advanced |
| ⭐⭐ PentesterLab PRO |
| Intermediate |

[PortSwigger Academy](https://portswigger.net/web-security)[HTB Web Penetration Tester](https://academy.hackthebox.com/path/preview/web-penetration-tester)[HTB Senior Web Penetration Tester](https://academy.hackthebox.com/path/preview/senior-web-penetration-tester)[OffSec WEB-200](https://www.offsec.com/courses/web-200/)[OffSec WEB-300](https://www.offsec.com/courses/web-300/)[SANS SEC542](https://www.sans.org/cyber-security-courses/web-app-penetration-testing-ethical-hacking/)[SANS SEC642](https://www.sans.org/cyber-security-courses/advanced-web-app-penetration-testing-ethical-hacking/)
HTB’s Web Penetration Tester path covers the full workflow from reconnaissance and vulnerability discovery to exploitation and reporting, while the Senior path adds white-box analysis, debugging, source review and advanced vulnerability research. ( [HTB Academy](https://academy.hackthebox.com/path/preview/web-penetration-tester))

---

## Section 12: Certifications <a name="section-12"></a>

| Certification | Focus |
| --- | --- |
| ⭐⭐⭐ BSCP |
| Burp Suite / practical web security |
| ⭐⭐⭐ OSWE |
| Advanced white-box web security |
| ⭐⭐⭐ OSWA |
| Practical web security |
| ⭐⭐ HTB CWES |
| Advanced web exploitation |
| ⭐⭐ HTB CWEE |
| Expert-level web |
| ⭐⭐ eWPT |
| Web penetration testing |
| ⭐⭐ eWPTX |
| Advanced web testing |
| ⭐⭐ GWAPT |
| SANS/GIAC web AppSec |

[Burp Suite Certified Practitioner](https://portswigger.net/web-security/certification)[OffSec OSWE](https://www.offsec.com/courses/web-300/)[OffSec OSWA](https://www.offsec.com/courses/web-200/)[GIAC GWAPT](https://www.giac.org/certifications/web-application-penetration-tester-gwapt/)

---

## Section 13: Books <a name="section-13"></a>

Your uploaded list already contains several core web books. 

#### Essential 

- ⭐⭐⭐ The Web Application Hacker's Handbook 
- ⭐⭐⭐ Real-World Bug Hunting 
- ⭐⭐⭐ Bug Bounty Bootcamp 
- ⭐⭐⭐ The Tangled Web 
- ⭐⭐ Web Application Security 
- ⭐⭐ Bug Bounty Playbook 
- ⭐⭐ Black Hat GraphQL 
- ⭐⭐ Hacking APIs — especially useful where web/API overlap exists [Real-World Bug Hunting](https://nostarch.com/bughunting)[Bug Bounty Bootcamp](https://nostarch.com/bug-bounty-bootcamp)[The Tangled Web](https://nostarch.com/tangledweb)
The Web Application Hacker’s Handbook remains historically important, but PortSwigger Academy is more current for evolving vulnerabilities.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

#### Top sources 

- ⭐⭐⭐ PortSwigger Research 
- ⭐⭐⭐ Project Zero 
- ⭐⭐⭐ Orange Tsai research 
- ⭐⭐⭐ Assetnote Research 
- ⭐⭐⭐ SonarSource Vulnerability Research 
- ⭐⭐ Detectify Labs 
- ⭐⭐ Trail of Bits 
- ⭐⭐ ProjectDiscovery Blog 
- ⭐⭐ OWASP articles 
- ⭐⭐ Intigriti Research 
- ⭐⭐ HackerOne Hacktivity [PortSwigger Research](https://portswigger.net/research)[Google Project Zero](https://googleprojectzero.blogspot.com/)[Orange Tsai Blog](https://blog.orange.tw/)[Assetnote Research](https://www.assetnote.io/resources/research)[Sonar Vulnerability Research](https://www.sonarsource.com/blog/?category=security)[Trail of Bits Blog](https://blog.trailofbits.com/)[ProjectDiscovery Blog](https://projectdiscovery.io/blog)[HackerOne Hacktivity](https://hackerone.com/hacktivity)

---

## Section 15: Research Papers <a name="section-15"></a>

#### Recommended sources: 
USENIX Security 
IEEE Security & Privacy 
ACM CCS 
NDSS 
WOOT 
Black Hat whitepapers 
PortSwigger Research 
[USENIX Security](https://www.usenix.org/conferences/byname/108)[IEEE Security & Privacy](https://www.ieee-security.org/TC/SP-Index.html)[ACM CCS](https://www.sigsac.org/ccs.html)[NDSS Papers](https://www.ndss-symposium.org/ndss-paper/)[WOOT Workshop](https://wootconference.org/)

#### Research topics worth indexing: 
HTTP request smuggling 
HTTP/2 desync 
HTTP/3 security 
Web cache poisoning 
Web cache deception 
XS-Leaks 
Browser isolation 
CORS 
OAuth 
SSRF 
SSTI 
Prototype pollution 
DOM clobbering 
Race conditions 
WebSockets 
GraphQL 
Server-side prototype pollution 
Web LLM attacks

---

## Section 16: White Papers <a name="section-16"></a>

OWASP WSTG 
OWASP ASVS 
OWASP Top 10 
NIST Secure Software Development Framework 
CISA Secure by Design 
PortSwigger annual/research publications 
PCI DSS guidance 
SANS AppSec papers 
[NIST SSDF](https://csrc.nist.gov/pubs/sp/800/218/final)[CISA Secure by Design](https://www.cisa.gov/securebydesign)[PCI SSC Document Library](https://www.pcisecuritystandards.org/document_library/)[PortSwigger Research](https://portswigger.net/research)

---

## Section 17: Conference Material <a name="section-17"></a>

| Conference | Focus |
| --- | --- |
| ⭐⭐⭐ OWASP Global AppSec |
| Application security |
| ⭐⭐⭐ Black Hat |
| Advanced web research |
| ⭐⭐⭐ DEF CON |
| Offensive security |
| ⭐⭐⭐ OffensiveCon |
| Advanced exploitation |
| ⭐⭐ BSides |
| Community AppSec research |
| ⭐⭐ USENIX Security |
| Academic research |
| ⭐⭐ Nullcon |
| Offensive AppSec |

[OWASP Global AppSec](https://owasp.org/events/)[Black Hat](https://www.blackhat.com/)[DEF CON](https://defcon.org/)[OffensiveCon](https://www.offensivecon.org/)[Security BSides](https://bsides.org/)[Nullcon](https://nullcon.net/)

---

## Section 18: Mind Maps <a name="section-18"></a>

#### Recommended structure for your GitHub/site: 
WEB APPLICATION SECURITY 

```
│
```

```
├── Recon
```

```
│   ├── Subdomains
```

```
│   ├── VHosts
```

```
│   ├── Content Discovery
```

```
│   └── Technology Fingerprinting
```

```
│
```

```
├── Authentication
```

```
│   ├── Passwords
```

```
│   ├── MFA
```

```
│   ├── Reset
```

```
│   └── OAuth/OIDC
```

```
│
```

```
├── Authorization
```

```
│   ├── IDOR
```

```
│   ├── BOLA
```

```
│   └── Privilege Escalation
```

```
│
```

```
├── Session Management
```

```
│
```

```
├── Injection
```

```
│   ├── SQL
```

```
│   ├── NoSQL
```

```
│   ├── Command
```

```
│   ├── LDAP
```

```
│   └── SSTI
```

```
│
```

```
├── Server-Side
```

```
│   ├── SSRF
```

```
│   ├── XXE
```

```
│   ├── File Inclusion
```

```
│   ├── Deserialization
```

```
│   └── Upload
```

```
│
```

```
├── Client-Side
```

```
│   ├── XSS
```

```
│   ├── DOM
```

```
│   ├── CSRF
```

```
│   ├── CORS
```

```
│   └── Clickjacking
```

```
│
```

```
├── HTTP
```

```
│   ├── Request Smuggling
```

```
│   ├── Cache Poisoning
```

```
│   ├── Cache Deception
```

```
│   └── Host Header
```

```
│
```

```
├── Business Logic
```

```
│
```

```
├── Race Conditions
```

```
│
```

```
├── WebSockets
```

```
│
```

```
└── Reporting / ASVS / WSTG
```

---

## Section 19: Sample Reports <a name="section-19"></a>

#### Useful sources: 
Public Pentesting Reports 
HackerOne Hacktivity 
Bugcrowd disclosures 
PortSwigger reporting guidance 
OWASP WSTG Reporting chapter 
[Public Pentest Reports GitHub](https://github.com/juliocesarfort/public-pentesting-reports)[HackerOne Hacktivity](https://hackerone.com/hacktivity)[OWASP WSTG Reporting](https://owasp.org/www-project-web-security-testing-guide/stable/5-Reporting/)

#### Recommended web report structure: 
Executive Summary 
Scope 
Methodology 
Application Architecture 
Attack Surface 
Authentication Review 
Authorization Review 
Session Review 
Input Validation 
Business Logic 
Client-Side Security 
Server-Side Security 
Dependencies 
Findings 
Evidence 
CVSS 
CWE 
OWASP Top 10 Mapping 
ASVS Mapping 
Remediation 
Retest 
Conclusion

---

## Section 20: Templates <a name="section-20"></a>

#### Recommended GitHub structure: 
/templates/web-security/ 

```
├── web-security-test-plan.md
```

```
├── web-pentest-checklist.md
```

```
├── web-test-cases.md
```

```
├── authentication-testing.md
```

```
├── authorization-testing.md
```

```
├── session-testing.md
```

```
├── input-validation.md
```

```
├── business-logic-testing.md
```

```
├── evidence-template.md
```

```
├── vulnerability-report.md
```

```
├── asvs-mapping.md
```

```
└── retest-report.md
```

#### Recommended fields: 
Test ID 
WSTG ID 
Test Name 
Endpoint 
Parameter 
HTTP Method 
Role 
Precondition 
Procedure 
Tool 
Expected Result 
Actual Result 
Evidence 
CWE 
CVSS 
OWASP Top 10 
ASVS Control 
Severity 
Status

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

Primary databases 
[CVE.org](https://www.cve.org/)[NIST NVD](https://nvd.nist.gov/)[MITRE CWE](https://cwe.mitre.org/)[CISA KEV](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)[HackerOne Hacktivity](https://hackerone.com/hacktivity)
Important CWE groups: 
CWE-79   XSS 
CWE-89   SQL Injection 
CWE-352  CSRF 
CWE-862  Missing Authorization 
CWE-22   Path Traversal 
CWE-78   OS Command Injection 
CWE-94   Code Injection 
CWE-200  Information Exposure 
CWE-918  SSRF 
CWE-639  Authorization Bypass / IDOR-related 
These are strongly represented in the current CWE Top 25. ( [CWE](https://cwe.mitre.org/top25/archive/2025/2025_cwe_top25.html))

---

## Section 22: GitHub Repositories <a name="section-22"></a>

#### Essential 

- ⭐⭐⭐ OWASP WSTG 
- ⭐⭐⭐ OWASP CheatSheetSeries 
- ⭐⭐⭐ PayloadsAllTheThings 
- ⭐⭐⭐ SecLists 
- ⭐⭐⭐ Nuclei 
- ⭐⭐⭐ Nuclei Templates 
- ⭐⭐⭐ sqlmap 
- ⭐⭐⭐ ffuf 
- ⭐⭐⭐ Juice Shop 
- ⭐⭐⭐ WebGoat 
- ⭐⭐⭐ DVWA [OWASP WSTG GitHub](https://github.com/OWASP/wstg)[OWASP CheatSheetSeries](https://github.com/OWASP/CheatSheetSeries)[PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)[SecLists](https://github.com/danielmiessler/SecLists)[Nuclei](https://github.com/projectdiscovery/nuclei)[Nuclei Templates](https://github.com/projectdiscovery/nuclei-templates)[sqlmap](https://github.com/sqlmapproject/sqlmap)[ffuf](https://github.com/ffuf/ffuf)[OWASP Juice Shop](https://github.com/juice-shop/juice-shop)[OWASP WebGoat](https://github.com/WebGoat/WebGoat)[DVWA](https://github.com/digininja/DVWA)
OWASP recommends consuming ASVS and Cheat Sheet content from maintained project sources, with the Cheat Sheet project itself hosted and actively developed on GitHub. ( [OWASP Developer Guide](https://devguide.owasp.org/en/06-verification/01-guides/03-asvs/))

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

For web security, prioritize HTTP request/response datasets, vulnerable apps and bug-bounty disclosures over generic PCAPs. 

#### Useful sources: 
OWASP Juice Shop 
WebGoat 
DVWA 
HackerOne disclosed reports 
Bugcrowd disclosed programs/research 
PortSwigger mystery labs 
HTTP Archive 
[HTTP Archive](https://httparchive.org/)[PortSwigger Mystery Labs](https://portswigger.net/web-security/mystery-lab-challenge)[HackerOne Hacktivity](https://hackerone.com/hacktivity)

---

## Section 24: Communities / Forums <a name="section-24"></a>

OWASP Community 
PortSwigger Community 
HackerOne 
Bugcrowd 
Intigriti 
r/netsec 
r/bugbounty 
Security Stack Exchange 
OWASP Slack 
[OWASP Community](https://owasp.org/chapters/)[PortSwigger Community Forum](https://forum.portswigger.net/)[HackerOne](https://www.hackerone.com/)[Bugcrowd](https://www.bugcrowd.com/)[Intigriti](https://www.intigriti.com/)[Security Stack Exchange](https://security.stackexchange.com/)

---

## Section 25: Vendors / Products <a name="section-25"></a>

For professional awareness: 

| Category | Products |
| --- | --- |
| Web proxy |
| Burp Suite, ZAP, Caido |
| DAST |
| Invicti, Acunetix, Burp Scanner |
| SAST |
| Semgrep, CodeQL, Checkmarx, Fortify |
| SCA |
| Snyk, Mend, Black Duck |
| WAF |
| Cloudflare, Akamai, F5, Imperva |
| Bug bounty |
| HackerOne, Bugcrowd, Intigriti |
| BAS / ASM |
| Detectify, ProjectDiscovery ecosystem |

For your resource site, keep open-source and standards-based content primary, commercial products secondary.

---

## Section 26: Latest Developments <a name="section-26"></a>

For a public repository, track continuously updated resources rather than individual news articles. 

#### Current sources 
[PortSwigger Research](https://portswigger.net/research)[OWASP Latest WSTG](https://owasp.org/www-project-web-security-testing-guide/latest/)[OWASP Top 10:2025](https://owasp.org/Top10/2025/)[Project Zero](https://googleprojectzero.blogspot.com/)[ProjectDiscovery Blog](https://projectdiscovery.io/blog)[CISA KEV](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)

#### Current high-value research topics include: 
HTTP/2 Request Smuggling 
HTTP/3 Security 
Web Cache Deception 
Web Cache Poisoning 
Web LLM Attacks 
AI Agent / Web Integration Security 
OAuth/OIDC Logic Flaws 
GraphQL 
NoSQL Injection 
Race Conditions 
Client-Side Prototype Pollution 
Server-Side Prototype Pollution 
XS-Leaks 
Browser Extension Security 
Supply Chain Failures 
PortSwigger’s current Academy already includes newer areas such as Web LLM attacks, API testing, NoSQL injection and web cache deception, showing how modern web testing has expanded well beyond classic SQLi/XSS. ( [PortSwigger](https://portswigger.net/web-security))

---

## Section 27: Learning Roadmap <a name="section-27"></a>

```
LEVEL 1 — Web Fundamentals
```
HTML 
CSS 
JavaScript 
HTTP 
HTTPS 
Cookies 
Sessions 
Headers 
DNS 
Browser Security 

→ ↓ 
```
LEVEL 2 — Web Architecture
```
Frontend 
Backend 
Databases 
REST 
GraphQL 
WebSockets 
CDN 
Reverse Proxy 

→ ↓ 
```
LEVEL 3 — Proxy / Traffic Analysis
```
Burp Suite 
ZAP 
Browser DevTools 
HTTP history 
Repeater 
Decoder 

→ ↓ 
```
LEVEL 4 — Recon
```
Subdomains 
Endpoints 
Content discovery 
Technology fingerprinting 
Parameter discovery 

→ ↓ 
```
LEVEL 5 — Authentication / Sessions
```
Login 
Password reset 
MFA 
Cookies 
Session fixation 
Session invalidation 

→ ↓ 
```
LEVEL 6 — Authorization
```
IDOR 
BOLA 
Horizontal escalation 
Vertical escalation 

→ ↓ 
```
LEVEL 7 — Injection
```
SQLi 
NoSQLi 
Command injection 
SSTI 
LDAP injection 
XPath injection 

→ ↓ 
```
LEVEL 8 — Client-Side
```
XSS 
DOM XSS 
CSRF 
CORS 
Clickjacking 
DOM clobbering 

→ ↓ 
```
LEVEL 9 — Server-Side
```
SSRF 
XXE 
LFI/RFI 
Path traversal 
File upload 
Deserialization 

→ ↓ 
```
LEVEL 10 — HTTP Advanced
```
Request smuggling 
Host header attacks 
Cache poisoning 
Cache deception 
HTTP/2 
HTTP/3 

→ ↓ 
```
LEVEL 11 — Logic
```
Business logic 
Race conditions 
Workflow bypass 
Price manipulation 
Rate limits 

→ ↓ 
```
LEVEL 12 — Modern Authentication
```
JWT 
OAuth 
OIDC 
SAML 
SSO 

→ ↓ 
```
LEVEL 13 — Advanced Web
```
Prototype pollution 
WebSockets 
GraphQL 
Web LLM attacks 
Browser security 
Source-code review 

→ ↓ 
```
LEVEL 14 — Automation
```
Nuclei 
ffuf 
httpx 
Katana 
Custom scripts 

→ ↓ 
```
LEVEL 15 — Standards
```
OWASP Top 10 
WSTG 
ASVS 
CWE 
NIST SSDF 
PCI DSS 

→ ↓ 
```
LEVEL 16 — Reporting
```
CVSS 
CWE 
Evidence 
Impact 
Remediation 
Retesting 

- ⭐ Web Application Security — Top 15 
| Rank | Resource | Purpose |
| --- | --- | --- |
| 1 |
| OWASP WSTG |
| Testing methodology |
| 2 |
| PortSwigger Academy |
| Practical learning |
| 3 |
| OWASP ASVS |
| Verification standard |
| 4 |
| Burp Suite |
| Main testing tool |
| 5 |
| OWASP Top 10:2025 |
| Risk awareness |
| 6 |
| OWASP Cheat Sheet Series |
| Secure implementation |
| 7 |
| OWASP Juice Shop |
| Practice |
| 8 |
| PentesterLab |
| Advanced labs |
| 9 |
| HTB Web Pentester Path |
| Structured learning |
| 10 |
| PayloadsAllTheThings |
| Payload/test reference |
| 11 |
| SecLists |
| Enumeration dictionaries |
| 12 |
| Nuclei |
| Automated validation |
| 13 |
| PortSwigger Research |
| Advanced research |
| 14 |
| CWE Top 25 |
| Weakness taxonomy |
| 15 |
| OSWE / Senior Web Training |
| Advanced specialization |

#### Recommended practical stack 
HTTP/browser fundamentals → OWASP WSTG → Burp Suite → PortSwigger Academy → Juice Shop → authentication/authorization → injection → server/client-side flaws → HTTP desync/cache attacks → business logic/races → source review → ASVS/Top 10 mapping → professional reporting.

---

<div align="center">
<sub>🕸️ Web Application Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>