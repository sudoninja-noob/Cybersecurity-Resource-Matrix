# 🐳 Domain 06: Container & Kubernetes Security

> **Group:** Cloud, Containers & Identity  
> **Curated links:** 127  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

This is the GitHub/website-ready Container & Kubernetes Security resource set, using the same 27-category structure. 
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
| Kubernetes Security Documentation |
| Official / Free |
| Core cluster and workload security |
| NIST SP 800-190 |
| Official / Free |
| Container security architecture and risks |
| CIS Kubernetes Benchmark |
| Industry / Free |
| Hardening benchmark |
| NSA/CISA Kubernetes Hardening Guidance |
| Official / Free |
| Practical secure configuration guidance |
| OWASP Kubernetes Top 10 |
| Community / Free |
| Common Kubernetes security risks |
| CNCF Cloud Native Security |
| Official / Free |
| Cloud-native security guidance |

[Kubernetes Security Docs](https://kubernetes.io/docs/concepts/security/)[NIST SP 800-190](https://csrc.nist.gov/pubs/sp/800/190/final)[CIS Kubernetes Benchmark](https://www.cisecurity.org/benchmark/kubernetes)[NSA/CISA Kubernetes Hardening Guidance](https://www.nsa.gov/Press-Room/News-Highlights/Article/Article/2716980/nsa-cisa-release-kubernetes-hardening-guidance/)[CNCF Security TAG](https://tag-security.cncf.io/)
NIST SP 800-190 is still the core U.S. government reference for container security, covering container-image risks, registries, orchestrators, hosts, and application isolation. ( [NIST Computer Security Resource Center](https://csrc.nist.gov/pubs/sp/800/190/final)) 
Core concepts 
Containers 
Images 
Registries 
Docker / containerd / CRI-O 
Namespaces 
cgroups 
Linux capabilities 
seccomp 
AppArmor / SELinux 
Kubernetes control plane 
API Server 
etcd 
Scheduler 
Controller Manager 
kubelet 
Pods 
Deployments 
Services 
Ingress 
RBAC 
Service Accounts 
Secrets 
Network Policies 
Pod Security 
Admission Control 
Image Security 
Runtime Security 
Supply Chain 
SBOM 
Signing / Verification 
Policy as Code

---

## Section 02: Methodology <a name="section-02"></a>

Use a combination of: 
Kubernetes Security documentation 
CIS Kubernetes Benchmark 
NSA/CISA Kubernetes Hardening Guidance 
NIST SP 800-190 
MITRE ATT&CK Containers Matrix 
OWASP Kubernetes Top 10 

#### Recommended assessment workflow 
Authorization / Scope 

→ ↓ Cluster Architecture Discovery 

→ ↓ Node / Control Plane Inventory 

→ ↓ Kubernetes API Exposure 

→ ↓ Authentication Review 

→ ↓ RBAC / Authorization Review 

→ ↓ Service Account Review 

→ ↓ Pod Security Review 

→ ↓ Container Image Review 

→ ↓ Registry Security 

→ ↓ Secrets Management 

→ ↓ Network Policy Review 

→ ↓ Ingress / Service Exposure 

→ ↓ Admission Control 

→ ↓ etcd Security 

→ ↓ kubelet Security 

→ ↓ Runtime Security 

→ ↓ Host / Node Hardening 

→ ↓ Supply Chain Security 

→ ↓ CI/CD and IaC Security 

→ ↓ Logging / Detection 

→ ↓ Compliance Mapping 

→ ↓ Reporting / Retest 

> Priority: ⭐⭐⭐

---

## Section 03: Standards / Compliance <a name="section-03"></a>

| Framework | Coverage |
| --- | --- |
| ⭐⭐⭐ CIS Kubernetes Benchmark |
| Kubernetes hardening |
| ⭐⭐⭐ NIST SP 800-190 |
| Container security |
| ⭐⭐⭐ NSA/CISA Kubernetes Hardening Guidance |
| Cluster hardening |
| NIST SP 800-53 |
| Security controls |
| NIST SSDF SP 800-218 |
| Secure software supply chain |
| SLSA |
| Build/supply-chain integrity |
| CIS Docker Benchmark |
| Docker hardening |
| MITRE ATT&CK Containers |
| Adversary behavior |
| PCI DSS |
| Containerized payment workloads |
| ISO/IEC 27001 |
| Security governance |
| SOC 2 |
| Cloud/container controls |

The CIS site currently lists Kubernetes Benchmark 2.0.1, plus specific benchmarks for EKS, AKS, GKE, GKE Autopilot, OKE and OpenShift. ( [CIS](https://www.cisecurity.org/benchmark/kubernetes)) 
[CIS Kubernetes Benchmark](https://www.cisecurity.org/benchmark/kubernetes)[NIST SP 800-190](https://csrc.nist.gov/pubs/sp/800/190/final)[NIST SSDF](https://csrc.nist.gov/pubs/sp/800/218/final)[SLSA](https://slsa.dev/)[MITRE ATT&CK Containers](https://attack.mitre.org/matrices/enterprise/containers/)

---

## Section 04: Official Documentation <a name="section-04"></a>

Kubernetes 
[Kubernetes Security](https://kubernetes.io/docs/concepts/security/)[Kubernetes RBAC](https://kubernetes.io/docs/reference/access-authn-authz/rbac/)[Pod Security Standards](https://kubernetes.io/docs/concepts/security/pod-security-standards/)[Network Policies](https://kubernetes.io/docs/concepts/services-networking/network-policies/)[Secrets](https://kubernetes.io/docs/concepts/configuration/secret/)[Admission Controllers](https://kubernetes.io/docs/reference/access-authn-authz/admission-controllers/)
Container runtimes 
[Docker Security](https://docs.docker.com/engine/security/)[containerd](https://containerd.io/)[CRI-O](https://cri-o.io/)
CNCF Security 
[CNCF Security TAG](https://tag-security.cncf.io/)[CNCF Cloud Native Security Whitepaper](https://github.com/cncf/tag-security/tree/main/security-whitepaper)

---

## Section 05: Checklists <a name="section-05"></a>

#### Recommended sources: 
CIS Kubernetes Benchmark 
NSA/CISA Hardening Guide 
Kubernetes Pod Security Standards 
Kubernetes Security Checklist 
OWASP Kubernetes Top 10 
kube-bench 
Kubescape 

#### Recommended security checklist 
API server exposure 
Anonymous authentication 
RBAC 
Cluster-admin assignments 
Service account token exposure 
AutomountServiceAccountToken 
Pod Security Standards 
Privileged containers 
HostPID / HostIPC / HostNetwork 
hostPath mounts 
Linux capabilities 
runAsRoot 
readOnlyRootFilesystem 
seccomp 
AppArmor / SELinux 
Secrets encryption 
etcd authentication 
etcd encryption 
kubelet authentication 
NetworkPolicies 
Ingress exposure 
NodePort / LoadBalancer exposure 
Image tags 
Image signatures 
Registry access 
Image vulnerabilities 
SBOM 
Admission policies 
Supply-chain provenance 
Runtime monitoring 
Audit logging 
Node hardening 
Kernel security 
CI/CD permissions 
IaC scanning 
Backup / recovery

---

## Section 06: Cheat Sheets <a name="section-06"></a>

#### Recommended: 
[Kubernetes kubectl Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/quick-reference/)[Docker Cheat Sheet](https://docs.docker.com/get-started/docker_cheatsheet.pdf)[HackTricks Kubernetes](https://cloud.hacktricks.wiki/en/pentesting-cloud/kubernetes-security/)[Kubernetes Security Context](https://kubernetes.io/docs/tasks/configure-pod-container/security-context/)[CIS Kubernetes Benchmark](https://www.cisecurity.org/benchmark/kubernetes)
Useful commands: 
kubectl auth can-i --list 
kubectl get pods -A 
kubectl get rolebindings -A 
kubectl get clusterrolebindings 
kubectl get serviceaccounts -A 
kubectl get secrets -A 
kubectl get networkpolicies -A 
kubectl get validatingwebhookconfigurations 
kubectl get mutatingwebhookconfigurations 
kubectl get nodes -o wide 
kubectl describe pod <pod>

---

## Section 07: Tools <a name="section-07"></a>

Image / Vulnerability Scanning 

| Tool | Purpose |
| --- | --- |
| ⭐⭐⭐ Trivy |
| Images, filesystem, IaC, SBOM, cluster |
| ⭐⭐⭐ Grype |
| Image/filesystem vulnerabilities |
| ⭐⭐⭐ Syft |
| SBOM generation |
| ⭐⭐ Clair |
| Container image scanning |

[Trivy](https://github.com/aquasecurity/trivy)[Grype](https://github.com/anchore/grype)[Syft](https://github.com/anchore/syft)[Clair](https://github.com/quay/clair)
Kubernetes Hardening / Compliance 

| Tool | Purpose |
| --- | --- |
| ⭐⭐⭐ kube-bench |
| CIS Benchmark checks |
| ⭐⭐⭐ Kubescape |
| Kubernetes security/compliance |
| ⭐⭐ Kubesec |
| Kubernetes manifest risk analysis |
| ⭐⭐ Polaris |
| Best-practice validation |
| ⭐⭐ Checkov |
| IaC / K8s manifests |

[Kube-bench](https://github.com/aquasecurity/kube-bench)[Kubescape](https://github.com/kubescape/kubescape)[Kubesec](https://github.com/controlplaneio/kubesec)[Polaris](https://github.com/FairwindsOps/polaris)[Checkov](https://github.com/bridgecrewio/checkov)
Kubernetes SIG Security currently references tools such as Trivy, Grype, kube-bench and Kubescape for vulnerability and configuration scanning. ( [GitHub](https://github.com/kubernetes/sig-security/blob/main/sig-security-docs/papers/policy_grc/kubernetes-grc.md)) 
Runtime Security 

| Tool | Purpose |
| --- | --- |
| ⭐⭐⭐ Falco |
| Runtime threat detection |
| ⭐⭐⭐ Tetragon |
| eBPF observability/enforcement |
| ⭐⭐ Tracee |
| eBPF runtime security |
| ⭐⭐ Cilium |
| Network + runtime security |

[Falco](https://falco.org/)[Tetragon](https://tetragon.io/)[Tracee](https://github.com/aquasecurity/tracee)[Cilium](https://cilium.io/)
Policy / Admission Control 

- ⭐⭐⭐ Kyverno 
- ⭐⭐⭐ OPA Gatekeeper Kubewarden 
[Kyverno](https://kyverno.io/)[OPA Gatekeeper](https://github.com/open-policy-agent/gatekeeper)[Kubewarden](https://www.kubewarden.io/)

---

## Section 08: Labs / Practice <a name="section-08"></a>

| Lab | Level |
| --- | --- |
| ⭐⭐⭐ Kubernetes Goat |
| Beginner → Advanced |
| ⭐⭐⭐ KubeGoat |
| Vulnerable Kubernetes lab |
| ⭐⭐⭐ Kubernetes Security Lab by Killer Shell |
| CKS-oriented |
| ⭐⭐⭐ KodeKloud CKS Labs |
| Structured hands-on |
| ⭐⭐ OWASP WrongSecrets |
| Secrets management |
| ⭐⭐ Container Security Playground |
| Container security |

[Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat)[Killer Shell CKS](https://killer.sh/cks)[KodeKloud CKS Learning Path](https://kodekloud.com/learning-path/cks/)[OWASP WrongSecrets](https://owasp.org/www-project-wrongsecrets/)
KodeKloud’s CKS path includes Linux, containers, Kubernetes, security concepts and practical challenges. ( [KodeKloud](https://kodekloud.com/learning-path/cks/))

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

For authorized test environments, focus on configuration and privilege scenarios rather than generic payloads. 
Test areas 
Privileged pod 
hostPath mount 
hostNetwork 
hostPID 
hostIPC 
CAP_SYS_ADMIN 
Run as root 
ServiceAccount token exposure 
Cluster-admin RBAC 
Wildcard RBAC 
Secrets access 
Unauthorized exec 
Anonymous API access 
Kubelet API exposure 
etcd access 
Weak NetworkPolicy 
Image pull from untrusted registry 
Unsigned image 
Latest-tag usage 
Image vulnerability 
Admission policy bypass 
Node breakout attempts 
Runtime process anomaly 
Useful references: 
[MITRE ATT&CK Containers](https://attack.mitre.org/matrices/enterprise/containers/)[Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat)[OWASP Kubernetes Top 10](https://owasp.org/www-project-kubernetes-top-ten/)

---

## Section 10: YouTube / Video <a name="section-10"></a>

#### Recommended channels: 
CNCF 
Kubernetes 
KubeCon + CloudNativeCon 
KodeKloud 
Aqua Security 
Sysdig 
Isovalent 
Black Hat 
DEF CON 
[CNCF YouTube](https://www.youtube.com/@cncf)[Kubernetes YouTube](https://www.youtube.com/@KubernetesCommunity)[KubeCon Videos](https://www.youtube.com/@cncf)[KodeKloud](https://www.youtube.com/@KodeKloud)[Sysdig](https://www.youtube.com/@Sysdig)
Search topics: 
Kubernetes RBAC 
Pod Security Standards 
Container escape 
eBPF security 
Kubernetes network policy 
Image signing 
Falco 
Tetragon 
Admission control 
Kubernetes supply chain

---

## Section 11: Courses / Training <a name="section-11"></a>

| Course | Level |
| --- | --- |
| ⭐⭐⭐ KodeKloud CKS |
| Intermediate → Advanced |
| ⭐⭐⭐ Linux Foundation Kubernetes Security Essentials |
| Intermediate |
| ⭐⭐⭐ Killer Shell CKS simulator |
| Exam practice |
| ⭐⭐ A Cloud Guru / Pluralsight Kubernetes Security |
| Beginner → Intermediate |
| ⭐⭐ SANS SEC584 |
| Cloud-native/Kubernetes security |
| ⭐⭐ CNCF Training Partners |
| Kubernetes security |

[Kubernetes Training](https://kubernetes.io/training/)[KodeKloud CKS](https://kodekloud.com/learning-path/cks/)[Killer Shell](https://killer.sh/)
Kubernetes officially states that CKS validates security skills across the build, deployment and runtime phases of containerized applications and Kubernetes platforms. ( [Kubernetes](https://kubernetes.io/training/))

---

## Section 12: Certifications <a name="section-12"></a>

| Certification | Focus |
| --- | --- |
| ⭐⭐⭐ CKS |
| Kubernetes security |
| ⭐⭐ KCSA |
| Kubernetes/cloud-native security fundamentals |
| ⭐⭐ CKA |
| Kubernetes administration prerequisite |
| ⭐⭐ KCNA |
| Kubernetes/cloud-native fundamentals |
| ⭐ Kubestronaut |
| Multi-cert CNCF path |

[Kubernetes Certifications](https://kubernetes.io/training/)[CKS](https://training.linuxfoundation.org/certification/certified-kubernetes-security-specialist/)[KCSA](https://training.linuxfoundation.org/certification/kubernetes-and-cloud-native-security-associate-kcsa/)
Important: CKS requires a valid CKA before you can sit the exam. ( [KodeKloud](https://kodekloud.com/learning-path/cks))

---

## Section 13: Books <a name="section-13"></a>

#### Recommended: 
Container Security — Liz Rice 
Kubernetes Security and Observability 
Hacking Kubernetes 
Kubernetes Security 
Kubernetes Best Practices 
Kubernetes Up & Running 
Docker Deep Dive 
For security-focused study, Container Security by Liz Rice is particularly useful for namespaces, capabilities, seccomp, containers and kernel isolation.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

High-value sources: 
Kubernetes Blog 
CNCF Security TAG 
Aqua Security Blog 
Sysdig Blog 
Isovalent Blog 
Chainguard Blog 
Trail of Bits 
Datadog Security Labs 
Wiz Research 
[Kubernetes Blog](https://kubernetes.io/blog/)[CNCF Security TAG](https://tag-security.cncf.io/)[Aqua Security Blog](https://www.aquasec.com/blog/)[Sysdig Blog](https://sysdig.com/blog/)[Isovalent Blog](https://isovalent.com/blog/)[Chainguard Blog](https://www.chainguard.dev/unchained)

---

## Section 15: Research Papers <a name="section-15"></a>

Track: 
USENIX Security 
IEEE S&P 
NDSS 
ACM CCS 
KubeCon security talks 
CNCF TAG Security papers 

#### Research topics: 
Container isolation 
Namespace escapes 
cgroups 
seccomp 
Container breakout 
Kubernetes RBAC 
Multi-tenancy 
Service mesh security 
eBPF security 
Kubernetes supply chain 
Admission control 
Cloud-native runtime detection

---

## Section 16: White Papers <a name="section-16"></a>

#### Recommended: 
NIST SP 800-190 
NSA/CISA Kubernetes Hardening Guidance 
CNCF Cloud Native Security Whitepaper 
CNCF Software Supply Chain papers 
SLSA specification 
Kubernetes Security Checklist 
[NSA/CISA Hardening Guidance](https://www.nsa.gov/Press-Room/News-Highlights/Article/Article/2716980/nsa-cisa-release-kubernetes-hardening-guidance/)[CNCF Security Whitepaper](https://github.com/cncf/tag-security/tree/main/security-whitepaper)[SLSA](https://slsa.dev/)
NSA/CISA’s Kubernetes guidance specifically emphasizes hardening, logging and threat detection. ( [National Security Agency](https://www.nsa.gov/Press-Room/News-Highlights/Article/Article/2716980/nsa-cisa-release-kubernetes-hardening-guidance/))

---

## Section 17: Conference Material <a name="section-17"></a>

| Conference | Focus |
| --- | --- |
| ⭐⭐⭐ KubeCon + CloudNativeCon |
| Cloud-native security |
| ⭐⭐⭐ Black Hat |
| Container/K8s attacks |
| ⭐⭐⭐ DEF CON |
| Offensive security |
| ⭐⭐ CloudNativeSecurityCon |
| Cloud-native security |
| ⭐⭐ USENIX Security |
| Research |
| ⭐⭐ BSides |
| Community talks |

[KubeCon + CloudNativeCon](https://www.cncf.io/kubecon-cloudnativecon-events/)[CNCF Events](https://www.cncf.io/events/)[Black Hat](https://www.blackhat.com/)[DEF CON](https://defcon.org/)

---

## Section 18: Mind Maps <a name="section-18"></a>

#### Recommended: 
CONTAINER & KUBERNETES SECURITY 

```
│
```

```
├── Container Security
```

```
│   ├── Images
```

```
│   ├── Registry
```

```
│   ├── Runtime
```

```
│   ├── Capabilities
```

```
│   ├── Namespaces
```

```
│   ├── seccomp
```

```
│   └── AppArmor / SELinux
```

```
│
```

```
├── Kubernetes Control Plane
```

```
│   ├── API Server
```

```
│   ├── etcd
```

```
│   ├── Scheduler
```

```
│   └── Controller Manager
```

```
│
```

```
├── Authentication
```

```
│
```

```
├── Authorization
```

```
│   └── RBAC
```

```
│
```

```
├── Workload Security
```

```
│   ├── Pod Security
```

```
│   ├── SecurityContext
```

```
│   └── Service Accounts
```

```
│
```

```
├── Networking
```

```
│   ├── NetworkPolicy
```

```
│   ├── Ingress
```

```
│   └── Service Mesh
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
├── Admission Control
```

```
│   ├── Kyverno
```

```
│   └── Gatekeeper
```

```
│
```

```
├── Supply Chain
```

```
│   ├── SBOM
```

```
│   ├── Signing
```

```
│   ├── Provenance
```

```
│   └── SLSA
```

```
│
```

```
├── Runtime
```

```
│   ├── Falco
```

```
│   └── Tetragon
```

```
│
```

```
└── Compliance
```

---

## Section 19: Sample Reports <a name="section-19"></a>

#### Recommended report structure: 
Executive Summary 
Scope 
Cluster Architecture 
Node Inventory 
Container Runtime 
API Server 
Authentication 
RBAC 
Service Accounts 
Pod Security 
Network Policies 
Secrets 
Image Security 
Registry Security 
Admission Control 
etcd Security 
kubelet Security 
Runtime Security 
Node Security 
Supply Chain 
Logging / Detection 
Findings 
Evidence 
CIS Mapping 
NIST Mapping 
MITRE ATT&CK Mapping 
Remediation 
Retest 
Conclusion 
Useful automated-report sources: 
Kubescape 
kube-bench 
Trivy 
Prowler Kubernetes checks

---

## Section 20: Templates <a name="section-20"></a>

#### Recommended GitHub structure: 
/templates/container-kubernetes/ 

```
├── container-security-test-plan.md
```

```
├── kubernetes-security-test-plan.md
```

```
├── cis-kubernetes-checklist.md
```

```
├── pod-security-review.md
```

```
├── rbac-review.md
```

```
├── secrets-review.md
```

```
├── network-policy-review.md
```

```
├── admission-control-review.md
```

```
├── image-security-review.md
```

```
├── supply-chain-review.md
```

```
├── runtime-security-review.md
```

```
├── evidence-template.md
```

```
└── kubernetes-security-report.md
```

#### Recommended fields: 
Test ID 
Cluster 
Namespace 
Workload 
Node 
Objective 
Tool 
Procedure 
Expected Result 
Actual Result 
Evidence 
CIS Control 
NIST Control 
MITRE Technique 
Severity 
Status

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

#### Primary resources: 
[CVE.org](https://www.cve.org/)[NVD](https://nvd.nist.gov/)[CISA KEV](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)[Kubernetes Security Announcements](https://kubernetes.io/docs/reference/issues-security/security/)
Track: 
Container runtime escapes 
runc vulnerabilities 
containerd vulnerabilities 
Kubernetes API flaws 
kubelet exposure 
Ingress vulnerabilities 
RBAC misconfiguration 
etcd exposure 
Service account token theft 
Supply-chain compromise 
Malicious images 
Admission-control bypass

---

## Section 22: GitHub Repositories <a name="section-22"></a>

#### Essential 

- ⭐⭐⭐ [Trivy](https://github.com/aquasecurity/trivy)
- ⭐⭐⭐ [kube-bench](https://github.com/aquasecurity/kube-bench)
- ⭐⭐⭐ [Kubescape](https://github.com/kubescape/kubescape)
- ⭐⭐⭐ [Falco](https://github.com/falcosecurity/falco)
- ⭐⭐⭐ [Tetragon](https://github.com/cilium/tetragon)
- ⭐⭐⭐ [Kyverno](https://github.com/kyverno/kyverno)
- ⭐⭐⭐ [OPA Gatekeeper](https://github.com/open-policy-agent/gatekeeper)
- ⭐⭐⭐ [Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat)
- ⭐⭐ [Kubesec](https://github.com/controlplaneio/kubesec)
- ⭐⭐ [Polaris](https://github.com/FairwindsOps/polaris)
- ⭐⭐ [Syft](https://github.com/anchore/syft)
- ⭐⭐ [Grype](https://github.com/anchore/grype)
- ⭐⭐ [Tracee](https://github.com/aquasecurity/tracee)
- ⭐⭐ [Cilium](https://github.com/cilium/cilium)Do not prioritize kube-hunter anymore: its own repository says it is no longer under active development and recommends Trivy for Kubernetes vulnerability and misconfiguration scanning instead. ( [GitHub](https://github.com/aquasecurity/kube-hunter))

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

Useful lab data: 
Kubernetes audit logs 
Falco alerts 
Container runtime logs 
Container images 
SBOMs 
Helm charts 
Kubernetes YAML 
NetworkPolicy manifests 
Dockerfiles 
Admission policies 
RBAC manifests 
CI/CD logs 
Sources: 
[Kubernetes Audit Documentation](https://kubernetes.io/docs/tasks/debug/debug-cluster/audit/)[Falco Rules](https://github.com/falcosecurity/rules)[Helm Charts](https://artifacthub.io/)[Docker Official Images](https://hub.docker.com/search?image_filter=official)

---

## Section 24: Communities / Forums <a name="section-24"></a>

CNCF 
Kubernetes Slack 
SIG Security 
Falco community 
Kyverno community 
Cilium community 
Aqua Security community 
KodeKloud 
Kubernetes subreddit 
[CNCF Community](https://www.cncf.io/community/)[Kubernetes Community](https://kubernetes.io/community/)[Kubernetes SIG Security](https://github.com/kubernetes/community/tree/master/sig-security)

---

## Section 25: Vendors / Products <a name="section-25"></a>

| Category | Examples |
| --- | --- |
| CNAPP / Container Security |
| Wiz, Prisma Cloud, Aqua, Sysdig |
| Runtime Security |
| Falco, Tetragon, Sysdig |
| Image Security |
| Trivy, Grype, Clair |
| Policy |
| Kyverno, OPA Gatekeeper |
| Network Security |
| Cilium, Calico |
| Service Mesh |
| Istio, Linkerd |
| Supply Chain |
| Sigstore, Cosign, SLSA |
| Kubernetes Posture |
| Kubescape, kube-bench |

For your site, keep open-source tools primary and commercial CNAPP platforms secondary.

---

## Section 26: Latest Developments <a name="section-26"></a>

For living updates, follow: 
[Kubernetes Security Announcements](https://kubernetes.io/docs/reference/issues-security/security/)[CNCF Security TAG](https://tag-security.cncf.io/)[Kubernetes Blog](https://kubernetes.io/blog/)[Aqua Security Blog](https://www.aquasec.com/blog/)[Sysdig Blog](https://sysdig.com/blog/)

#### Important current topics: 
Pod Security Standards 
eBPF runtime security 
Kubernetes supply chain 
Signed images 
Sigstore / Cosign 
SBOM 
SLSA 
Workload Identity 
Ephemeral containers 
Multi-tenancy 
Admission policy 
Confidential containers 
Kubernetes AI workloads 
GPU workload security 
Service mesh security 
Kubernetes ransomware 
Container escape detection 
Also note the ecosystem change around security tooling: Trivy is becoming the default Aqua recommendation for Kubernetes vulnerability/misconfiguration assessment in place of kube-hunter. ( [GitHub](https://github.com/aquasecurity/kube-hunter))

---

## Section 27: Learning Roadmap <a name="section-27"></a>

```
LEVEL 1 — Containers
```
Docker 
Images 
Layers 
Registries 
Volumes 
Namespaces 
cgroups 

→ ↓ 
```
LEVEL 2 — Linux Security
```
Capabilities 
seccomp 
AppArmor 
SELinux 
Namespaces 

→ ↓ 
```
LEVEL 3 — Kubernetes Fundamentals
```
Pods 
Deployments 
Services 
Ingress 
ConfigMaps 
Secrets 
Namespaces 

→ ↓ 
```
LEVEL 4 — Authentication / RBAC
```
Users 
ServiceAccounts 
Roles 
ClusterRoles 
RoleBindings 

→ ↓ 
```
LEVEL 5 — Workload Security
```
SecurityContext 
Pod Security Standards 
Privileged containers 
Capabilities 

→ ↓ 
```
LEVEL 6 — Network Security
```
NetworkPolicy 
Ingress 
Service exposure 
Cilium / Calico 

→ ↓ 
```
LEVEL 7 — Secrets
```
Kubernetes Secrets 
External secrets 
KMS 
Vault 

→ ↓ 
```
LEVEL 8 — Image Security
```
Trivy 
Grype 
SBOM 
Syft 
Registry scanning 

→ ↓ 
```
LEVEL 9 — Cluster Hardening
```
CIS Benchmark 
kube-bench 
NSA/CISA guidance 
Kubescape 

→ ↓ 
```
LEVEL 10 — Admission Control
```
Kyverno 
OPA Gatekeeper 
Policy as Code 

→ ↓ 
```
LEVEL 11 — Runtime Security
```
Falco 
Tetragon 
Tracee 
eBPF 

→ ↓ 
```
LEVEL 12 — Supply Chain
```
Cosign 
Sigstore 
SBOM 
SLSA 
Provenance 

→ ↓ 
```
LEVEL 13 — Offensive Security
```
Kubernetes Goat 
RBAC abuse 
ServiceAccount abuse 
Node access 
Container breakout labs 

→ ↓ 
```
LEVEL 14 — Detection
```
Audit logs 
Falco rules 
Runtime telemetry 
SIEM 

→ ↓ 
```
LEVEL 15 — Managed Kubernetes
```
EKS 
AKS 
GKE 
Cloud IAM integration 

→ ↓ 
```
LEVEL 16 — Compliance
```
CIS 
NIST SP 800-190 
NSA/CISA 
MITRE ATT&CK 
SLSA 

→ ↓ 
```
LEVEL 17 — Advanced
```
Multi-tenancy 
Confidential containers 
Service mesh 
eBPF 
AI/GPU workload security 

- ⭐ Container & Kubernetes Security — Top 15 
| Rank | Resource | Purpose |
| --- | --- | --- |
| 1 |
| [Kubernetes Security Docs](https://kubernetes.io/docs/concepts/security/) |
| Core reference |
| 2 |
| [CIS Kubernetes Benchmark](https://www.cisecurity.org/benchmark/kubernetes) |
| Hardening |
| 3 |
| [NSA/CISA Hardening Guide](https://www.nsa.gov/Press-Room/News-Highlights/Article/Article/2716980/nsa-cisa-release-kubernetes-hardening-guidance/) |
| Government guidance |
| 4 |
| [NIST SP 800-190](https://csrc.nist.gov/pubs/sp/800/190/final) |
| Container security |
| 5 |
| [Trivy](https://github.com/aquasecurity/trivy) |
| Images/config/SBOM |
| 6 |
| [Kubescape](https://github.com/kubescape/kubescape) |
| Cluster posture |
| 7 |
| [kube-bench](https://github.com/aquasecurity/kube-bench) |
| CIS checking |
| 8 |
| [Falco](https://falco.org/) |
| Runtime security |
| 9 |
| [Tetragon](https://tetragon.io/) |
| eBPF security |
| 10 |
| [Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat) |
| Hands-on lab |
| 11 |
| [Kyverno](https://kyverno.io/) |
| Policy enforcement |
| 12 |
| [OPA Gatekeeper](https://github.com/open-policy-agent/gatekeeper) |
| Admission control |
| 13 |
| [Syft](https://github.com/anchore/syft) |
| SBOM |
| 14 |
| [CKS](https://training.linuxfoundation.org/certification/certified-kubernetes-security-specialist/) |
| Certification |
| 15 |
| [CNCF Security TAG](https://tag-security.cncf.io/) |
| Cloud-native security research |

#### Recommended practical stack 
Docker/Linux fundamentals → Kubernetes architecture → RBAC → Pod Security Standards → NetworkPolicy → Secrets → Trivy/Syft → CIS + kube-bench → Kubescape → Kyverno/Gatekeeper → Falco/Tetragon → supply-chain signing/SBOM/SLSA → Kubernetes Goat → CKS → professional security assessment report.

---

<div align="center">
<sub>🐳 Container & Kubernetes Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>