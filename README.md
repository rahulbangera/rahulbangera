<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Rahul%20N%20Bangera&fontSize=56&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Backend%20%26%20Infrastructure%20Engineer&descSize=20&descAlignY=60" alt="Rahul N Bangera" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=38BDF8&center=true&vCenter=true&width=720&lines=I+build+systems+that+hold+up+in+production.;Lead+engineer+behind+The+Warden+%E2%80%94+2%2C000%2B+students%2C+67+tables.;Shipped+a+48-table+commerce+platform+solo+in+4+weeks.;Tech+lead+for+a+3%2C000-registration+hackathon%2C+zero+downtime.)](https://github.com/rahulbangera)

<p>
  <a href="https://linkedin.com/in/rahul-n-bangera"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:rahulnbangera2005@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://thewarden.inspirantech.in"><img src="https://img.shields.io/badge/The%20Warden-0f172a?style=for-the-badge&logo=googlechrome&logoColor=white" alt="The Warden" /></a>
  <img src="https://img.shields.io/badge/Karnataka%2C%20India-1f2937?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
</p>

<img src="https://komarev.com/ghpvc/?username=rahulbangera&label=Profile%20views&color=0e75b6&style=flat-square" alt="Profile views" />

</div>

---

## 👋 About

B.Tech CSE student at **NMAMIT** (class of 2027, **CGPA 8.89**) who ships real software for real users. I work across the backend and infrastructure stack: API design, relational schemas, queues, locking and concurrency, CI/CD, and the deployment pipelines that keep it all running.

- 🏨 **Software Engineer Intern** at Inspirante Technologies, wrote ~90% of a platform that runs hostel operations for 2,000+ students
- ⚡ **Solo-shipped** a full D2C commerce platform on Cloudflare's edge in four weeks
- 🏆 **Tech lead** for a national 36-hour hackathon: 3,000 registrations, zero downtime on a single VPS
- 🧑‍🏫 **Technical Manager** of Finite Loop Club: choose the stack, review every PR, onboard new members

---

## 📈 By the numbers

<div align="center">

| 🧱 | 🎓 | 🚀 | 👥 |
|:--:|:--:|:--:|:--:|
| **67** tables in The Warden's Postgres schema | **2,000+** students served, ~400 DAU | **3,000** hackathon registrations, 0 downtime | **~3,300** accounts on the club platform |

</div>

---

## 🛠️ What I'm building

### 🏨 The Warden — hostel operations platform
[`thewarden.inspirantech.in`](https://thewarden.inspirantech.in) · *Lead engineer, 3-person team · Aug 2025 – Present*

![Hono](https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-DC382D?style=flat-square)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

Replaced paper-driven attendance, leave, maintenance and room allocation across **4 hostels, 11 blocks and 20 staff**. I wrote roughly 90% of it: the API, the schema, and all **7 client apps**, including native apps on the Play Store and App Store.

### 👖 denimcode — D2C commerce platform
[`thedenimcode.com`](https://thedenimcode.com) · *Sole author · Jul – Aug 2026*

![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Durable Objects](https://img.shields.io/badge/Durable%20Objects-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Hyperdrive](https://img.shields.io/badge/Hyperdrive-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![R2](https://img.shields.io/badge/R2-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

Storefront, admin dashboard and API over a **48-table schema**, designed and shipped alone in **four weeks**, with separate staging and production. Order events go through a **transactional outbox**, with publishers claiming batches via `SELECT ... FOR UPDATE SKIP LOCKED`. Postgres runs through Hyperdrive and media through R2, keeping the whole stack on the edge.

### 🏁 HackFest 2026 — national hackathon platform
[`hackfest.dev`](https://hackfest.dev) · *Tech lead · Dec 2025 – Apr 2026*

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

Led an **8-person team** through a 36-hour national hackathon: **3,000 registrations, 700 teams, 550 submissions**, zero downtime on a single 4 vCPU VPS. Built registration, two-round online evaluation for 30 judges, mentoring, and the multi-panel final, plus **judge-normalised scoring** so finalists could be ranked fairly across panels with different scoring tendencies.

### ♾️ Finite Loop Club platform — membership & events
[`finiteloop.club`](https://finiteloop.club) · *Lead maintainer · Jun 2025 – Present*

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Razorpay](https://img.shields.io/badge/Razorpay-0C2451?style=flat-square&logo=razorpay&logoColor=white)

Top contributor with ~60% of commits, ~3,300 accounts. Migrated the live app from **Prisma to Drizzle in a single release with no downtime**, and integrated Razorpay checkout and its payment webhook.

---

## 💻 Tech stack

<div align="center">

| | |
|:--|:--|
| **Languages** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white) |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![Hono](https://img.shields.io/badge/Hono-E36002?style=for-the-badge&logo=hono&logoColor=white) ![tRPC](https://img.shields.io/badge/tRPC-2596BE?style=for-the-badge&logo=trpc&logoColor=white) ![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white) ![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) |
| **Infra & DevOps** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white) ![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Dokploy](https://img.shields.io/badge/Dokploy-000000?style=for-the-badge) |
| **Frontend & Mobile** | ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![React Native](https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white) |
| **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=claude&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) |

</div>

### 🧠 Things I reach for

`advisory locks` · `transactional outbox` · `SKIP LOCKED queues` · `idempotent webhooks` · `debounced recomputation` · `RBAC` · `zero-downtime ORM migrations` · `CI-gated deploys` · `edge-first architecture`

---

## 🏆 Recognition

| Award | Event |
|:--|:--|
| 🥉 **Second Runner-up** | CodeKudla 2026 |
| 🥈 **Runner-up** | Innovex National Hackathon |
| 🥇 **Winner** | HackExpo S3 |

## 🧑‍🤝‍🧑 Leadership

**Finite Loop Club, NMAMIT** · *Jun 2024 – Present*: promoted four times in two years.

```
Member ─► Technical Head ─► Vice President (Tech) ─► Technical Manager
          Aug 2025          Jan 2026                 Aug 2026
```

---

## 📊 GitHub stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=rahulbangera&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rahulbangera&theme=tokyonight&hide_border=true&layout=compact&langs_count=8" alt="Top languages" />

<img src="https://streak-stats.demolab.com?user=rahulbangera&theme=tokyonight&hide_border=true" alt="GitHub streak" />

<img src="https://github-profile-trophy.vercel.app/?username=rahulbangera&theme=tokyonight&no-frame=true&no-bg=true&margin-w=12&row=1&column=7" alt="Trophies" />

</div>

---

<div align="center">

### 📬 Let's build something

I'm open to backend and infrastructure roles, internships, and interesting problems.

[![Email me](https://img.shields.io/badge/Say%20hello-rahulnbangera2005%40gmail.com-38BDF8?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rahulnbangera2005@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" alt="" />

</div>
