# Hi there, I'm Igor Kliuchnik 👋

**Senior Frontend Engineer** — React & Vue  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-iharkliuchnik-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/iharkliuchnik)
[![Telegram](https://img.shields.io/badge/Telegram-@Igor__Kliuchnik-2CA5E0?style=flat&logo=telegram)](https://t.me/Igor_Kliuchnik)
[![Email](https://img.shields.io/badge/Email-igor.kliuchnik.job@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:igor.kliuchnik.job@gmail.com)

---

Frontend engineer with 6+ years in React and Vue. I've led a frontend team, rescued broken codebases, and shipped products from scratch — and I've always been curious about the bigger picture: how the backend is structured, how the system behaves under load, how decisions made today affect the developer who touches this code a year from now.

---

## 💻 Stack

**Frontend**  
`React` `Next.js` `Vue 3` `Nuxt 3` `TypeScript` `JavaScript` `HTML5` `CSS3` `SCSS` `Tailwind CSS`

**State & Data**  
`RTK Query` `Pinia` `Vuex` `React Hook Form` `Zod` `Context API`

**Backend & DB**  
`Node.js` `Express.js` `REST APIs` `WebSockets` `Firebase` `PostgreSQL` `MongoDB` `IndexedDB` `Redis`

**Tooling**  
`Git` `Docker` `CI/CD` `Storybook` `Sentry` `ESLint` `Husky` `commitlint` `Jest`

**Other**  
`SPA` `SSR`

---

## 🚀 Projects

### 🧘‍♂️ **Just Breath** ([PWA](https://just-breath.netlify.app/) / [Chrome Extension](https://chromewebstore.google.com/detail/just-breath/mdlliaajfdghjomkpbembokopmabnigb) / [TG Bot](https://t.me/breath_in_breath_out_bot))
* **What:** A minimalist breathing app with a 1-click start.
    *  Instant access via Web/PWA, Chrome Side Panel, or Telegram to quickly de-stress and refocus.
    *  Soft, procedurally generated organic sounds with 100% offline autonomy.
    *  Science-backed presets: SOS, Focus, Energy, Sleep, Balance, Therapy, and **Quit Smoking**.
    *  Fully customizable personal patterns down to the second.
* **Tech:** High-performance, zero-overhead client-side architecture.
    *  Perfect 100/100 Lighthouse scores across all four categories.
    *  Ultra-lightweight footprint: 338 KB total cached size (FCP 0.3s, LCP 0.4s).
    *  Native Web Audio API for mathematical real-time sound synthesis (zero audio files overhead).
    *  True multi-platform ecosystem running as PWA, Chrome Side Panel (MV3), and Telegram Mini App.
    *  Strict 100% privacy: zero external SDKs or tracking, with all state isolated in client LocalStorage.
* **Stack:** Vanilla JS, HTML5, CSS3, Vite, Web Audio API, PWA, Chrome Manifest V3.

##

### 🤖 **Interactive AI Resume** ([Web](https://igor-kliuchnik-south-park-styled-in.vercel.app/) / [TG Bot](https://t.me/MY_DEV_CV_BOT))

* **What:** An interactive digital avatar that conducts live, conversational job interview tailored to my CV.
    * Replaces traditional static PDFs with an animated 2D SVG avatar featuring CSS-driven lip-sync synchronized to typewriter text effects.
    * Provides instant, deterministic answers about my tech stack, experience, and soft skills in both English and Russian.
    * Features smart Telegram session tracking that isolates conversations across restarts.
    * Allows 1-click export of the interview transcript as an AI-ready `.md` file optimized for recruiter parsing.
* **Tech:** High-availability, zero-cost serverless architecture powered by a deterministic-first fallback cascade.
    * *Zero-Hallucination Flow:* Prioritizes instant, pre-written answers via UI autocomplete shortcuts and sub-millisecond Redis caching. If a direct match fails, Fuse.js fuzzy matching catches variations before an LLM is ever engaged.
    * *AI as a Semantic Router:* When algorithmic matching isn't enough, the AI is not allowed to "chat"; it acts strictly as a classifier, outputting a JSON intent ID to fetch verified data. This eliminates generative hallucinations by design and significantly minimizes token consumption by avoiding unnecessary text generation.
    * *0-Cost Failover Chain:* Powered by a tiered chain of 4 Groq API models. If a primary model hits a rate limit or goes down, the request seamlessly routes to the next, ensuring enterprise-grade uptime on free tiers.
    * *Isolated Generative RAG:* True text generation is strictly sandboxed to a single intent (cv.meta.cv_search) for niche technical questions. It reads the full plain-text CV to generate custom answers based on my actual experience.
    * *Graceful Degradation:* Redis tracks global and per-session API limits to prevent DDoS and quota exhaustion, degrading smoothly to pure algorithmic search if limits are hit. 
    * *Continuous Logging:* Every interaction, including the query, resolved intent, and resolution source, is logged to Supabase to analyze and improve the flow.
* **Stack:** Nuxt 4, Vue 3, Tailwind CSS, PostgreSQL, Redis, Fuse.js, AI (Groq API (GPT-OSS / Llama 3.1)).

---

## 📋 Highlights

- 🏗️ Led a 4-person frontend team on a high-load logistics CRM. Migrated client-side storage from localStorage to IndexedDB, introduced Storybook component library, set up ESLint + Husky + commitlint pipeline
- 📈 Vue 2 → Vue 3 migration, TradingView charts integration, Crowdin localization across 5+ languages
- ⚡ WordPress → Next.js migration (load time: 3s → 1s), greenfield Next.js platform from scratch
- 🎨 Full SPA from zero: UI/UX design, booking flow, discount engine, business dashboard

---

## 🎓 Certifications

- Certified Nuxt Master — Vue School (2022)
- NodeJS: The Complete Guide — Udemy (2024)

---

## 🌍 Languages

`English - C1` `Russian - Native`
