# 🌍 Domain 36: DNS / PKI / Certificate Security

> **Group:** Network, Web & Application  
> **Curated links:** 5  
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

- ⭐⭐⭐ DNSSEC ⭐⭐⭐ X.509 / PKIX ⭐⭐⭐ TLS ⭐⭐⭐ Certificate Transparency ⭐⭐⭐ ACME ⭐⭐ DANE [IANA DNSSEC Information](https://www.iana.org/dnssec)[RFC 8555 — ACME](https://www.rfc-editor.org/rfc/rfc8555.html)[RFC 9162 — Certificate Transparency 2.0](https://www.rfc-editor.org/rfc/rfc9162.html)
IANA operates the DNS root KSK and publishes root trust anchors, rollover information and key-ceremony material. ( [IANA](https://www.iana.org/dnssec))

---

## Section 02: Methodology <a name="section-02"></a>

Namespace → authoritative DNS → resolver → DNSSEC → CA hierarchy → issuance → certificate lifecycle → key storage → validation → revocation → transparency → automation.

---

## Section 03: Standards / Compliance <a name="section-03"></a>

DNSSEC RFCs 4033–4035 · PKIX RFC 5280 · ACME RFC 8555 · CT RFC 9162 · DANE RFC 6698 · CAA RFC 8659.

---

## Section 04: Official Documentation <a name="section-04"></a>

IANA · ICANN · IETF · CA/Browser Forum · Let's Encrypt · Certificate Transparency.

---

## Section 05: Checklists <a name="section-05"></a>

zone transfer · recursion · DNSSEC · registrar MFA · registry lock · CAA · certificate expiry · SANs · key size · weak signature · private-key protection · revocation · OCSP · CT monitoring · ACME

---

## Section 06: Cheat Sheets <a name="section-06"></a>

dig · drill · delv · openssl x509/s_client · keytool · certutil.

---

## Section 07: Tools <a name="section-07"></a>

dig · DNSViz · dnsviz CLI · testssl.sh · sslyze · OpenSSL · step-ca · certbot · zlint · crt.sh.

---

## Section 08: Labs / Practice <a name="section-08"></a>

BIND/Unbound DNSSEC lab · step-ca · Smallstep PKI lab · ACME local CA · TLS certificate lab.

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

DNS spoofing resistance · chain validation · expired/revoked certs · hostname checks · weak keys · certificate misissuance monitoring.

---

## Section 10: YouTube / Video <a name="section-10"></a>

> Source combines sections 10–12: Videos / Courses / Certifications

ICANN DNSSEC training · Let's Encrypt documentation · PKI engineering courses.

---

## Section 11: Courses / Training <a name="section-11"></a>

> Source combines sections 10–12: Videos / Courses / Certifications

ICANN DNSSEC training · Let's Encrypt documentation · PKI engineering courses.

---

## Section 12: Certifications <a name="section-12"></a>

> Source combines sections 10–12: Videos / Courses / Certifications

ICANN DNSSEC training · Let's Encrypt documentation · PKI engineering courses.

---

## Section 13: Books <a name="section-13"></a>

Bulletproof TLS and PKI · DNS and BIND · applied PKI references.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

> Source combines sections 14–17: Research

Cloudflare · Let's Encrypt · Google CT · IETF · NDSS · USENIX.

---

## Section 15: Research Papers <a name="section-15"></a>

> Source combines sections 14–17: Research

Cloudflare · Let's Encrypt · Google CT · IETF · NDSS · USENIX.

---

## Section 16: White Papers <a name="section-16"></a>

> Source combines sections 14–17: Research

Cloudflare · Let's Encrypt · Google CT · IETF · NDSS · USENIX.

---

## Section 17: Conference Material <a name="section-17"></a>

> Source combines sections 14–17: Research

Cloudflare · Let's Encrypt · Google CT · IETF · NDSS · USENIX.

---

## Section 18: Mind Maps <a name="section-18"></a>

DNS → DNSSEC → registrar → CA → X.509 → TLS → CT → ACME → DANE → revocation.

---

## Section 19: Sample Reports <a name="section-19"></a>

> Source combines sections 19–20: Reports / Templates

DNS security assessment · PKI architecture review · certificate inventory · crypto-agility plan.

---

## Section 20: Templates <a name="section-20"></a>

> Source combines sections 19–20: Reports / Templates

DNS security assessment · PKI architecture review · certificate inventory · crypto-agility plan.

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

DigiNotar · Comodo CA compromise · certificate misissuance · DNS hijacking incidents.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

certbot · zlint · step-ca · testssl.sh · DNSViz.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

CT logs · DNSSEC measurements · certificate datasets · Rapid7/Internet measurement datasets.

---

## Section 24: Communities / Forums <a name="section-24"></a>

> Source combines sections 24–25: Communities / Vendors

CA/Browser Forum · Let's Encrypt · Sectigo · DigiCert · GlobalSign · ICANN.

---

## Section 25: Vendors / Products <a name="section-25"></a>

> Source combines sections 24–25: Communities / Vendors

CA/Browser Forum · Let's Encrypt · Sectigo · DigiCert · GlobalSign · ICANN.

---

## Section 26: Latest Developments <a name="section-26"></a>

Certificate Transparency v2 is defined by RFC 9162, which superseded RFC 6962 and uses publicly auditable append-only certificate logs to improve detection of misissuance. ( [RFC Editor](https://www.rfc-editor.org/info/rfc9162/)) 
Also track PQC certificates, hybrid key exchange, automated certificate lifecycle and crypto-agility.

---

## Section 27: Learning Roadmap <a name="section-27"></a>

DNS → DNSSEC → cryptography → X.509 → PKIX → TLS → CT → ACME → enterprise PKI → PQC migration.

---

<div align="center">
<sub>🌍 DNS / PKI / Certificate Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>