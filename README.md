<!--
  GitHub profile README — github.com/kurniawan-Donn
  Visual direction: Secure Systems / Technical Editorial
  Palette: #080A0D · #11151B · #F2F0E9 · #00D9FF · #9299A5 · #70E1A1

  TODO before publishing:
  1. Verify each project repository URL (see comments inside each project).
  2. Add the real LinkedIn URL (see the Contact section).
  3. Make sure ./assets/banner-dony.jpg exists in this repository.
-->

<div align="center">

<img src="./assets/banner-dony.jpg" alt="Dony Kurniawan — IT Audit, IT Governance, Cybersecurity, and Software Development" width="100%" />

# Dony Kurniawan

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3200&pause=1200&color=00D9FF&center=true&vCenter=true&repeat=true&width=640&height=36&lines=IT+Audit+%26+IT+Governance;Cybersecurity+%26+Risk+Assessment;Software+Development+%26+Python+Automation" alt="Animated text cycling through: IT Audit and IT Governance, Cybersecurity and Risk Assessment, Software Development and Python Automation" />

Final-year D3 Information Technology student at **Politeknik Negeri Madiun**, Indonesia 🇮🇩

I like understanding how systems work, where risks emerge, and how practical controls make technology more secure and reliable.

[About](#about) · [Projects](#featured-projects) · [Tech Stack](#tech-stack) · [Learning](#learning-roadmap) · [Contact](#get-in-touch)

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-11151B?style=for-the-badge&logo=vercel&logoColor=00D9FF)](https://portofolio-dony.vercel.app)
[![Email](https://img.shields.io/badge/EMAIL-11151B?style=for-the-badge&logo=gmail&logoColor=00D9FF)](mailto:donykurniawan128@gmail.com)
[![GitHub](https://img.shields.io/badge/GITHUB-11151B?style=for-the-badge&logo=github&logoColor=00D9FF)](https://github.com/kurniawan-Donn)

</div>

<br />

| At a glance | |
|:--|:--|
| **Education** | D3 Information Technology, Politeknik Negeri Madiun (final year) |
| **Primary direction** | IT Audit and IT Governance |
| **Supporting areas** | Cybersecurity, risk assessment, software development, Python automation |
| **Currently learning** | ISO 27001, COBIT 2019, threat modeling, Next.js, TypeScript, Supabase |
| **Open to** | Internships · entry-level IT roles · technical collaboration |

---

## About

> A technology enthusiast focused on understanding systems, identifying risks, and building practical solutions through IT audit, security, and software development.

My main career interest is **IT audit**: checking whether systems have appropriate controls, whether those controls work as intended, and where technology-related risks need attention. I approach it through three connected areas:

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#11151B', 'primaryTextColor': '#F2F0E9', 'primaryBorderColor': '#00D9FF', 'lineColor': '#9299A5', 'fontFamily': 'monospace'}}}%%
flowchart LR
    DEV["BUILD<br/>Software development<br/>how systems are made"] --> SEC["PROTECT<br/>Cybersecurity<br/>how systems are attacked and defended"] --> AUD["VERIFY<br/>IT audit and governance<br/>whether controls work"]
```

- **Software development** shows me how applications are actually built, and where controls belong or fail.
- **Cybersecurity** helps me understand threats and the technical safeguards that counter them.
- **IT audit and governance** give me the framework to evaluate controls, compliance, and risk.

**Principles:** *Secure by design, auditable by default.* · *Build to understand. Create to solve.*

---

## Featured Projects

### 🔐 Regulation Audit Assistant

![Status: Experimental](https://img.shields.io/badge/status-experimental-00D9FF?style=flat-square&labelColor=11151B)
![Focus: IT audit automation](https://img.shields.io/badge/focus-IT_audit_automation-9299A5?style=flat-square&labelColor=11151B)

**Problem.** Public IT regulations are long, and turning them into consistent audit procedures by hand is slow and repetitive.

**Approach.** An exploration of Python-assisted document processing and AI to extract requirements from regulatory documents and organize them into structured audit procedures, with Excel as the target output. The project is exploratory, and AI-extracted results must be reviewed by a human before any real audit use.

**Stack.** `Python` `PDF processing` `AI-assisted workflows` `Excel`

<details>
<summary><b>View the intended workflow</b> (conceptual)</summary>

<br />

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#11151B', 'primaryTextColor': '#F2F0E9', 'primaryBorderColor': '#00D9FF', 'lineColor': '#9299A5', 'fontFamily': 'monospace'}}}%%
flowchart LR
    A["Regulatory<br/>document"] --> B["Text<br/>extraction"] --> C["AI-assisted<br/>requirement<br/>extraction"] --> D["Human<br/>review"] --> E["Structured audit<br/>procedures"] --> F["Excel<br/>export"]
```

This shows the design intent, not a list of finished features. Human review is a deliberate step because audit conclusions should never rest on unverified AI output.

</details>

<!-- TODO: add the verified repository link:
[View repository →](https://github.com/kurniawan-Donn/REPLACE-WITH-REPOSITORY-NAME)
TODO: once features land, add a short "Implemented / Planned" list so the status stays accurate. -->

<br />

### 📱 LumiNote

![Status: Complete](https://img.shields.io/badge/status-complete-70E1A1?style=flat-square&labelColor=11151B)
![Platform: Android](https://img.shields.io/badge/platform-android-9299A5?style=flat-square&labelColor=11151B)

**Problem.** Note-taking apps are hard to rely on when the connection is unreliable.

**What it does.** An offline-first notes and tasks app that works fully without an internet connection, using local storage for everyday data.

**Stack.** `Kotlin` `Android` `Room`

<!-- TODO: add the verified LumiNote repository link.
     Unverified candidate from an earlier draft (do not publish until checked): https://github.com/kurniawan-Donn/LumiNote -->

<br />

### 🎲 Spinly

![Status: Complete](https://img.shields.io/badge/status-complete-70E1A1?style=flat-square&labelColor=11151B)
![Platform: Android](https://img.shields.io/badge/platform-android-9299A5?style=flat-square&labelColor=11151B)

**Problem.** Group decisions work best when everyone sees the same result at the same moment.

**What it does.** A multiplayer random spinner. Users join a room with a room code and see the same result in real time.

**Stack.** `Android` `Firebase Authentication` `Cloud Firestore`

<details>
<summary><b>View how room sync works</b> (simplified)</summary>

<br />

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#11151B', 'primaryTextColor': '#F2F0E9', 'primaryBorderColor': '#00D9FF', 'lineColor': '#9299A5', 'fontFamily': 'monospace'}}}%%
flowchart LR
    P["Player"] -->|"signs in"| A["Firebase<br/>Authentication"]
    P -->|"joins with room code"| F[("Cloud Firestore<br/>room state")]
    F -->|"real-time sync"| R["Same result<br/>for every player"]
```

</details>

<!-- TODO: add the verified Spinly repository link, and confirm the implementation language. -->

<br />

### 🌐 Internship Program CMS

![Status: Complete](https://img.shields.io/badge/status-complete-70E1A1?style=flat-square&labelColor=11151B)
![Platform: Web](https://img.shields.io/badge/platform-web-9299A5?style=flat-square&labelColor=11151B)

**Problem.** Internship program information tends to end up scattered across different places.

**What it does.** A web-based content management system for managing internship program information, activity galleries, alumni data, and FAQs in one place.

**Stack.** `Laravel` `PHP` `MySQL`

<!-- TODO: add the verified Internship Program CMS repository link. -->

<div align="center">

<br />

[![Browse all repositories](https://img.shields.io/badge/BROWSE_ALL_REPOSITORIES-11151B?style=for-the-badge&logo=github&logoColor=00D9FF)](https://github.com/kurniawan-Donn?tab=repositories)

</div>

---

## Tech Stack

**Languages**
<br />
![PHP](https://img.shields.io/badge/PHP-11151B?style=flat-square&logo=php&logoColor=00D9FF)
![Python](https://img.shields.io/badge/Python-11151B?style=flat-square&logo=python&logoColor=00D9FF)
![Kotlin](https://img.shields.io/badge/Kotlin-11151B?style=flat-square&logo=kotlin&logoColor=00D9FF)
![JavaScript](https://img.shields.io/badge/JavaScript-11151B?style=flat-square&logo=javascript&logoColor=00D9FF)
![TypeScript](https://img.shields.io/badge/TypeScript-11151B?style=flat-square&logo=typescript&logoColor=00D9FF)
![HTML5](https://img.shields.io/badge/HTML5-11151B?style=flat-square&logo=html5&logoColor=00D9FF)
![CSS3](https://img.shields.io/badge/CSS3-11151B?style=flat-square&logo=css3&logoColor=00D9FF)

<sub>Used in projects: PHP, Python, Kotlin.</sub>

**Frameworks and tools**
<br />
![Laravel](https://img.shields.io/badge/Laravel-11151B?style=flat-square&logo=laravel&logoColor=00D9FF)
![Next.js](https://img.shields.io/badge/Next.js-11151B?style=flat-square&logo=nextdotjs&logoColor=00D9FF)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-11151B?style=flat-square&logo=tailwindcss&logoColor=00D9FF)
![Android Studio](https://img.shields.io/badge/Android_Studio-11151B?style=flat-square&logo=androidstudio&logoColor=00D9FF)
![Git](https://img.shields.io/badge/Git-11151B?style=flat-square&logo=git&logoColor=00D9FF)
![Figma](https://img.shields.io/badge/Figma-11151B?style=flat-square&logo=figma&logoColor=00D9FF)
![VS Code](https://img.shields.io/badge/VS_Code-11151B?style=flat-square&logo=visualstudiocode&logoColor=00D9FF)

<sub>Used in projects: Laravel, Android Studio. Learning: Next.js.</sub>

**Databases and backend services**
<br />
![MySQL](https://img.shields.io/badge/MySQL-11151B?style=flat-square&logo=mysql&logoColor=00D9FF)
![SQLite](https://img.shields.io/badge/SQLite-11151B?style=flat-square&logo=sqlite&logoColor=00D9FF)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-11151B?style=flat-square&logo=postgresql&logoColor=00D9FF)
![Firebase](https://img.shields.io/badge/Firebase-11151B?style=flat-square&logo=firebase&logoColor=00D9FF)
![Supabase](https://img.shields.io/badge/Supabase-11151B?style=flat-square&logo=supabase&logoColor=00D9FF)

<sub>Used in projects: MySQL, Firebase (Authentication and Firestore), Room on SQLite. Learning: Supabase.</sub>

**Audit, governance, and security interests**
<br />
`IT audit` `IT governance` `Risk assessment` `System analysis`

<sub>The technologies above reflect a mix of project experience and ongoing learning, not equal proficiency in every tool.</sub>

---

## Learning Roadmap

| Area | Current focus | Why it matters to my path |
|:--|:--|:--|
| **IT audit frameworks** | ISO 27001, COBIT 2019 | Common reference points for information security management and IT governance |
| **Cybersecurity** | Network analysis, threat modeling | Shows how systems can be attacked and where safeguards belong |
| **Python automation** | Audit and document-processing scripts | Reduces repetitive manual work when reviewing documents and evidence |
| **Responsible AI** | Human-reviewed AI-assisted workflows | AI output needs verification before it is used in audit work |
| **Modern web stack** | Next.js, TypeScript, Supabase | Broadens how I build and understand modern applications |

---

## GitHub Activity

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=kurniawan-Donn&show_icons=true&hide_border=true&border_radius=8&bg_color=11151B&title_color=00D9FF&icon_color=00D9FF&text_color=F2F0E9" alt="GitHub profile statistics for kurniawan-Donn" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kurniawan-Donn&layout=compact&langs_count=6&hide_border=true&border_radius=8&bg_color=11151B&title_color=00D9FF&text_color=F2F0E9" alt="Most-used languages across public GitHub repositories" />

<sub>These cards come from a third-party service and may occasionally be unavailable. Language statistics describe repository contents, not overall skill.</sub>

</div>

---

## Get in Touch

I'm open to **internships, entry-level IT roles, and technical collaboration**, especially in IT audit, governance, cybersecurity, and risk-related work. If you're working on something in those areas, I'd be glad to hear from you.

- **Portfolio:** [portofolio-dony.vercel.app](https://portofolio-dony.vercel.app)
- **Email:** [donykurniawan128@gmail.com](mailto:donykurniawan128@gmail.com)
- **GitHub:** [@kurniawan-Donn](https://github.com/kurniawan-Donn)
<!-- TODO: add LinkedIn once the real URL is known:
- **LinkedIn:** [your name](https://www.linkedin.com/in/YOUR-REAL-USERNAME) -->

<div align="center">

<br />

<img src="https://komarev.com/ghpvc/?username=kurniawan-Donn&label=PROFILE%20VIEWS&color=00D9FF&style=flat-square" alt="Profile view counter" />

</div>