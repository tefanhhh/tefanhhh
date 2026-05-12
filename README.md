<h1 align="center">Hi there, I'm Tefan 👋</h1>
<h3 align="center">Full-Stack Software Engineer · AI & Computer Vision Enthusiast</h3>

<p align="center">
  <a href="https://linkedin.com/in/tefanhaetami" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

<br />

I'm a developer with over **8 years of experience** building scalable, high-performance web applications. I specialize in bridging the gap between robust back-end systems and polished front-end experiences, with a growing focus on integrating artificial intelligence into practical, real-world tools.

---

## 🚀 What I'm up to

- 💻 **Currently building:** Advanced full-stack CMS platforms utilizing `pnpm` workspaces, **NestJS** for schema-first GraphQL APIs, and **Next.js** for performant client interfaces
- 🧠 **Exploring:** AI-driven applications, specifically utilizing device cameras and computer vision for environmental monitoring and analysis
- ⚙️ **My go-to stack:** TypeScript, Node.js, NestJS, Next.js, Vue/Nuxt, GraphQL, PostgreSQL, Redis
- 💡 **Always looking to:** Build tools that solve tangible problems and explore new entrepreneurial ventures

---

## 🛠️ Tech Stack & Tools

### Languages & Runtimes
<p>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
</p>

### Frameworks & Libraries
<p>
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Nuxt-002E3B?style=for-the-badge&logo=nuxtdotjs&logoColor=00DC82" alt="Nuxt" />
  <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D" alt="Vue.js" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
</p>

### API & Data
<p>
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white" alt="GraphQL" />
  <img src="https://img.shields.io/badge/Apollo-311C87?style=for-the-badge&logo=apollographql&logoColor=white" alt="Apollo" />
  <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=react-query&logoColor=white" alt="TanStack Query" />
  <img src="https://img.shields.io/badge/Zod-3068B7?style=for-the-badge&logo=zod&logoColor=white" alt="Zod" />
  <img src="https://img.shields.io/badge/REST-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="REST" />
</p>

### Databases & Caching
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/TypeORM-FE0902?style=for-the-badge&logo=typeorm&logoColor=white" alt="TypeORM" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
</p>

### Styling & UI
<p>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/shadcn/ui-000000?style=for-the-badge&logo=shadcnui&logoColor=white" alt="shadcn/ui" />
  <img src="https://img.shields.io/badge/Radix_UI-161618?style=for-the-badge&logo=radix-ui&logoColor=white" alt="Radix UI" />
</p>

### DevOps, Tooling & Auth
<p>
  <img src="https://img.shields.io/badge/pnpm-F69220?style=for-the-badge&logo=pnpm&logoColor=white" alt="pnpm" />
  <img src="https://img.shields.io/badge/Turborepo-EF4444?style=for-the-badge&logo=turborepo&logoColor=white" alt="Turborepo" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white" alt="JWT" />
  <img src="https://img.shields.io/badge/Passport-34E27A?style=for-the-badge&logo=passport&logoColor=white" alt="Passport" />
  <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" alt="ESLint" />
  <img src="https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=black" alt="Prettier" />
</p>

---

## 🏗️ How I Architect Things

When I build full-stack systems, a few principles are non-negotiable:

- **Monorepo-first** — `pnpm` workspaces + Turborepo for shared configs, UI components, and codegen pipelines across apps
- **Schema-first GraphQL** — SDL is the single source of truth; types are always generated, never handwritten
- **Static by default** — Next.js App Router with SSG + `use cache`; dynamic data fetched client-side via TanStack Query
- **Security by design** — JWT access/refresh token pattern, global guards, bcrypt ≥10 rounds, Redis-only caching in production
- **Migration-driven DB** — TypeORM migrations only; never `synchronize: true` outside tests; UUID PKs and soft deletes everywhere
- **Type-safe end-to-end** — strict TypeScript, Zod validation on every boundary, codegen from GraphQL schema to client hooks

---

## 🧪 Testing & Quality

- Co-located unit tests (`.spec.ts`) for all services and resolvers
- E2E tests with Supertest against a real DB
- `pnpm check` — runs `typecheck` + `lint` + `format:check` + workspace boundary checks before every push
- Conventional Commits enforced via `commitlint` + `husky`

---

## 📫 Connect with me

<p>
  <a href="https://linkedin.com/in/tefanhaetami" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>
