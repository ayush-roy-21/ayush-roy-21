<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Ayush%20Roy&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Senior%20Cybersecurity%20Engineer%20%7C%20Blockchain%20Security%20%7C%20SVNIT%20Surat&descAlignY=58&descSize=16" width="100%"/>

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-my--portfolio--msk9.vercel.app-6d28d9?style=for-the-badge&logoColor=white)](https://my-portfolio-msk9.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayush-roy-83689032b/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/ayush_roy__08/)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ayush2006kumar996@gmail.com)

[![Profile Views](https://komarev.com/ghpvc/?username=ayush-roy-21&style=for-the-badge&color=6d28d9&label=PROFILE+VIEWS)](https://github.com/ayush-roy-21)
[![GitHub followers](https://img.shields.io/github/followers/ayush-roy-21?style=for-the-badge&color=6d28d9&labelColor=1a1a2e&label=Followers)](https://github.com/ayush-roy-21?tab=followers)

</div>

---

## 🧠 About Me

```python
class AyushRoy:
    role       = "Senior Cybersecurity Engineer"
    location   = "Vadodara → Surat, Gujarat, India 🇮🇳"
    education  = "B.Tech Mathematics & Computing @ SVNIT Surat (2024–2028)"
    cgpa       = 7.98 / 10.0

    expertise  = [
        "🔐 Penetration Testing & Vulnerability Assessment (VAPT)",
        "⛓️  Smart Contract Security Auditing (Solidity, Slither, Mythril)",
        "🧬 Malware Analysis, Reverse Engineering & OSINT",
        "📊 ML-Driven Financial Systems & LLM Integration",
        "🌐 Digital Forensics, DeFi Fraud Prevention & Crypto Tracing",
    ]

    portfolio  = "https://my-portfolio-msk9.vercel.app/"
    stack      = ["Next.js App Router", "Tailwind CSS", "Framer Motion", "GSAP"]
    currently  = "Building AI-powered threat detection & DeFi security tooling"
    interests  = ["Geopolitics × Cyber Warfare", "Dark Web Monitoring", "AML Systems"]
```

---

## 🎓 Education

| Degree | Institution | Year | Score |
|--------|-------------|------|-------|
| **B.Tech – Mathematics & Computing** | Sardar Vallabhbhai NIT (SVNIT), Surat | 2024 – 2028 | CGPA: **7.98 / 10** |
| **Class XII – Gujarat Board** | Baroda High School, Vadodara | 2022 – 2024 | **85%** |

---

## 🌐 Portfolio — `My-portfolio`

> **Ayush Roy · Senior Cybersecurity Engineer** — Live at [my-portfolio-msk9.vercel.app](https://my-portfolio-msk9.vercel.app/)

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Click%20Here-6d28d9?style=for-the-badge&logo=vercel&logoColor=white)](https://my-portfolio-msk9.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![Deploy Status](https://img.shields.io/github/actions/workflow/status/ayush-roy-21/My-portfolio/deploy-to-vercel.yml?style=for-the-badge&label=CI%2FCD&logo=githubactions&logoColor=white)](https://github.com/ayush-roy-21/My-portfolio/actions)

### 🛠️ Built With

| Layer | Technology |
|-------|-----------|
| **Framework** | Next.js (App Router) |
| **Styling** | Tailwind CSS |
| **Animations** | Framer Motion + GSAP |
| **Deployment** | Vercel (auto-deploy via GitHub Actions) |
| **Dynamic Routing** | `src/app/projects/[slug]` — per-project detail pages |
| **SEO** | Auto-generated sitemap via `src/app/sitemap.ts` |

### 📁 Project Structure

```
My-portfolio/
├── src/
│   └── app/
│       ├── layout.tsx                   # Root layout
│       ├── page.tsx                     # Home / Hero
│       ├── projects/
│       │   └── [slug]/                  # Dynamic project detail pages
│       │       └── page.tsx
│       └── sitemap.ts                   # Auto-generated SEO sitemap
├── .github/
│   └── workflows/
│       ├── deploy-to-vercel.yml         # Primary CI/CD → Vercel
│       └── deploy-vercel-cli.yml        # CLI fallback deploy
├── public/
├── tailwind.config.ts
├── next.config.ts
└── package.json
```

### ⚙️ CI/CD — GitHub Actions → Vercel

```yaml
# Triggers on every push to `main`
# Required GitHub Secrets:
#   VERCEL_TOKEN        — Vercel personal access token
#   VERCEL_ORG_ID       — Vercel organization ID
#   VERCEL_PROJECT_ID   — Vercel project ID
#
# Fallback: deploy-vercel-cli.yml (needs VERCEL_TOKEN only)
```

| Deploy Method | Details |
|---------------|---------|
| **GitHub Actions (primary)** | Push to `main` → auto-deploy via `deploy-to-vercel.yml` |
| **Vercel CLI (fallback)** | `VERCEL_TOKEN` only → `deploy-vercel-cli.yml` |
| **Vercel manual import** | Import repo → connect `main` branch → defaults are fine |
| **Netlify** | Build cmd: `npm run build` · Publish dir: `.next` |

---

## 🛡️ Technical Arsenal

<details>
<summary><b>🔐 Cybersecurity & Offensive Security</b></summary>
<br>

- **VAPT** — Penetration Testing & Vulnerability Assessment using industry-standard methodologies
- **Network Security** — Traffic Analysis via Wireshark, Tcpdump, ARP Spoofing Detection
- **Web App Security** — OWASP Top 10 Testing & Patching
- **Malware Analysis** — Reverse Engineering, Static/Dynamic Analysis & Threat Intelligence
- **OSINT** — Open-Source Intelligence gathering & Dark Web Monitoring

</details>

<details>
<summary><b>⛓️ Blockchain & Smart Contract Security</b></summary>
<br>

- **Solidity** Smart Contract Development (Ethereum, Binance Smart Chain, Polygon)
- **Security Auditing** — Reentrancy, Integer Overflow, Gas Optimization via Slither & Mythril
- **Crypto Forensics** — Transaction Tracing, Wallet Clustering & Fraud Detection
- **DeFi Security** — Multi-Sig Wallets, Trustless Escrow, AML Dashboard Design

</details>

<details>
<summary><b>💻 Languages</b></summary>
<br>

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![PL/SQL](https://img.shields.io/badge/PL%2FSQL-F80000?style=flat-square&logo=oracle&logoColor=white)

</details>

<details>
<summary><b>🧰 Frameworks, Tools & Security Stack</b></summary>
<br>

**Web & Frontend:**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Web3.js](https://img.shields.io/badge/Web3.js-F16822?style=flat-square&logo=web3dotjs&logoColor=white)

**Security Tools:**

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-6d28d9?style=flat-square&logoColor=white)
![Slither](https://img.shields.io/badge/Slither-363636?style=flat-square&logo=solidity&logoColor=white)
![Mythril](https://img.shields.io/badge/Mythril-FF4500?style=flat-square&logoColor=white)

**DevOps & Infra:**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</details>

---

## 🚀 Featured Projects

### 1. 📈 EigenTrade — Automated ML Trading System
> `Python` · `Machine Learning` · `PL/SQL` · `LLM Integration`

An automated trading engine powered by custom regression models and a real-time LLM-based "Explainer Module" that generates human-readable market justifications per trade.

| Metric | Result |
|--------|--------|
| 🎯 Prediction Accuracy | **50–55%** on historical stock data |
| ⚡ Trade Interpretation Latency | Reduced to **2 seconds** via LLM Explainer Module |
| 🗄️ Data Retrieval Optimization | **40% faster** via advanced PL/SQL query tuning |
| 📊 Records Processed | **10–20 million** historical records efficiently |

---

### 2. 🔍 Smart Contract Vulnerability Scanner
> `Python` · `Solidity` · `Slither` · `Mythril`

Multi-engine static analysis pipeline that automates smart contract auditing and generates developer-facing remediation reports in seconds.

| Metric | Result |
|--------|--------|
| 🐛 Vulnerability Patterns | **15+ critical patterns** (Reentrancy, Integer Overflow, etc.) |
| ⏱️ Audit Time Reduction | **40%** less manual review time |
| ✅ False Negatives | **Zero** in controlled test environments |
| 💨 Report Generation | **< 5 seconds** via developer web interface |

---

### 3. 🎣 Phishing Threat Detection & Analysis System
> `Python` · `Laravel` · `Browser Extension`

Browser extension + honeypot deception system that blocks malicious domains before page load and auto-reports threats to authorities via custom scraping bots.

| Metric | Result |
|--------|--------|
| ⚡ URL Analysis Speed | **50ms** per URL — pre-page-load |
| 🪤 Honeypot Neutralization | **20–30%** of active threats redirected to isolated environments |
| 📬 Response Automation | Automated takedown reporting to authorities |

---

### 4. 🌐 Decentralized Remittance Platform
> `Solidity` · `React.js` · `Web3.js`

Blockchain-based payment gateway with Multi-Sig Wallets, trustless Escrow contracts, and a real-time AML dashboard for suspicious wallet cluster detection.

| Metric | Result |
|--------|--------|
| 💸 Transaction Fee Reduction | **90%** vs traditional cross-border banking |
| ⏳ Settlement Time | **< 1 minute** vs days with SWIFT |
| 🔐 Fund Security | **100%** secured via Multi-Sig + Escrow |
| 🔎 AML Dashboard | Real-time suspicious wallet cluster flagging |

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=ayush-roy-21&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ayush-roy-21&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=ayush-roy-21&theme=tokyonight&hide_border=true&background=0d1117)](https://git.io/streak-stats)

</div>

---

## 🏆 GitHub Trophies

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=ayush-roy-21&theme=tokyonight&no-frame=true&row=1&column=7&margin-w=8)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 🎯 Areas of Deep Interest

```
🔬  Digital Forensics & Investigation  →  Cyber Crime, Malware Analysis, Reverse Engineering
⛓️   Blockchain Security               →  Smart Contract Auditing, DeFi Fraud, Crypto Tracing
🌍  Threat Intelligence                →  OSINT, Dark Web Monitoring, APT Tracking
💳  Financial Security                 →  Online Fraud Detection, Secure Payment Architectures
🌐  Geopolitics × Cyber Warfare        →  International Relations & State-Sponsored Cyber Ops
```

---

## 🌐 Languages

| Language | Level |
|----------|-------|
| 🇬🇧 English | Professional Proficiency (C1) |
| 🇮🇳 Hindi | Native |
| 🇮🇳 Gujarati | Fluent |

---

## 🤝 Leadership & Volunteering

**🎭 Surat Literature Festival (LitFest) — Event Volunteer** · *Surat, Gujarat · 2026*

> Managed on-ground logistics, guest relations, and crowd control for major sessions, ensuring seamless event execution.

---

## 📫 Let's Connect

<div align="center">

Working on **cybersecurity**, **blockchain security**, **DeFi**, or **ML-driven threat intelligence**? Let's collaborate.

[![Portfolio](https://img.shields.io/badge/🌐_Visit_Portfolio-6d28d9?style=for-the-badge)](https://my-portfolio-msk9.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ayush2006kumar996@gmail.com)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

*"Security is not a product, but a process."* — Bruce Schneier

</div>
