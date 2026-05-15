<div align="center">

```
╔════════════════════════════════════════════════════════════╗
║  oi, eu sou a Duda — desenvolvedora full-stack em formação ║
╚════════════════════════════════════════════════════════════╝
```

☕ movida a café &nbsp;·&nbsp; 🎓 Estudante de Ciência da Computação &nbsp;·&nbsp; 🎬 cinema, artes & música &nbsp;·&nbsp; 🌱 sempre construindo algo

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maria-eduarda-brito-a18064358/)
[![GitHub](https://img.shields.io/badge/GitHub-171515?style=flat-square&logo=github&logoColor=white)](https://github.com/maria-brito15)
[![Visualizações](https://komarev.com/ghpvc/?username=maria-brito15&color=6e40c9&style=flat-square&label=visualizações)](https://github.com/maria-brito15)

🌐 **Outras versões:** [English](README.md)

</div>

---

## sobre mim

Sou estudante de Ciência da Computação apaixonada por **desenvolvimento full-stack**, com foco em construir sistemas reais e prontos para produção. Gosto de toda a jornada — desde o design de modelos de dados e APIs REST até a criação de interfaces limpas e responsivas.

Meu trabalho é guiado por alguns princípios: **escrever código que escala, documentar o que importa e nunca parar de aprender.** Atualmente estou aprofundando minha expertise em Java/Spring Boot, TypeScript e padrões de design para sistemas distribuídos.

---

## stack tecnológica

**Linguagens**

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

**Bancos de Dados & Cache**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**DevOps & Ferramentas**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)

---

## projetos em destaque

### 🍽️ TableCheck — Plataforma de Reservas para Restaurantes `[em desenvolvimento]`

> **SaaS · Spring Boot · Multi-tenant · Stripe · PostgreSQL · Redis**

Uma **plataforma SaaS multi-tenant** para gestão de reservas em restaurantes, construída com arquitetura de nível produtivo. Proprietários gerenciam toda a operação — mesas, disponibilidade, períodos de bloqueio, avaliações e analytics — enquanto clientes fazem reservas, remarcam e recebem lembretes automaticamente.

**Destaques:**
- Arquitetura multi-tenant com isolamento completo de dados por restaurante
- Autenticação JWT com rotação de refresh token e blacklist gerenciada no **Redis**
- Rate limiting por usuário/IP via **Bucket4j + Redis**
- Lembretes por e-mail automatizados via **jobs agendados** (Quartz)
- Integração com webhooks do Stripe para cobrança por assinatura
- Dashboard de analytics com métricas de ocupação e receita
- Exportação para CSV; trilha completa de auditoria
- Suite de testes de integração com **Testcontainers** + testes unitários com JUnit 5
- Documentação OpenAPI/Swagger; logs estruturados via **Logstash + Logback**
- Totalmente containerizado com Docker Compose

`Java 21` `Spring Boot 3.5` `PostgreSQL` `Redis` `Flyway` `Stripe` `Docker` `GitHub Actions`

---

### 🌿 [EcoShop](https://github.com/maria-brito15/ecoshop-nextjs) — E-Commerce de Produtos Sustentáveis

> **Next.js 15 · IA · TypeScript · Prisma · Redis · Azure · Gemini**

Plataforma de e-commerce full-stack para produtos sustentáveis com um **scanner de materiais por IA**. Aponte a câmera para qualquer objeto — o Azure Custom Vision identifica o material, e o Google Gemini retorna uma análise ambiental completa (tempo de decomposição, dicas de reciclagem, orientações de descarte).

**Destaques:**
- Estratégia de cache em duas camadas: **Redis** no servidor + `Map` em memória com stale-while-revalidate no cliente
- Autenticação JWT stateless com `jose` + `bcryptjs`, centralizada via Middleware do Next.js
- Controle de acesso por roles: `ADMIN`, `CLIENTE`, `MARCA`
- Painel administrativo com CRUD completo de produtos, categorias, marcas, certificados e usuários
- Fallback de IA: degradação graciosa quando Azure ou Gemini estão indisponíveis
- Chat de sustentabilidade alimentado pelo Gemini 2.0 Flash
- Build Docker multi-stage; pipeline de CI/CD publicando no **GitHub Container Registry**

`Next.js 15` `TypeScript` `PostgreSQL` `Prisma` `Redis` `Azure Custom Vision` `Google Gemini` `Tailwind CSS` `Docker`

---

### 🔗 [ShortURL](https://github.com/maria-brito15/shorturl-express) — Encurtador de URLs com Analytics de Cliques

> **Node.js · TypeScript · MongoDB · Redis · Docker**

Um encurtador de URLs pronto para produção com **camada de cache Redis** para redirecionamentos em sub-milissegundos e rastreamento atômico de cliques. Arquitetura em camadas com validação via **Zod** e CI pelo GitHub Actions.

**Destaques:**
- Cache Redis com TTL de 10 minutos — cache-miss busca no MongoDB e repopula automaticamente
- Contador de cliques atômico incrementado de forma assíncrona a cada redirecionamento
- Middleware de validação Zod rejeita URLs malformadas antes de chegar ao controller
- API REST + frontend estático servidos pelo mesmo servidor Express
- Docker Compose completo: um único comando sobe a API, o MongoDB e o Redis

`Node.js 20` `TypeScript 5` `Express` `MongoDB` `Redis` `Zod` `Docker` `GitHub Actions`

---

### 📚 BECAS — Plataforma de Sala de Estudos `[aguardando lançamento · refatorando para Spring Boot]`

> **Java · Spring Boot · PostgreSQL · JWT · PDFBox**

Plataforma colaborativa que conecta estudantes a materiais de estudo de qualidade. Atualmente sendo refatorada para **Spring Boot** com uma arquitetura mais limpa e escalável.

**Funcionalidades planejadas:** integração com webhooks da Hotmart, busca avançada, processamento de PDF com Apache PDFBox, autenticação JWT e notificações por e-mail.

`Java` `Spring Boot` `PostgreSQL` `JWT` `Apache PDFBox`

---

## estatísticas do github

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=maria-brito15&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6e40c9&icon_color=6e40c9&text_color=c9d1d9)
&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=maria-brito15&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6e40c9&text_color=c9d1d9)

</div>

---

<div align="center">

*"Fale menos, programe mais."* - Hamilton

</div>
