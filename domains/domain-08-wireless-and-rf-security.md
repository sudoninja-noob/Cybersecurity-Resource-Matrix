# 📡 Domain 08: Wireless & RF Security

> **Group:** Wireless, Hardware & Embedded  
> **Curated links:** 79  
> **Author:** [@sudoninja](https://github.com/sudoninja-noob) · SGS Brightsight

---

## Overview

This is the GitHub/website-ready Wireless & RF Security resource set in the same 27-category format. 
Your uploaded resources already contain a strong wireless section with OSWP, SANS SEC617, Aircrack-ng, Wifite, Kismet, Wireshark, Bettercap, Proxmark3, Ubertooth, WiFi-Pumpkin3, Airgeddon, EAPHammer, Flipper Zero, wireless books, labs, blogs and conference material. I’ve refined that list and expanded it to cover Wi-Fi + Bluetooth/BLE + RFID/NFC + SDR + Zigbee + Z-Wave + LoRa/LoRaWAN + GNSS and general RF analysis. 
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
| NIST SP 800-153 |
| Official / Free |
| WLAN security baseline |
| Bluetooth SIG Security |
| Official / Free |
| Bluetooth/BLE security |
| Wi-Fi Alliance |
| Official |
| Wi-Fi standards/security ecosystem |
| Wireless Broadband Alliance Security Guidelines |
| Industry / Free |
| Modern Wi-Fi security guidance |
| GNU Radio |
| Open Source |
| SDR/RF fundamentals |
| Great Scott Gadgets Tutorials |
| Free |
| SDR/Bluetooth/RF practical learning |

[NIST SP 800-153](https://csrc.nist.gov/pubs/sp/800/153/final)[Bluetooth SIG Security](https://www.bluetooth.com/learn-about-bluetooth/key-attributes/bluetooth-security/)[Wi-Fi Alliance](https://www.wi-fi.org/)[WBA Wi-Fi Security Guidelines](https://wballiance.com/wba-wi-fi-security-guidelines/)[GNU Radio](https://www.gnuradio.org/)[Great Scott Gadgets Tutorials](https://greatscottgadgets.com/)
NIST SP 800-153 focuses on securing WLAN components—including clients, APs and wireless infrastructure—across design, deployment, operation and monitoring. ( [NIST](https://www.nist.gov/publications/guidelines-securing-wireless-local-area-networks-wlans)) 
Core technologies 
802.11 Wi-Fi 
WPA2 
WPA3 
802.1X 
EAP 
RADIUS 
Bluetooth Classic 
Bluetooth Low Energy 
NFC 
RFID 
UHF RFID 
Zigbee 
Thread 
Z-Wave 
LoRa / LoRaWAN 
DECT 
Sub-GHz ISM 
433 MHz / 868 MHz / 915 MHz 
GNSS / GPS 
SDR 
RF modulation 
Spectrum analysis 
Antennas 
RF sniffing 
Protocol decoding

---

## Section 02: Methodology <a name="section-02"></a>

Use: 
NIST SP 800-153 
OWASP Wi-Fi Security Testing Guide 
Bluetooth SIG security guidance 
WBA Wi-Fi Security Guidelines 
FCC/ETSI radio references where applicable 
protocol-specific specifications 
The OWASP Wi-Fi Security Testing Guide project is specifically intended to create a standard Wi-Fi testing methodology covering procedures, vulnerabilities and recommendations. ( [GitHub](https://github.com/OWASP/www-project-wi-fi-security-testing-guide/blob/main/index.md)) 

#### Recommended Wireless Assessment Workflow 
Authorization / RF Scope 

→ ↓ Spectrum Survey 

→ ↓ Device / AP Discovery 

→ ↓ SSID / BSSID Mapping 

→ ↓ Channel / Frequency Mapping 

→ ↓ Security Mode Identification 

→ ↓ Authentication Review 

→ ↓ Encryption Review 

→ ↓ Client Behavior Analysis 

→ ↓ Enterprise 802.1X / EAP Review 

→ ↓ Management Frame Review 

→ ↓ Rogue AP Detection 

→ ↓ Segmentation Review 

→ ↓ Wireless-to-LAN Access Review 

→ ↓ Protocol Capture 

→ ↓ RF / SDR Analysis 

→ ↓ BLE / RFID / NFC / Zigbee Testing 

→ ↓ Privacy Review 

→ ↓ Monitoring / WIDS Review 

→ ↓ Risk Rating 

→ ↓ Reporting / Retest

---

## Section 03: Standards / Compliance <a name="section-03"></a>

| Standard / Framework | Area |
| --- | --- |
| ⭐⭐⭐ IEEE 802.11 |
| Wi-Fi |
| ⭐⭐⭐ WPA2/WPA3 |
| WLAN security |
| ⭐⭐⭐ NIST SP 800-153 |
| WLAN security |
| NIST SP 800-121 Rev.2 |
| Bluetooth security |
| IEEE 802.1X |
| Port-based authentication |
| EAP RFC 3748 |
| Authentication framework |
| Bluetooth Core Specification |
| Bluetooth/BLE |
| ISO/IEC 14443 |
| Contactless smart cards |
| ISO/IEC 15693 |
| Vicinity RFID |
| ISO/IEC 18000 |
| RFID |
| LoRaWAN Specification |
| LPWAN |
| Zigbee Specification |
| Zigbee |
| ETSI EN 303 645 |
| Consumer IoT wireless security |
| PCI DSS |
| Wireless networks in card environments |

[NIST Bluetooth Security Guidance](https://www.nist.gov/publications/updated-nist-guidance-bluetooth-security)[IEEE Standards](https://standards.ieee.org/)[Bluetooth Specifications](https://www.bluetooth.com/specifications/)[LoRa Alliance Specifications](https://lora-alliance.org/resource_hub/lorawan-specification-v1-0/)
Bluetooth SIG explicitly provides a Bluetooth LE Security Study Guide and a Security and Privacy Best Practices Guide for implementers. ( [Bluetooth® Technology Website](https://www.bluetooth.com/learn-about-bluetooth/key-attributes/bluetooth-security/))

---

## Section 04: Official Documentation <a name="section-04"></a>

Wi-Fi 
Wi-Fi Alliance 
IEEE 802.11 
NIST WLAN guidance 
hostapd/wpa_supplicant 
[Wi-Fi Alliance](https://www.wi-fi.org/)[hostapd / wpa_supplicant](https://w1.fi/)[NIST WLAN Guidance](https://csrc.nist.gov/pubs/sp/800/153/final)
Bluetooth 
[Bluetooth SIG Security](https://www.bluetooth.com/learn-about-bluetooth/key-attributes/bluetooth-security/)[Bluetooth Specifications](https://www.bluetooth.com/specifications/specs/)
SDR 
[GNU Radio Documentation](https://wiki.gnuradio.org/)[HackRF Documentation](https://hackrf.readthedocs.io/)[RTL-SDR Documentation](https://www.rtl-sdr.com/)

---

## Section 05: Checklists <a name="section-05"></a>

#### Recommended checklist areas: 
Authorized frequencies 
SSID inventory 
Hidden SSIDs 
BSSID inventory 
AP inventory 
Rogue APs 
WEP 
WPA/WPA2/WPA3 
PSK strength 
Enterprise authentication 
802.1X 
EAP methods 
Certificate validation 
PMF / 802.11w 
WPS 
Guest WLAN 
Client isolation 
VLAN segmentation 
Captive portal 
RADIUS 
Management interface 
AP firmware 
Default credentials 
Wireless IDS/IPS 
Logging 
BLE pairing 
BLE bonding 
BLE GATT permissions 
NFC/RFID access controls 
Zigbee keys 
LoRaWAN keys 
RF replay resistance 
Jamming resilience 
Privacy / MAC randomization 

#### Useful sources: 
[OWASP Wi-Fi Security Testing Guide](https://owasp.org/www-project-wi-fi-security-testing-guide/)[NIST SP 800-153](https://csrc.nist.gov/pubs/sp/800/153/final)[WBA Security Guidelines](https://wballiance.com/wba-wi-fi-security-guidelines/)
The WBA’s 2026 Wi-Fi Security Guidelines specifically address rogue APs, credential theft, privacy, Layer-2 protection, RadSec, federation governance, Passpoint/OpenRoaming and future PQC readiness. ( [Wireless Broadband Alliance](https://wballiance.com/wba-wi-fi-security-guidelines/))

---

## Section 06: Cheat Sheets <a name="section-06"></a>

Useful references: 
[Aircrack-ng Documentation](https://www.aircrack-ng.org/documentation.html)[Kismet Documentation](https://www.kismetwireless.net/docs/)[Wireshark WLAN Display Filters](https://www.wireshark.org/docs/dfref/w/wlan.html)[HackTricks Wi-Fi Pentesting](https://book.hacktricks.wiki/en/generic-methodologies-and-resources/pentesting-wifi/index.html)[Bettercap Documentation](https://www.bettercap.org/legacy/)
Your uploaded resource file also already includes HackTricks Wi-Fi, wireless penetration testing checklists, evil-twin guides and Aircrack-ng tutorials.

---

## Section 07: Tools <a name="section-07"></a>

Wi-Fi 

| Tool | Purpose |
| --- | --- |
| ⭐⭐⭐ Aircrack-ng |
| Wi-Fi auditing suite |
| ⭐⭐⭐ Kismet |
| Wireless discovery/sniffing/WIDS |
| ⭐⭐⭐ Wireshark |
| Packet analysis |
| ⭐⭐⭐ Bettercap |
| Network/wireless assessment |
| ⭐⭐ Wifite2 |
| Automated wireless auditing |
| ⭐⭐ Airgeddon |
| Wireless auditing framework |
| ⭐⭐ EAPHammer |
| Enterprise Wi-Fi assessment |
| ⭐⭐ hcxdumptool / hashcat |
| WPA handshake analysis |
| ⭐⭐ hostapd-wpe |
| 802.1X lab testing |

[Aircrack-ng GitHub](https://github.com/aircrack-ng/aircrack-ng)[Kismet](https://www.kismetwireless.net/)[Wifite2](https://github.com/derv82/wifite2)[Airgeddon](https://github.com/v1s1t0r1sh3r3/airgeddon)[EAPHammer](https://github.com/s0lst1c3/eaphammer)
Aircrack-ng’s current project describes itself as a complete Wi-Fi auditing suite covering monitoring, packet capture, injection/testing and WPA/WEP analysis. ( [GitHub](https://github.com/aircrack-ng/aircrack-ng)) 
Bluetooth / BLE 
Ubertooth 
btlejack 
Bettercap BLE 
BlueZ 
nRF Connect 
GATTacker 
[Ubertooth](https://github.com/greatscottgadgets/ubertooth)[btlejack](https://github.com/virtualabs/btlejack)[BlueZ](http://www.bluez.org/)
RFID / NFC 
Proxmark3 
Flipper Zero 
libnfc 
NFC Tools 
[Proxmark3](https://github.com/RfidResearchGroup/proxmark3)[libnfc](https://github.com/nfc-tools/libnfc)
SDR / RF 
GNU Radio 
HackRF 
RTL-SDR 
Universal Radio Hacker 
SDR++ 
GQRX 
Inspectrum 
[GNU Radio](https://www.gnuradio.org/)[Universal Radio Hacker](https://github.com/jopohl/urh)[SDR++](https://github.com/AlexandreRouma/SDRPlusPlus)[Inspectrum](https://github.com/miek/inspectrum)

---

## Section 08: Labs / Practice <a name="section-08"></a>

Your uploaded material already lists TryHackMe, HTB, Aircrack-ng, Kismet, Bettercap, Proxmark3, Ubertooth and wireless lab-building resources. 

#### Recommended: 

| Lab | Focus |
| --- | --- |
| ⭐⭐⭐ WiFiChallenge Lab |
| Wi-Fi |
| ⭐⭐⭐ TryHackMe Wireless rooms |
| Wi-Fi |
| ⭐⭐⭐ HTB Academy Wi-Fi path |
| Wi-Fi |
| ⭐⭐⭐ Great Scott Gadgets SDR tutorials |
| SDR |
| ⭐⭐ Microcorruption RF-related crossover |
| Embedded |
| ⭐⭐ BLE CTF |
| Bluetooth |
| ⭐⭐ Proxmark3 practice tags |
| RFID/NFC |

[HTB Wi-Fi Penetration Tester Path](https://academy.hackthebox.com/path/preview/wi-fi-penetration-tester)[BLE CTF](https://github.com/hackgnar/ble_ctf)[Great Scott Gadgets SDR Course](https://greatscottgadgets.com/sdr/)

---

## Section 09: Payloads / Test Cases <a name="section-09"></a>

For authorized lab use, structure tests around protocol behavior rather than generic payloads. 
Wi-Fi 
Open WLAN validation 
Weak PSK validation 
WPS exposure 
PMF configuration 
802.1X certificate validation 
EAP downgrade resistance 
Guest isolation 
Client isolation 
Rogue AP detection 
Evil-twin resilience 
Roaming security 
Management-frame protection 
BLE 
Pairing mode 
Just Works usage 
MITM protection 
LE Secure Connections 
GATT permissions 
Sensitive characteristic access 
Bonding behavior 
Address privacy 
Replay resistance 
RFID/NFC 
UID reliance 
Weak sector keys 
Authentication 
Replay resistance 
Clone resistance 
Access-bit configuration 
Sensitive data exposure 
RF / SDR 
Protocol identification 
Modulation analysis 
Replay resistance 
Rolling codes 
Static identifiers 
Unencrypted frames 
Weak checksums 
Jamming resilience

---

## Section 10: YouTube / Video <a name="section-10"></a>

#### Recommended: 
Great Scott Gadgets 
Hak5 
DEF CON 
Black Hat 
Hardwear.io 
David Bombal 
SANS 
GNU Radio 
RF Hacker Sanctuary 
[Great Scott Gadgets YouTube](https://www.youtube.com/@greatscottgadgets)[DEF CON YouTube](https://www.youtube.com/@DEFCONConference)[Black Hat YouTube](https://www.youtube.com/@BlackHatOfficialYT)[Hardwear.io YouTube](https://www.youtube.com/@hardweario)[David Bombal YouTube](https://www.youtube.com/@davidbombal)
Your uploaded resource list also includes David Bombal, NetworkChuck, Null Byte and major conference material for wireless security.

---

## Section 11: Courses / Training <a name="section-11"></a>

Your source already lists OSWP, SANS SEC617, Wi-Fi Security & Pentesting, HTB Wi-Fi path and RFID/BLE workshops. 

#### Recommended current training: 

| Course | Focus |
| --- | --- |
| ⭐⭐⭐ OffSec PEN-210 / OSWP |
| Wi-Fi pentesting |
| ⭐⭐⭐ SANS SEC617 |
| Advanced wireless |
| ⭐⭐⭐ HTB Wi-Fi Penetration Tester |
| Hands-on Wi-Fi |
| ⭐⭐⭐ Great Scott Gadgets SDR Course |
| SDR |
| ⭐⭐ Lab401 BLE/RFID workshops |
| BLE/RFID |
| ⭐⭐ Hardwear.io training |
| RF/hardware |

[OffSec PEN-210 / OSWP](https://www.offsec.com/courses/pen-210/)[SANS SEC617](https://www.sans.org/cyber-security-courses/wireless-penetration-testing-ethical-hacking/)[HTB Wi-Fi Path](https://academy.hackthebox.com/path/preview/wi-fi-penetration-tester)
SANS still lists SEC617 as its advanced Wireless Penetration Testing and Ethical Hacking course in 2026. ( [SANS Institute](https://www.sans.org/cyber-security-training-events/network-security-2026))

---

## Section 12: Certifications <a name="section-12"></a>

| Certification | Focus |
| --- | --- |
| ⭐⭐⭐ OSWP |
| Wi-Fi offensive security |
| ⭐⭐⭐ GAWN |
| Wireless assessment/auditing |
| ⭐⭐ CWSP |
| Wireless security |
| ⭐⭐ CWNA |
| Wireless fundamentals |
| ⭐ CWDP |
| WLAN design |

[OSWP](https://www.offsec.com/courses/pen-210/)[GIAC GAWN](https://www.giac.org/certifications/assessing-auditing-wireless-networks-gawn/)[CWNP Certifications](https://www.cwnp.com/certifications/)

---

## Section 13: Books <a name="section-13"></a>

#### Recommended: 

- ⭐⭐⭐ Wi-Fu: Wireless Security 
- ⭐⭐⭐ Kali Linux Wireless Penetration Testing 
- ⭐⭐⭐ Practical Packet Analysis 
- ⭐⭐⭐ Inside Radio 
- ⭐⭐⭐ Software Defined Radio for Engineers 
- ⭐⭐ The Hardware Hacking Handbook 
- ⭐⭐ RFID Security Your uploaded list contains several of these wireless and RF-oriented books, including Wi-Fi pentesting books and RFID/SDR resources.

---

## Section 14: Blogs / Articles <a name="section-14"></a>

Follow: 
Aircrack-ng 
Kismet 
Great Scott Gadgets 
Trail of Bits 
NCC Group Research 
Pentest Partners 
Quarkslab 
Bluetooth SIG 
Wi-Fi Alliance 
WBA 
[Great Scott Gadgets Blog](https://greatscottgadgets.com/)[NCC Group Research](https://www.nccgroup.com/research-blog/)[Pentest Partners Blog](https://www.pentestpartners.com/security-blog/)[Bluetooth Security](https://www.bluetooth.com/learn-about-bluetooth/key-attributes/bluetooth-security/)

---

## Section 15: Research Papers <a name="section-15"></a>

Track: 
ACM WiSec 
USENIX Security 
IEEE S&P 
NDSS 
ACM CCS 
Bluetooth security research 
RF side-channel research 
Your uploaded file already includes ACM WiSec, IEEE S&P, USENIX Security, NDSS, Black Hat and DEF CON wireless material. 
Important topics: 
WPA3 
Dragonblood-style research 
802.11 management frames 
Wi-Fi fingerprinting 
Wi-Fi privacy 
BLE tracking 
BLE pairing 
RF replay 
RF fingerprinting 
LoRaWAN security 
Zigbee security 
GNSS spoofing 
RF side channels

---

## Section 16: White Papers <a name="section-16"></a>

#### Recommended: 
NIST SP 800-153 
NIST SP 800-121 Rev.2 
WBA Wi-Fi Security Guidelines 
Bluetooth Security & Privacy Best Practices 
Wi-Fi Alliance security material 
LoRa Alliance security documents 
[NIST SP 800-153](https://csrc.nist.gov/pubs/sp/800/153/final)[Bluetooth Security Guidance](https://www.bluetooth.com/learn-about-bluetooth/key-attributes/bluetooth-security/)[WBA Wi-Fi Security Guidelines](https://wballiance.com/wba-wi-fi-security-guidelines/)

---

## Section 17: Conference Material <a name="section-17"></a>

| Conference | Focus |
| --- | --- |
| ⭐⭐⭐ DEF CON Wireless Village |
| Wireless |
| ⭐⭐⭐ RF Hacker Sanctuary |
| RF/SDR |
| ⭐⭐⭐ Hardwear.io |
| RF/hardware |
| ⭐⭐⭐ Black Hat |
| Wireless research |
| ⭐⭐⭐ ACM WiSec |
| Academic wireless |
| ⭐⭐ ShmooCon |
| RF/wireless |
| ⭐⭐ HITB |
| BLE/RFID |

---

## Section 18: Mind Maps <a name="section-18"></a>

#### Recommended hierarchy: 
WIRELESS & RF SECURITY 

```
│
```

```
├── Wi-Fi
```

```
│   ├── 802.11
```

```
│   ├── WPA2/WPA3
```

```
│   ├── 802.1X
```

```
│   ├── EAP
```

```
│   ├── WPS
```

```
│   └── PMF
```

```
│
```

```
├── Bluetooth
```

```
│   ├── Classic
```

```
│   ├── BLE
```

```
│   ├── Pairing
```

```
│   ├── GATT
```

```
│   └── Privacy
```

```
│
```

```
├── RFID / NFC
```

```
│   ├── LF
```

```
│   ├── HF
```

```
│   ├── UHF
```

```
│   ├── MIFARE
```

```
│   └── Smart Cards
```

```
│
```

```
├── SDR
```

```
│   ├── GNU Radio
```

```
│   ├── HackRF
```

```
│   └── RTL-SDR
```

```
│
```

```
├── Zigbee / Thread
```

```
├── Z-Wave
```

```
├── LoRa / LoRaWAN
```

```
├── GNSS
```

```
│   ├── GPS
```

```
│   ├── Galileo
```

```
│   └── Spoofing resilience
```

```
│
```

```
└── RF Fundamentals
```

```
    ├── Frequency
```

```
    ├── Modulation
```

```
    ├── Spectrum
```

```
    └── Antennas
```

---

## Section 19: Sample Reports <a name="section-19"></a>

#### Recommended report structure: 
Executive Summary 
Scope / Frequency Range 
Environment 
AP / Device Inventory 
SSID / BSSID Inventory 
Spectrum Analysis 
Authentication 
Encryption 
802.1X / EAP 
Management Frames 
Rogue AP Review 
Guest Network 
Segmentation 
Client Security 
Bluetooth / BLE 
RFID / NFC 
Zigbee / LoRa 
RF Analysis 
Monitoring / WIDS 
Findings 
Evidence 
CVSS 
Standards Mapping 
Remediation 
Retest 
Conclusion

---

## Section 20: Templates <a name="section-20"></a>

/templates/wireless-rf-security/ 

```
├── wireless-security-test-plan.md
```

```
├── wifi-checklist.md
```

```
├── wpa2-wpa3-testing.md
```

```
├── enterprise-wifi-review.md
```

```
├── rogue-ap-review.md
```

```
├── bluetooth-ble-checklist.md
```

```
├── rfid-nfc-checklist.md
```

```
├── sdr-rf-analysis.md
```

```
├── zigbee-security.md
```

```
├── lorawan-security.md
```

```
├── gnss-security.md
```

```
├── evidence-template.md
```

```
└── wireless-security-report.md
```
Suggested columns: 
Test ID 
Technology 
Frequency 
Channel 
SSID / Device 
Protocol 
Security Mode 
Objective 
Tool 
Procedure 
Expected Result 
Actual Result 
Evidence 
Standard 
Severity 
Status

---

## Section 21: Case Studies / CVEs <a name="section-21"></a>

Track: 
Wi-Fi chipset/driver CVEs 
AP firmware CVEs 
WPA/WPA3 protocol weaknesses 
Bluetooth stack CVEs 
BLE privacy issues 
Zigbee/LoRa implementations 
RF remote-control systems 
GNSS spoofing cases 

#### Useful sources: 
[CVE.org](https://www.cve.org/)[NVD](https://nvd.nist.gov/)[CISA KEV](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)[Bluetooth Security Notices](https://www.bluetooth.com/learn-about-bluetooth/key-attributes/bluetooth-security/reporting-security/)

---

## Section 22: GitHub Repositories <a name="section-22"></a>

Wi-Fi 

- ⭐⭐⭐ Aircrack-ng 
- ⭐⭐⭐ Kismet 
- ⭐⭐⭐ Wifite2 
- ⭐⭐ Airgeddon 
- ⭐⭐ EAPHammer 
- ⭐⭐ hcxdumptool 
- ⭐⭐ Bettercap Bluetooth 

- ⭐⭐⭐ Ubertooth 
- ⭐⭐⭐ btlejack 
- ⭐⭐ BlueZ 
- ⭐⭐ GATTacker RFID/NFC 

- ⭐⭐⭐ Proxmark3 
- ⭐⭐ libnfc SDR/RF 

- ⭐⭐⭐ GNU Radio 
- ⭐⭐⭐ Universal Radio Hacker 
- ⭐⭐⭐ SDR++ 
- ⭐⭐ Inspectrum [Aircrack-ng GitHub](https://github.com/aircrack-ng/aircrack-ng)[Proxmark3 GitHub](https://github.com/RfidResearchGroup/proxmark3)[Ubertooth GitHub](https://github.com/greatscottgadgets/ubertooth)[URH GitHub](https://github.com/jopohl/urh)

---

## Section 23: Datasets / PCAPs / Samples <a name="section-23"></a>

Useful datasets: 
Wireshark Wi-Fi PCAPs 
WPA handshake lab captures 
Bluetooth captures 
BLE advertisements 
Zigbee PCAPs 
RF IQ recordings 
GNU Radio examples 
[Wireshark Sample Captures](https://wiki.wireshark.org/SampleCaptures)[GNU Radio Examples](https://github.com/gnuradio/gnuradio)
For your repository: 
datasets/ 

```
├── wifi/
```

```
│   ├── 80211/
```

```
│   ├── wpa2/
```

```
│   └── wpa3/
```

```
├── bluetooth/
```

```
├── ble/
```

```
├── zigbee/
```

```
├── lorawan/
```

```
├── rfid/
```

```
└── rf-iq/
```

---

## Section 24: Communities / Forums <a name="section-24"></a>

#### Recommended: 
Aircrack-ng community 
Kismet community 
GNU Radio community 
Great Scott Gadgets 
RTL-SDR community 
Bluetooth SIG 
Wi-Fi Alliance 
r/RTLSDR 
r/amateurradio 
r/netsec 
Aircrack-ng also provides GitHub Discussions and IRC-based community support. ( [GitHub](https://github.com/aircrack-ng/aircrack-ng))

---

## Section 25: Vendors / Products <a name="section-25"></a>

| Category | Examples |
| --- | --- |
| Wi-Fi adapters |
| Alfa Network, TP-Link |
| SDR |
| Ettus USRP, HackRF, RTL-SDR, LimeSDR |
| BLE |
| Ubertooth, Nordic nRF |
| RFID/NFC |
| Proxmark3, Flipper Zero |
| Spectrum analysis |
| Keysight, Rohde & Schwarz, Anritsu |
| WLAN assessment |
| AirMagnet, Ekahau |
| WIDS/WIPS |
| Cisco, Aruba, Fortinet |

For your resource site, organize products by testing capability, not just vendor.

---

## Section 26: Latest Developments <a name="section-26"></a>

#### Important current topics: 
WPA3 adoption 
Wi-Fi 6E 
Wi-Fi 7 
6 GHz security 
Protected Management Frames 
Passpoint 
OpenRoaming 
RadSec 
Enterprise certificate validation 
BLE privacy 
BLE direction finding 
UWB security 
Matter / Thread security 
LoRaWAN 
GNSS spoofing resilience 
RF fingerprinting 
Post-quantum wireless authentication 
A particularly current resource is the Wireless Broadband Alliance Wi-Fi Security Guidelines released in 2026, which expands attention beyond normal WPA configuration into OpenRoaming, Passpoint, RadSec, federation security, Layer-2 security and PQC readiness. ( [Wireless Broadband Alliance](https://wballiance.com/wba-issues-new-wi-fi-security-guidelines/))

---

## Section 27: Learning Roadmap <a name="section-27"></a>

```
LEVEL 1 — Networking
```
TCP/IP 
Ethernet 
ARP 
DHCP 
DNS 

→ ↓ 
```
LEVEL 2 — RF Fundamentals
```
Frequency 
Wavelength 
Amplitude 
Phase 
Modulation 
Spectrum 
Antennas 

→ ↓ 
```
LEVEL 3 — Wi-Fi Fundamentals
```
802.11 
SSID 
BSSID 
Channels 
Frames 
Management/Data/Control 

→ ↓ 
```
LEVEL 4 — Wi-Fi Security
```
WEP 
WPA 
WPA2 
WPA3 
PSK 
PMF 

→ ↓ 
```
LEVEL 5 — Packet Capture
```
Monitor mode 
Wireshark 
tcpdump 
Aircrack-ng 
Kismet 

→ ↓ 
```
LEVEL 6 — Enterprise Wi-Fi
```
802.1X 
RADIUS 
EAP 
PEAP 
EAP-TLS 
Certificates 

→ ↓ 
```
LEVEL 7 — WLAN Architecture
```
Guest networks 
VLANs 
Client isolation 
Roaming 
WIDS/WIPS 

→ ↓ 
```
LEVEL 8 — Bluetooth / BLE
```
Advertising 
Pairing 
Bonding 
GATT 
Privacy 

→ ↓ 
```
LEVEL 9 — RFID / NFC
```
LF 
HF 
UHF 
ISO14443 
MIFARE 
Proxmark3 

→ ↓ 
```
LEVEL 10 — SDR
```
RTL-SDR 
HackRF 
GNU Radio 
IQ data 
Modulation 

→ ↓ 
```
LEVEL 11 — IoT RF
```
Zigbee 
Thread 
Z-Wave 
LoRaWAN 
Sub-GHz 

→ ↓ 
```
LEVEL 12 — Advanced RF
```
Replay analysis 
Rolling codes 
Signal decoding 
RF fingerprinting 

→ ↓ 
```
LEVEL 13 — GNSS / UWB
```
GPS/GNSS security 
Spoofing resilience 
UWB ranging security 

→ ↓ 
```
LEVEL 14 — Standards
```
NIST 800-153 
NIST 800-121 
IEEE 802.11 
802.1X 
Bluetooth SIG 
WBA 

→ ↓ 
```
LEVEL 15 — Reporting
```
Evidence 
PCAPs 
Spectrum plots 
Risk 
Remediation 
Retest 

- ⭐ Wireless & RF Security — Top 20 
| Rank | Resource | Purpose |
| --- | --- | --- |
| 1 |
| NIST SP 800-153 |
| WLAN security baseline |
| 2 |
| Aircrack-ng |
| Wi-Fi auditing |
| 3 |
| Kismet |
| Wireless discovery |
| 4 |
| Wireshark |
| 802.11 analysis |
| 5 |
| OSWP / PEN-210 |
| Wi-Fi training |
| 6 |
| SANS SEC617 |
| Advanced wireless |
| 7 |
| Bluetooth SIG Security Guide |
| BLE/Bluetooth |
| 8 |
| WBA Wi-Fi Security Guidelines |
| Modern Wi-Fi guidance |
| 9 |
| Bettercap |
| Wireless/network assessment |
| 10 |
| EAPHammer |
| Enterprise Wi-Fi |
| 11 |
| Proxmark3 |
| RFID/NFC |
| 12 |
| Ubertooth |
| Bluetooth |
| 13 |
| GNU Radio |
| SDR |
| 14 |
| HackRF |
| RF experimentation |
| 15 |
| Universal Radio Hacker |
| RF protocol analysis |
| 16 |
| HTB Wi-Fi path |
| Hands-on practice |
| 17 |
| HackTricks Wi-Fi |
| Pentest reference |
| 18 |
| Wireshark sample captures |
| Practice |
| 19 |
| OWASP Wi-Fi Security Testing Guide |
| Testing methodology |
| 20 |
| Great Scott Gadgets tutorials |
| RF learning |

#### Recommended practical stack 
Networking → RF fundamentals → 802.11 → WPA2/WPA3 → monitor-mode capture → Wireshark/Kismet/Aircrack-ng → enterprise 802.1X/EAP → BLE → RFID/NFC → SDR → Zigbee/LoRa → GNSS/UWB → standards/compliance → professional wireless security reporting.

---

<div align="center">
<sub>📡 Wireless & RF Security · Cybersecurity Resource Matrix V4 · <a href="https://github.com/sudoninja-noob">@sudoninja</a></sub>
</div>