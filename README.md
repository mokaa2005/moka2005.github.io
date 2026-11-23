# MITRE ATT&CK® — Persian Edition | مایتر اتک فارسی

**The full MITRE ATT&CK Enterprise framework in Persian & English — built for SOC analysts.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Open%20the%20site-brightgreen)](https://mokaa2005.github.io/moka2005.github.io/mitre-attack/)
![ATT&CK version](https://img.shields.io/badge/ATT%26CK-Enterprise%20v20.1-blue)
![Language](https://img.shields.io/badge/Language-Persian%20%2B%20English-orange)

## 🔴 Live site

**[Open the site →](https://mokaa2005.github.io/moka2005.github.io/mitre-attack/)**

No install, no server — the whole framework runs in your browser, even offline.

## What is this?

[attack.mitre.org](https://attack.mitre.org) is the world's standard knowledge base of real-world adversary tactics and techniques — but it is entirely in English. This project rebuilds it as a bilingual site:

- **English where a SOC analyst must know English:** technique names, IDs (e.g. `T1059.001`), tactic names, platforms and detection terms stay in English, on their own lines.
- **Persian everywhere else:** explanations, tactic guides and SOC tips are written in Persian, kept separate so mixed text never gets jumbled.
- **Deep Persian explanations** for the techniques that matter most in a SOC — PowerShell, Phishing, LSASS credential dumping and more — with the exact log sources to detect them (Sysmon, Windows Event IDs).

## What's inside (official MITRE data, Enterprise v20.1)

- Full **ATT&CK Matrix** — 15 tactics in the original site's layout
- **227 techniques + 479 sub-techniques**
- **178 adversary groups** and **842 software / malware** entries
- **44 mitigations**, **57 campaigns**
- **38 data sources / 106 data components**
- **706 detection strategies** with exact log sources
- Global search by name, ID or alias — plus deep search inside MITRE's own descriptions

## فارسی

این پروژه کل چارچوب MITRE ATT&CK را به صورت دوزبانه بازسازی می‌کند: اسم‌ها، آیدی‌ها و اصطلاح‌هایی که یک کارشناس SOC باید انگلیسی بداند، انگلیسی مانده‌اند و همه توضیح‌ها، راهنمای تاکتیک‌ها و نکته‌های تشخیص فارسی‌اند. داده‌ها عیناً از داده رسمی MITRE (نسخه Enterprise 20.1) گرفته شده‌اند.

## Tech

- Single self-contained web app — all data embedded, zero external requests
- Data: official MITRE ATT&CK STIX bundle, Enterprise v20.1
- Layout mirrors attack.mitre.org

## Author

**Mohammad Mehdi Kalantari (Moka)** — SOC Intern, Yazd, Iran
GitHub: [@mokaa2005](https://github.com/mokaa2005)

⭐ **If this project helps you, please give it a star — it helps other Persian-speaking analysts find it.**

> ATT&CK® is a registered trademark of The MITRE Corporation. This is an independent educational project and is not affiliated with or endorsed by MITRE.
