<div align="center">

# Muhammed Mufinuddin Afraz
### AI Engineer · AI Product Manager · Full-Stack SaaS Architect · Founding Engineer

[![Portfolio](https://img.shields.io/badge/Portfolio-mmafraz.vect.pro-6366f1?style=for-the-badge&logo=vercel&logoColor=white)](https://mmafraz.vect.pro)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-afraz--analytics-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/afraz-analytics/)
[![Email](https://img.shields.io/badge/Email-afrazaffu31@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:afrazaffu31@gmail.com)
[![Location](https://img.shields.io/badge/Location-Bangalore,_India-22c55e?style=for-the-badge&logo=googlemaps&logoColor=white)](https://maps.app.goo.gl/bangalore)
[![Open to Work](https://img.shields.io/badge/Open_To-Remote_Only-f59e0b?style=for-the-badge&logo=remotework&logoColor=white)](#)

</div>

---

## 👋 Who I Am

I am an **AI Engineer and Product Manager** who builds, ships, and scales production-ready AI SaaS platforms **independently** — owning every layer from database architecture to UI design, payment orchestration, and user acquisition.

In the last 12 months, I have independently architected, built, and shipped **5 production-grade AI platforms** serving **1,000+ active users**. I do not just write code — I own the complete product lifecycle: market discovery, system design, full-stack engineering, AI integration, and go-to-market execution.

My core strength is **multi-agent AI orchestration** — I have built stateful agentic systems, RAG pipelines, and structured LLM output engines using Gemini 2.5 Flash, Claude, and GPT across real, revenue-generating products.

My execution speed comes from an **AI-native workflow**: I use agentic IDEs (Cursor + Antigravity) and orchestrate frontier models daily, which lets me operate at the velocity of a full product team while working solo.

> **Open to remote-only opportunities globally as an AI Engineer, AI Product Manager, Founding AI Engineer, or Full-Stack AI Architect.**

---

## 🚀 Production Projects

### 🧠 [VectAI](https://mmafraz.vect.pro/work/vectai) — AI Marketing Command Center
> **The crown jewel.** An all-in-one autonomous marketing platform consolidating 10+ GTM tools into a single AI-powered workspace.

- **Scale:** 1,000+ active users | Listed for acquisition on Flippa
- **Core Achievement:** Engineered a **1,017-line stateful AI engine** with enterprise-grade retry logic, exponential backoff, and autonomous reasoning loops across 26 AI functions
- **AI Stack:** Gemini 2.5 Flash + Google Search Grounding + Imagen 3 + Veo 3.1
- **Revenue:** Freemium + $49/mo Pro via LemonSqueezy | Atomic Firebase `runTransaction` prevents all double-spend exploits
- **Tech:** React 19, TypeScript, Firebase Firestore, Vite, Gemini SDK

**Key Engineering Decisions:**
- Custom `SynapseAIError` class with 6 centralized error constants for production-grade UX
- `responseSchema` enforcement on all structured AI output — zero prompt-based JSON parsing
- Real-time Firestore `onSnapshot` listeners for instant UI updates
- Google Search grounding for live brand intelligence and market research

---

### 🤖 [OpenClaw](https://mmafraz.vect.pro/work/openclaw) — AI Chatbot Deployment SaaS
> Deploy a personal AI assistant to Telegram, Discord, or WhatsApp in under 60 seconds. BYOK model — users bring their own Claude/GPT/Gemini API key.

- **Revenue Model:** $29/mo flat rate — pay-first, no free tier
- **Architecture Highlight:** 162-line middleware handles a complete 4-state routing machine (unauth → unpaid → unonboarded → dashboard)
- **Real-time Payment Confirmation:** Supabase Realtime triggers instant redirect the moment a LemonSqueezy webhook fires — zero polling
- **Security:** HMAC-SHA256 webhook verification | 6-event subscription lifecycle handler
- **Tech:** Next.js 16, Supabase Postgres, LemonSqueezy, Oracle Cloud VPS + Docker
- **5 runtime dependencies only** — ultra-minimal attack surface

---

### 📋 [IncidentPost](https://mmafraz.vect.pro/work/incidentpost) — AI Postmortem Generator
> A "panic-to-calm engine" for engineers. Convert raw incident timelines into professional postmortem reports in seconds. Includes HN post, Twitter thread, and ZIP export.

- **Revenue Model:** $199 per incident (one-time)
- **AI:** Gemini 2.5 Flash at temperature 0.3 for factual, professional output
- **Output:** Executive summary + timeline + root cause + action items + HN post + Twitter thread
- **Business Model:** Preview gate (free summary) → Paywall → Full report + public shareable page + ZIP download
- **Tech:** Astro 5, TypeScript, Supabase Postgres, IP-based rate limiting

---

### 🏪 [BioBiz](https://mmafraz.vect.pro/work/biobiz) — Premium Link-in-Bio Storefront
> A Linktree competitor for service businesses. Ultra-fast mobile storefronts with WhatsApp booking, payment buttons, and a viral growth engine.

- **Viral Flywheel:** Free pages show "⚡ Created with BioBiz" badge → Business owners embed in Instagram bio → Their customers discover BioBiz organically
- **Revenue Model:** Free + $9/mo Pro (custom themes, white-label, payment button)
- **Database:** Supabase Postgres with RLS on all 3 tables — proper multi-tenancy from day one
- **UX:** Live split-screen editor with phone mockup preview, 4 themes, drag-and-drop links, Review Booster
- **Tech:** Next.js 16, React 19, Tailwind 4, Supabase, Framer Motion, Server Actions

---

### 📝 [VectBlog](https://mmafraz.vect.pro/work/vectblog) — LLM-First SEO Engine
> 69 MDX articles driving 2,500+ monthly visitors with a smart deep-linking system that funnels readers directly into VectAI's specific tools.

- **LLM-First SEO:** `robots.ts` explicitly authorizes 50+ AI crawlers in 3 tiers (GPTBot, ClaudeBot, PerplexityBot, Google-Extended...)
- **Smart Deep-Links:** Article CTA → `vect.pro/signup?continue=/app/tools?tool=CampaignBuilder` → User lands on the exact tool they were reading about
- **Tech:** React Router v7, MDX, SSG, Tailwind 4, Framer Motion

---

## 🛠️ Technical Stack

```
Languages        TypeScript · JavaScript · Python · Node.js · SQL
AI / LLM         Gemini 2.5 Flash · Claude Opus · GPT-5 · Imagen 3 · Veo 3.1
AI Patterns      Agentic Workflows · RAG Pipelines · Structured Output (responseSchema)
                 Prompt Engineering · Google Search Grounding · Multi-LLM Orchestration
Frontend         Next.js 16 · React 19 · Astro 5 · Vite · Tailwind 4 · Framer Motion
Backend          Supabase (Postgres + RLS + Realtime) · Firebase Firestore · Supabase Auth
Payments         LemonSqueezy · Webhook HMAC Verification · Atomic Transactions
DevOps           Vercel · Docker · Oracle Cloud VPS · CI/CD Pipelines
Agentic IDEs     Cursor · Antigravity (Google DeepMind)
Testing          Playwright (learning) · Acceptance Criteria Ownership
```

---

## 🧠 Engineering Philosophy

**I measure experience in shipping velocity, not calendar years.**

> *"The value of AI is not in the model itself — it's in the orchestration. How the model is integrated into a user's workflow to solve a genuine pain point."*

**How I build:**
- Every project has a monetization strategy **before** a single line of code is written
- Security is structural: Supabase RLS on every table, HMAC-verified webhooks, atomic DB transactions
- AI is a first-class citizen: I don't bolt AI onto products — I design products around AI capabilities
- Documentation ships **with** the feature, not after it
- I define acceptance criteria as tests, not as ticket descriptions

---

## 📊 Cross-Project Patterns

| Project | Stack | Database | AI | Revenue Model | Status |
|---------|-------|----------|----|---------------|--------|
| VectAI | React 19 + Vite + TS | Firebase | Gemini + Imagen + Veo | $49/mo Pro | 1,000+ users |
| OpenClaw | Next.js 16 | Supabase | BYOK (Claude/GPT/Gemini) | $29/mo flat | Live |
| IncidentPost | Astro 5 + TS | Supabase | Gemini 2.5 Flash | $199/incident | Live |
| BioBiz | Next.js 16 + Tailwind 4 | Supabase | None | Free + $9/mo Pro | Active Dev |
| VectBlog | React Router v7 | Static | None | Organic funnel | 2.5k/mo |

---

## 🎯 Open To Work — Remote Only

I am actively seeking **remote-only** opportunities globally. I bring the full-stack depth of a senior engineer, the product thinking of a PM, and the execution speed of a founding team — all in one person.

**Roles I am a strong fit for:**

| Role | Why I Fit |
|---|---|
| **AI Engineer** | Built 5 production AI systems with multi-agent orchestration, RAG pipelines, and structured LLM output at scale |
| **AI Product Manager / Owner** | Defined roadmaps, wrote acceptance criteria as tests, owned demos, shipped end-to-end with zero hand-offs |
| **Founding AI Engineer** | Ideal first AI hire — I can prototype, architect, build, and ship a full product independently |
| **Full-Stack AI Architect** | Designed scalable systems across Next.js, Supabase, Firebase, Gemini, Claude, and LemonSqueezy |
| **Product Engineer (AI)** | Bridged product strategy and engineering execution across 5 shipped SaaS products |

**Non-negotiables:**
- ✅ Remote only (open to any timezone)
- ✅ AI-first product or company
- ✅ High ownership — I want to build, not just review tickets

**I will not consider:** In-office roles, or roles limited to a single layer of the stack.

---

## 📬 Let's Connect

If you are building something ambitious with AI and need someone who can think in systems, ship fast, and own the entire product lifecycle — let's talk.

[![Portfolio](https://img.shields.io/badge/View_Full_Portfolio-mmafraz.vect.pro-6366f1?style=for-the-badge)](https://mmafraz.vect.pro)
[![Email](https://img.shields.io/badge/Email_Me-afrazaffu31@gmail.com-EA4335?style=for-the-badge)](mailto:afrazaffu31@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge)](https://www.linkedin.com/in/afraz-analytics/)

---

<div align="center">
  <sub>Built with an AI-native workflow · Cursor + Antigravity · Gemini + Claude · Shipped fast, shipped right</sub>
</div>
