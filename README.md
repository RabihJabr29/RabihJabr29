# Hi, I'm Rabih Jabr 👋

<div align="center">

### Senior Full-Stack Software Engineer

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://rabih-jabr-portfolio.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rabih-jabr-888720190/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rabihjabrz2@gmail.com)

📍 Beirut, Lebanon · Remote &nbsp;|&nbsp; 💼 5+ years &nbsp;|&nbsp; 🛠️ Platform Engineer @ Klopotek

</div>

---

## About

I build the product **and** the platform it runs on — React and Next.js on the front, Node.js
and Java/Spring Boot on the back, PostgreSQL underneath, and the deployment pipeline that gets
it all into production.

- 🛠️ I own an internal deployment platform that configures and ships **50+ applications** to
  client tenants across Azure, private cloud, and on-premise environments
- 📡 Built an automated monitoring service for scheduled jobs, wired into Jira — replaced manual
  watching and cut wasted compute
- 🚀 Shipped **two products end-to-end as the only developer**: a full-stack event platform and
  an offline desktop app running a real manufacturing business
- 🤖 I use **AI aggressively** — Claude Code and Copilot are daily drivers, not novelties. They're
  how I went from zero Ansible/Linux to owning production deployment tooling in weeks
- ✍️ I care about documentation that **both people and AI agents** can work from

---

## Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

**Platform & DevOps**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**AI-Assisted Development**

![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=for-the-badge&logo=githubcopilot&logoColor=white)

---

## Featured Projects

### 📚 Documentation RAG Platform *(internal, built at Murex)*

> A Python retrieval system over a large internal wiki, letting engineering teams ask questions
> against their own documentation.

- Scheduled index refresh rather than live indexing — the design decision that keeps queries fast
  and inference cost low
- Pages are scored for relevance and freshness before they reach the index, so stale documentation
  doesn't dilute retrieval
- Runs on locally hosted open-weight models (Llama) as well as hosted APIs, cutting inference cost
  while holding retrieval quality

**Tech:** Python · RAG · Vector Search · Embeddings · Llama

---

### 🎉 [JoyDayz](https://joydayz-dev.kataflow.ch/) — Event Discovery Platform

> Designing and building a full-stack event platform end-to-end, solo.

- Next.js 16 App Router frontend with React 19 Server Components
- Spring Boot REST backend with JPA persistence and JWT authentication
- PostgreSQL schema powering the calendar, bookmarking, messaging, and notification systems
- Infinite-scroll feed with CDN-backed image optimization and public-URL sharing
- Built with heavy Claude Code assistance — the reason one person can cover the whole stack

**Tech:** Next.js 16 · React 19 · TypeScript · Spring Boot · PostgreSQL · JPA · JWT · Tailwind CSS

---

### 🏭 Factory Management System — Offline Desktop App *(freelance, private)*

> A production desktop app I designed, built, and delivered single-handedly for a real
> manufacturing client. Fully offline, single operator, no server to fall back on.

- Customer intake, production yield calculation, invoicing, inventory, and financial reporting
- Relational schema and migration strategy on SQLite, with unit tests covering the money,
  allocation, and stock logic — including regression tests for real production bugs
- Machine-bound license verification (HMAC) and an automated backup pipeline
- Bilingual UI (Arabic RTL / English LTR) with custom HTML-to-PDF invoice printing
- Documentation maintained as an **agent-readable knowledge base** of domain rules and
  invariants, so AI agents make correct changes without re-deriving the business logic

**Tech:** Electron · React 19 · TypeScript · Node.js · SQLite · Vitest · Tailwind CSS

---

<details>
<summary><b>Earlier work</b></summary>

<br>

**[DevFlow](https://github.com/RabihJabr29/Modern-StackOverflow)** — StackOverflow clone with
voting, view tracking, a reputation system, and prototyped AI-generated answer drafts.
`Next.js` `React` `MongoDB` `Tailwind CSS`

**[Educate](https://github.com/RabihJabr29/Educate-Frontend)** — E-learning platform with course
delivery, progress tracking, and an admin dashboard for content and analytics.
`Angular` `Node.js` `Express` `MongoDB` `TypeScript`


</details>

---

## Experience

**Platform Engineer @ Klopotek** — *Jun 2026 – Present*
- Own the deployment platform that configures and ships **50+ applications** across Azure,
  private cloud, and on-premise environments
- Built an automated monitoring and observability service for scheduled jobs, integrated with Jira
- Automate the deployment lifecycle with Ansible, Linux, and Bash across heterogeneous environments

**Senior Software Engineer & Scrum Master @ Murex** — *Jun 2021 – May 2026*
- Built a **documentation RAG platform** over the internal wiki, making locally hosted models a
  viable option and cutting AI inference cost
- Designed and deployed a global performance-metrics feature used by **3 major clients**
- Built internal tooling used daily by **~50 QAs and PMs**
- E2E test suites that cut regression incidents to **under 1%**
- CI/CD pipeline improvements that shortened the development cycle by **30%**
- Mentored and onboarded **9 engineers**

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=RabihJabr29&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=RabihJabr29&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com/?user=RabihJabr29&theme=tokyonight&hide_border=true)

</div>

---

## Let's connect

I'm open to remote roles and interesting problems.

- 📧 [rabihjabrz2@gmail.com](mailto:rabihjabrz2@gmail.com)
- 💼 [linkedin.com/in/rabih-jabr-888720190](https://www.linkedin.com/in/rabih-jabr-888720190/)
- 🌐 [rabih-jabr-portfolio.vercel.app](https://rabih-jabr-portfolio.vercel.app/)
