# 🗺️ 0xRoot Lab — Course Structure (Master Guide)

> **Single source of truth** for course order, numbering, and tags.
> Brand: **0xRoot Lab — From Zero to Root**
> Sequential numbering, no gaps. Numbers finalize as each block is written.
> When continuing in a new chat: send this file's link so numbering & tags stay in sync.

---

## 🏷️ TAG SYSTEM (per channel)

Two separate channels = two separate main tags:

- **RU channel** (`0xRoot Lab | Pentest RU`): main tag `#0xRootRU`
- **EN channel** (`0xRoot Lab | Pentest EN`): main tag `#0xRootEN`
- **GitHub** (EN files): tag `#0xRootEN`

Each lesson carries: mainTag + blockTag + topicTag
- RU example: `#0xRootRU #Блок02 #Закон`
- EN example: `#0xRootEN #Block02 #Law`
- Tool/command tags are universal: `#Nmap`, `#Hydra`, `#OSINT`

---

## 🔰 LEVEL 0 — FOUNDATION

| # | Block | Lessons (est.) | Status |
|---|-------|----------------|--------|
| 1 | ⚖️ Legal & Ethics | **1–5** | ✅ DONE |
| 2 | 🌍 Jurisdiction & Compliance (RU: Российская специфика) | **6–12** | 🔄 6–11 done |
| 3 | 🐧 Linux | 13–32 | ⬜ next |
| 4 | 📜 Bash Scripting | 33–44 | ⬜ |
| 5 | 🌐 Networking | 45–59 | ⬜ |
| 6 | 🐍 Python | 60–74 | ⬜ |
| 7 | 🔐 Cryptography | 75–86 | ⬜ |

## 🔍 LEVEL 1 — RECON & INITIAL ACCESS

| # | Block | Lessons (est.) | Status |
|---|-------|----------------|--------|
| 8 | 🕵️ OSINT | 87–106 | ⬜ |
| 9 | 🎭 Social Engineering | 107–118 | ⬜ |
| 10 | 📧 Email Security Attacks | 119–126 | ⬜ |
| 11 | 🏠 Home Lab Setup | 127–136 | ⬜ |
| 12 | 🛡️ Pentest Basics | 137–166 | ⬜ |
| 13 | 🌐 OWASP Top 10 | 167–186 | ⬜ |
| 14 | 📡 Wireshark | 187–194 | ⬜ |

## 🔓 LEVEL 2 — PRIVILEGE ESCALATION

| # | Block | Lessons (est.) | Status |
|---|-------|----------------|--------|
| 15 | 🔑 Password Attacks | 195–209 | ⬜ |
| 16 | 🧨 Metasploit Framework | 210–221 | ⬜ |
| 17 | 🐧 Linux PrivEsc | 222–239 | ⬜ |
| 18 | 🪟 Windows PrivEsc | 240–257 | ⬜ |

## 🏰 LEVEL 3 — PERSISTENCE & LATERAL MOVEMENT

| # | Block | Lessons (est.) | Status |
|---|-------|----------------|--------|
| 19 | 🏢 Active Directory | 258–277 | ⬜ |
| 20 | 🕳️ Pivoting | 278–289 | ⬜ |
| 21 | 🔁 Post-Exploitation & Persistence | 290–301 | ⬜ |
| 22 | 🗄️ Database Attacks | 302–313 | ⬜ |

## 🌐 LEVEL 4 — INFRASTRUCTURE & SPECIALIZATION

| # | Block | Lessons (est.) | Status |
|---|-------|----------------|--------|
| 23 | 🔗 API Security | 314–328 | ⬜ |
| 24 | 📱 Mobile Security | 329–343 | ⬜ |
| 25 | 📶 Wireless Security | 344–358 | ⬜ |
| 26 | ☁️ Cloud Security | 359–378 | ⬜ |
| 27 | ⚙️ DevSecOps | 379–393 | ⬜ |
| 28 | ☸️ Container / Kubernetes Security | 394–405 | ⬜ |
| 29 | 🧩 Modern Applications | 406–415 | ⬜ |
| 30 | 🔒 Secure Coding & Supply Chain | 416–430 | ⬜ |
| 31 | 🐙 GitHub / Open Source | 431–442 | ⬜ |

## 🔴 LEVEL 5 — ADVANCED RED TEAM

| # | Block | Lessons (est.) | Status |
|---|-------|----------------|--------|
| 32 | 🎯 Red Team | 443–467 | ⬜ |
| 33 | 🕵️ OPSEC & Anonymity | 468–477 | ⬜ |
| 34 | 💥 Exploit Development / Buffer Overflow | 478–497 | ⬜ |
| 35 | 🔬 Reverse Engineering | 498–517 | ⬜ |
| 36 | 🖼️ Steganography | 518–525 | ⬜ |
| 37 | 🦠 Malware Analysis | 526–543 | ⬜ |
| 38 | 🔍 DFIR — Digital Forensics | 544–558 | ⬜ |
| 39 | 🚪 Physical Security | 559–566 | ⬜ |
| 40 | 🔌 IoT / Hardware Hacking | 567–578 | ⬜ |

## 📋 LEVEL 6 — REAL WORLD, DEFENSE & CAREER

| # | Block | Lessons (est.) | Status |
|---|-------|----------------|--------|
| 41 | 🔴 Real Pentest / Bug Bounty | 579–598 | ⬜ |
| 42 | 📝 Reporting & Methodology | 599–610 | ⬜ |
| 43 | 👁️ SOC / Threat Hunting | 611–630 | ⬜ |
| 44 | 🤖 AI for Cybersecurity | 631–655 | ⬜ |
| 45 | 🏁 CTF Strategies | 656–667 | ⬜ |
| 46 | 📋 GRC / Compliance | 668–679 | ⬜ |
| 47 | 🎓 Career | 680–689 | ⬜ |

---

## 📌 Lesson Format

Why → Explanation → Remember → Key Terms → Commands → Command Breakdown → Practice (THM/HTB hints only) → Defense → Homework → Beginner Mistakes → Summary → (Walkthrough)

- Two versions per lesson: RU (Telegram) + EN (Telegram + GitHub) — same topics, same order.
- THM/HTB practice only when a real room/machine exists — hints only, no solutions.
- GitHub file naming: `Block-XX-Name/Lesson-YY.md`
- Jurisdiction/legal topics: RU = local law (ФЗ-149, УК РФ), EN = international (CFAA, etc.)

---

## ✅ PROGRESS

**Block 1 — Legal & Ethics (1–5)** ✅ DONE — RU + EN + GitHub
- [x] 1 — What is pentesting & permission
- [x] 2 — Responsible disclosure
- [x] 3 — Scope & Rules of Engagement
- [x] 4 — Roles: Red / Blue / Purple
- [x] 5 — Pentest methodology: 5 stages

**Block 2 — Jurisdiction & Compliance (6–12)** 🔄 6–11 done
- [x] 6 — Law & unauthorized access (ФЗ-149, УК РФ 272)
- [x] 7 — Tools & malware statute (УК РФ 273)
- [x] 8 — Critical Infrastructure / КИИ (274.1, ФЗ-187)
- [x] 9 — Regulators (ФСТЭК / ФСБ / НКЦКИ / Roskomnadzor)
- [x] 10 — Personal data (ФЗ-152 / GDPR)
- [x] 11 — Working legally: freelance vs in-house
- [ ] 12 — Block 2 recap & self-check  ← NEXT

**Block 3 — Linux (13–32)** ⬜ — starts with directory structure
- [ ] 13 — Linux directory structure (FHS)
- [ ] 14 — Directories that matter for pentesters
- [ ] ... (detail when we reach the block)

---

## 🎨 BRAND ASSETS

- Name: **0xRoot Lab | Pentest RU / EN**
- Slogan: **From Zero to Root**
- Avatar: 0xROOT neon-green wordmark with circuit "roots" on dark bg
- Colors: bg #0D1117, accent #00FF9C
- Username: @zeroxrootlab_ru / @zeroxrootlab_en
- GitHub: github.com/zeroxrootpentest/cyber-lab-course

> Note: lessons 1–10 were published with old #CyberLab tags — update to #0xRootRU / #0xRootEN when convenient.
