<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:1F6FEB&height=200&section=header&text=Shreyas&fontColor=ffffff&fontSize=72&animation=fadeIn&fontAlignY=36&desc=High%20School%20Builder%20%20%7C%20%20Cybersecurity%20and%20AI&descSize=18&descAlignY=58" width="100%" alt="Shreyas profile banner" />

**High school student in the Dallas-Fort Worth area building a cybersecurity and AI portfolio.**

Current focus: defensive security tooling, ML classifiers, and Rust systems work.

I direct Claude Code and other AI agents end to end and own the architecture, security, and product decisions.

<img src="https://komarev.com/ghpvc/?username=shreyas-tech7&label=Profile%20views&color=1F6FEB&style=flat" alt="Profile views" />

</div>

---

## Tech Stack

**Languages**

![Rust](https://img.shields.io/badge/Rust-0D1117?style=for-the-badge&logo=rust&logoColor=DEA584)
![Python](https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=3776AB)
![TypeScript](https://img.shields.io/badge/TypeScript-0D1117?style=for-the-badge&logo=typescript&logoColor=3178C6)
![JavaScript](https://img.shields.io/badge/JavaScript-0D1117?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

**Frameworks**

![Next.js](https://img.shields.io/badge/Next.js-0D1117?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-0D1117?style=for-the-badge&logo=tailwindcss&logoColor=06B6D4)
![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=for-the-badge&logo=fastapi&logoColor=009688)
![Tauri](https://img.shields.io/badge/Tauri-0D1117?style=for-the-badge&logo=tauri&logoColor=24C8DB)

**Data and Infra**

![Supabase](https://img.shields.io/badge/Supabase-0D1117?style=for-the-badge&logo=supabase&logoColor=3FCF8E)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=4169E1)
![Vercel](https://img.shields.io/badge/Vercel-0D1117?style=for-the-badge&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0D1117?style=for-the-badge&logo=githubactions&logoColor=white)

**Machine Learning**

![scikit-learn](https://img.shields.io/badge/scikit--learn-0D1117?style=for-the-badge&logo=scikitlearn&logoColor=F7931E)

**Security**

![Semgrep](https://img.shields.io/badge/Semgrep-0D1117?style=for-the-badge&logo=semgrep&logoColor=white)
![Bandit](https://img.shields.io/badge/Bandit-0D1117?style=for-the-badge)
![Nmap](https://img.shields.io/badge/Nmap-0D1117?style=for-the-badge)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-0D1117?style=for-the-badge)
![Wireshark](https://img.shields.io/badge/Wireshark-0D1117?style=for-the-badge&logo=wireshark&logoColor=1679A7)
![Splunk](https://img.shields.io/badge/Splunk-0D1117?style=for-the-badge&logo=splunk&logoColor=65A637)
![OWASP](https://img.shields.io/badge/OWASP-0D1117?style=for-the-badge)
![CWE](https://img.shields.io/badge/CWE-0D1117?style=for-the-badge)
![ASVS](https://img.shields.io/badge/ASVS-0D1117?style=for-the-badge)

**AI Orchestration**

![Claude Code](https://img.shields.io/badge/Claude_Code-0D1117?style=for-the-badge&logo=anthropic&logoColor=D97757)

---

## Featured Projects

A few of these live in private repos, so those entries carry no link. Every link below was verified public at the time of writing.

### [TITAN-Runner](https://github.com/shreyas-tech7/TITAN-Runner) ([live dashboard](https://shreyas-tech7.github.io/TITAN-Runner/))

A public GitHub Actions cron pipeline that serves as the public arm of a larger AI orchestration project. A scheduled workflow wakes every 15 minutes, pulls tasks from a queue, and routes work across free-tier LLM providers (Groq, Together AI, HuggingFace, OpenRouter, and Gemini), then commits results back to the repo.

`GitHub Actions` `JavaScript` `GitHub Pages` `LLM orchestration`

### [Malicious URL Detector](https://github.com/shreyas-tech7/malicious-url-detector) ([live demo](https://malicious-url-detector-bice.vercel.app))

A cloud ML classifier that flags malicious and phishing URLs from the URL string alone. Its gradient-boosted model scores 0.92 precision and 0.91 recall on a domain-grouped holdout, and a companion endpoint checks file signatures by hash without ever uploading file content.

`Python` `scikit-learn` `FastAPI` `Next.js` `Supabase` `Vercel`

### rOSt (Forge)

A hobby operating system written from scratch in Rust, with an x86_64 kernel covering interrupt handling, a hardware timer, and keyboard input. It carries real hardening (W^X memory protection, guard pages, IDT audits, interrupt rate limiting, and heap hardening) and ships boot-tested launcher bundles through a GitHub Actions CI matrix.

`Rust` `x86_64` `OSDev` `GitHub Actions`

### Aero

A lightweight, secure, cross-platform browser for Windows, macOS, and Linux, built with Rust and Tauri. It centers on privacy with built-in tracker and ad blocking, strict IPC isolation between the frontend and the system, a themeable UI, custom keyboard shortcuts, and an extension system on the roadmap.

`Rust` `Tauri` `TypeScript`

### [SENTINEL](https://github.com/shreyas-tech7/sentinel)

A defensive static-analysis security-audit framework built for AI-generated code. It runs a fixed six-phase workflow against a versioned catalog of 45 vulnerability classes grounded in OWASP and CWE, and ships as a Claude Code skill plus a standalone prompt that runs on any model.

`Python` `OWASP` `CWE` `Static analysis`

### Gauntlet

A dynamic red-team harness built as SENTINEL's offensive counterpart. It exercises target apps like OWASP Juice Shop and DVWA in Docker.

`Docker` `OWASP Juice Shop` `DVWA`

### ReconBrief

A Next.js and Supabase tool that turns raw Nmap and Burp Suite output into structured triage reports. It treats scan data as untrusted input and applies prompt-injection defenses before anything reaches an LLM.

`Next.js` `Supabase` `Nmap` `Burp Suite`

### [PromptVault](https://github.com/shreyas-tech7/promptvault) ([live demo](https://project-v66l5.vercel.app))

A community prompt-discovery platform where users save, organize, and upvote AI prompts. Vote integrity is enforced at the database layer with Postgres row-level security and a one-vote-per-user constraint.

`Next.js` `TypeScript` `Supabase` `Tailwind CSS`

---

## More Shipped Work

| Project | What it is | Links |
|---|---|---|
| [Prept](https://github.com/shreyas-tech7/Prept) | AI interview coach. Speak answers aloud through the Web Speech API and get scored coaching from Gemini. | [Live demo](https://prept-red-nine.vercel.app) |
| [Keystone](https://github.com/shreyas-tech7/keystone) | Calm daily workspace for tasks, notes, habits, and focus, built with Next.js and Supabase. | Repo only |

---

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=shreyas-tech7&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&bg_color=00000000&title_color=1F6FEB&icon_color=1F6FEB" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shreyas-tech7&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=00000000&title_color=1F6FEB" alt="Top languages" />

<br />

<img src="https://streak-stats.demolab.com?user=shreyas-tech7&theme=tokyonight&hide_border=true&background=00000000&ring=1F6FEB&fire=1F6FEB&currStreakLabel=1F6FEB" alt="Contribution streak" />

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F6FEB,100:0D1117&height=120&section=footer" width="100%" alt="Footer banner" />

Thanks for stopping by.

</div>
