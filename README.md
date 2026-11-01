<div align="center">

# 👨‍💻 Rufat Azizzade

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&pause=1000&color=25D366&center=true&vCenter=true&width=435&lines=Test+Automation+Developer+%40+Gen;Software+Engineering+Student;Open+Source+Contributor)](https://git.io/typing-svg)

<p align="center">
  <img src="https://img.shields.io/badge/Location-Prague%2C%20Czech%20Republic-0969da?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Education-FIT%20%C4%8CVUT%20Prague-blue?style=for-the-badge&logo=graduationschool&logoColor=white" alt="Education" />
  <img src="https://img.shields.io/badge/Role-QA%20%26%20Software%20Engineer-success?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Role" />
  <img src="https://komarev.com/ghpvc/?username=rufatazizzade&label=Profile%20Views&color=0e75b6&style=for-the-badge" alt="Profile Views" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/rufatazizzade"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:azizzruf@fit.cvut.cz"><img src="https://img.shields.io/badge/Academic%20Email-azizzruf%40fit.cvut.cz-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="mailto:rufatazizzade@gmail.com"><img src="https://img.shields.io/badge/Personal%20Email-rufatazizzade%40gmail.com-EA4335?style=flat-square&logo=mail.ru&logoColor=white" alt="Email" /></a>
</p>

---

### 🧭 Navigation
[🧪 **QA Test Runner**](#-interactive-qa-test-runner) • 
[💼 **Experience**](#-work-experience) • 
[🏆 **Hackathons**](#-hackathon-hall-of-fame) • 
[🚀 **Featured Projects**](#-featured-projects) • 
[🛠️ **Tech Stack**](#-tech-stack--arsenal) • 
[📊 **Metrics**](#-github-metrics--activity) • 
[📫 **Contact**](#-get-in-touch)

---

</div>

## 📌 Executive Summary

Detail-oriented Software Engineering student at **Czech Technical University in Prague (CTU FIT)** with hands-on expertise in:
- **Test Automation & QA Architecture**: Browser automation with Python, regression frameworks, BrowserStack device/browser matrix testing, and TeamCity CI/CD validation.
- **Systematic Root Cause Analysis**: Reproduce ➔ Isolate Root Cause ➔ Formulate Failure Scenarios ➔ Patch ➔ Automated Verification.
- **Competitive Innovation**: Multiple **1st Place** champion across prestigious international hackathons (*Teknofest 2024*, *EuroTeQ*, *World Robot Olympiad*).

---

## 🧪 Interactive QA Test Runner

```shell
============================= test session starts ==============================
platform: cross-platform (Linux / Windows / macOS) | runtime: Python 3.12 | runner: TeamCity CI
rootdir: /home/rufat/profile-specs
plugins: pytest-xdist, pytest-cov, allure-pytest

tests/test_profile.py::test_education_ctu_prague             PASSED [ 14%] (FIT ČVUT Software Engineering)
tests/test_profile.py::test_industry_qa_gen_digital          PASSED [ 28%] (Avast, AVG, Neo Browser automation)
tests/test_profile.py::test_sec_vulnerability_bp_brazil      PASSED [ 42%] (Enterprise anomaly detection)
tests/test_profile.py::test_embedded_iot_versetech           PASSED [ 57%] (ATmega diagnostic routine automation)
tests/test_profile.py::test_hackathon_championships          PASSED [ 71%] (1st @ Teknofest, 1st @ EuroTeQ, 1st @ WRO)
tests/test_profile.py::test_automation_regression_suite      PASSED [ 85%] (Python, BrowserStack, Jira, Docker)
tests/test_profile.py::test_multilingual_proficiency         PASSED [100%] (EN: Fluent, AZ: Native, TR: Fluent)

======================== 7 passed, 0 failed in 0.42s =========================
```

<details>
<summary>🔍 <b>CLICK TO INSPECT: Defect Lifecycle & Root Cause Methodology (QA Standard)</b></summary>
<br>

```yaml
Defect ID: DEF-2026-042
Severity: High | Priority: P1 | Status: RESOLVED & VERIFIED
Product: Cross-Browser Core Engine
Target Platform: Win11 / macOS Sonoma / Ubuntu 24.04 (BrowserStack Matrix)

Reproducible Steps:
  1. Trigger high-throughput asynchronous API requests through client session.
  2. Simulate network latency fluctuation and sudden socket disconnect.
  3. Verify whether browser worker thread gracefully recovers or stalls.

Expected Result: Worker thread retries with exponential backoff and logs telemetry.
Actual Result: Worker thread stalled due to uncaught race condition in connection pooling.

Root Cause Analysis:
  - Connection teardown listener lacked mutex guard during concurrent async cleanup.

Remediation & Regression Suite:
  - Patched socket teardown synchronization.
  - Authored automated Python regression test covering 500 parallel socket drops.
  - CI verification: 100% Passing on TeamCity build pipeline across all configurations.
```

</details>

<details>
<summary>⚙️ <b>CLICK TO INSPECT: Automated Browser & Platform Testing Matrix</b></summary>
<br>

| Browser / Target | Automation Engine | Execution Matrix | Pipeline |
| :--- | :--- | :--- | :--- |
| **Avast Secure Browser** | Python + Selenium / PyTest | Win 10/11, macOS, Android | TeamCity CI / Daily Regression | E2E Automation |
| **Neo Browser** | Python Custom Test Scripts | Cross-platform builds | Continuous Smoke & Functional | Performance Testing | 
| **AVG Secure Browser** | BrowserStack Automation | Multi-OS version matrix | Pre-release sanity gates |
| **Backend REST APIs** | Requests / PyTest / Docker | Sandboxed container runtime | Automated security & contract checks |

</details>

---

## 💼 Work Experience

### 🏢 **Gen Digital** · *Test Automation Engineer*
`June 2026 – Present` · *Prague, Czech Republic*
- Perform comprehensive manual and automated testing across **Avast Secure Browser**, **Neo Browser**, and **AVG Secure Browser** across multiple OS versions and platforms.
- Author and maintain **Python-based automation scripts** to drastically reduce manual regression effort and elevate test coverage across continuous builds.
- Execute cross-platform testing via **BrowserStack**, isolating environment-specific edge cases across complex OS and browser version matrices.
- Track defects in **Jira**, authoring reproducible steps, expected vs. actual behaviors, and severity classifications for rapid developer handoff.
- Validate **TeamCity CI/CD pipelines**, triaging test failures and verifying fixes across regression cycles in Agile sprints.

### 🏛️ **Czech Technical University in Prague** · *Technical Assistant*
`February 2026 – Present` · *Prague, Czech Republic*
- Supervise and operate complex audiovisual streaming infrastructures for live academic sessions, isolating and resolving live technical faults in real time.
- Apply structured QA methodology: **Reproduce ➔ Isolate Root Cause ➔ Apply Fix ➔ Verify Resolution**.
- Document recurring technical anomalies and develop operational knowledge bases to prevent system regressions.

### 🛡️ **BP Brazil (via AFS Global STEM Academies)** · *Information Security Intern*
`July 2025 – August 2025` · *Brazil*
- Monitored enterprise infrastructure for security deviations and anomalous traffic patterns with a test-and-verify mindset.
- Documented vulnerabilities with precise reproduction steps, communicating remediation actions to technical engineering teams.
- Selected via a **Full Merit Scholarship** international STEM exchange.

### ⚡ **VerseTech** · *Software Developer & Co-founder*
`January 2024 – October 2025` · *Prague, Czech Republic*
- Co-founded an embedded IoT hardware-software startup; designed, tested, and iterated firmware for ATmega-based smart devices.
- Built **Python and C++ test automation scripts** for diagnostics and sensor data acquisition, catching regressions across firmware versions.
- Translated physical hardware behaviors into automated software test cases and documented integration defects.

---

## 🏆 Hackathon Hall of Fame

<div align="center">

| Award | Event | Project / Focus | Tech Stack |
| :---: | :--- | :--- | :--- |
| 🥇 **1st Place** | **Teknofest 2024** (Türkiye) | **Secture**: Automated Backend Security Validation Tool | Docker, Python, TypeScript, AI API |
| 🥇 **1st Place** | **EuroTeQ Hackathon** | **Pmesh**: Industrial Early Acoustic Leak Detection | ATmega, Embedded C, Sensors, DSP |
| 🥇 **1st Place** | **Teens in AI Hackathon** | AI Innovation & Applied Machine Learning | Python, ML Models, API Architecture |
| 🥇 **1st Place** | **World Robot Olympiad (WRO)**, Rome | Robotics Engineering, Autonomous Control & Logic | C++, Embedded Controllers, Sensors |
| 🥈 **2nd Place** | **Google AI Hackathon** | Generative AI & Developer Tooling | Python, Google Gemini APIs, Cloud |
| 🥈 **2nd Place** | **Cultech Hackathon** | Applied Technology Solutions | Full-Stack Web, APIs |
| 🎖️ **Nomination** | **Teknofest 2025** (Türkiye) | Best Engineering & Technology Team Nomination | System Architecture & Automation |
| 🎓 **Scholarship** | **AFS Global STEM Academies** | Full Merit International Scholarship (Brazil) | Information Security & Global Leadership |

</div>

---

## 🚀 Featured Projects

<table width="100%">
<tr>
<td width="50%" valign="top">

### 🛡️ **Secture – Backend Security Validation Tool**
> *🥇 1st Place – Teknofest 2024 (Türkiye)*

A CLI framework that spins up backend services in sandboxed Docker containers to execute automated regression and vulnerability test suites.
- **AI-Assisted Triaging**: Automatically categorizes defects by severity and outputs actionable code patch recommendations.
- **Approval-Based Patch Verification**: Automatically re-runs full test suites upon patch application to prevent regressions.
- **Stack**: `Docker` · `Python` · `TypeScript` · `AI API` · `Security Auditing`

</td>
<td width="50%" valign="top">

### 📡 **Pmesh – Industrial Acoustic Leak Detection**
> *🥇 1st Place – EuroTeQ Hackathon* • [GitHub Repository](https://github.com/rufatazizzade/p-mesh-net)

A real-time acoustic sensing and signal processing mesh network for early industrial pipeline fault detection.
- **Hardware-in-the-Loop (HIL) Testing**: Validated sensor ranges and anomaly thresholds under simulated physical stress.
- **Edge Diagnostics**: Deployed low-latency deviation detection directly on microcontrollers.
- **Stack**: `ATmega` · `Embedded C` · `Acoustic Sensors` · `Signal Processing`

</td>
</tr>
</table>

<details>
<summary>📂 <b>View More Open-Source Repositories</b></summary>
<br>

- 🔔 [**PatchAlert**](https://github.com/rufatazizzade/PatchAlert) — Continuous vulnerability and patch monitoring utility.
- 🎓 [**CVUT_Username_Creator**](https://github.com/rufatazizzade/CVUT_Username_Creator) — Automated credential & identity generator for university systems.
- 🤟 [**Real-Time Speech to Hand Sign**](https://github.com/rufatazizzade/real-time-speech-to-hand-sign) — Computer vision and accessibility translation system.
- 🌐 [**WebControl**](https://github.com/rufatazizzade/webcontrol) & [**RemoteControl**](https://github.com/rufatazizzade/remotecontrol) — Automated remote system management interfaces.

</details>

---

## 🛠️ Tech Stack & Arsenal

<div align="center">

### 💻 Programming Languages
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
</p>

### 🧪 QA & Test Automation
<p>
  <img src="https://img.shields.io/badge/PyTest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/BrowserStack-0052CC?style=for-the-badge&logo=browserstack&logoColor=white" />
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/API%20Testing-4A154B?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Regression%20Testing-2EA44F?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

### ⚙️ CI/CD, DevOps & Security
<p>
  <img src="https://img.shields.io/badge/TeamCity-000000?style=for-the-badge&logo=teamcity&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white" />
  <img src="https://img.shields.io/badge/Nmap-002B49?style=for-the-badge&logo=linux&logoColor=white" />
</p>


</div>

---

## 📊 GitHub Metrics & Activity

<div align="center">

### 🐍 Contribution Activity Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rufatazizzade/rufatazizzade/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/rufatazizzade/rufatazizzade/output/github-contribution-grid-snake.svg">
  <img alt="GitHub Contribution Snake Animation" src="https://raw.githubusercontent.com/rufatazizzade/rufatazizzade/output/github-contribution-grid-snake.svg">
</picture>

<br><br>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=rufatazizzade&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" height="175" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rufatazizzade&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="175" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=rufatazizzade&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

</div>

---

## 🎓 Education & 🌍 Languages

<table width="100%">
<tr>
<td width="55%" valign="top">

### 🎓 Education
- **BSc in Informatics – Software Engineering**  
  *Czech Technical University in Prague (CTU FIT)* · `Sep 2025 – Present`  
  *Relevant Coursework*: Algorithms & Data Structures, Operating Systems, Computer Networks, Object-Oriented Programming, Database Systems.
- **International STEM Exchange**  
  *AFS Global STEM Academies (Brazil)* · `June 2025 – Aug 2025`  
  *Full Merit Scholarship* recipient.

</td>
<td width="45%" valign="top">

### 🗣️ Languages
- 🇦🇿 **Azerbaijani**: Native
- 🇬🇧 **English**: Fluent (Professional Working Proficiency)
- 🇹🇷 **Turkish**: Fluent
- 🇧🇷 **Portuguese**: Beginner (A1–A2)

</td>
</tr>
</table>

---

## 📫 Get In Touch

<div align="center">

```bash
$ curl -sL https://api.github.com/users/rufatazizzade | jq '{name, location, role, email}'
```

```json
{
  "name": "Rufat Azizzade",
  "location": "Prague, Czech Republic 🇨🇿",
  "role": "QA Engineer & Software Engineering Student",
  "academic_email": "azizzruf@fit.cvut.cz",
  "personal_email": "rufatazizzade@gmail.com",
  "linkedin": "https://linkedin.com/in/rufatazizzade"
}
```

<br>

<a href="https://linkedin.com/in/rufatazizzade">
  <img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="mailto:azizzruf@fit.cvut.cz">
  <img src="https://img.shields.io/badge/Send%20an%20Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<br><br>

> *"If debugging is the process of removing software bugs, then programming must be the process of putting them in."*  
> — **Edsger W. Dijkstra**

</div>
