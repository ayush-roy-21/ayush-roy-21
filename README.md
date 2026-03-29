<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Ayush%20Roy&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Senior%20Cybersecurity%20Engineer%20%7C%20Blockchain%20Security%20%7C%20SVNIT%20Surat&descAlignY=58&descSize=16" width="100%"/>

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio?style=for-the-badge&logoColor=white)](https://my-portfolio-msk9.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/YOUR_LEETCODE)
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

    flagship   = "https://sc-vulnerability-scanner-12sr.vercel.app/"
    portfolio  = "https://my-portfolio-msk9.vercel.app/"
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

## 🔐 Flagship Project — Smart Contract Vulnerability Scanner

> A comprehensive smart contract security analysis tool combining **static analysis** and **symbolic execution** for thorough security assessment of Ethereum smart contracts.

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-sc--vulnerability--scanner--12sr.vercel.app-6d28d9?style=for-the-badge&logo=vercel&logoColor=white)](https://sc-vulnerability-scanner-12sr.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org/)
[![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)](https://soliditylang.org/)

---

### ✨ Key Features

| Feature | Description |
|---------|-------------|
| 🔬 **Static Analysis** | Slither-like control/data flow analysis and pattern matching |
| 🧮 **Symbolic Execution** | Mythril-like path exploration and constraint solving |
| 🖥️ **Interactive Web UI** | Upload contracts, view reports, get security recommendations |
| 🐛 **Detects** | Reentrancy · Arithmetic Overflow/Underflow · Access Control · Gas Inefficiencies |
| ⚡ **Fast Reports** | Full vulnerability report generated in **< 5 seconds** |
| ✅ **Zero False Negatives** | In controlled test environments across 15+ vulnerability patterns |

---

### 🏗️ System Architecture

```
┌─────────────────┐      ┌─────────────────┐      ┌──────────────────┐
│    Frontend     │      │     Backend     │      │  Smart Contracts │
│    (React)      │◄────►│    (Python)     │◄────►│   (Solidity)     │
├─────────────────┤      ├─────────────────┤      ├──────────────────┤
│ • Contract Form │      │ • Static Anlys  │      │ • AST Analysis   │
│ • Results View  │      │ • Symbolic Exec │      │ • Vuln Patterns  │
│ • Vuln Dashboard│      │ • Detectors     │      │ • Test Cases     │
│                 │      │ • API Endpoints │      │                  │
└────────┬────────┘      └────────┬────────┘      └────────┬─────────┘
         │                        │                         │
         ▼                        ▼                         ▼
┌─────────────────┐      ┌─────────────────┐      ┌──────────────────┐
│ External Svcs   │      │    Database     │      │   Blockchain     │
├─────────────────┤      ├─────────────────┤      ├──────────────────┤
│ • Code Repos    │      │ • Scan History  │      │ • Mainnet        │
│ • Docs          │      │ • Vulns Store   │      │ • Testnet        │
│ • Updates       │      │ • Analytics     │      │ • Local Node     │
└─────────────────┘      └─────────────────┘      └──────────────────┘
```

---

### 🔄 Analysis Flow

**Backend Pipeline:**

```mermaid
flowchart TB
    A[Contract Input] --> B[Static Analyzer]
    A --> C[Symbolic Executor]
    B --> D[Detectors]
    C --> D
    D --> E[Access Control]
    D --> F[Arithmetic]
    D --> G[Gas]
    D --> H[Reentrancy]
    E & F & G & H --> I[Analysis Results]
    I --> J[API Response]
```

**Frontend Pipeline:**

```mermaid
flowchart TB
    A[Contract Form] --> B[Contract Analysis Page]
    B --> C[Analysis Results]
    C --> D[Vulnerability Report]
    D --> E[Issue Details]
    D --> F[Stats Summary]
    D --> G[Vulnerability Chart]
    E & F & G --> H[Dashboard]
    H --> I[Recent Scans]

    style A fill:#f9f,stroke:#333
    style H fill:#bbf,stroke:#333
```

---

### 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | React · TypeScript |
| **Backend** | Python · Flask / FastAPI |
| **Analysis Engines** | Static Analyzer · Symbolic Executor · AST Parser |
| **Vulnerability Detectors** | Reentrancy · Arithmetic · Access Control · Gas |
| **Target Contracts** | Solidity (Ethereum) |
| **Deployment** | Vercel |

---

### 📁 Project Structure

```
sc-vulnerability-scanner/
├── backend/
│   ├── analyzers/
│   │   ├── ast_parser.py           # Solidity AST parsing
│   │   ├── static_analyzer.py      # Static analysis engine
│   │   └── symbolic_executor.py    # Symbolic execution engine
│   ├── detectors/
│   │   ├── access_control_detector.py
│   │   ├── arithmetic_detector.py
│   │   ├── gas_detector.py
│   │   └── reentrancy_detector.py
│   ├── tests/
│   │   └── contracts/              # Test Solidity contracts
│   ├── app.py                      # Main Flask/FastAPI app
│   └── requirements.txt
├── frontend/
│   ├── src/
│   │   ├── components/             # Reusable UI components
│   │   ├── pages/                  # Application pages
│   │   ├── theme/                  # UI theme config
│   │   └── utils/                  # Helper utilities
│   ├── package.json
│   └── tsconfig.json
└── scripts/                        # Utility scripts
```

---

### ⚙️ Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/ayush-roy-21/sc-vulnerability-scanner.git

# 2. Backend setup
cd backend
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py                   # Starts on http://localhost:5000

# 3. Frontend setup (new terminal)
cd frontend
npm install
npm start                       # Starts on http://localhost:3000

# 4. Scan a contract via CLI
curl -X POST -F "file=@MyContract.sol" http://localhost:5000/analyze
```

---

### 🐛 Supported Vulnerability Types

```
⚠️  Reentrancy Attacks          →  Cross-function and cross-contract reentrancy
🔢  Arithmetic Overflow          →  Integer overflow / underflow in Solidity <0.8
🔑  Access Control Issues        →  Unprotected functions, tx.origin misuse
⛽  Gas Inefficiencies           →  Unbounded loops, expensive storage patterns
```

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
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</details>

---

## 🚀 Other Projects

### 📈 EigenTrade — Automated ML Trading System
> `Python` · `Machine Learning` · `PL/SQL` · `LLM Integration`

| Metric | Result |
|--------|--------|
| 🎯 Prediction Accuracy | **50–55%** on historical stock data |
| ⚡ LLM Explainer Latency | Reduced to **2 seconds** per trade |
| 🗄️ Data Retrieval Speed | **40% faster** via advanced PL/SQL tuning |
| 📊 Records Processed | **10–20 million** historical records |

---

### 🎣 Phishing Threat Detection & Analysis System
> `Python` · `Laravel` · `Browser Extension`

| Metric | Result |
|--------|--------|
| ⚡ URL Analysis Speed | **50ms** per URL — pre-page-load blocking |
| 🪤 Honeypot Neutralization | **20–30%** of active threats isolated |
| 📬 Response Automation | Auto-reporting to authorities via scraping bots |

---

### 🌐 Decentralized Remittance Platform
> `Solidity` · `React.js` · `Web3.js`

| Metric | Result |
|--------|--------|
| 💸 Fee Reduction | **90%** vs traditional cross-border banking |
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

Working on **smart contract security**, **DeFi**, **blockchain forensics**, or **ML-driven threat intelligence**? Let's collaborate.

[![Live Tool](https://img.shields.io/badge/🔐_Try_SC_Scanner-6d28d9?style=for-the-badge)](https://sc-vulnerability-scanner-12sr.vercel.app/)
[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-111827?style=for-the-badge)](https://my-portfolio-msk9.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ayush2006kumar996@gmail.com)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

*"Security is not a product, but a process."* — Bruce Schneier

</div>
