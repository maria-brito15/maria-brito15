<div align="center">

```
╔══════════════════════════════════════════════════════╗
║  hey, I'm Duda — full-stack developer in the making  ║
╚══════════════════════════════════════════════════════╝
```

☕ fueled by coffee &nbsp;·&nbsp; 🎓 CS Student &nbsp;·&nbsp; 🎬 cinema, arts & music &nbsp;·&nbsp; 🌱 always building something

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maria-eduarda-brito-a18064358/)
[![GitHub](https://img.shields.io/badge/GitHub-171515?style=flat-square&logo=github&logoColor=white)](https://github.com/maria-brito15)
[![Profile Views](https://komarev.com/ghpvc/?username=maria-brito15&color=6e40c9&style=flat-square&label=profile+views)](https://github.com/maria-brito15)

🌐 **Other versions:** [Português](README_pt.md)

</div>

---

## about me

I'm a Computer Science student passionate about **full-stack development**, with a strong focus on building real, production-ready systems. I enjoy the full journey — from designing data models and REST APIs to crafting clean, responsive UIs.

My work is guided by a few principles: **write code that scales, document what matters, and never stop learning.** Right now I'm deepening my expertise in Java/Spring Boot, TypeScript, and distributed system design patterns.

---

## tech stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

**Databases & Cache**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)

---

## featured projects

### 🍽️ TableCheck — Restaurant Reservation Platform `[in development]`

> **SaaS · Spring Boot · Multi-tenant · Stripe · PostgreSQL · Redis**

A **multi-tenant SaaS platform** for restaurant reservation management, built with production-grade architecture. Owners manage their entire operation — tables, availability, blackout periods, reviews and analytics — while guests book, reschedule and get reminded automatically.

**Highlights:**
- Multi-tenant architecture with full data isolation per restaurant
- JWT auth with refresh token rotation and a Redis-backed blacklist
- Rate limiting per user/IP via **Bucket4j + Redis**
- Automated email reminders via **scheduled jobs** (Quartz)
- Stripe webhook integration for subscription billing
- Analytics dashboard with occupancy and revenue metrics
- Exports to CSV; full audit log trail
- **Testcontainers**-powered integration test suite + unit tests with JUnit 5
- OpenAPI/Swagger docs; structured logs via **Logstash + Logback**
- Fully containerized with Docker Compose

`Java 21` `Spring Boot 3.5` `PostgreSQL` `Redis` `Flyway` `Stripe` `Docker` `GitHub Actions`

---

### 🌿 [EcoShop](https://github.com/maria-brito15/ecoshop-nextjs) — Sustainable E-Commerce Platform

> **Next.js 15 · AI · TypeScript · Prisma · Redis · Azure · Gemini**

A full-stack e-commerce platform for eco-friendly products with an **AI-powered material scanner**. Point your camera at any object — Azure Custom Vision identifies the material, then Google Gemini returns a complete environmental analysis (decomposition time, recycling tips, disposal guidance).

**Highlights:**
- Two-layer cache strategy: **Redis** on the server + in-memory `Map` with stale-while-revalidate on the client
- JWT stateless auth with `jose` + `bcryptjs`, centralized via Next.js Middleware
- Role-based access control: `ADMIN`, `CLIENTE`, `MARCA`
- Admin dashboard for full CRUD on products, categories, brands, certificates and users
- AI fallback: graceful degradation if Azure or Gemini are unavailable
- Sustainability chat powered by Gemini 2.0 Flash
- Multi-stage Docker build; CI/CD pipeline publishing to **GitHub Container Registry**

`Next.js 15` `TypeScript` `PostgreSQL` `Prisma` `Redis` `Azure Custom Vision` `Google Gemini` `Tailwind CSS` `Docker`

---

### 🔗 [ShortURL](https://github.com/maria-brito15/shorturl-express) — URL Shortener with Click Analytics

> **Node.js · TypeScript · MongoDB · Redis · Docker**

A production-ready URL shortener with a **Redis caching layer** for sub-millisecond redirects and atomic click tracking. Clean layered architecture with input validation via **Zod** and CI via GitHub Actions.

**Highlights:**
- Redis cache with 10-minute TTL — cache-miss falls back to MongoDB and repopulates automatically
- Atomic click counter incremented asynchronously on every redirect
- Zod validation middleware rejects malformed URLs before reaching the controller
- REST API + static frontend served from the same Express server
- Full Docker Compose setup: one command spins up the API, MongoDB and Redis

`Node.js 20` `TypeScript 5` `Express` `MongoDB` `Redis` `Zod` `Docker` `GitHub Actions`

---

### 📚 BECAS — Study Room Platform `[awaiting launch · Spring Boot refactor in progress]`

> **Java · Spring Boot · PostgreSQL · JWT · PDFBox**

A collaborative platform connecting students with quality study materials. Currently being refactored to **Spring Boot** with a cleaner, more scalable architecture.

**Planned features:** Hotmart webhook integration, advanced search, PDF processing with Apache PDFBox, JWT authentication and email notifications.

`Java` `Spring Boot` `PostgreSQL` `JWT` `Apache PDFBox`

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
