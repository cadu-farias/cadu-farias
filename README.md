# Carlos Eduardo Farias

**Full Stack Software Engineer at [12min](https://github.com/12min)** · Piripiri, PI · Brazil

I build product end to end: backend services and queues, web and mobile apps, and the integrations and AI agents that tie them together. Most of my work lives in 12min's private repositories, with 200+ merged pull requests so far.

[🇧🇷 Leia em português](#-em-português)

---

## What I work on at 12min

**CRM and messaging platform.** I am the main contributor to the in-house CRM that runs 12min's customer communication:

- Campaigns over WhatsApp (Meta Cloud API), push notifications (APNs/FCM) and e-mail, with segmentation, scheduling and delivery monitoring
- A journey engine for automated, event-triggered flows (delays, branches, exit events, conversational steps)
- Event ingestion with behavioral segmentation, and link attribution for revenue
- Web and React Native SDKs that the 12min apps and funnels use to send events to the CRM

**AI support agents.** These conversational agents answer subscribers and resolve subscription requests (lookups, cancellations, upgrade links) across several payment providers. They can read payment receipts from PDFs and images, and they hand off to humans with approval steps in Slack. They are integrated with Chatwoot.

**Consumer apps.**

- **Web app:** e-mail and social sign-in (Google, Facebook, Apple), audio player with progress sync, reader, search on Meilisearch, i18n (pt-BR, en, es)
- **Mobile app (React Native / Expo):** paywall and onboarding fixes, playback, deep links, and E2E test flows with Maestro on EAS

**Growth and support automation.** A/B experiments in the onboarding funnel, analytics events (RudderStack), Ruby on Rails API endpoints, n8n workflows, and a RAG knowledge base on Supabase/pgvector for the help desk.

## Tech stack

| Area | Tools |
|---|---|
| Languages | TypeScript, JavaScript, Python, Ruby, SQL |
| Frontend | React, Next.js, Vue / Nuxt, Tailwind CSS, shadcn/ui, TanStack Query |
| Mobile | React Native, Expo, Maestro (E2E) |
| Backend | Bun, Node.js, Hono, Ruby on Rails, BullMQ |
| Data | PostgreSQL, Redis, Supabase, pgvector, Drizzle ORM, Meilisearch |
| Infra | Docker, Google Cloud, Vercel, GitHub Actions |
| Integrations | WhatsApp Cloud API, FCM / APNs, Chatwoot, OneSignal, RudderStack, Slack, n8n |
| AI | LLM agents with tool calling, RAG, AI-assisted development |

## How I work

- I start from a written PRD and ship it in small phased pull requests, each reviewable on its own
- I treat typed contracts, tests and smoke/E2E gates as part of the feature
- I build logs and metrics in from the first version, so problems in production can be traced
- I write Conventional Commits and keep changes close to the code around them

## Side projects

These are private for now:

- **BarberApp:** white-label scheduling platform for barbershops (Next.js 16, shadcn/ui, Drizzle)
- **FinanceFlow:** personal finance manager (Next.js, Supabase)
- **PDV Ótica:** point-of-sale system for optical stores (Next.js, PostgreSQL)

---

## 🇧🇷 Em português

**Engenheiro de Software Full Stack na [12min](https://github.com/12min)**, em Piripiri (PI).

Construo produto de ponta a ponta: serviços de backend e filas, apps web e mobile, e as integrações e agentes de IA que conectam tudo. A maior parte do meu trabalho fica nos repositórios privados da 12min, com mais de 200 pull requests mergeados até agora.

**O que faço na 12min:**

- **CRM e mensageria:** sou o principal contribuidor do CRM interno. Ele cuida de campanhas de WhatsApp, push e e-mail, de jornadas automatizadas disparadas por eventos, da segmentação comportamental e da atribuição de receita. Também mantenho os SDKs web e React Native que alimentam o CRM.
- **Agentes de IA para o suporte:** atendem assinantes, consultam e cancelam assinaturas em vários meios de pagamento e leem comprovantes em PDF e imagem. Quando precisam, passam o caso para uma pessoa, com aprovação no Slack. Estão integrados ao Chatwoot.
- **Apps:** no novo web app, fiz autenticação com login social, player de áudio, leitor, busca e i18n. No app mobile (Expo), corrigi paywall, onboarding e reprodução e criei testes E2E com Maestro.
- **Growth e automação:** experimentos A/B no funil de onboarding, eventos de analytics, endpoints na API em Rails, workflows no n8n e uma base de conhecimento com RAG para o suporte.

**Como trabalho:** parto de um PRD e entrego em PRs pequenos, por fases. Testes, contratos tipados e observabilidade fazem parte da entrega.

**Stack principal:** TypeScript, React, Next.js, React Native/Expo, Bun, Hono, Node.js, Rails, PostgreSQL, Redis, Supabase, Docker, GCP e Vercel.
