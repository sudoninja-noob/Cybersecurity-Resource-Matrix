# 🔗 Domain 03: API Security

> **Group:** Network, Web & Application  
> **Curated links:** 106  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

This is the GitHub/website-ready API Security resource set, organized in the same 27-category format. 
Your uploaded Offensive Resources material already includes a dedicated API section with OWASP API Security Project, OAES Offensive API Exploitation and Security, OWASP API Security Playbook-style resources, vulnerable APIs, and labs such as Tiredful API and vulnerable-api. I’ve refined that list and expanded it with stronger current official sources. 
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
| OWASP API Security Project |
| Official / Free |
| Primary API security reference |
| OWASP API Security Top 10:2023 |
| Official / Free |
| Core API-specific risk model |
| OWASP WSTG API Testing |
| Official / Free |
| API testing methodology |
| PortSwigger API Testing Path |
| Free / Labs |
| Practical API attack-surface discovery and testing |
| REST Security Cheat Sheet |
| Official / Free |
| REST implementation guidance |
| GraphQL Cheat Sheet |
| Official / Free |
| GraphQL security guidance |
| OAuth 2.0 Security BCP |
| Standard |
| Token/authentication security |
| JWT Best Current Practices |
| Standard |
| Secure JWT handling |

[OWASP API Security Project](https://owasp.org/www-project-api-security/)[OWASP API Security Top 10](https://owasp.org/API-Security/)[OWASP WSTG API Testing](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/12-API_Testing/00-API_Testing_Overview)[PortSwigger API Testing Path](https://portswigger.net/web-security/learning-paths/api-testing)[OWASP REST Security Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/REST_Security_Cheat_Sheet.html)[OWASP GraphQL Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/GraphQL_Cheat_Sheet.html)
OWASP’s current official API risk list is still API Security Top 10:2023. It includes BOLA, Broken Authentication, Broken Object Property Level Authorization, Unrestricted Resource Consumption, BFLA, Sensitive Business Flows, SSRF, Security Misconfiguration, Improper Inventory Management and Unsafe Consumption of APIs. ( [OWASP Developer Guide](https://devguide.owasp.org/en/07-training-education/07-api-top-ten/))

---

## Section 02: Methodology <a name="section-02"></a>

Primary methodology sources 
OWASP API Security Top 10 
OWASP WSTG API Testing 
OWASP API Security Testing Framework 
PortSwigger API Testing 
OWASP ASVS 
PTES 
NIST SP 800-115 
[OWASP API Testing Overview](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/12-API_Testing/00-API_Testing_Overview)[OWASP API Security Testing Framework](https://owasp.org/www-project-api-security-testing-framework/)[OWASP ASVS](https://owasp.org/www-project-application-security-verification-standard/)[PTES](http://www.pentest-standard.org/)
OWASP's current WSTG explicitly includes API testing and discusses REST-style APIs alongside GraphQL and other API technologies. ( [OWASP Foundation](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/12-API_Testing/00-API_Testing_Overview)) 

#### Recommended API Security Testing Workflow 
Authorization / Scope 

→ ↓ API Inventory 

→ ↓ Documentation Discovery 

→ ↓ Endpoint Discovery 

→ ↓ Technology Identification 

→ ↓ Authentication Analysis 

→ ↓ Authorization Analysis 

→ ↓ Object-Level Access Testing 

→ ↓ Property-Level Access Testing 

→ ↓ Function-Level Access Testing 

→ ↓ Input Validation 

→ ↓ Rate Limiting / Resource Controls 

→ ↓ Business Logic Testing 

→ ↓ SSRF / Backend Interaction 

→ ↓ Token / OAuth / JWT Testing 

→ ↓ GraphQL / gRPC / WebSocket Testing 

→ ↓ API Version / Shadow API Discovery 

→ ↓ Third-Party API Trust Testing 

→ ↓ Security Configuration Review 

→ ↓ Risk Rating 

→ ↓ Reporting 

→ ↓ Retest 

> Priority: ⭐⭐⭐

---

## Section 03: Standards / Compliance <a name="section-03"></a>

| Standard / Framework | Coverage |
| --- | --- |
| OWASP API Security Top 10 |
| API-specific risk awareness |
| OWASP ASVS |
| Application/API verification requirements |
| OWASP WSTG API Testing |
| Testing methodology |
| OWASP REST Security Cheat Sheet |
| Secure REST API design |
| OAuth 2.0 Security BCP |
| OAuth security |
| JWT BCP – RFC 8725 |
| JWT implementation |
| OpenAPI Specification |
| API contract/specification |
| NIST SSDF SP 800-218 |
| Secure software development |
| PCI DSS |
| APIs handling payment data |
| ISO/IEC 27001 |
| Security management |
| CWE |
| Weakness classification |

[RFC 8725 JWT Best Practices](https://www.rfc-editor.org/rfc/rfc8725)[OpenAPI Specification](https://spec.openapis.org/oas/latest.html)[NIST SSDF SP 800-218](https://csrc.nist.gov/pubs/sp/800/218/final)[CWE Database](https://cwe.mitre.org/)

---

## Section 04: Official Documentation <a name="section-04"></a>

OWASP 
API Security Project 
API Top 10 
REST Security Cheat Sheet 
GraphQL Cheat Sheet 
Authentication Cheat Sheet 
Authorization Cheat Sheet 
OAuth Cheat Sheet 
JWT guidance 
API Security Testing Framework 
[OWASP API Security](https://owasp.org/API-Security/)[OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/)[OWASP ASTF](https://owasp.org/www-project-api-security-testing-framework/)
Specifications 
OpenAPI 
GraphQL 
OAuth 
OIDC 
gRPC 
JSON Schema 
[OpenAPI Initiative](https://www.openapis.org/)[GraphQL Specification](https://spec.graphql.org/)[OAuth Specifications](https://oauth.net/2/)[OpenID Connect](https://openid.net/developers/how-connect-works/)[gRPC Documentation](https://grpc.io/docs/)[JSON Schema](https://json-schema.org/)

---

## Section 05: Checklists <a name="section-05"></a>

Best checklist sources: 
OWASP API Security Top 10 
OWASP WSTG 
OWASP ASVS 
REST Security Cheat Sheet 
GraphQL Security Cheat Sheet 
OAuth Security Cheat Sheet 
HackTricks API testing notes 
[OWASP REST Security Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/REST_Security_Cheat_Sheet.html)[OWASP GraphQL Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/GraphQL_Cheat_Sheet.html)[HackTricks API Pentesting](https://book.hacktricks.wiki/en/network-services-pentesting/pentesting-web/index.html)

#### Recommended API checklist 
API inventory 
API versions 
Deprecated APIs 
Shadow APIs 
Documentation exposure 
OpenAPI/Swagger exposure 
Authentication 
API keys 
JWT 
OAuth 
OIDC 
Object authorization 
Property authorization 
Function authorization 
Mass assignment 
Rate limits 
Resource consumption 
Business flows 
SSRF 
Injection 
Schema validation 
HTTP methods 
Content types 
CORS 
TLS 
Error handling 
Sensitive data 
Pagination 
Batch requests 
GraphQL introspection 
GraphQL depth/complexity 
gRPC 
WebSockets 
Third-party APIs 
Logging 
Monitoring 
Secrets 
API gateway configuration

---

## Section 06: Cheat Sheets <a name="section-06"></a>

| Resource | Focus |
| --- | --- |
| OWASP REST Security Cheat Sheet |
| REST APIs |
| OWASP GraphQL Cheat Sheet |
| GraphQL |
| OWASP OAuth2 Cheat Sheet |
| OAuth |
| OWASP JWT guidance |
| Tokens |
| PayloadsAllTheThings API sections |
| Test inputs |
| HackTricks API notes |
| Pentest reference |
| 42Crunch API Top 10 Cheat Sheet |
| API risk reference |

[OWASP REST Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/REST_Security_Cheat_Sheet.html)[OAuth2 Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/OAuth2_Cheat_Sheet.html)[JWT Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/JSON_Web_Token_for_Java_Cheat_Sheet.html)[PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)

---

## Section 07: Tools <a name="section-07"></a>

Interception / Manual Testing 

| Tool | Purpose |
| --- | --- |
| ⭐⭐⭐ Burp Suite |
| HTTP/API testing |
| ⭐⭐⭐ Postman |
| API interaction and collections |
| ⭐⭐⭐ Insomnia |
| API client |
| ⭐⭐⭐ OWASP ZAP |
| Proxy/API scanning |
| ⭐⭐ Caido |
| Modern proxy |
| ⭐⭐ mitmproxy |
| Scriptable proxy |

[Burp Suite](https://portswigger.net/burp)[Postman](https://www.postman.com/)[Insomnia](https://insomnia.rest/)[OWASP ZAP](https://www.zaproxy.org/)
API Security-Specific Tools 
OWASP API Security Testing Framework 
Schemathesis 
RESTler 
Kiterunner 
Arjun 
Nuclei 
InQL 
GraphQL Cop 
Clairvoyance 
grpcurl 
jwt_tool 
[OWASP ASTF](https://owasp.org/www-project-api-security-testing-framework/)[Schemathesis GitHub](https://github.com/schemathesis/schemathesis)[Microsoft RESTler](https://github.com/microsoft/restler-fuzzer)[Kiterunner](https://github.com/assetnote/kiterunner)[Arjun](https://github.com/s0md3v/Arjun)[InQL](https://github.com/doyensec/inql)[GraphQL Cop](https://github.com/dolevf/graphql-cop)[grpcurl](https://github.com/fullstorydev/grpcurl)[jwt_tool](https://github.com/ticarpi/jwt_tool)
OWASP’s ASTF currently advertises 16 automated API security tests covering the API Top 10 plus GraphQL, gRPC, mTLS, LLM/chatbot and general injection scenarios. ( [OWASP Foundation](https://owasp.org/www-project-api-security-testing-framework/))

---

## Section 08: Labs / Practice <a name="section-08"></a>

Your uploaded source already included vulnerable API labs such as Tiredful API, vulnerable-api and websheep. 
For a refined current list: 

| Lab | Level |
| --- | --- |
| ⭐⭐⭐ OWASP crAPI |
| Beginner → Advanced |
| ⭐⭐⭐ PortSwigger API Labs |
| Beginner → Advanced |
| ⭐⭐⭐ VAmPI |
| Beginner → Intermediate |
| ⭐⭐⭐ DVGA |
| GraphQL |
| ⭐⭐ Juice Shop API challenges |
| Beginner → Intermediate |
| ⭐⭐ Damn Vulnerable GraphQL Application |
| GraphQL |
| ⭐⭐ HTB API-focused labs |
| Intermediate |

[OWASP crAPI](https://owasp.org/www-project-crapi/)[crAPI GitHub](https://github.com/OWASP/crAPI)[VAmPI GitHub](https://github.com/erev0s/VAmPI)[DVGA GitHub](https://github.com/dolevf/Damn-Vulnerable-GraphQL-Application)[PortSwigger API Labs](https://portswigger.net/web-security/learning-paths/api-testing)
PortSwigger's current API track includes API recon, documentation discovery, undocumented endpoints, HTTP method manipulation and server-side parameter pollution. ( [PortSwigger](https://portswigger.net/web-security/learning-paths/api-testing))

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

Use only in authorized environments. 
Resource collections 
PayloadsAllTheThings 
SecLists 
FuzzDB 
Nuclei Templates 
RESTler test generation 
Schemathesis schema-driven tests 
[PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)[SecLists](https://github.com/danielmiessler/SecLists)[FuzzDB](https://github.com/fuzzdb-project/fuzzdb)[Nuclei Templates](https://github.com/projectdiscovery/nuclei-templates)
Test categories should include: 
BOLA 
BFLA 
BOPLA 
Mass assignment 
JWT validation 
OAuth authorization 
Rate limiting 
Resource exhaustion 
Schema bypass 
Method tampering 
Content-Type confusion 
SSRF 
Injection 
GraphQL introspection 
GraphQL batching 
GraphQL depth 
Version bypass 
Deprecated endpoint access 
Sensitive business flows 
Third-party API trust

---

## Section 10: YouTube / Video <a name="section-10"></a>

#### Recommended channels/resources: 
OWASP 
PortSwigger 
APIsec University 
42Crunch 
Black Hat 
DEF CON 
HackerOne 
NahamSec 
[OWASP YouTube](https://www.youtube.com/@OWASPGLOBAL)[PortSwigger YouTube](https://www.youtube.com/@PortSwigger)[Black Hat YouTube](https://www.youtube.com/@BlackHatOfficialYT)[DEF CON YouTube](https://www.youtube.com/@DEFCONConference)

#### Recommended video topics: 
API recon 
BOLA / IDOR 
BFLA 
JWT attacks 
OAuth security 
GraphQL testing 
gRPC security 
REST API testing 
API gateway security 
Shadow APIs 
API fuzzing

---

## Section 11: Courses / Training <a name="section-11"></a>

| Course | Level |
| --- | --- |
| ⭐⭐⭐ PortSwigger API Testing Path |
| Beginner → Practitioner |
| ⭐⭐⭐ APIsec University |
| Beginner → Advanced |
| ⭐⭐⭐ HTB API-focused modules |
| Hands-on |
| ⭐⭐ SANS SEC542 |
| Web/API |
| ⭐⭐ OffSec WEB-200/300 |
| Web/API crossover |
| ⭐⭐ PentesterLab API exercises |
| Practical |

[PortSwigger API Testing](https://portswigger.net/web-security/learning-paths/api-testing)[APIsec University](https://www.apisecuniversity.com/)[PentesterLab](https://pentesterlab.com/)

---

## Section 12: Certifications <a name="section-12"></a>

API-security-only certifications are less common, so use a mix of dedicated and AppSec credentials: 

| Certification | Focus |
| --- | --- |
| APIsec Certified Expert / APIsec University credentials |
| API security |
| BSCP |
| Burp/API/web testing |
| OSWE |
| Advanced web/API security |
| GWAPT |
| Web/API pentesting |
| HTB CWES/CWEE |
| Web/API exploitation |
| eWPT/eWPTX |
| Web/API security |

[Burp Suite Certified Practitioner](https://portswigger.net/web-security/certification)[GIAC GWAPT](https://www.giac.org/certifications/web-application-penetration-tester-gwapt/)

---

## Section 13: Books <a name="section-13"></a>

#### Recommended API security books: 

| Book | Focus |
| --- | --- |
| ⭐⭐⭐ Hacking APIs — Corey Ball |
| Practical API pentesting |
| ⭐⭐⭐ API Security in Action — Neil Madden |
| Defensive API architecture |
| ⭐⭐⭐ Black Hat GraphQL |
| GraphQL security |
| ⭐⭐ OAuth 2 in Action |
| OAuth |
| ⭐⭐ Microservices Security in Action |
| Microservices/API security |
| ⭐⭐ Web Application Hacker's Handbook |
| Web/API foundations |

[Hacking APIs – No Starch Press](https://nostarch.com/hacking-apis)[API Security in Action – Manning](https://www.manning.com/books/api-security-in-action)[Black Hat GraphQL – No Starch Press](https://nostarch.com/black-hat-graphql)

---

## Section 14: Blogs / Articles <a name="section-14"></a>

Top API-security research sources: 
PortSwigger Research 
Salt Security Research 
42Crunch Blog 
Traceable API Security Blog 
Noname Security Research 
Wallarm Research 
Cequence Research 
Assetnote 
Doyensec 
ProjectDiscovery 
[PortSwigger Research](https://portswigger.net/research)[42Crunch Blog](https://42crunch.com/blog/)[Assetnote Research](https://www.assetnote.io/resources/research)[Doyensec Blog](https://blog.doyensec.com/)[ProjectDiscovery Blog](https://projectdiscovery.io/blog)

---

## Section 15: Research Papers <a name="section-15"></a>

Track: 
USENIX Security 
IEEE S&P 
ACM CCS 
NDSS 
Black Hat whitepapers 
OWASP research 
OAuth Security Workshop 
[USENIX Security](https://www.usenix.org/conferences/byname/108)[IEEE Security & Privacy](https://www.ieee-security.org/TC/SP-Index.html)[NDSS Papers](https://www.ndss-symposium.org/ndss-paper/)
Research areas: 
BOLA automation 
API authorization models 
OAuth attacks 
JWT security 
GraphQL abuse 
API schema fuzzing 
REST API fuzzing 
Shadow APIs 
API discovery 
Microservice trust boundaries 
API gateway bypass 
gRPC security 
Server-side parameter pollution

---

## Section 16: White Papers <a name="section-16"></a>

#### Recommended: 
OWASP API Security Top 10 
OWASP API Security Project documentation 
NIST SSDF 
42Crunch State of API Security 
Salt Labs reports 
API gateway security whitepapers 
OAuth Security BCP 
[OWASP API Security Top 10](https://owasp.org/API-Security/)[NIST SSDF](https://csrc.nist.gov/pubs/sp/800/218/final)[42Crunch State of API Security](https://42crunch.com/42crunch-publishes-state-of-api-security-2026/)
A 2026 42Crunch report highlighted authorization failures, input-processing issues and missing authentication as continuing major production API risks. Treat it as vendor research, but it is useful for tracking real-world trends. ( [42Crunch](https://42crunch.com/42crunch-publishes-state-of-api-security-2026/))

---

## Section 17: Conference Material <a name="section-17"></a>

| Conference | Relevant Focus |
| --- | --- |
| OWASP Global AppSec |
| API/AppSec |
| Black Hat |
| API exploitation |
| DEF CON |
| API research |
| OAuth Security Workshop |
| OAuth/OIDC |
| USENIX Security |
| Research |
| Nullcon |
| Offensive API security |
| BSides |
| Community research |

[OWASP Events](https://owasp.org/events/)[Black Hat](https://www.blackhat.com/)[DEF CON](https://defcon.org/)[OAuth Security Workshop](https://oauth.secworkshop.events/)

---

## Section 18: Mind Maps <a name="section-18"></a>

#### Recommended website mind-map structure: 
API SECURITY 

```
│
```

```
├── Discovery
```

```
│   ├── API Inventory
```

```
│   ├── OpenAPI / Swagger
```

```
│   ├── Shadow APIs
```

```
│   └── Deprecated APIs
```

```
│
```

```
├── Authentication
```

```
│   ├── API Keys
```

```
│   ├── JWT
```

```
│   ├── OAuth
```

```
│   ├── OIDC
```

```
│   └── mTLS
```

```
│
```

```
├── Authorization
```

```
│   ├── BOLA
```

```
│   ├── BOPLA
```

```
│   └── BFLA
```

```
│
```

```
├── Business Logic
```

```
│   └── Sensitive Business Flows
```

```
│
```

```
├── Input Handling
```

```
│   ├── Injection
```

```
│   ├── Mass Assignment
```

```
│   ├── SSRF
```

```
│   └── Schema Bypass
```

```
│
```

```
├── Resource Controls
```

```
│   ├── Rate Limiting
```

```
│   └── Resource Consumption
```

```
│
```

```
├── API Technologies
```

```
│   ├── REST
```

```
│   ├── GraphQL
```

```
│   ├── gRPC
```

```
│   ├── SOAP
```

```
│   └── WebSockets
```

```
│
```

```
├── Inventory
```

```
│   ├── Versions
```

```
│   ├── Documentation
```

```
│   └── Shadow APIs
```

```
│
```

```
└── Supply Chain
```

```
    └── Third-Party APIs
```

---

## Section 19: Sample Reports <a name="section-19"></a>

Useful reference sources: 
OWASP WSTG reporting 
HackerOne disclosures 
Bugcrowd disclosures 
public pentest reports 
PortSwigger reports/research 
[OWASP WSTG Reporting](https://owasp.org/www-project-web-security-testing-guide/stable/5-Reporting/)[HackerOne Hacktivity](https://hackerone.com/hacktivity)[Public Pentest Reports GitHub](https://github.com/juliocesarfort/public-pentesting-reports)

#### Recommended API report structure: 
Executive Summary 
Scope 
API Inventory 
Architecture 
Authentication 
Authorization 
Object Access 
Business Logic 
Resource Controls 
Input Validation 
API Versions 
GraphQL/gRPC/WebSocket Review 
Third-Party Integrations 
Findings 
OWASP API Top 10 Mapping 
CWE 
CVSS 
Evidence 
Remediation 
Retest 
Conclusion

---

## Section 20: Templates <a name="section-20"></a>

#### Recommended GitHub structure: 
/templates/api-security/ 

```
├── api-security-test-plan.md
```

```
├── api-test-cases.md
```

```
├── api-inventory-template.md
```

```
├── rest-api-checklist.md
```

```
├── graphql-checklist.md
```

```
├── grpc-checklist.md
```

```
├── jwt-testing.md
```

```
├── oauth-testing.md
```

```
├── authorization-testing.md
```

```
├── rate-limit-testing.md
```

```
├── evidence-template.md
```

```
├── api-pentest-report.md
```

```
└── api-top10-mapping.md
```

#### Recommended fields: 
Test ID 
API Name 
Endpoint 
Method 
Version 
Role 
Authentication 
Object Identifier 
Parameter 
Test Objective 
Procedure 
Expected Result 
Actual Result 
Evidence 
OWASP API Category 
CWE 
CVSS 
Severity 
Status

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

Primary sources: 
CVE.org 
NIST NVD 
CISA KEV 
CWE 
HackerOne Hacktivity 
PortSwigger Research 
[CVE.org](https://www.cve.org/)[NVD](https://nvd.nist.gov/)[CISA KEV](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)[MITRE CWE](https://cwe.mitre.org/)
Particularly track: 
Broken access control 
IDOR / BOLA 
Missing authentication 
JWT validation flaws 
OAuth misconfiguration 
SSRF 
Mass assignment 
GraphQL authorization 
API gateway bypass 
Rate-limit bypass 
Shadow APIs 
Third-party API compromise

---

## Section 22: GitHub Repositories <a name="section-22"></a>

#### Essential 

- ⭐⭐⭐ OWASP crAPI 
- ⭐⭐⭐ OWASP API Security Testing Framework 
- ⭐⭐⭐ Schemathesis 
- ⭐⭐⭐ RESTler 
- ⭐⭐⭐ VAmPI 
- ⭐⭐⭐ DVGA 
- ⭐⭐⭐ Kiterunner 
- ⭐⭐ InQL 
- ⭐⭐ GraphQL Cop 
- ⭐⭐ jwt_tool 
- ⭐⭐ Nuclei 
- ⭐⭐ SecLists [OWASP crAPI GitHub](https://github.com/OWASP/crAPI)[OWASP ASTF GitHub](https://github.com/OWASP/www-project-api-security-testing-framework)[Schemathesis](https://github.com/schemathesis/schemathesis)[RESTler](https://github.com/microsoft/restler-fuzzer)[VAmPI](https://github.com/erev0s/VAmPI)[DVGA](https://github.com/dolevf/Damn-Vulnerable-GraphQL-Application)[Kiterunner](https://github.com/assetnote/kiterunner)

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

API security is better served by OpenAPI specifications, request collections and intentionally vulnerable APIs than generic PCAP datasets. 
Useful resources: 
OWASP crAPI 
VAmPI 
DVGA 
Swagger Petstore 
OpenAPI example specs 
Postman public collections 
RESTler sample APIs 
[Swagger Petstore](https://petstore.swagger.io/)[OpenAPI Examples](https://github.com/OAI/OpenAPI-Specification/tree/main/examples)[Postman Public API Network](https://www.postman.com/explore)

---

## Section 24: Communities / Forums <a name="section-24"></a>

OWASP API Security 
PortSwigger Community 
APIsec University 
HackerOne 
Bugcrowd 
Security Stack Exchange 
r/netsec 
r/bugbounty 
[OWASP API Security Project](https://owasp.org/www-project-api-security/)[PortSwigger Community](https://forum.portswigger.net/)[Security Stack Exchange](https://security.stackexchange.com/)

---

## Section 25: Vendors / Products <a name="section-25"></a>

| Category | Examples |
| --- | --- |
| API Security Testing |
| 42Crunch, Salt Security, Traceable, Wallarm |
| API Discovery / Posture |
| Noname, Salt, Traceable, Cequence |
| API Gateway |
| Kong, Apigee, AWS API Gateway, Azure API Management |
| WAF/API Protection |
| Cloudflare, Akamai, Imperva |
| Developer testing |
| Postman, Insomnia, Burp Suite |
| Open Source |
| ZAP, Schemathesis, RESTler, crAPI |

OWASP itself separates API tooling conceptually into areas such as security posture/inventory, runtime security and API testing, which is a useful way to organize this vendor section. ( [OWASP Foundation](https://owasp.org/www-community/api_security_tools))

---

## Section 26: Latest Developments <a name="section-26"></a>

For a public repository, link to living feeds: 
OWASP API Security Project 
OWASP WSTG Latest 
PortSwigger Research 
42Crunch Research 
Salt Labs 
CISA KEV 
OAuth Security Workshop 
Current important API-security topics: 
BOLA / BFLA 
Shadow APIs 
Zombie APIs 
API inventory 
Machine-to-machine APIs 
GraphQL 
gRPC 
OAuth 2.1 
JWT hardening 
mTLS 
API gateways 
API supply chain 
Third-party API trust 
LLM APIs 
Agentic APIs 
AI tool/API authorization 
Server-side parameter pollution 
Schema-driven fuzzing 
OWASP's newer API Security Testing Framework is notable because it explicitly adds tests beyond traditional REST, including GraphQL, gRPC, mutual TLS and LLM/chatbot API scenarios. ( [OWASP Foundation](https://owasp.org/www-project-api-security-testing-framework/))

---

## Section 27: Learning Roadmap <a name="section-27"></a>

```
LEVEL 1 — API Fundamentals
```
HTTP 
JSON 
XML 
REST 
SOAP 
OpenAPI 
Status codes 
Headers 

→ ↓ 
```
LEVEL 2 — API Clients
```
curl 
Postman 
Insomnia 
Burp Suite 

→ ↓ 
```
LEVEL 3 — API Discovery
```
Swagger/OpenAPI 
Endpoint discovery 
API versions 
Shadow APIs 
Parameter discovery 

→ ↓ 
```
LEVEL 4 — Authentication
```
API keys 
Basic/Bearer 
JWT 
OAuth 
OIDC 
mTLS 

→ ↓ 
```
LEVEL 5 — Authorization
```
BOLA 
BOPLA 
BFLA 
Horizontal escalation 
Vertical escalation 

→ ↓ 
```
LEVEL 6 — Input Validation
```
Injection 
Mass assignment 
Schema manipulation 
Content-Type confusion 

→ ↓ 
```
LEVEL 7 — Resource Security
```
Rate limits 
Resource exhaustion 
Pagination 
Batching 

→ ↓ 
```
LEVEL 8 — Business Logic
```
Sensitive business flows 
Workflow bypass 
Race conditions 

→ ↓ 
```
LEVEL 9 — Server-Side
```
SSRF 
Internal APIs 
Backend trust 
Third-party APIs 

→ ↓ 
```
LEVEL 10 — GraphQL
```
Introspection 
Authorization 
Depth 
Complexity 
Batching 

→ ↓ 
```
LEVEL 11 — gRPC / WebSockets
```
Protobuf 
grpcurl 
Streaming 
Authorization 

→ ↓ 
```
LEVEL 12 — Automation
```
Schemathesis 
RESTler 
Nuclei 
ASTF 
Kiterunner 

→ ↓ 
```
LEVEL 13 — DevSecOps
```
OpenAPI linting 
Schema validation 
CI/CD API testing 
API inventory 

→ ↓ 
```
LEVEL 14 — Standards
```
OWASP API Top 10 
WSTG 
ASVS 
OAuth BCP 
JWT BCP 
NIST SSDF 

→ ↓ 
```
LEVEL 15 — Reporting
```
OWASP API mapping 
CWE 
CVSS 
Evidence 
Remediation 
Retest 

- ⭐ API Security — Top 15 
| Rank | Resource | Purpose |
| --- | --- | --- |
| 1 |
| OWASP API Security Top 10 |
| Risk model |
| 2 |
| OWASP WSTG API Testing |
| Methodology |
| 3 |
| PortSwigger API Testing |
| Hands-on labs |
| 4 |
| OWASP crAPI |
| Practical vulnerable API |
| 5 |
| Burp Suite |
| Manual testing |
| 6 |
| OWASP REST Security Cheat Sheet |
| Defensive reference |
| 7 |
| Schemathesis |
| Schema-based testing |
| 8 |
| Microsoft RESTler |
| Stateful API fuzzing |
| 9 |
| Kiterunner |
| API discovery |
| 10 |
| VAmPI |
| Practice |
| 11 |
| DVGA |
| GraphQL practice |
| 12 |
| jwt_tool |
| JWT analysis |
| 13 |
| OWASP ASTF |
| Automated API assessment |
| 14 |
| API Security in Action |
| Defensive architecture |
| 15 |
| Hacking APIs |
| Practical learning |

#### Recommended practical stack 
HTTP/REST fundamentals → OpenAPI/Swagger → Burp/Postman → OWASP API Top 10 → crAPI → BOLA/BOPLA/BFLA → JWT/OAuth → rate-limit/business-flow testing → GraphQL/gRPC → Schemathesis/RESTler → API inventory/shadow API detection → OWASP/NIST mapping → professional API security report.

---

<div align="center">
<sub>🔗 API Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>