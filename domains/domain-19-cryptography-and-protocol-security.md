# 🔒 Domain 19: Cryptography & Protocol Security

> **Group:** Exploitation, RE, Malware & Systems  
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

- ⭐⭐⭐ [NIST Cryptographic Standards and Guidelines](https://csrc.nist.gov/projects/cryptographic-standards-and-guidelines)⭐⭐⭐ [IETF RFC Editor](https://www.rfc-editor.org/)⭐⭐⭐ [Cryptographic Forum Research Group](https://irtf.org/cfrg)Learn: 
Entropy 
PRNG 
Hashing 
MAC 
Symmetric crypto 
Public-key crypto 
Signatures 
Key exchange 
KDF 
AEAD 
PKI 
Certificates 
TLS 
SSH 
IPsec 
Kerberos 
PQC

---

## Section 02: Methodology <a name="section-02"></a>

Protocol state machine → threat model → algorithms → key lifecycle → randomness → authentication → replay → downgrade → implementation → side channels.

---

## Section 03: Standards / Compliance <a name="section-03"></a>

FIPS 140-3 · FIPS 186-5 · FIPS 197 · SP 800-56 · SP 800-57 · TLS · IPsec · SSH · PKIX.

---

## Section 04: Official Documentation <a name="section-04"></a>

NIST · RFC Editor · IETF · OpenSSL docs · BoringSSL.

---

## Section 05: Checklists <a name="section-05"></a>

Weak algorithms, key size, key reuse, nonce reuse, certificate validation, forward secrecy, replay, downgrade, randomness and key storage.

---

## Section 06: Cheat Sheets <a name="section-06"></a>

OWASP Cryptographic Storage Cheat Sheet · TLS Cheat Sheet · OpenSSL CLI.

---

## Section 07: Tools <a name="section-07"></a>

OpenSSL · testssl.sh · sslyze · Wireshark · Scapy · Cryptool · SageMath.

---

## Section 08: Labs / Practice <a name="section-08"></a>

Cryptopals · CryptoHack · Cryptohack Academy-style challenges.

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

Padding, nonce reuse, IV handling, certificate validation, downgrade, replay, weak suites and protocol-state errors.

---

## Section 10: YouTube / Video <a name="section-10"></a>

> Source combines sections 10–12: Training / Certifications

Cryptopals · CryptoHack · Coursera crypto courses · IACR schools.

---

## Section 11: Courses / Training <a name="section-11"></a>

> Source combines sections 10–12: Training / Certifications

Cryptopals · CryptoHack · Coursera crypto courses · IACR schools.

---

## Section 12: Certifications <a name="section-12"></a>

> Source combines sections 10–12: Training / Certifications

Cryptopals · CryptoHack · Coursera crypto courses · IACR schools.

---

## Section 13: Books <a name="section-13"></a>

- ⭐⭐⭐ Serious Cryptography ⭐⭐⭐ Cryptography Engineering ⭐⭐⭐ Real-World Cryptography ⭐⭐ Applied Cryptography

---

## Section 14: Blogs / Articles <a name="section-14"></a>

> Source combines sections 14–17: Research

IACR ePrint · CRYPTO · EUROCRYPT · CHES · Real World Crypto · USENIX.

---

## Section 15: Research Papers <a name="section-15"></a>

> Source combines sections 14–17: Research

IACR ePrint · CRYPTO · EUROCRYPT · CHES · Real World Crypto · USENIX.

---

## Section 16: White Papers <a name="section-16"></a>

> Source combines sections 14–17: Research

IACR ePrint · CRYPTO · EUROCRYPT · CHES · Real World Crypto · USENIX.

---

## Section 17: Conference Material <a name="section-17"></a>

> Source combines sections 14–17: Research

IACR ePrint · CRYPTO · EUROCRYPT · CHES · Real World Crypto · USENIX.

---

## Section 18: Mind Maps <a name="section-18"></a>

Primitives → protocols → PKI → implementation → side channels → PQC.

---

## Section 19: Sample Reports <a name="section-19"></a>

> Source combines sections 19–20: Reports / Templates

Algorithm inventory, key management, protocol flows, implementation findings and standards mapping.

---

## Section 20: Templates <a name="section-20"></a>

> Source combines sections 19–20: Reports / Templates

Algorithm inventory, key management, protocol flows, implementation findings and standards mapping.

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

Heartbleed, POODLE, BEAST, Lucky13, ROBOT and protocol downgrade families.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

testssl.sh · sslscan · TLS-Attacker · cryptography Python library.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

TLS PCAPs, RFC test vectors, NIST CAVP vectors.

---

## Section 24: Communities / Forums <a name="section-24"></a>

> Source combines sections 24–25: Communities / Vendors

IACR · CFRG · NIST · OpenSSL · Cloudflare research.

---

## Section 25: Vendors / Products <a name="section-25"></a>

> Source combines sections 24–25: Communities / Vendors

IACR · CFRG · NIST · OpenSSL · Cloudflare research.

---

## Section 26: Latest Developments <a name="section-26"></a>

This category needs a major PQC subsection. NIST has finalized FIPS 203, 204 and 205 for ML-KEM, ML-DSA and SLH-DSA; HQC was also selected for future standardization. ( [NIST Computer Security Resource Center](https://csrc.nist.gov/Projects/post-quantum-cryptography)) 
Also note an important 2026 documentation update: RFC 9846 now specifies TLS 1.3 and obsoletes RFC 8446. ( [RFC Editor](https://www.rfc-editor.org/info/rfc9846/))

---

## Section 27: Learning Roadmap <a name="section-27"></a>

Math basics → symmetric crypto → hashes/MAC → public key → PKI → TLS → protocol attacks → implementations → side channels → PQC.

---

<div align="center">
<sub>🔒 Cryptography & Protocol Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>