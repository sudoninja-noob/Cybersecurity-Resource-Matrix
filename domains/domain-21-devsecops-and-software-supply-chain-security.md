# 🚀 Domain 21: DevSecOps & Software Supply Chain Security

> **Group:** AI, DevSecOps & Supply Chain  
> **Curated links:** 15  
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

Core resources: 
[NIST Secure Software Development Framework — SP 800-218](https://csrc.nist.gov/pubs/sp/800/218/final)[SLSA Specification](https://slsa.dev/spec/v1.2/)[OpenSSF](https://openssf.org/)[OWASP Software Component Verification Standard](https://scvs.owasp.org/)[OWASP CycloneDX](https://cyclonedx.org/)
SLSA 1.2 is the current approved specification and organizes supply-chain assurance into levels/tracks covering areas such as source and build provenance. ( [SLSA](https://slsa.dev/spec/v1.2/))

---

## Section 02: Methodology <a name="section-02"></a>

Threat Modeling 
→ Source Control 
→ Branch Protection 
→ Dependency Security 
→ Build Security 
→ CI/CD Security 
→ Secrets 
→ Artifact Integrity 
→ SBOM 
→ Signing 
→ Provenance 
→ Deployment 
→ Runtime 
→ Vulnerability Management

---

## Section 03: Standards / Compliance <a name="section-03"></a>

NIST SSDF · SLSA · OWASP SCVS · OpenSSF · CIS Software Supply Chain Security Benchmark · ISO 27001 · NIST 800-161. 
CIS explicitly includes a Software Supply Chain Security Benchmark in its DevSecOps family. ( [CIS](https://resources.cisecurity.org/benchmarks))

---

## Section 04: Official Documentation <a name="section-04"></a>

[NIST SSDF](https://csrc.nist.gov/projects/ssdf)[SLSA](https://slsa.dev/)[OpenSSF Best Practices](https://bestpractices.coreinfrastructure.org/)[Sigstore](https://www.sigstore.dev/)[in-toto](https://in-toto.io/)

---

## Section 05: Checklists <a name="section-05"></a>

MFA for developers 
Branch protection 
Signed commits/releases 
Dependency pinning 
Secret scanning 
SAST 
SCA 
DAST 
IaC scanning 
Container scanning 
SBOM 
VEX 
Artifact signatures 
Build provenance 
Isolated builders 
CI/CD least privilege 
OIDC workload identities 
Release approvals

---

## Section 06: Cheat Sheets <a name="section-06"></a>

[OWASP Software Supply Chain Security Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Software_Supply_Chain_Security_Cheat_Sheet.html)[SLSA Threats & Mitigations](https://slsa.dev/spec/v1.2/threats-overview)

---

## Section 07: Tools <a name="section-07"></a>

- ⭐⭐⭐ Semgrep · CodeQL · Trivy · Syft · Grype · Dependency-Track · OSV-Scanner · Checkov · Gitleaks · TruffleHog · Cosign · Renovate · Dependabot. Dependency-Track 5.0 became generally available in June 2026 and consumes SBOM data to continuously monitor component vulnerabilities and policy issues. ( [OWASP Foundation](https://owasp.org/blog/2026/06/09/dependency-track-v5))

---

## Section 08: Labs / Practice <a name="section-08"></a>

OWASP DevSlop · Damn Vulnerable CI/CD · TerraGoat · Kubernetes Goat · vulnerable GitHub Actions examples.

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

Dependency confusion · compromised package · secret leakage · unsigned artifact · tampered build · vulnerable dependency · malicious CI action · excessive pipeline privilege.

---

## Section 10: YouTube / Video <a name="section-10"></a>

OpenSSF · OWASP · CNCF · DEF CON · Black Hat · GitHub Security.

---

## Section 11: Courses / Training <a name="section-11"></a>

SANS SEC540 · SEC510 · Linux Foundation DevSecOps · OpenSSF courses.

---

## Section 12: Certifications <a name="section-12"></a>

GIAC Cloud Security Automation · CSSLP · GitHub Advanced Security certification · Kubernetes security credentials.

---

## Section 13: Books <a name="section-13"></a>

Securing DevOps · Alice and Bob Learn Application Security · Container Security.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

OpenSSF · Chainguard · Trail of Bits · GitHub Security Lab · Google OSS Security.

---

## Section 15: Research Papers <a name="section-15"></a>

USENIX · IEEE S&P · ACM CCS · software-supply-chain research.

---

## Section 16: White Papers <a name="section-16"></a>

NIST SSDF · SLSA · OpenSSF guides · CNCF software-supply-chain papers.

---

## Section 17: Conference Material <a name="section-17"></a>

OpenSSF Community Day · KubeCon · Black Hat · DEF CON · USENIX.

---

## Section 18: Mind Maps <a name="section-18"></a>

DevSecOps 

```
├── Source
```

```
├── CI/CD
```

```
├── Dependencies
```

```
├── SAST
```

```
├── SCA
```

```
├── IaC
```

```
├── Containers
```

```
├── SBOM
```

```
├── Signing
```

```
├── Provenance
```

```
└── Runtime
```

---

## Section 19: Sample Reports <a name="section-19"></a>

Pipeline assessment · dependency-risk report · SBOM report · CI/CD security review.

---

## Section 20: Templates <a name="section-20"></a>

devsecops-checklist.md 
cicd-security-review.md 
sbom-template.md 
dependency-review.md 
supply-chain-report.md

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

SolarWinds · Codecov · event-stream · ua-parser-js · XZ Utils · malicious package ecosystems.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

Syft · Grype · Trivy · Cosign · in-toto · Gitleaks · TruffleHog · Semgrep · OSV-Scanner.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

OSV vulnerability database · SBOM samples · package metadata · malicious-package datasets.

---

## Section 24: Communities / Forums <a name="section-24"></a>

OpenSSF · OWASP · CNCF Security TAG · GitHub Security Lab.

---

## Section 25: Vendors / Products <a name="section-25"></a>

Chainguard · Snyk · GitHub Advanced Security · GitLab · JFrog · Sonatype · Anchore.

---

## Section 26: Latest Developments <a name="section-26"></a>

Major themes: SBOM + VEX, keyless signing, workload identity, build provenance, reproducible builds and dependency-risk automation.

---

## Section 27: Learning Roadmap <a name="section-27"></a>

Git → CI/CD → SAST/SCA → secrets → containers/IaC → SBOM → signing → SLSA → provenance → runtime controls.

---

<div align="center">
<sub>🚀 DevSecOps & Software Supply Chain Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>