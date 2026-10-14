<h1 align="center">Hi there, I'm Gilang Fauzan 👋</h1>
<p align="center"><b>Tech Developer</b> at <a href="https://studiaacademy.com">Studia Academy</a> · Remote from Jakarta, Indonesia</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mohammad-gilang-fauzan-6975411a6/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://portofolio-gilang-lime.vercel.app"><img src="https://img.shields.io/badge/Portfolio-E56047?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <img src="https://komarev.com/ghpvc/?username=glgmainstream12&style=for-the-badge&color=blue" alt="Profile views"/>
</p>

---

I'm a Tech Developer at Studia Academy, an online tutoring company based in Hong Kong. I work remotely from Jakarta. I build the software the company runs on: the Angular web app students and tutors use, the NestJS API behind it, the admin dashboard staff work in, and Studia AI, an LLM agent for tutors and students. I also write SwiftUI apps.

Play a small game I built into my [portfolio](https://portofolio-gilang-lime.vercel.app): find a hidden Bluetooth beacon from noisy signal readings. · CV: [Software Engineer](https://portofolio-gilang-lime.vercel.app/Gilang-Fauzan-CV.pdf) · [AI Engineer](https://portofolio-gilang-lime.vercel.app/Gilang-Fauzan-CV-AI.pdf)

### 🛠️ When I code, I rely on

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude_API-191919?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?style=flat-square&logo=swift&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![TypeORM](https://img.shields.io/badge/TypeORM-FE0803?style=flat-square&logo=typeorm&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### 🤝 Open-source contributions

- **[PangMo5/SwiftyCrow](https://github.com/PangMo5/SwiftyCrow)**: open-source macOS screen translator. My merged fix (PR #11) lays out vertical Chinese and Japanese text correctly when translating into other languages.
  - ✅ Merged: [fix(overlay): lay vertical CJK blocks out horizontally for non-CJK targets (#11)](https://github.com/PangMo5/SwiftyCrow/pull/11)

### 💼 What I build at Studia Academy (private repos)

| Area | What |
|---|---|
| Classes | Booking, scheduling, tutor availability, and an in-house browser classroom |
| Learning | A question bank, homework that tutors assign, and a shared materials library |
| Money | Invoices, Stripe payments, a make-up class credit ledger, and tutor payroll |
| Shop | The online shop and its Google Merchant Center catalog sync |
| Meta platforms | Server-side Conversions API, Meta Pixel and a WhatsApp Cloud API calling module, alongside GA4 funnel tracking |
| AI | Studia AI, an LLM agent for tutors and students, plus an MCP server and a RAG pipeline (see Applied AI below) |
| Sign-in | Password, one-time email code, and Google sign-in, plus tutor approval |
| Keeping it running | Staging CI/CD on GitHub Actions and a security audit |

### 🤖 Applied AI (private repos)

| Year | What | Stack |
|---|---|---|
| 2026 | **Studia AI agent** (on staging): an LLM agent for tutors and a hint-only study coach for students that never sees the answer key. Every tool call goes through the company API with the user's own token, so existing permissions decide what the model can see. Write actions (homework, file sharing, leave requests) are proposals a person confirms. Prompt caching, conversation history and a cost dashboard. | TypeScript · NestJS · Claude / OpenAI / DeepSeek · SSE |
| 2026 | **MCP server**: gives AI assistants scoped, API-key access to courses, users, credits, practice questions and WhatsApp chats; also used to author practice questions. | TypeScript · Model Context Protocol |
| 2026 | **API-key router**: a reverse proxy that hides Anthropic and OpenAI keys behind per-client keys, with streaming and upstream fallback. | Go · AWS |
| 2025 | **RAG pipeline**: turns exam papers into a searchable dataset with OCR, chunking, embeddings and similarity search. | TypeScript · LangChain · OpenAI embeddings |
| 2025 | **Past-paper pipeline**: converts IB past-paper PDFs into a structured, topic-classified question database, with S3, Google Drive and Sheets sync. | Python · FastAPI · SQLAlchemy · Claude Vision |

### 🧭 Experience

**Tech Developer** · Studia Academy Ltd (Hong Kong, remote) · *2025 – present*
- Full-stack development across the platform: the Angular web app, the NestJS API and the admin dashboard.
- 326 pull requests across 8 company repositories, 306 merged; top committer on the web app and the API.
- Built Studia AI, an LLM agent for tutors and students: tool calling through the company API with each user's own permissions, SSE streaming, and Claude, OpenAI and DeepSeek behind one provider layer.
- Built an MCP server that gives AI assistants scoped access to platform data: courses, users, credits, practice questions and WhatsApp chats.
- Built a Go API-key router that hides Anthropic and OpenAI keys behind per-client keys, with streaming and upstream fallback.
- Built the online shop and its Google Merchant Center catalog sync.
- Integrating Meta's platforms: server-side Conversions API, Meta Pixel and a WhatsApp Cloud API calling module, alongside GA4 funnel tracking.
- Help onboard and train interns, and keep proposals, runbooks and a team knowledge base up to date.

**Operation Analyst** · Studia Academy Ltd (Hong Kong, remote) · *Jun 2023 – 2025*
- Coordinated a 4-person team across UI/UX, backend (NestJS) and frontend (Angular).
- Automated admin work: about 240 hours saved per person each year, over 1,000 hours in total.
- Shipped the Back-to-School booking page (Next.js + Express) as a low-cost static site; bookings became three times faster.
- Looked after AWS and handled incidents, avoiding about US$2,000 in costs.

**Education**: Full-Stack Web Development (certification), Purwadhika Digital Technology School, Jakarta · *Aug 2024 – Jan 2025* · BSc, Animal Science, IPB University (Institut Pertanian Bogor) · *2018 – 2022*

### 📈 Contribution history

| | |
|---|---|
| **Contributions** | 1,470+ since Oct 2024 (210 in 2024 · 626 in 2025 · 641 in 2026 so far) |
| **Pull requests** | 354 authored, 332 merged · 62 reviewed |
| **Studia Academy** | 326 PRs (306 merged) across 8 repos · top committer on both the web app and the API |
| **Open source** | Merged fix in [SwiftyCrow](https://github.com/PangMo5/SwiftyCrow/pull/11) |

> Most of my work is in private repositories, so the green squares show it but the repo list doesn't.

### 🚀 Featured projects

| Project | What it is | Stack |
|---|---|---|
| [bluetooth-tracker-ios](https://github.com/glgmainstream12/bluetooth-tracker-ios) ⭐ 11 | Finds a Bluetooth device by signal strength, with experimental modes that estimate direction and position | SwiftUI · CoreBluetooth · ARKit |
| [PDFkrama](https://github.com/glgmainstream12/PDFkrama) | A PDF viewer I wrote from scratch in SwiftUI | SwiftUI · PDFKit |
| [AI-chatroom](https://github.com/glgmainstream12/AI-chatroom) | A chat API that keeps conversation history and streams AI replies | Node.js |
| [web-template](https://github.com/glgmainstream12/web-template) | A monorepo starter with a Next.js frontend, an Express backend and Docker support | Turborepo · Next.js · Express |

### 📊 GitHub stats

<p align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=glgmainstream12&theme=github_dark" alt="Profile details"/>
</p>

<p align="center">
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=glgmainstream12&theme=github-dark-blue&hide_border=true" alt="Contribution streak"/>
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=glgmainstream12&theme=github_dark" alt="Repos per language"/>
</p>
