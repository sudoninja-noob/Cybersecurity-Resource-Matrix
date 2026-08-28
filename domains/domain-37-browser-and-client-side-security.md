# 🌐 Domain 37: Browser & Client-Side Security

> **Group:** Network, Web & Application  
> **Curated links:** 4  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

Your uploaded material already includes browser zero-day research, sandbox-escape material, WebKit fuzzing, Pwn2Own, OffensiveCon and Google Project Zero references.

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

- ⭐⭐⭐ [Chromium Security Architecture/Core Principles](https://www.chromium.org/Home/chromium-security/core-principles/)⭐⭐⭐ [MDN Web Security](https://developer.mozilla.org/en-US/docs/Web/Security)⭐⭐⭐ PortSwigger Client-Side topics Chromium's security model emphasizes defense in depth, combining process sandboxing with exploit mitigations and safe-update mechanisms. ( [Chromium](https://www.chromium.org/Home/chromium-security/core-principles/))

---

## Section 02: Methodology <a name="section-02"></a>

Origin model → parser → DOM → JavaScript → rendering engine → IPC → sandbox → extensions → WebAssembly → native interfaces → OS boundary.

---

## Section 03: Standards / Compliance <a name="section-03"></a>

WHATWG HTML · ECMAScript · CSP · Trusted Types · Same-Origin Policy · Fetch/CORS · WebAssembly.

---

## Section 04: Official Documentation <a name="section-04"></a>

MDN · Chromium Security · Mozilla Security · WebKit Security · WHATWG.

---

## Section 05: Checklists <a name="section-05"></a>

SOP · CORS · CSP · Trusted Types · sandboxed iframes · postMessage · DOM sinks · extensions · service workers · storage · WebAssembly · downloads · permissions

---

## Section 06: Cheat Sheets <a name="section-06"></a>

OWASP DOM XSS Cheat Sheet · CSP Cheat Sheet · PortSwigger DOM-based vulnerability references.

---

## Section 07: Tools <a name="section-07"></a>

Chrome DevTools · Firefox DevTools · Burp DOM Invader · Ghidra · LLDB/GDB · WinDbg · Frida · AFL++ · libFuzzer.

---

## Section 08: Labs / Practice <a name="section-08"></a>

PortSwigger DOM labs · browser-engine fuzzing labs · Pwn2Own writeups · WebKit/Chromium builds.

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

DOM XSS · prototype pollution · origin confusion · postMessage trust · extension permission abuse · sandbox boundary tests in controlled builds.

---

## Section 10: YouTube / Video <a name="section-10"></a>

> Source combines sections 10–12: Video / Courses / Certifications

Project Zero talks · Pwn2Own · OffensiveCon browser exploitation · OpenSecurityTraining.

---

## Section 11: Courses / Training <a name="section-11"></a>

> Source combines sections 10–12: Video / Courses / Certifications

Project Zero talks · Pwn2Own · OffensiveCon browser exploitation · OpenSecurityTraining.

---

## Section 12: Certifications <a name="section-12"></a>

> Source combines sections 10–12: Video / Courses / Certifications

Project Zero talks · Pwn2Own · OffensiveCon browser exploitation · OpenSecurityTraining.

---

## Section 13: Books <a name="section-13"></a>

The Tangled Web · browser internals references · JavaScript-engine internals material.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

> Source combines sections 14–17: Research

Google Project Zero · Chrome Security · Mozilla Security · WebKit · ZDI/Pwn2Own · OffensiveCon.

---

## Section 15: Research Papers <a name="section-15"></a>

> Source combines sections 14–17: Research

Google Project Zero · Chrome Security · Mozilla Security · WebKit · ZDI/Pwn2Own · OffensiveCon.

---

## Section 16: White Papers <a name="section-16"></a>

> Source combines sections 14–17: Research

Google Project Zero · Chrome Security · Mozilla Security · WebKit · ZDI/Pwn2Own · OffensiveCon.

---

## Section 17: Conference Material <a name="section-17"></a>

> Source combines sections 14–17: Research

Google Project Zero · Chrome Security · Mozilla Security · WebKit · ZDI/Pwn2Own · OffensiveCon.

---

## Section 18: Mind Maps <a name="section-18"></a>

HTML/parser → DOM → JS engine → renderer → IPC → sandbox → browser process → OS.

---

## Section 19: Sample Reports <a name="section-19"></a>

> Source combines sections 19–20: Reports / Templates

Client-side test plan · CSP review · extension security review · browser vulnerability research notes.

---

## Section 20: Templates <a name="section-20"></a>

> Source combines sections 19–20: Reports / Templates

Client-side test plan · CSP review · extension security review · browser vulnerability research notes.

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

Chrome/V8 · Firefox/SpiderMonkey · Safari/WebKit · Edge/Chromium vulnerabilities.

---

## Section 22: GitHub Repositories <a name="section-22"></a>

Chromium · WebKit · Firefox · DOMPurify · fuzzing tools.

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

Pwn2Own writeups · OSS-Fuzz browser bugs · JavaScript test corpora.

---

## Section 24: Communities / Forums <a name="section-24"></a>

> Source combines sections 24–25: Communities / Vendors

Chromium · Mozilla · WebKit · Project Zero · ZDI.

---

## Section 25: Vendors / Products <a name="section-25"></a>

> Source combines sections 24–25: Communities / Vendors

Chromium · Mozilla · WebKit · Project Zero · ZDI.

---

## Section 26: Latest Developments <a name="section-26"></a>

Trusted Types became broadly available across current browsers in 2026, making it more practical as a cross-browser DOM-XSS defense alongside CSP. ( [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/Content-Security-Policy/trusted-types))

---

## Section 27: Learning Roadmap <a name="section-27"></a>

Web platform → JavaScript → SOP/CORS/CSP → DOM security → browser internals → IPC/sandbox → JS-engine RE → browser VR.

---

<div align="center">
<sub>🌐 Browser & Client-Side Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>