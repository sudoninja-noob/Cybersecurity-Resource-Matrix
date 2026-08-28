# ⚛️ Domain 43: Quantum & Post-Quantum Cryptography Security

> **Group:** Governance, Privacy & Assurance  
> **Curated links:** 7  
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

- ⭐⭐⭐ [NIST Post-Quantum Cryptography Project](https://csrc.nist.gov/projects/post-quantum-cryptography)⭐⭐⭐ [NIST PQC Overview](https://www.nist.gov/pqc)⭐⭐⭐ FIPS 203 — ML-KEM ⭐⭐⭐ FIPS 204 — ML-DSA ⭐⭐⭐ FIPS 205 — SLH-DSA ⭐⭐ IETF PQC work ⭐⭐ Open Quantum Safe NIST's three finalized PQC standards are already ready for deployment: ML-KEM, ML-DSA and SLH-DSA. Falcon is planned for FIPS 206, and HQC was selected for future standardization in 2025. ( [NIST Computer Security Resource Center](https://csrc.nist.gov/Projects/Post-Quantum-Cryptography/Post_Quantum_Cryptography-Standardization))

---

## Section 02: Methodology <a name="section-02"></a>

Cryptographic Inventory 
→ Identify RSA/ECC/DH 
→ Data Lifetime Analysis 
→ Harvest-Now-Decrypt-Later Risk 
→ Crypto-Agility 
→ PQC Compatibility 
→ Performance Testing 
→ Hybrid Migration 
→ Key/Certificate Migration 
→ Verification

---

## Section 03: Standards / Compliance <a name="section-03"></a>

- ⭐⭐⭐ FIPS 203 ML-KEM 
- ⭐⭐⭐ FIPS 204 ML-DSA 
- ⭐⭐⭐ FIPS 205 SLH-DSA Future FIPS 206 Falcon 
HQC forthcoming 
NSA CNSA 2.0 
IETF PQC/hybrid protocol standards

---

## Section 04: Official Documentation <a name="section-04"></a>

[NIST PQC Standardization](https://csrc.nist.gov/Projects/Post-Quantum-Cryptography/Post_Quantum_Cryptography-Standardization)[NIST PQC Migration Project](https://www.nccoe.nist.gov/projects/building-blocks/post-quantum-cryptography)

---

## Section 05: Checklists <a name="section-05"></a>

RSA inventory 
ECC inventory 
DH inventory 
Certificates 
VPN 
TLS 
SSH 
Code signing 
Firmware signing 
HSM 
PKI 
Data retention 
Protocol support 
PQC algorithms 
Hybrid mode 
Performance 
Crypto agility

---

## Section 06: Cheat Sheets <a name="section-06"></a>

ML-KEM parameters · ML-DSA parameters · OpenSSL algorithm listing · OQS algorithm tables.

---

## Section 07: Tools <a name="section-07"></a>

- ⭐⭐⭐ Open Quantum Safe liboqs ⭐⭐⭐ OQS-OpenSSL provider ⭐⭐ OpenSSL ⭐⭐ BoringSSL experimental PQC ⭐⭐ Wireshark ⭐⭐ Botan

---

## Section 08: Labs / Practice <a name="section-08"></a>

OQS TLS lab · PQC certificate lab · hybrid TLS tests · performance benchmarking.

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

Algorithm negotiation · key-size handling · signature verification · downgrade resistance · certificate compatibility · resource consumption.

---

## Section 10: YouTube / Video <a name="section-10"></a>

NIST PQC · IACR · Real World Crypto · PQCrypto conference.

---

## Section 11: Courses / Training <a name="section-11"></a>

Quantum computing fundamentals · lattice cryptography · IACR schools · NIST PQC migration workshops.

---

## Section 12: Certifications <a name="section-12"></a>

No dominant PQC-specific security credential yet.

---

## Section 13: Books <a name="section-13"></a>

Post-Quantum Cryptography An Introduction to Mathematical Cryptography lattice-cryptography references.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

NIST · Cloudflare Research · Google Security · AWS Cryptography · Microsoft Research.

---

## Section 15: Research Papers <a name="section-15"></a>

IACR ePrint · CRYPTO · EUROCRYPT · PQCrypto · CHES.

---

## Section 16: White Papers <a name="section-16"></a>

NIST migration guidance · NSA CNSA 2.0 · industry crypto-agility papers.

---

## Section 17: Conference Material <a name="section-17"></a>

Real World Crypto · CRYPTO · EUROCRYPT · PQCrypto · CHES.

---

## Section 18: Mind Maps <a name="section-18"></a>

Quantum Security 

```
├── Quantum Algorithms
```

```
│   ├── Shor
```

```
│   └── Grover
```

```
├── Lattices
```

```
├── Hash-Based
```

```
├── Code-Based
```

```
├── ML-KEM
```

```
├── ML-DSA
```

```
├── SLH-DSA
```

```
├── HQC
```

```
└── Migration
```

---

## Section 19: Sample Reports <a name="section-19"></a>

Crypto inventory · quantum-risk assessment · migration plan · PQC compatibility report.

---

## Section 20: Templates <a name="section-20"></a>

crypto-inventory.md 
pqc-readiness.md 
crypto-agility-plan.md 
pqc-test-plan.md 
pqc-migration-report.md

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

Harvest-now-decrypt-later risk · protocol migration · certificate/PQC interoperability studies.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

liboqs · oqs-provider · PQClean · Botan.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

NIST algorithm vectors · KATs · PQC benchmark results.

---

## Section 24: Communities / Forums <a name="section-24"></a>

NIST PQC · IACR · Open Quantum Safe · CFRG.

---

## Section 25: Vendors / Products <a name="section-25"></a>

Thales · Entrust · DigiCert · Cloudflare · IBM · AWS · Microsoft · PQC-focused vendors.

---

## Section 26: Latest Developments <a name="section-26"></a>

A notable 2026 development: a vulnerability was found in HAWK, a candidate signature scheme, and it was withdrawn from consideration. NIST explicitly states this does not affect finalized ML-KEM or ML-DSA standards. ( [NIST](https://www.nist.gov/pqc)) 
NIST's migration FAQ was updated in June 2026 and tells users of public-key cryptography to begin becoming PQC-ready now. ( [NIST Pages](https://pages.nist.gov/nccoe-migration-post-quantum-cryptography/))

---

## Section 27: Learning Roadmap <a name="section-27"></a>

Classical crypto → quantum computing basics → Shor/Grover → lattice crypto → ML-KEM → ML-DSA → SLH-DSA → hybrid protocols → enterprise migration.

---

<div align="center">
<sub>⚛️ Quantum & Post-Quantum Cryptography Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>