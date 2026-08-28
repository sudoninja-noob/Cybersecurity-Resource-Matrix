# ☁️ Domain 05: Cloud Security

> **Group:** Cloud, Containers & Identity  
> **Curated links:** 143  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

This is the GitHub/website-ready Cloud Security resource set using the same 27-category structure. 
Your uploaded Offensive Resources collection already has a Cloud section covering AWS Penetration Testing, Hands-On AWS Penetration Testing with Kali Linux, Pentesting Azure Applications, Mastering Cloud Penetration Testing, SANS SEC588, and AWS pentesting labs. I’ve used those as a baseline, but expanded the category considerably because modern cloud security now needs AWS + Azure + GCP + multi-cloud + IAM + CSPM/CNAPP + cloud detection/IR + IaC + serverless + compliance. 
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

Start with cloud architecture before offensive testing. 

| Resource | Type | Why Use It |
| --- | --- | --- |
| AWS Well-Architected Security Pillar |
| Official / Free |
| AWS security architecture |
| Microsoft Cloud Security Benchmark |
| Official / Free |
| Azure/multi-cloud security baseline |
| Google Cloud Security Best Practices Center |
| Official / Free |
| GCP architecture and hardening |
| CSA Cloud Controls Matrix |
| Industry / Free |
| Vendor-neutral cloud controls |
| NIST SP 800-144 |
| Official / Free |
| Public-cloud security/privacy fundamentals |
| MITRE ATT&CK Cloud Matrix |
| Official / Free |
| Cloud adversary techniques |

[AWS Well-Architected Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html)[Microsoft Cloud Security Benchmark](https://learn.microsoft.com/en-us/security/benchmark/azure/)[Google Cloud Security Best Practices](https://cloud.google.com/security/best-practices)[CSA Cloud Controls Matrix](https://cloudsecurityalliance.org/research/cloud-controls-matrix/)[NIST SP 800-144](https://csrc.nist.gov/pubs/sp/800/144/final)[MITRE ATT&CK Cloud Matrix](https://attack.mitre.org/matrices/enterprise/cloud/)
AWS currently structures its Well-Architected Security Pillar around areas including security foundations, IAM, detection, infrastructure protection, data protection, incident response and application security. ( [AWS Documentation](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/security.html)) 
Core concepts 
IaaS 
PaaS 
SaaS 
FaaS / Serverless 
Shared Responsibility Model 
Regions / Availability Zones 
Organizations / Accounts / Projects / Subscriptions 
IAM 
Federation 
Temporary Credentials 
Resource Policies 
Networking 
Storage 
Encryption 
Secrets 
Logging 
Cloud APIs 
Metadata Services 
Containers 
Serverless 
Infrastructure as Code 
Cloud Detection & Response 
CSPM / CNAPP

---

## Section 02: Methodology <a name="section-02"></a>

There is no single perfect cloud-pentesting methodology. I recommend combining: 
CSA Cloud Controls Matrix 
MITRE ATT&CK Cloud 
NIST SP 800-115 
AWS Well-Architected Security Pillar 
Microsoft Cloud Security Benchmark 
Google security blueprints 
provider-specific penetration-testing rules 
[CSA CCM](https://cloudsecurityalliance.org/artifacts/cloud-controls-matrix-v4-1)[MITRE ATT&CK Cloud](https://attack.mitre.org/matrices/enterprise/cloud/)[NIST SP 800-115](https://csrc.nist.gov/pubs/sp/800/115/final)

#### Recommended Cloud Security Assessment Workflow 
Authorization / Scope 

→ ↓ Cloud Provider Identification 

→ ↓ Organization / Tenant Mapping 

→ ↓ Account / Subscription / Project Inventory 

→ ↓ Asset Discovery 

→ ↓ Identity & IAM Review 

→ ↓ Privilege Analysis 

→ ↓ Network Architecture Review 

→ ↓ Storage Exposure Review 

→ ↓ Compute Security 

→ ↓ Database Security 

→ ↓ Serverless Review 

→ ↓ Secrets / Keys / Tokens 

→ ↓ Logging & Detection 

→ ↓ Security Services 

→ ↓ Public Exposure 

→ ↓ Metadata Service Review 

→ ↓ Cross-Account / Cross-Tenant Trust 

→ ↓ CI/CD & IaC Review 

→ ↓ Container / Kubernetes Integration 

→ ↓ Controlled Cloud Attack Simulation 

→ ↓ Persistence / Lateral Movement Validation 

→ ↓ Data Protection 

→ ↓ Incident Response Readiness 

→ ↓ Compliance Mapping 

→ ↓ Report / Remediation / Retest 

> Priority: ⭐⭐⭐

---

## Section 03: Standards / Compliance <a name="section-03"></a>

This section should be especially strong on your website. 

| Framework | Coverage |
| --- | --- |
| ⭐⭐⭐ CSA CCM v4.1 |
| Cloud-native control framework |
| ⭐⭐⭐ CSA CAIQ |
| Cloud provider assessment questionnaire |
| NIST CSF 2.0 |
| Enterprise security |
| NIST SP 800-144 |
| Public cloud security |
| NIST SP 800-53 |
| Security controls |
| NIST SP 800-207 |
| Zero Trust |
| ISO/IEC 27001 |
| ISMS |
| ISO/IEC 27017 |
| Cloud security controls |
| ISO/IEC 27018 |
| Cloud privacy |
| SOC 2 |
| Service organization controls |
| PCI DSS |
| Payment/cloud workloads |
| FedRAMP |
| US government cloud |
| CIS Foundations Benchmarks |
| AWS/Azure/GCP baseline |
| AWS Well-Architected |
| AWS architecture |
| Microsoft Cloud Security Benchmark |
| Azure/multicloud |
| Google Cloud security foundations |
| GCP |

CSA released CCM v4.1 in January 2026. The current artifact includes 207 controls across 17 security domains, plus CAIQ, auditing/implementation guidance and machine-readable JSON/YAML/OSCAL versions. ( [Cloud Security Alliance](https://cloudsecurityalliance.org/artifacts/cloud-controls-matrix-v4-1)) 
[CSA CCM v4.1](https://cloudsecurityalliance.org/artifacts/cloud-controls-matrix-v4-1)[CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks)[NIST CSF 2.0](https://www.nist.gov/cyberframework)[NIST SP 800-53](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)[NIST Zero Trust Architecture](https://csrc.nist.gov/pubs/sp/800/207/final)

---

## Section 04: Official Documentation <a name="section-04"></a>

AWS 
[AWS Security Documentation](https://docs.aws.amazon.com/security/)[AWS Security Learning Center](https://aws.amazon.com/security/security-learning/)[AWS Well-Architected Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html?pg=cloudessentials)[AWS Security Reference Architecture](https://docs.aws.amazon.com/prescriptive-guidance/latest/security-reference-architecture/welcome.html)[AWS IAM Documentation](https://docs.aws.amazon.com/iam/)
Azure 
[Microsoft Cloud Security Benchmark](https://learn.microsoft.com/en-us/security/benchmark/azure/?source=recommendations)[Azure Security Architecture](https://learn.microsoft.com/en-us/azure/architecture/security/security-get-started)[Microsoft Defender for Cloud](https://learn.microsoft.com/en-us/azure/defender-for-cloud/)[Microsoft Entra ID Security](https://learn.microsoft.com/en-us/entra/architecture/security-operations-introduction)
Google Cloud 
[Google Cloud Security Best Practices Center](https://cloud.google.com/security/best-practices?hl=en)[Google Cloud Security Documentation](https://cloud.google.com/docs/security)[Google Cloud IAM Documentation](https://cloud.google.com/iam/docs)

---

## Section 05: Checklists <a name="section-05"></a>

Best checklist sources: 
CSA CCM / CAIQ 
CIS AWS Foundations 
CIS Azure Foundations 
CIS Google Cloud Foundations 
AWS Well-Architected Security 
Microsoft Cloud Security Benchmark 
Google Cloud enterprise foundations 
Prowler checks 

#### Recommended Cloud Security Checklist 
Cloud account inventory 
Organizations / management groups 
Subscriptions / accounts / projects 
Root / break-glass accounts 
MFA 
SSO / federation 
IAM users 
IAM roles 
Service accounts 
Managed identities 
Access keys 
Unused credentials 
Privilege escalation paths 
Cross-account trust 
Resource policies 
Public storage 
Public databases 
Security groups 
NSGs / firewall rules 
VPC/VNet architecture 
Internet gateways 
Private endpoints 
Secrets management 
Key management 
Encryption at rest 
Encryption in transit 
Logging 
CloudTrail / Activity Logs / Audit Logs 
Threat detection 
CSPM 
Vulnerability management 
Metadata service 
Serverless 
Containers 
Kubernetes 
CI/CD 
IaC 
Backups 
Recovery 
Data retention 
Incident response 
Compliance

---

## Section 06: Cheat Sheets <a name="section-06"></a>

#### Recommended references: 
[HackTricks Cloud Pentesting](https://cloud.hacktricks.wiki/)[AWS CLI Command Reference](https://awscli.amazonaws.com/v2/documentation/api/latest/reference/index.html)[Azure CLI Reference](https://learn.microsoft.com/en-us/cli/azure/reference-index)[gcloud CLI Reference](https://cloud.google.com/sdk/gcloud/reference)[Prowler Documentation](https://docs.prowler.com/)[MITRE ATT&CK Cloud Matrix](https://attack.mitre.org/matrices/enterprise/cloud/)
Useful commands to index: 
aws sts get-caller-identity 
aws iam 
aws s3 
aws ec2 
aws organizations 
az account show 
az role assignment 
az ad 
az vm 
az storage 
gcloud auth list 
gcloud projects 
gcloud iam 
gcloud compute 
gsutil

---

## Section 07: Tools <a name="section-07"></a>

Multi-cloud posture / auditing 

| Tool | Provider |
| --- | --- |
| ⭐⭐⭐ Prowler |
| AWS, Azure, GCP, Kubernetes, OCI, M365, GitHub etc. |
| ⭐⭐⭐ ScoutSuite |
| Multi-cloud |
| ⭐⭐ Steampipe |
| Query cloud APIs with SQL |
| ⭐⭐ Cloud Custodian |
| Policy-as-code |
| ⭐⭐ CloudQuery |
| Cloud asset inventory/query |

[Prowler GitHub](https://github.com/prowler-cloud/prowler)[ScoutSuite GitHub](https://github.com/nccgroup/scoutsuite)[Steampipe](https://github.com/turbot/steampipe)[Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)[CloudQuery](https://github.com/cloudquery/cloudquery)
Prowler is particularly useful for a resource directory because it currently supports assessments across AWS, Azure, GCP, Kubernetes, M365, OCI, Alibaba Cloud, Cloudflare and other environments, with provider-specific checks and compliance frameworks. ( [GitHub](https://github.com/prowler-cloud/prowler)) 
AWS Offensive / IAM Analysis 

- ⭐⭐⭐ Pacu 
- ⭐⭐⭐ CloudGoat Parliament 
PMapper 
CloudFox 
enumerate-iam 
IAM Vulnerable 
[Rhino Security Labs Pacu](https://github.com/RhinoSecurityLabs/pacu)[CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat)[CloudFox](https://github.com/BishopFox/cloudfox)[PMapper](https://github.com/nccgroup/PMapper)[Parliament](https://github.com/duo-labs/parliament)
Azure 
ROADtools 
AzureHound 
MicroBurst 
Stormspotter 
GraphRunner 
[ROADtools](https://github.com/dirkjanm/ROADtools)[AzureHound](https://github.com/SpecterOps/AzureHound)[MicroBurst](https://github.com/NetSPI/MicroBurst)[GraphRunner](https://github.com/dafthack/GraphRunner)
GCP 
gcp_enum 
GCPBucketBrute 
ScoutSuite 
Prowler 
[gcp_enum](https://github.com/initstring/gcp_enum)[GCPBucketBrute](https://github.com/RhinoSecurityLabs/GCPBucketBrute)
IaC / Misconfiguration 
Checkov 
Trivy 
tfsec 
Terrascan 
KICS 
[Checkov](https://github.com/bridgecrewio/checkov)[Trivy](https://github.com/aquasecurity/trivy)[tfsec](https://github.com/aquasecurity/tfsec)[Terrascan](https://github.com/tenable/terrascan)[KICS](https://github.com/Checkmarx/kics)

---

## Section 08: Labs / Practice <a name="section-08"></a>

Your original resource map mentioned AWS pentesting labs. These current labs are stronger for a public resource collection. 

| Lab | Cloud | Level |
| --- | --- | --- |
| ⭐⭐⭐ CloudGoat |
| AWS / Azure |
| Intermediate → Advanced |
| ⭐⭐⭐ flaws.cloud |
| AWS |
| Beginner |
| ⭐⭐⭐ flaws2.cloud |
| AWS |
| Intermediate |
| ⭐⭐⭐ AWSGoat |
| AWS |
| Intermediate |
| ⭐⭐⭐ IAM Vulnerable |
| AWS |
| IAM |
| ⭐⭐ CloudFoxable |
| AWS |
| Attack-path labs |
| ⭐⭐ Thunder CTF |
| GCP |
| GCP |
| ⭐⭐ Sadcloud |
| Multi-cloud/IaC |
| Misconfiguration |
| ⭐⭐ TerraGoat |
| IaC |
| Terraform |

[CloudGoat GitHub](https://github.com/rhinosecuritylabs/cloudgoat)[flaws.cloud](http://flaws.cloud/)[flaws2.cloud](http://flaws2.cloud/)[AWSGoat](https://github.com/ine-labs/AWSGoat)[IAM Vulnerable](https://github.com/BishopFox/iam-vulnerable)[CloudFoxable](https://github.com/BishopFox/cloudfoxable)[TerraGoat](https://github.com/bridgecrewio/terragoat)
CloudGoat provides intentionally vulnerable cloud scenarios and explicitly warns users to deploy them only in isolated lab environments, not production accounts. ( [GitHub](https://github.com/RhinoSecurityLabs/cloudgoat))

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

For authorized cloud-security labs, focus less on traditional “payloads” and more on policy, identity, metadata, token and configuration test cases. 
Useful resources: 
[Pacu](https://github.com/RhinoSecurityLabs/pacu)[CloudFox](https://github.com/BishopFox/cloudfox)[MITRE ATT&CK Cloud](https://attack.mitre.org/matrices/enterprise/cloud/)[Prowler](https://github.com/prowler-cloud/prowler)
Test categories: 
Public object storage 
Overprivileged IAM 
Privilege escalation paths 
Cross-account role assumptions 
Exposed secrets 
Leaked access keys 
Instance metadata 
Service account tokens 
Public snapshots 
Public databases 
Security-group exposure 
Key-management misuse 
Serverless privileges 
Resource-policy bypass 
CI/CD credential exposure 
Logging disablement 
Cross-tenant trust 
Unused credentials 
Temporary-token abuse

---

## Section 10: YouTube / Video <a name="section-10"></a>

#### Recommended channels: 
AWS Events / AWS re:Inforce 
Google Cloud Tech 
Microsoft Security 
Cloud Security Alliance 
Black Hat 
DEF CON 
SANS 
John Hammond 
IppSec 
Rhino Security Labs presentations 
[AWS Events YouTube](https://www.youtube.com/@AWSEventsChannel)[Google Cloud Tech](https://www.youtube.com/@googlecloudtech)[Microsoft Security](https://www.youtube.com/@MicrosoftSecurity)[Cloud Security Alliance](https://www.youtube.com/@CloudSecurityAlliance)[Black Hat](https://www.youtube.com/@BlackHatOfficialYT)[DEF CON](https://www.youtube.com/@DEFCONConference)
Search topics: 
AWS IAM privilege escalation 
Azure Entra attack paths 
GCP IAM security 
Cloud metadata services 
Cloud incident response 
Serverless security 
Cloud attack paths 
AWS Organizations security 
Azure managed identities 
GCP service accounts 
Cloud detection engineering

---

## Section 11: Courses / Training <a name="section-11"></a>

Your uploaded source included SANS SEC588 as a cloud-security training resource. 

#### Vendor Training 

| Training | Provider |
| --- | --- |
| ⭐⭐⭐ AWS Security Learning Plan |
| AWS |
| ⭐⭐⭐ Microsoft Cloud Security learning paths |
| Microsoft |
| ⭐⭐⭐ Google Cloud Security Engineer path |
| Google |
| ⭐⭐⭐ CSA CCSK Training |
| CSA |
| ⭐⭐⭐ SANS SEC588 |
| SANS |
| ⭐⭐ Hack The Box Cloud modules |
| HTB |
| ⭐⭐ INE Cloud Security |
| INE |

[AWS Security Learning Plan](https://aws.amazon.com/training/learn-about/security/)[Microsoft Cloud Security Training](https://learn.microsoft.com/en-us/training/courses/az-500t00)[Google Professional Cloud Security Engineer Learning Path](https://cloud.google.com/learn/certification/cloud-security-engineer/?linkId=72090691)[SANS Cloud Security Courses](https://www.sans.org/cyber-security-courses/?focus-area=cloud-security)[Cloud Security Alliance Training](https://cloudsecurityalliance.org/education)
AWS's current learning offerings include a Security Learning Plan, security fundamentals, IAM material, simulated security learning and hands-on AWS training. ( [Amazon Web Services](https://aws.amazon.com/training/learn-about/security/))

---

## Section 12: Certifications <a name="section-12"></a>

Vendor-neutral 

| Certification | Focus |
| --- | --- |
| ⭐⭐⭐ ISC2 CCSP |
| Cloud architecture/security |
| ⭐⭐⭐ CSA CCSK |
| Cloud-security fundamentals |
| ⭐⭐ GIAC GCLD |
| Cloud security / automation |
| ⭐⭐ GIAC GCSA |
| Cloud security automation |

[ISC2 CCSP](https://www.isc2.org/certifications/CCSP)[CSA CCSK](https://cloudsecurityalliance.org/education/ccsk)[GIAC Cloud Certifications](https://www.giac.org/focus-areas/cloud-security/)
CCSP currently covers six domains: cloud concepts/architecture, data security, platform and infrastructure security, application security, security operations, and legal/risk/compliance. ( [ISC2](https://www.isc2.org/certifications/CCSP)) 
AWS 

- ⭐⭐⭐ AWS Certified Security – Specialty The current SCS-C03 blueprint covers detection, incident response, infrastructure security, IAM, data protection, and security foundations/governance. ( [AWS Documentation](https://docs.aws.amazon.com/aws-certification/latest/security-specialty-03/security-specialty-03.html)) 
[AWS Certified Security – Specialty](https://docs.aws.amazon.com/aws-certification/latest/security-specialty-03/security-specialty-03.html)
Azure 
Microsoft Azure Security Engineer Associate / AZ-500 has been highly relevant, but note an important current change: Microsoft says AZ-500 retires on August 31, 2026. Therefore, mark it as retiring, not a long-term recommendation. ( [Microsoft Learn](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-500)) 
[AZ-500 Certification Page](https://learn.microsoft.com/en-us/credentials/certifications/azure-security-engineer/)
Google Cloud 

- ⭐⭐⭐ Professional Cloud Security Engineer Current coverage includes access, communications/boundary protection, data protection, operations, compliance, security automation, AI workloads and software supply-chain security. ( [Google Cloud](https://cloud.google.com/learn/certification/cloud-security-engineer/?linkId=72090691)) 
[Google Professional Cloud Security Engineer](https://cloud.google.com/learn/certification/cloud-security-engineer/?linkId=72090691)

---

## Section 13: Books <a name="section-13"></a>

Your uploaded material already includes several cloud-pentesting books. 

#### Recommended categories: 
Offensive 
Hands-On AWS Penetration Testing with Kali Linux 
Pentesting Azure Applications 
Mastering Cloud Penetration Testing 
Architecture / Defensive 
Practical Cloud Security 
Cloud Security Handbook 
CCSP Official Study Guide 
AWS Security documentation — effectively a living reference 
CSA Security Guidance — living reference 
[CSA Security Guidance](https://cloudsecurityalliance.org/research/guidance/)[AWS Security Learning Resources](https://aws.amazon.com/security/security-learning/)
Because cloud services change rapidly, provider documentation and continuously updated repositories often age better than printed cloud-security books.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

AWS 
[AWS Security Blog](https://aws.amazon.com/blogs/security/)
Azure 
[Microsoft Security Blog](https://www.microsoft.com/en-us/security/blog/)
GCP 
[Google Cloud Security Blog](https://cloud.google.com/blog/products/identity-security)
Independent Research 
Rhino Security Labs 
Wiz Research 
Orca Research 
Unit 42 
Mandiant 
Datadog Security Labs 
SpecterOps 
NetSPI 
Bishop Fox 
[Rhino Security Labs Research](https://rhinosecuritylabs.com/blog/)[Wiz Research](https://www.wiz.io/research)[SpecterOps Blog](https://specterops.io/blog/)[NetSPI Technical Blog](https://www.netspi.com/blog/technical-blog/)[Bishop Fox Blog](https://bishopfox.com/blog)

---

## Section 15: Research Papers <a name="section-15"></a>

Follow: 
USENIX Security 
IEEE Security & Privacy 
ACM CCS 
NDSS 
CSA Research 
Black Hat papers 
cloud-provider security research 
[USENIX Security](https://www.usenix.org/conferences/byname/108)[IEEE Security & Privacy](https://www.ieee-security.org/TC/SP-Index.html)[NDSS](https://www.ndss-symposium.org/ndss-paper/)[CSA Research](https://cloudsecurityalliance.org/research)

#### Important research topics: 
Cloud IAM privilege escalation 
Cross-account trust 
Cloud tenant isolation 
Metadata service attacks 
Serverless isolation 
Cloud control-plane security 
Confused deputy attacks 
Cloud supply chain 
Multi-cloud identity 
Cloud lateral movement 
Cloud credential theft 
Managed-service security 
Cloud attack-path graphs

---

## Section 16: White Papers <a name="section-16"></a>

Strong resources: 
AWS Security Pillar 
AWS Security Reference Architecture 
Microsoft Cloud Security Benchmark 
Google Enterprise Foundations Blueprint 
CSA Security Guidance 
CSA CCM 
NIST SP 800-144 
NIST Zero Trust Architecture 
[AWS Security Pillar PDF](https://docs.aws.amazon.com/pdfs/wellarchitected/latest/security-pillar/wellarchitected-security-pillar.pdf)[CSA CCM v4.1](https://cloudsecurityalliance.org/artifacts/cloud-controls-matrix-v4-1)[Google Cloud Security Best Practices](https://cloud.google.com/security/best-practices?hl=en)[Microsoft Cloud Security Benchmark](https://learn.microsoft.com/en-us/security/benchmark/azure/overview-mcsb-v1)

---

## Section 17: Conference Material <a name="section-17"></a>

| Conference | Focus |
| --- | --- |
| ⭐⭐⭐ AWS re:Inforce |
| AWS security |
| ⭐⭐⭐ AWS re:Invent |
| Cloud architecture/security |
| ⭐⭐⭐ Microsoft Ignite |
| Azure/security |
| ⭐⭐⭐ Google Cloud Next |
| GCP/security |
| ⭐⭐⭐ Black Hat |
| Cloud attack research |
| ⭐⭐⭐ DEF CON Cloud Village |
| Cloud offensive security |
| ⭐⭐⭐ Cloud Security Alliance Events |
| GRC/architecture |
| ⭐⭐ SANS CloudSecNext |
| Cloud security |
| ⭐⭐ BSides |
| Practitioner research |

[AWS re:Inforce](https://reinforce.awsevents.com/)[DEF CON Cloud Village](https://cloud-village.org/)[CSA Events](https://cloudsecurityalliance.org/events)[Black Hat](https://www.blackhat.com/)

---

## Section 18: Mind Maps <a name="section-18"></a>

#### Recommended structure for your own cloud-security mind map: 
CLOUD SECURITY 

```
│
```

```
├── Architecture
```

```
│   ├── IaaS
```

```
│   ├── PaaS
```

```
│   ├── SaaS
```

```
│   └── Serverless
```

```
│
```

```
├── Identity
```

```
│   ├── Users
```

```
│   ├── Roles
```

```
│   ├── Service Accounts
```

```
│   ├── Federation
```

```
│   └── Temporary Credentials
```

```
│
```

```
├── Networking
```

```
│   ├── VPC / VNet
```

```
│   ├── Security Groups
```

```
│   ├── Firewall
```

```
│   ├── Private Endpoints
```

```
│   └── Peering
```

```
│
```

```
├── Data
```

```
│   ├── Object Storage
```

```
│   ├── Databases
```

```
│   ├── Encryption
```

```
│   └── KMS
```

```
│
```

```
├── Compute
```

```
│   ├── VM
```

```
│   ├── Containers
```

```
│   └── Kubernetes
```

```
│
```

```
├── Serverless
```

```
│
```

```
├── Secrets
```

```
│
```

```
├── IAM Attack Paths
```

```
│
```

```
├── CI/CD
```

```
│
```

```
├── IaC
```

```
│
```

```
├── Logging
```

```
│
```

```
├── Detection
```

```
│
```

```
├── Incident Response
```

```
│
```

```
├── CSPM / CNAPP
```

```
│
```

```
└── Compliance
```

---

## Section 19: Sample Reports <a name="section-19"></a>

Useful report/reference sources: 
Prowler reports 
ScoutSuite output 
public cloud security assessments 
CSA CCM/CAIQ 
AWS Well-Architected reviews 
[Prowler Documentation](https://docs.prowler.com/)[ScoutSuite GitHub](https://github.com/nccgroup/ScoutSuite)[CSA CCM/CAIQ](https://cloudsecurityalliance.org/artifacts/cloud-controls-matrix-v4-1)

#### Recommended structure: 
Executive Summary 
Scope 
Cloud Provider 
Accounts / Subscriptions / Projects 
Architecture 
Asset Inventory 
Identity & Access 
Network Security 
Compute 
Storage 
Database 
Encryption / KMS 
Secrets 
Logging & Monitoring 
Threat Detection 
Serverless 
CI/CD & IaC 
Containers 
Public Exposure 
Attack Paths 
Findings 
Evidence 
MITRE ATT&CK Mapping 
CSA CCM Mapping 
CIS Mapping 
Risk Rating 
Remediation 
Retest 
Conclusion

---

## Section 20: Templates <a name="section-20"></a>

#### Recommended GitHub structure: 
/templates/cloud-security/ 

```
├── cloud-security-test-plan.md
```

```
├── aws-security-checklist.md
```

```
├── azure-security-checklist.md
```

```
├── gcp-security-checklist.md
```

```
├── cloud-iam-review.md
```

```
├── cloud-network-review.md
```

```
├── cloud-storage-review.md
```

```
├── serverless-security.md
```

```
├── cloud-logging-review.md
```

```
├── cloud-ir-template.md
```

```
├── cloud-evidence-template.md
```

```
├── cloud-pentest-report.md
```

```
├── ccm-mapping.md
```

```
└── cis-benchmark-mapping.md
```

#### Recommended test-case columns: 
Test ID 
Provider 
Account / Subscription / Project 
Service 
Resource 
Region 
Objective 
Precondition 
Tool 
Procedure 
Expected Result 
Actual Result 
Evidence 
MITRE Technique 
CSA CCM 
CIS Control 
Severity 
Status

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

#### Primary resources: 
[CVE.org](https://www.cve.org/)[NIST NVD](https://nvd.nist.gov/)[CISA KEV](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)[MITRE ATT&CK Cloud](https://attack.mitre.org/matrices/enterprise/cloud/)
Also study misconfiguration case studies, because many cloud breaches are not conventional CVEs. 
Track: 
Public S3 / Blob / GCS buckets 
IAM privilege escalation 
Exposed access keys 
Overprivileged roles 
Cloud metadata exposure 
Cross-account trust 
Public snapshots 
CI/CD credential theft 
OAuth application abuse 
Serverless secrets 
Kubernetes cloud IAM 
SaaS identity compromise 
Cloud control-plane persistence

---

## Section 22: GitHub Repositories <a name="section-22"></a>

This should be one of the largest sections of your Cloud page. 
Cloud Assessment 

- ⭐⭐⭐ Prowler 
- ⭐⭐⭐ ScoutSuite 
- ⭐⭐ CloudQuery 
- ⭐⭐ Cloud Custodian 
- ⭐⭐ Steampipe 
#### Offensive AWS 

- ⭐⭐⭐ Pacu 
- ⭐⭐⭐ CloudFox 
- ⭐⭐⭐ CloudGoat 
- ⭐⭐ PMapper 
- ⭐⭐ enumerate-iam 
- ⭐⭐ IAM Vulnerable 
- ⭐⭐ CloudFoxable Azure 

- ⭐⭐⭐ AzureHound 
- ⭐⭐⭐ ROADtools 
- ⭐⭐ MicroBurst 
- ⭐⭐ GraphRunner IaC 

- ⭐⭐⭐ Checkov 
- ⭐⭐⭐ Trivy 
- ⭐⭐ tfsec 
- ⭐⭐ Terrascan 
- ⭐⭐ KICS [Prowler](https://github.com/prowler-cloud/prowler)[ScoutSuite](https://github.com/nccgroup/scoutsuite)[Rhino Security Labs Repositories](https://github.com/rhinosecuritylabs)[CloudFox](https://github.com/BishopFox/cloudfox)[AzureHound](https://github.com/SpecterOps/AzureHound)[Checkov](https://github.com/bridgecrewio/checkov)
Rhino Security Labs continues to maintain Pacu and CloudGoat; its repository listing showed Pacu updated in May 2026 and CloudGoat in April 2026. ( [GitHub](https://github.com/orgs/RhinoSecurityLabs/repositories))

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

For cloud security, prioritize audit logs and IaC samples. 
Useful data types: 
AWS CloudTrail 
AWS VPC Flow Logs 
Azure Activity Logs 
Entra Sign-in Logs 
Microsoft Defender alerts 
GCP Cloud Audit Logs 
VPC Flow Logs 
IAM policies 
Terraform 
CloudFormation 
ARM / Bicep 
OpenTofu 
Kubernetes manifests 

#### Useful sources: 
[AWS Security Lake sample resources](https://docs.aws.amazon.com/security-lake/)[Microsoft Sentinel Samples](https://github.com/Azure/Azure-Sentinel)[Google Security Operations Samples](https://github.com/GoogleCloudPlatform/security-analytics)[TerraGoat Vulnerable IaC](https://github.com/bridgecrewio/terragoat)

---

## Section 24: Communities / Forums <a name="section-24"></a>

Cloud Security Alliance 
AWS Security community 
Microsoft Security community 
Google Cloud Security community 
r/cloudsecurity 
r/aws 
r/AZURE 
Security Stack Exchange 
Prowler community 
Cloud Village 
[Cloud Security Alliance](https://cloudsecurityalliance.org/)[AWS Security Community](https://community.aws/)[Microsoft Security Community](https://techcommunity.microsoft.com/category/security-compliance-and-identity)[Cloud Village](https://cloud-village.org/)[Security Stack Exchange](https://security.stackexchange.com/)

---

## Section 25: Vendors / Products <a name="section-25"></a>

For awareness, categorize commercial platforms rather than simply listing names. 

| Category | Examples |
| --- | --- |
| CNAPP |
| Wiz, Palo Alto Prisma Cloud, Orca, Microsoft Defender for Cloud |
| CSPM |
| Prowler, Wiz, Prisma Cloud, Orca |
| CWPP |
| Prisma Cloud, CrowdStrike, Sysdig |
| CIEM |
| SailPoint, Sonrai, Wiz, Microsoft |
| Cloud Detection/Response |
| Microsoft Sentinel, AWS GuardDuty, Google Security Operations |
| Cloud-native SIEM |
| Sentinel, Google SecOps, Splunk |
| Cloud IAM |
| AWS IAM, Entra ID, Google Cloud IAM |
| Secrets |
| AWS Secrets Manager, Azure Key Vault, Google Secret Manager, HashiCorp Vault |

Keep neutral/open-source tools such as Prowler and ScoutSuite above vendor products on your resource site.

---

## Section 26: Latest Developments <a name="section-26"></a>

This is a fast-changing domain, so maintain links to living sources: 
[AWS Security Blog](https://aws.amazon.com/blogs/security/)[Microsoft Security Blog](https://www.microsoft.com/en-us/security/blog/)[Google Cloud Security Blog](https://cloud.google.com/blog/products/identity-security)[CSA Research](https://cloudsecurityalliance.org/research)[MITRE Cloud ATT&CK Matrix](https://attack.mitre.org/matrices/enterprise/cloud/)
Important 2026 items 
CSA CCM v4.1 is the current major cloud-control update, released January 27, 2026, with machine-readable controls and implementation/audit guidance. ( [Cloud Security Alliance](https://cloudsecurityalliance.org/artifacts/cloud-controls-matrix-v4-1)) 
Microsoft Cloud Security Benchmark v2 is currently in preview and expands the benchmark into areas including network security, identity, privileged access, data protection, logging, incident response, posture/vulnerability management, DevOps and AI security. ( [Microsoft Learn](https://learn.microsoft.com/en-us/security/benchmark/azure/introduction)) 
For certifications, AZ-500 is retiring August 31, 2026, so your website should visibly label it as retiring rather than presenting it as a long-term certification path. ( [Microsoft Learn](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-500)) 
Current cloud-security research areas worth tracking: 
Cloud attack paths 
Machine identities 
Workload identities 
Short-lived credentials 
Identity-first cloud attacks 
Cross-cloud identity 
SaaS security 
CNAPP 
Cloud detection and response 
Serverless security 
Metadata service security 
CI/CD compromise 
IaC security 
Cloud software supply chain 
AI workloads in cloud 
LLM cloud services 
Shadow cloud 
Cloud data exfiltration 
Multi-cloud governance 
DSPM 
Kubernetes-to-cloud privilege escalation

---

## Section 27: Learning Roadmap <a name="section-27"></a>

```
LEVEL 1 — Cloud Fundamentals
```
IaaS 
PaaS 
SaaS 
Regions 
Availability Zones 
Shared responsibility 
Accounts / subscriptions / projects 

→ ↓ 
```
LEVEL 2 — One Cloud Provider
```
Start with: 
AWS OR Azure OR GCP 
Compute 
Storage 
Networking 
Database 
IAM 

→ ↓ 
```
LEVEL 3 — Identity
```
Users 
Groups 
Roles 
Policies 
Service accounts 
Managed identities 
Federation 
Temporary credentials 

→ ↓ 
```
LEVEL 4 — Networking
```
VPC / VNet 
Subnets 
Security groups 
NSGs 
Firewall 
Peering 
Private endpoints 
Load balancers 

→ ↓ 
```
LEVEL 5 — Data
```
S3 / Blob / GCS 
Databases 
Encryption 
KMS 
Secrets 
Backups 

→ ↓ 
```
LEVEL 6 — Logging
```
CloudTrail 
Azure Activity Logs 
GCP Audit Logs 
Flow logs 
SIEM 

→ ↓ 
```
LEVEL 7 — Cloud Security Services
```
GuardDuty 
Defender for Cloud 
Security Command Center 

→ ↓ 
```
LEVEL 8 — Assessment
```
Prowler 
ScoutSuite 
CIS Benchmarks 
CSA CCM 

→ ↓ 
```
LEVEL 9 — Offensive Cloud
```
Pacu 
CloudFox 
AzureHound 
ROADtools 
CloudGoat 

→ ↓ 
```
LEVEL 10 — IAM Attack Paths
```
Privilege escalation 
Cross-account trust 
Service identities 
Federation 
Token abuse 

→ ↓ 
```
LEVEL 11 — Serverless
```
Lambda 
Azure Functions 
Cloud Functions 
Permissions 
Secrets 
Events 

→ ↓ 
```
LEVEL 12 — IaC
```
Terraform 
CloudFormation 
Bicep 
Checkov 
Trivy 

→ ↓ 
```
LEVEL 13 — Container / Kubernetes Integration
```
Cloud IAM 
Managed Kubernetes 
Workload identity 
Registry security 

→ ↓ 
```
LEVEL 14 — Detection / IR
```
MITRE ATT&CK Cloud 
Threat detection 
Cloud forensics 
Incident response 

→ ↓ 
```
LEVEL 15 — Multi-Cloud
```
AWS 
Azure 
GCP 
SaaS 
Central identity 

→ ↓ 
```
LEVEL 16 — Compliance
```
CSA CCM 
CIS 
NIST 
ISO 27017 
PCI DSS 
SOC 2 

→ ↓ 
```
LEVEL 17 — Architecture
```
Zero Trust 
Landing zones 
Security reference architecture 
Guardrails 
Policy as Code 

→ ↓ 
```
LEVEL 18 — Advanced
```
Attack paths 
CIEM 
CNAPP 
DSPM 
Cloud supply chain 
AI cloud security 
Machine identities 

- ⭐ Cloud Security — Top 20 Resources 
| Rank | Resource | Purpose |
| --- | --- | --- |
| 1 |
| CSA Cloud Controls Matrix |
| Cloud control baseline |
| 2 |
| AWS Well-Architected Security Pillar |
| AWS security architecture |
| 3 |
| Microsoft Cloud Security Benchmark |
| Azure/multi-cloud security |
| 4 |
| Google Cloud Security Best Practices |
| GCP security |
| 5 |
| MITRE ATT&CK Cloud |
| Cloud attacker TTPs |
| 6 |
| Prowler |
| Automated multi-cloud assessment |
| 7 |
| ScoutSuite |
| Multi-cloud security auditing |
| 8 |
| CloudGoat |
| Cloud offensive lab |
| 9 |
| CloudFox |
| AWS attack-path discovery |
| 10 |
| Pacu |
| AWS security testing |
| 11 |
| AzureHound |
| Azure identity/attack paths |
| 12 |
| ROADtools |
| Entra/Azure identity |
| 13 |
| CloudFoxable |
| AWS lab |
| 14 |
| flaws.cloud |
| AWS beginner lab |
| 15 |
| Checkov |
| IaC security |
| 16 |
| Trivy |
| IaC/container/cloud checks |
| 17 |
| NIST SP 800-144 |
| Cloud security fundamentals |
| 18 |
| CCSP |
| Vendor-neutral certification |
| 19 |
| CCSK |
| Cloud-security knowledge |
| 20 |
| AWS / Azure / GCP security certification paths |
| Provider specialization |

#### Recommended Practical Stack 
Cloud fundamentals → choose AWS/Azure/GCP → IAM → networking → storage/data → logging → CIS/CSA CCM → Prowler/ScoutSuite → CloudGoat → CloudFox/Pacu/AzureHound → IaC security → serverless → detection/IR → multi-cloud → compliance → architecture and reporting. 
For your repository, I would also make AWS Security, Azure Security, GCP Security, Cloud IAM, Cloud Pentesting, Serverless Security, Cloud Detection & IR, and Cloud Compliance separate subfolders underneath this main Cloud Security domain.

---

<div align="center">
<sub>☁️ Cloud Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>