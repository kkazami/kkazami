[README.md](https://github.com/user-attachments/files/31409369/README.md)
<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Neil%20Kirby%20%E2%80%94%20kazami&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=42&desc=IT%20Student%20%E2%80%A2%20Full-Stack%20Developer%20%E2%80%A2%20Philippines&descAlignY=62&descSize=16&descColor=c4b5fd)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=A78BFA&center=true&vCenter=true&width=620&lines=Building+cross-platform+systems+from+scratch;Web+%E2%86%92+Mobile+%E2%86%92+Desktop%2C+one+monorepo+at+a+time;Currently+architecting+LMS-CDM+%F0%9F%8E%93;Always+willing+to+learn.+Always+building.)](https://git.io/typing-svg)

</div>

---

## About me

IT student building full-stack applications and real-world institutional systems. I focus on **Web-Based Systems** with a cross-platform approach — shipping the same product across web, mobile, and desktop from a single codebase.

Currently architecting **LMS-CDM**, a production-scale Learning Management System designed for CDM colleges — built as a Turborepo monorepo with Next.js, React Native, Electron, PostgreSQL, and Docker.

- 📍 Philippines &nbsp;|&nbsp; 🕐 UTC+8 &nbsp;|&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/neil-kirby-amigo-4a7b923b5)
- 🌐 Focused on scalable web systems with real users in mind
- 📱 Expanding into mobile with React Native + Expo (already shipping it in LMS-CDM)
- 🔭 Next goal: production mobile deployment

---

## What I primarily build with

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=prisma&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

<details>
<summary><b>Also experienced with</b></summary>
<br>

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-191970?style=for-the-badge&logo=electron&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=for-the-badge&logo=turborepo&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=for-the-badge&logo=pnpm&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</details>

---

## Featured projects

### 🎓 LMS-CDM — Learning Management System
> *Cross-platform monorepo LMS for CDM colleges (ICS · IBE · ITE)*

A production-scale Learning Management System architected as a **Turborepo monorepo**, delivering the same product across three platforms from a single shared codebase. Designed to serve up to **5,000 users** across **3 colleges** with **8 supported subject categories** and **240 total learning levels**.

**What I built:**
- Role-based access control (student, instructor, admin) with full auth flow
- Course enrollment, instructor approval workflow, and progress tracking
- Cross-platform deployment: web (Next.js), mobile (Expo React Native), desktop (Electron)
- Shared packages for types, config, utils, and API client across all platforms
- Dockerized local dev environment with PostgreSQL and Prisma ORM
- Deployed to Vercel with Next.js API Routes as the backend layer

**Architecture:**

```
LMS-CDM/
├── apps/
│   ├── web/        → Next.js (TypeScript + Tailwind + Prisma)
│   ├── mobile/     → Expo React Native
│   └── desktop/    → Electron
├── packages/       → Shared config, types, utils, API client
├── prisma/         → PostgreSQL schema
└── docker/         → Containerized dev environment
```

**Stack:** TypeScript · Next.js · React Native · Electron · PostgreSQL · Prisma ORM · Docker · Turborepo · pnpm · Vercel

[![Live Demo](https://img.shields.io/badge/Live%20Demo-lms--cdm.vercel.app-7c3aed?style=for-the-badge&logo=vercel&logoColor=white)](https://lms-cdm.vercel.app)
[![View Repo](https://img.shields.io/badge/View%20Repo-kkazami%2FLMS--CDM-24292e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kkazami/LMS-CDM)

---

### 🐾 WindowsForm Pet Adoption System
> *Desktop GUI application for managing pet adoption workflows*

A Windows Forms desktop application built in **C# / .NET** with a connected database backend. Supports pet registration, adoption request management, and status tracking.

**What I built:** Full CRUD for pet records · Adoption workflow with status states · Windows Forms UI with data-bound controls · Database integration

[![View Repo](https://img.shields.io/badge/View%20Repo-GitHub-24292e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kkazami/WindowsForm----Pet-Adoption-System-)

---

### 🧭 Digital Compass
> *Web-based directional tool built with vanilla HTML/CSS/JS*

A browser-based compass application using the Web API's DeviceOrientationEvent — no libraries, no frameworks. An exercise in working directly with browser APIs and real-time sensor data.

[![View Repo](https://img.shields.io/badge/View%20Repo-GitHub-24292e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kkazami/Digital-Compass)

---

## GitHub stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=kkazami&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0d1117&count_private=true&include_all_commits=true" height="165"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kkazami&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0d1117&langs_count=8" height="165"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=kkazami&theme=midnight-purple&hide_border=true&background=0d1117&ring=7c3aed&fire=a78bfa&currStreakLabel=a78bfa)](https://git.io/streak-stats)

</div>

---

## Currently building toward

- [ ] Production mobile release of LMS-CDM on Expo/EAS
- [ ] Notification system (push + in-app) for the LMS
- [ ] Deeper TypeScript patterns — generics, utility types, conditional types
- [ ] Learning more about system design for scale

---

<div align="center">

*"Always willing to learn and currently improving my tech stack."*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/neil-kirby-amigo-4a7b923b5)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-kkazami-24292e?style=flat-square&logo=github&logoColor=white)](https://github.com/kkazami)

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=100&section=footer)

</div>
