# 📱 Domain 04: Mobile Security

> **Group:** Network, Web & Application  
> **Curated links:** 124  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

This is the GitHub/website-ready Mobile Security resource set in the same 27-category structure. 
Your uploaded Offensive Resources material already includes a dedicated mobile section with OWASP Mobile Security Testing Guide, Mobile Application Hacker’s Handbook, Android Hacker’s Handbook, iOS Hacker’s Handbook, eMAPT, SEC575, Damn Vulnerable iOS Application, vulnerable Android apps, and ExploitMe labs. I’ve refined that list and expanded it with the current OWASP MAS ecosystem, platform documentation, modern tools, labs, and compliance references. 
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

The strongest starting point today is the OWASP Mobile Application Security project. 

| Resource | Type | Why Use It |
| --- | --- | --- |
| OWASP MASVS |
| Official / Free |
| Mobile security verification standard |
| OWASP MASTG |
| Official / Free |
| Complete mobile security testing guide |
| OWASP MASWE |
| Official / Free |
| Mobile weakness enumeration |
| Android Security Documentation |
| Official / Free |
| Android platform/application security |
| Apple Platform Security |
| Official / Free |
| iOS/iPadOS platform security architecture |
| NIST SP 800-163 Rev.1 |
| Official / Free |
| Mobile application vetting methodology |

[OWASP Mobile Application Security](https://mas.owasp.org/)[OWASP MASVS](https://mas.owasp.org/MASVS/)[OWASP MASTG](https://mas.owasp.org/MASTG/)[OWASP MASWE](https://mas.owasp.org/MASWE/)[Apple Platform Security](https://support.apple.com/guide/security/welcome/web)[NIST SP 800-163 Rev.1](https://csrc.nist.gov/pubs/sp/800/163/r1/final)
OWASP now has a particularly clean traceability model: 
MASVS control → MASWE weakness → MASTG test → MASTG demo. 
MASTG v2.0.0 became the first stable release of the refactored testing guide in 2026, while MASWE v1.0.0 became stable in August 2026 with 78 weaknesses. ( [OWASP Mobile Application Security](https://mas.owasp.org/news/2026/07/04/mastg-v200-release/))

---

## Section 02: Methodology <a name="section-02"></a>

Primary Methodology 
Use these together: 
OWASP MASVS 
OWASP MASWE 
OWASP MASTG 
NIST SP 800-163 Rev.1 
Android security documentation 
Apple Platform Security 
[OWASP MAS Project](https://mas.owasp.org/)[NIST Mobile App Vetting](https://www.nist.gov/publications/vetting-security-mobile-applications-0)
NIST SP 800-163 Rev.1 defines a structured mobile-application vetting process for determining whether an application meets an organization's security requirements and is reasonably free from vulnerabilities. ( [NIST](https://www.nist.gov/publications/vetting-security-mobile-applications-0)) 

#### Recommended Mobile Pentest Workflow 
Authorization / Scope 

→ ↓ Platform Identification 

→ ↓ Application Acquisition 

→ ↓ APK / IPA Analysis 

→ ↓ Application Metadata 

→ ↓ Static Analysis 

→ ↓ Manifest / Entitlement Review 

→ ↓ Permissions 

→ ↓ Local Storage 

→ ↓ Cryptography 

→ ↓ Authentication 

→ ↓ Authorization 

→ ↓ Network Communication 

→ ↓ Platform Interaction 

→ ↓ IPC / Deep Links 

→ ↓ WebViews 

→ ↓ Dynamic Analysis 

→ ↓ Runtime Instrumentation 

→ ↓ Backend/API Testing 

→ ↓ Resilience / Anti-Tamper 

→ ↓ Privacy Review 

→ ↓ MASVS / MASWE Mapping 

→ ↓ Reporting 

→ ↓ Retesting

---

## Section 03: Standards / Compliance <a name="section-03"></a>

| Standard / Framework | Coverage |
| --- | --- |
| ⭐⭐⭐ OWASP MASVS |
| Mobile application security verification |
| ⭐⭐⭐ OWASP MASWE |
| Mobile weakness taxonomy |
| ⭐⭐⭐ OWASP MASTG |
| Mobile security testing |
| NIST SP 800-163 Rev.1 |
| Application security vetting |
| NIST SP 800-124 Rev.2 |
| Enterprise mobile-device security |
| NIAP Mobile Application PP |
| Mobile application assurance |
| PCI DSS |
| Payment applications/mobile payment |
| ISO/IEC 27001 |
| General information security |
| ISO/IEC 27034 |
| Application security |
| GDPR |
| Mobile privacy/data processing |
| Apple Platform Security |
| iOS platform security reference |
| Android Security |
| Android application/platform requirements |

MASVS currently organizes controls across areas such as storage, cryptography, authentication, networking, platform interaction, code quality, resilience, and privacy. ( [OWASP Mobile Application Security](https://mas.owasp.org/MASVS/))

---

## Section 04: Official Documentation <a name="section-04"></a>

OWASP 
[OWASP MAS](https://mas.owasp.org/)
[MASVS](https://mas.owasp.org/MASVS/)
[MASTG](https://mas.owasp.org/MASTG/)
[MASWE](https://mas.owasp.org/MASWE/)
[MASTG Testing Tools](https://mas.owasp.org/MASTG/tools/)
[MASTG Tests](https://mas.owasp.org/MASTG/tests/)
[MASTG Techniques](https://mas.owasp.org/MASTG/techniques/)
Android 
[Android Developers Security](https://developer.android.com/privacy-and-security/security)
[Android App Security Best Practices](https://developer.android.com/privacy-and-security/security-best-practices)
[Android Keystore](https://developer.android.com/privacy-and-security/keystore)
[Network Security Configuration](https://developer.android.com/privacy-and-security/security-config)
Apple 
[Apple Platform Security](https://support.apple.com/guide/security/welcome/web)
[Apple Developer Security](https://developer.apple.com/security/)
[Keychain Services](https://developer.apple.com/documentation/security/keychain-services)
[App Transport Security](https://developer.apple.com/documentation/security/preventing-insecure-network-connections)
Apple's current Platform Security guide covers hardware, system security, encryption/data protection and application security across Apple's platforms. ( [Apple Support](https://support.apple.com/en-by/guide/security/secfe0c7d4a5/web))

---

## Section 05: Checklists <a name="section-05"></a>

Best sources: 
OWASP MASVS 
OWASP MASTG tests 
MASWE 
Android security best practices 
Apple Platform Security 
NIST SP 800-163 

#### Recommended Mobile Security Checklist 
Application metadata 
Application signing 
Debuggable status 
Backup settings 
Permissions 
Exported components 
Deep links 
Universal links 
Intent filters 
URL schemes 
Local storage 
SharedPreferences 
SQLite 
Files 
Caches 
Logs 
Clipboard 
Screenshots 
Keychain / Keystore 
Cryptographic algorithms 
Cryptographic keys 
Biometric authentication 
Authentication 
Authorization 
Session handling 
Tokens 
JWT 
Network security 
TLS 
Certificate validation 
Certificate pinning 
WebViews 
JavaScript bridges 
IPC 
Intents 
Content providers 
Services 
Broadcast receivers 
Custom URL schemes 
Root / jailbreak detection 
Anti-debugging 
Anti-tamper 
Obfuscation 
Runtime integrity 
Privacy 
Tracking 
Third-party SDKs 
Backend/API security

---

## Section 06: Cheat Sheets <a name="section-06"></a>

#### Recommended: 
[OWASP MASTG](https://mas.owasp.org/MASTG/)
[OWASP MAS Cheat Sheets](https://mas.owasp.org/)
[HackTricks Android](https://book.hacktricks.wiki/en/mobile-pentesting/android-app-pentesting/index.html)
[HackTricks iOS](https://book.hacktricks.wiki/en/mobile-pentesting/ios-pentesting/index.html)
[Frida Documentation](https://frida.re/docs/home/)
[ADB Documentation](https://developer.android.com/tools/adb)
Useful command areas 
adb 
aapt / aapt2 
apkanalyzer 
apktool 
jadx 
frida 
objection 
ideviceinstaller 
ideviceinfo 
iproxy 
codesign 
otool 
nm 
strings 
class-dump

---

## Section 07: Tools <a name="section-07"></a>

OWASP MASTG maintains its own current testing-tool catalogue and explicitly includes tools for static analysis, dynamic analysis and interception. Frida, MobSF and adb are among tools currently indexed there. ( [OWASP Mobile Application Security](https://mas.owasp.org/MASTG/tools/)) 
Android 

| Tool | Purpose |
| --- | --- |
| ⭐⭐⭐ MobSF |
| Automated static/dynamic analysis |
| ⭐⭐⭐ Frida |
| Runtime instrumentation |
| ⭐⭐⭐ Objection |
| Runtime mobile exploration |
| ⭐⭐⭐ JADX |
| APK/Dex decompilation |
| ⭐⭐⭐ APKTool |
| APK decode/rebuild |
| adb |
| Device interaction |
| Drozer |
| Android component testing |
| Androguard |
| APK analysis |
| Ghidra |
| Native binary reversing |
| Burp Suite |
| Network/API interception |

[MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF)[Frida](https://frida.re/)[Objection](https://github.com/sensepost/objection)[JADX](https://github.com/skylot/jadx)[APKTool](https://apktool.org/)[Androguard](https://github.com/androguard/androguard)
iOS 

| Tool | Purpose |
| --- | --- |
| ⭐⭐⭐ Frida |
| Runtime instrumentation |
| ⭐⭐⭐ Objection |
| Dynamic testing |
| Ghidra |
| Mach-O/native reversing |
| LLDB |
| Debugging |
| MobSF |
| IPA analysis |
| Burp Suite |
| Network interception |
| libimobiledevice |
| Device interaction |
| class-dump |
| Objective-C metadata |
| otool |
| Mach-O analysis |
| Hopper |
| Commercial reversing |

[libimobiledevice](https://github.com/libimobiledevice/libimobiledevice)[LLDB](https://lldb.llvm.org/)[Ghidra](https://github.com/NationalSecurityAgency/ghidra)

---

## Section 08: Labs / Practice <a name="section-08"></a>

Your original source already included DVIA, intentionally vulnerable Android apps and ExploitMe mobile labs. 
A stronger current collection: 

| Lab | Platform |
| --- | --- |
| ⭐⭐⭐ InsecureShop |
| Android |
| ⭐⭐⭐ DIVA |
| Android |
| ⭐⭐⭐ DVIA-v2 |
| iOS |
| ⭐⭐⭐ OWASP MSTG Crackmes |
| Android / iOS |
| ⭐⭐ UnCrackable Apps |
| Android |
| ⭐⭐ InsecureBankv2 |
| Android |
| ⭐⭐ Damn Vulnerable Bank |
| Android |
| ⭐⭐ iGoat-Swift |
| iOS |
| ⭐⭐ OWASP GoatDroid |
| Android |

[OWASP MSTG Hacking Playground](https://github.com/OWASP/MASTG-Hacking-Playground)[DIVA Android](https://github.com/payatu/diva-android)[DVIA-v2](https://github.com/prateek147/DVIA-v2)[iGoat-Swift](https://github.com/OWASP/iGoat-Swift)[InsecureShop](https://github.com/optiv/InsecureShop)

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

For authorized assessment environments, maintain tests covering: 
Storage 
Tokens in SharedPreferences 
Credentials in SQLite 
Secrets in logs 
Sensitive cache data 
Clipboard exposure 
Backup exposure 
Screenshots 
Keychain / Keystore misuse 
Android Components 
Exported activities 
Exported services 
Broadcast receivers 
Content providers 
Intent manipulation 
PendingIntent misuse 
Deep links 
Network 
Cleartext HTTP 
TLS downgrade 
Invalid certificates 
Hostname validation 
Pinning 
Proxy behavior 
Sensitive headers 
WebView 
JavaScript enabled 
JavascriptInterface 
File access 
Universal access 
URL validation 
Mixed content 
Runtime 
Root/jailbreak checks 
Debugger detection 
Hook detection 
Integrity verification 
Repackaging resistance 
Useful collections: 
[PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)
[SecLists](https://github.com/danielmiessler/SecLists)
[MASTG Tests](https://mas.owasp.org/MASTG/tests/)

---

## Section 10: YouTube / Video <a name="section-10"></a>

#### Recommended sources: 

| Channel | Focus |
| --- | --- |
| ⭐⭐⭐ OWASP Global |
| MASVS/MASTG talks |
| ⭐⭐⭐ Hardwear.io |
| Mobile/hardware research |
| ⭐⭐⭐ Black Hat |
| Android/iOS security |
| ⭐⭐⭐ DEF CON |
| Mobile exploitation |
| ⭐⭐ NowSecure |
| Mobile AppSec |
| ⭐⭐ Guardsquare |
| Mobile reverse engineering |
| ⭐⭐ LiveOverflow |
| Exploitation/reversing |

[OWASP YouTube](https://www.youtube.com/@OWASPGLOBAL)[Black Hat YouTube](https://www.youtube.com/@BlackHatOfficialYT)[DEF CON YouTube](https://www.youtube.com/@DEFCONConference)[Hardwear.io](https://www.youtube.com/@hardweario)
Search for: 
Android reverse engineering 
Frida Android 
Frida iOS 
APK reversing 
IPA reversing 
Android IPC security 
iOS Keychain 
Android Keystore 
Certificate pinning 
Mobile malware 
Secure mobile storage

---

## Section 11: Courses / Training <a name="section-11"></a>

Your source already lists eMAPT and SANS SEC575 in the mobile track. 

#### Recommended current options: 

| Course | Level |
| --- | --- |
| ⭐⭐⭐ SANS SEC575 |
| Intermediate / Advanced |
| ⭐⭐⭐ INE Mobile Security/eMAPT path |
| Practical |
| ⭐⭐⭐ 7ASecurity Mobile Hacking |
| Advanced |
| ⭐⭐ PentesterLab Mobile-related exercises |
| Practical |
| ⭐⭐ Hack The Box Academy Android modules |
| Hands-on |
| ⭐⭐ OWASP MASTG self-study |
| Free |

[SANS SEC575](https://www.sans.org/cyber-security-courses/mobile-device-security-ethical-hacking/)[OWASP MASTG](https://mas.owasp.org/MASTG/)[7ASecurity](https://7asecurity.com/)

---

## Section 12: Certifications <a name="section-12"></a>

| Certification | Focus |
| --- | --- |
| eMAPT |
| Mobile application pentesting |
| GMOB |
| Mobile device/mobile application security |
| OSWE |
| Useful for mobile backend/source review |
| BSCP |
| Useful for API/backend testing |
| CPTS |
| Broader pentest foundation |

[GIAC GMOB](https://www.giac.org/certifications/mobile-device-security-analyst-gmob/)[INE Security Certifications](https://security.ine.com/certifications/)
Dedicated mobile pentesting certifications remain much less common than web/network certifications.

---

## Section 13: Books <a name="section-13"></a>

Your uploaded collection has several foundational mobile books. 

#### Recommended: 

- ⭐⭐⭐ Mobile Application Hacker's Handbook 
- ⭐⭐⭐ Android Hacker's Handbook 
- ⭐⭐⭐ iOS Hacker's Handbook 
- ⭐⭐⭐ OWASP MASTG — treat it as a living book 
- ⭐⭐ Learning Android Forensics 
- ⭐⭐ Android Security Internals 
- ⭐⭐ iOS Application Security For current technical work, MASTG is more important than older printed mobile-hacking books, because Android/iOS security APIs and platform protections evolve quickly.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

High-value sources: 

- ⭐⭐⭐ [OWASP MAS Blog](https://mas.owasp.org/news/)
- ⭐⭐⭐ [Google Project Zero](https://googleprojectzero.blogspot.com/)
- ⭐⭐⭐ [Google Security Blog](https://security.googleblog.com/)
- ⭐⭐⭐ [Android Security Blog](https://security.googleblog.com/search/label/Android)
- ⭐⭐⭐ [Apple Security Research](https://security.apple.com/)
- ⭐⭐⭐ [NowSecure Blog](https://www.nowsecure.com/blog/)
- ⭐⭐ [Guardsquare Blog](https://www.guardsquare.com/blog)
- ⭐⭐ [WithSecure Labs](https://labs.withsecure.com/)
- ⭐⭐ [Trail of Bits](https://blog.trailofbits.com/)
- ⭐⭐ [Quarkslab Blog](https://blog.quarkslab.com/)OWASP's MAS project is especially useful as a living update feed because it publishes MASTG/MASWE release changes and testing guidance. ( [OWASP Mobile Application Security](https://mas.owasp.org/news/?trk=public_post-text))

---

## Section 15: Research Papers <a name="section-15"></a>

#### Recommended repositories/conferences: 
USENIX Security 
IEEE Security & Privacy 
NDSS 
ACM CCS 
ACM WiSec 
Mobile Security Workshop 
WOOT 
arXiv 
[USENIX Security](https://www.usenix.org/conferences/byname/108)[IEEE Security & Privacy](https://www.ieee-security.org/TC/SP-Index.html)[NDSS](https://www.ndss-symposium.org/ndss-paper/)[ACM CCS](https://www.sigsac.org/ccs.html)

#### Important research topics: 
Android sandbox escapes 
Binder security 
Intent vulnerabilities 
WebView exploitation 
iOS sandbox 
iOS kernel attacks 
Secure Enclave 
Mobile baseband 
Mobile spyware 
App supply chain 
SDK security 
Runtime instrumentation detection 
Mobile privacy

---

## Section 16: White Papers <a name="section-16"></a>

Strong references: 
OWASP MASVS 
OWASP MASTG 
OWASP MASWE 
NIST SP 800-163 Rev.1 
Apple Platform Security 
Android Security 
Google Android Security & Privacy Year in Review 
NowSecure research reports 
Guardsquare mobile security reports 
[NIST Mobile Application Vetting](https://www.nist.gov/publications/vetting-security-mobile-applications-0)[Apple Platform Security](https://support.apple.com/guide/security/welcome/web)[Google Android Security](https://source.android.com/docs/security)

---

## Section 17: Conference Material <a name="section-17"></a>

| Conference | Relevant Focus |
| --- | --- |
| ⭐⭐⭐ Black Hat |
| Android/iOS exploitation |
| ⭐⭐⭐ DEF CON |
| Mobile research |
| ⭐⭐⭐ OWASP Global AppSec |
| Mobile AppSec |
| ⭐⭐⭐ Hardwear.io |
| Mobile/hardware |
| ⭐⭐⭐ USENIX Security |
| Academic mobile research |
| ⭐⭐ Nullcon |
| Mobile offensive research |
| ⭐⭐ TROOPERS |
| Mobile/network security |
| ⭐⭐ REcon |
| Reverse engineering |

[Black Hat](https://www.blackhat.com/)[DEF CON](https://defcon.org/)[OWASP Events](https://owasp.org/events/)[Hardwear.io](https://hardwear.io/)[REcon](https://recon.cx/)

---

## Section 18: Mind Maps <a name="section-18"></a>

#### Recommended structure: 
MOBILE SECURITY 

```
│
```

```
├── Android
```

```
│   ├── APK
```

```
│   ├── Manifest
```

```
│   ├── Permissions
```

```
│   ├── Activities
```

```
│   ├── Services
```

```
│   ├── Receivers
```

```
│   ├── Providers
```

```
│   └── Intents
```

```
│
```

```
├── iOS
```

```
│   ├── IPA
```

```
│   ├── Entitlements
```

```
│   ├── Keychain
```

```
│   ├── URL Schemes
```

```
│   ├── Universal Links
```

```
│   └── ATS
```

```
│
```

```
├── Storage
```

```
│   ├── Files
```

```
│   ├── Database
```

```
│   ├── Preferences
```

```
│   └── Secrets
```

```
│
```

```
├── Authentication
```

```
│   ├── Biometrics
```

```
│   ├── PIN
```

```
│   ├── Tokens
```

```
│   └── Sessions
```

```
│
```

```
├── Network
```

```
│   ├── TLS
```

```
│   ├── Pinning
```

```
│   └── API
```

```
│
```

```
├── Platform
```

```
│   ├── IPC
```

```
│   ├── Deep Links
```

```
│   ├── WebViews
```

```
│   └── Clipboard
```

```
│
```

```
├── Reverse Engineering
```

```
│   ├── JADX
```

```
│   ├── Ghidra
```

```
│   ├── Frida
```

```
│   └── LLDB
```

```
│
```

```
├── Resilience
```

```
│   ├── Root/Jailbreak
```

```
│   ├── Anti-debug
```

```
│   ├── Anti-hook
```

```
│   └── Anti-tamper
```

```
│
```

```
└── Privacy
```

---

## Section 19: Sample Reports <a name="section-19"></a>

#### Useful sources: 
OWASP MASTG 
OWASP MASVS assessment mapping 
NIST app-vetting methodology 
public pentest reports 
mobile bug-bounty disclosures 

#### Recommended report structure: 
Executive Summary 
Scope 
Application Information 
Platform / OS 
Application Version 
Methodology 
Static Analysis 
Dynamic Analysis 
Storage 
Cryptography 
Authentication 
Network 
Platform Interaction 
Code Quality 
Resilience 
Privacy 
Backend/API Security 
Findings 
Evidence 
MASVS Mapping 
MASWE Mapping 
CWE 
CVSS 
Remediation 
Retest 
Conclusion

---

## Section 20: Templates <a name="section-20"></a>

#### Recommended GitHub structure: 
/templates/mobile-security/ 

```
├── mobile-test-plan.md
```

```
├── android-checklist.md
```

```
├── ios-checklist.md
```

```
├── mobile-test-cases.md
```

```
├── apk-analysis.md
```

```
├── ipa-analysis.md
```

```
├── storage-testing.md
```

```
├── crypto-testing.md
```

```
├── auth-testing.md
```

```
├── network-testing.md
```

```
├── deep-link-testing.md
```

```
├── webview-testing.md
```

```
├── resilience-testing.md
```

```
├── privacy-testing.md
```

```
├── evidence-template.md
```

```
├── mobile-pentest-report.md
```

```
└── masvs-maswe-mapping.md
```

#### Recommended fields: 
Test ID 
MASTG Test ID 
MASWE ID 
MASVS Control 
Platform 
Application Version 
Objective 
Precondition 
Tool 
Procedure 
Expected Result 
Actual Result 
Evidence 
CWE 
CVSS 
Severity 
Status

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

Primary sources: 
[CVE.org](https://www.cve.org/)
[NVD](https://nvd.nist.gov/)
[Google Project Zero](https://googleprojectzero.blogspot.com/)
[Android Security Bulletins](https://source.android.com/docs/security/bulletin)
[Apple Security Releases](https://support.apple.com/en-us/100100)
[CISA KEV](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)
Track vulnerabilities involving: 
Android framework 
Binder 
WebView 
Bluetooth 
Baseband 
Kernel 
iOS kernel 
WebKit 
Sandbox escapes 
Secure Enclave 
Mobile browsers 
Deep links 
Intents 
Third-party SDKs 
Authentication 
Mobile spyware

---

## Section 22: GitHub Repositories <a name="section-22"></a>

#### Essential 

- ⭐⭐⭐ [OWASP MASTG](https://github.com/OWASP/mastg)
- ⭐⭐⭐ [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF)
- ⭐⭐⭐ [Frida](https://github.com/frida/frida)
- ⭐⭐⭐ [Objection](https://github.com/sensepost/objection)
- ⭐⭐⭐ [JADX](https://github.com/skylot/jadx)
- ⭐⭐⭐ [APKTool](https://github.com/iBotPeaches/Apktool)
- ⭐⭐ [Androguard](https://github.com/androguard/androguard)
- ⭐⭐ [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice)
- ⭐⭐ [DIVA](https://github.com/payatu/diva-android)
- ⭐⭐ [DVIA-v2](https://github.com/prateek147/DVIA-v2)
- ⭐⭐ [iGoat-Swift](https://github.com/OWASP/iGoat-Swift)
- ⭐⭐ [MASTG Hacking Playground](https://github.com/OWASP/MASTG-Hacking-Playground)

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

#### Useful sources: 
intentionally vulnerable APKs 
MASTG test apps 
DIVA 
InsecureShop 
iGoat 
DVIA 
malware datasets for defensive research 
Android application datasets 
For clean lab organization: 
mobile-security-lab/ 

```
│
```

```
├── android/
```

```
│   ├── apks/
```

```
│   ├── decompiled/
```

```
│   ├── frida/
```

```
│   └── reports/
```

```
│
```

```
├── ios/
```

```
│   ├── ipa/
```

```
│   ├── binaries/
```

```
│   ├── frida/
```

```
│   └── reports/
```

```
│
```

```
├── pcaps/
```

```
├── backend-api/
```

```
└── evidence/
```

---

## Section 24: Communities / Forums <a name="section-24"></a>

#### Recommended: 
[OWASP Mobile Application Security](https://mas.owasp.org/)
[OWASP Slack](https://owasp.org/slack/invite)
[Frida Community](https://github.com/frida/frida)
[Android Security Discussions](https://source.android.com/docs/security)
[Reverse Engineering Stack Exchange](https://reverseengineering.stackexchange.com/)
[Security Stack Exchange](https://security.stackexchange.com/)
r/ReverseEngineering 
r/netsec 
mobile security research communities

---

## Section 25: Vendors / Products <a name="section-25"></a>

| Area | Important Platforms |
| --- | --- |
| Mobile App Security Testing |
| NowSecure |
| Mobile App Protection |
| Guardsquare |
| RASP / Anti-tamper |
| Guardsquare, Promon |
| Automated analysis |
| MobSF |
| Runtime instrumentation |
| Frida |
| Device security |
| Zimperium |
| Mobile threat defense |
| Lookout, Zimperium |
| App shielding |
| Appdome |
| SAST/SCA |
| Semgrep, CodeQL, Snyk |

Keep OWASP MASVS/MASTG as the neutral testing baseline and use commercial products as additional tooling.

---

## Section 26: Latest Developments <a name="section-26"></a>

This category has several important 2026 changes. 
MASTG v2.0.0 
OWASP released the first stable version of the fully refactored MASTG in 2026. It now uses smaller, independently referenceable tests, techniques and demos rather than the older long-form structure. ( [OWASP Mobile Application Security](https://mas.owasp.org/news/2026/07/04/mastg-v200-release/)) 
MASWE v1.0.0 
Released August 17, 2026. 
It now contains 78 stable weaknesses organized under: 
Storage 
Cryptography 
Authentication 
Network 
Platform 
Code 
Resilience 
Privacy 
It also adds weaknesses covering areas such as accessibility-service leakage, malicious code in apps, root/jailbreak detection, malware detection, privacy-preserving functionality and reproducible builds. ( [OWASP Mobile Application Security](https://mas.owasp.org/news/2026/08/17/maswe-v100-release/)) 

#### Important current topics 
Mobile supply-chain security 
Third-party SDK security 
App privacy 
Mobile spyware 
Passkeys 
Biometric authentication 
Hardware-backed keys 
Runtime protection 
Root / jailbreak bypass 
Mobile API security 
Android exported components 
Android intent security 
iOS universal links 
WebViews 
Secure Enclave 
Play Integrity API 
App Attest 
DeviceCheck 
AI-powered mobile applications 
LLM/mobile backend integration

---

## Section 27: Learning Roadmap <a name="section-27"></a>

```
LEVEL 1 — Mobile Fundamentals
```
Android architecture 
iOS architecture 
APK 
IPA 
DEX 
Mach-O 
Application sandbox 

→ ↓ 
```
LEVEL 2 — Android Basics
```
Manifest 
Permissions 
Activities 
Services 
Receivers 
Providers 
Intents 

→ ↓ 
```
LEVEL 3 — iOS Basics
```
Entitlements 
Keychain 
ATS 
URL schemes 
Universal Links 
App sandbox 

→ ↓ 
```
LEVEL 4 — Static Analysis
```
JADX 
APKTool 
MobSF 
strings 
Ghidra 
Manifest analysis 

→ ↓ 
```
LEVEL 5 — Storage
```
SharedPreferences 
SQLite 
Files 
Cache 
Keychain 
Keystore 
Logs 

→ ↓ 
```
LEVEL 6 — Network
```
Burp Suite 
TLS 
Certificates 
Certificate pinning 
API traffic 

→ ↓ 
```
LEVEL 7 — Authentication
```
Tokens 
JWT 
Biometrics 
Sessions 
Device binding 

→ ↓ 
```
LEVEL 8 — Platform Interaction
```
Intents 
IPC 
Deep Links 
Universal Links 
WebViews 

→ ↓ 
```
LEVEL 9 — Dynamic Analysis
```
adb 
Frida 
Objection 
LLDB 
Runtime hooking 

→ ↓ 
```
LEVEL 10 — Reverse Engineering
```
Smali 
Java/Kotlin 
Swift/Objective-C 
ARM 
Ghidra 

→ ↓ 
```
LEVEL 11 — Resilience
```
Root detection 
Jailbreak detection 
Anti-debugging 
Anti-hooking 
Obfuscation 
Integrity checks 

→ ↓ 
```
LEVEL 12 — Backend/API
```
REST 
GraphQL 
OAuth 
JWT 
BOLA 
Authorization 

→ ↓ 
```
LEVEL 13 — Privacy
```
Permissions 
Tracking 
Identifiers 
PII 
Third-party SDKs 

→ ↓ 
```
LEVEL 14 — Advanced
```
Native libraries 
JNI 
Mach-O 
ARM64 
Runtime patching 
Mobile malware 

→ ↓ 
```
LEVEL 15 — Standards
```
MASVS 
MASWE 
MASTG 
NIST 800-163 
Platform security 

→ ↓ 
```
LEVEL 16 — Reporting
```
MASVS mapping 
MASWE mapping 
CWE 
CVSS 
Evidence 
Remediation 
Retest 

- ⭐ Mobile Security — Top 15 Resources 
| Rank | Resource | Purpose |
| --- | --- | --- |
| 1 |
| [OWASP MASTG](https://mas.owasp.org/MASTG/) |
| Testing methodology |
| 2 |
| [OWASP MASVS](https://mas.owasp.org/MASVS/) |
| Security requirements |
| 3 |
| [OWASP MASWE](https://mas.owasp.org/MASWE/) |
| Weakness taxonomy |
| 4 |
| [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) |
| Automated analysis |
| 5 |
| [Frida](https://frida.re/) |
| Runtime instrumentation |
| 6 |
| [JADX](https://github.com/skylot/jadx) |
| Android reversing |
| 7 |
| [APKTool](https://apktool.org/) |
| APK analysis/rebuild |
| 8 |
| [Objection](https://github.com/sensepost/objection) |
| Runtime exploration |
| 9 |
| [MASTG Hacking Playground](https://github.com/OWASP/MASTG-Hacking-Playground) |
| Hands-on practice |
| 10 |
| [DIVA](https://github.com/payatu/diva-android) |
| Android lab |
| 11 |
| [DVIA-v2](https://github.com/prateek147/DVIA-v2) |
| iOS lab |
| 12 |
| [Apple Platform Security](https://support.apple.com/guide/security/welcome/web) |
| iOS security reference |
| 13 |
| [Android Security](https://source.android.com/docs/security) |
| Android security reference |
| 14 |
| [NIST SP 800-163 Rev.1](https://csrc.nist.gov/pubs/sp/800/163/r1/final) |
| App vetting |
| 15 |
| [Ghidra](https://github.com/NationalSecurityAgency/ghidra) |
| Native reversing |

#### Recommended practical stack 
Android/iOS fundamentals → MASVS → MASTG → MobSF → JADX/APKTool → Burp → Frida/Objection → local storage → auth/network/platform testing → reverse engineering → resilience/privacy → MASWE mapping → professional mobile security report.

---

<div align="center">
<sub>📱 Mobile Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>