<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║  hey, I'm Duda — software architecture student · full-stack dev  ║
╚══════════════════════════════════════════════════════════════════╝
```

☕ fueled by coffee &nbsp;·&nbsp; 🎓 CS @ PUC Minas &nbsp;·&nbsp; 🎬 cinema, arts & music &nbsp;·&nbsp; 🌱 always building something

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maria-eduarda-brito-a18064358/)
[![GitHub](https://img.shields.io/badge/GitHub-171515?style=flat-square&logo=github&logoColor=white)](https://github.com/maria-brito15)
[![Profile Views](https://komarev.com/ghpvc/?username=maria-brito15&color=6e40c9&style=flat-square&label=profile+views)](https://github.com/maria-brito15)

🌐 **Other versions:** [Português](README_pt.md)

</div>

---

## about me

I'm a Computer Science student at **PUC Minas**, taking my first steps on a journey that goes beyond writing code: I want to learn how to **design software with intention**. I'm still far from being an architect — but that's exactly the destination that drives me.

I build full-stack systems with a back-end focus — Node.js, Java, and now learning Golang — while diving into the fundamentals of software architecture. My work is guided by a few principles: **write code that scales, document what matters, and never stop learning.**

📍 Belo Horizonte, MG &nbsp;·&nbsp; Portuguese (native) · English (fluent) · French (basic)

---

## tech stack

**Backend**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Databases, Cache & Job Queues**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-FF4438?style=flat-square&logo=bullmq&logoColor=white)

**Testing**

![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-C5D928?style=flat-square&logo=java&logoColor=black)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

---

## featured projects

### 🌿 [EcoShop](https://github.com/maria-brito15/ecoshop-nextjs) — Sustainable E-Commerce Platform `🏆 PUC Minas Finalist`

A full-stack e-commerce platform for eco-friendly products with an **AI-powered material scanner**. Born as a finalist academic project and completely rewritten to consolidate learning with a modern stack.

**v1 · Original (2025) — Java + Spark Framework**
> Academic version selected among the semester's best projects. Classic MVC architecture with Controller → Service → DAO layers, direct PostgreSQL via JDBC, BCrypt session auth, JUnit 5 + Mockito tests, Docker deploy on Render.

`Java` `Spark Framework` `PostgreSQL` `JDBC` `BCrypt` `JUnit 5` `Mockito` `Docker` `Azure Vision` `Gemini API`

**v2 · Refactor (2026) — Next.js 15 + TypeScript**
> Full rewrite with a modern stack. App Router, two-layer cache (Redis + Map stale-while-revalidate), typed Prisma ORM, stateless JWT with centralized middleware and Zod validation on every route.

- Two-layer cache: **Redis** (server) + `Map` stale-while-revalidate (client)
- AI scanner: Azure Custom Vision + Gemini 2.0 Flash
- Role-based access control: `ADMIN`, `CLIENTE`, `MARCA`
- AI fallback: graceful degradation if Azure or Gemini are unavailable
- CI/CD with GitHub Actions + GitHub Container Registry

`Next.js 15` `TypeScript 5` `Prisma 7` `PostgreSQL` `Redis 4` `JWT / jose` `Zod 3` `React 19` `Tailwind CSS 4` `Azure Custom Vision` `Gemini 2.0 Flash` `Docker` `GitHub Actions`

---

### 🔗 [ShortURL](https://github.com/maria-brito15/shorturl-express) — URL Shortener with Click Analytics

A production-ready URL shortener with a **Redis caching layer** for sub-millisecond redirects and atomic click tracking.

**Highlights:**
- Redis cache with 10-minute TTL — cache-miss falls back to MongoDB and repopulates automatically
- Atomic click counter incremented asynchronously on every redirect
- Zod validation middleware rejects malformed URLs before reaching the controller
- REST API + static frontend served from the same Express server
- Full Docker Compose setup: one command spins up the API, MongoDB and Redis

`Node.js 20` `TypeScript 5` `Express` `MongoDB` `Redis` `Zod` `Docker` `GitHub Actions`

---

## 🔌 [WhatsApp Dispatcher](https://github.com/maria-brito15/whatsapp-dispatcher) — Mass Messaging System `in development`

A high‑performance message dispatcher for WhatsApp campaigns and flows. Built from scratch with **Domain‑Driven Design**, **Clean Architecture**, and a hexagonal‑inspired structure to keep business logic independent of infrastructure.

**What makes it different:**
- **Scheduler + Workers:** BullMQ handles millions of messages with retries, backoff and concurrency control
- **Two‑stage reconciliation:** recovers stalled jobs and re‑activates failed flows automatically
- **Cache layer:** Redis for fast status counts and reduced database load
- **Full audit trail:** every sent, failed, paused or completed action is logged
- **Soft deletes & versioning:** safe data retention for production environments

`Node.js 20` `TypeScript 5` `Prisma 7` `PostgreSQL` `Redis 4` `BullMQ` `Docker` `Zod` `JWT` `DDD` `Clean Architecture`

---

## extracurricular

- 🏆 **2× Finalist — Best Projects at PUC Minas** · EcoShop and Planoriza (2025–2026)
- ⚡ **SBC Marathon** · ICPC Brasil participation (2025)
- 👩‍🏫 **CS Speaker** · Programming workshop instructor at PUC Minas (2025)
- 📊 **Data Analysis with Python** · Alura Immersion — pandas, matplotlib (2026)
- 🎨 **DevArt — UI/UX & Animations** · Figma, responsive design and animations (2026)

---

## github stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=maria-brito15&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6e40c9&icon_color=6e40c9&text_color=c9d1d9)
&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=maria-brito15&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6e40c9&text_color=c9d1d9)

</div>

---

<div align="center">

*"Talk less, code more."*

</div>
