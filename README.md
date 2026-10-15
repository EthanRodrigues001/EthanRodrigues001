<p align="center">
  <img alt="Ethan Rodrigues" src="https://shieldcn.dev/header/surface.svg?title=Ethan+Rodrigues&amp;subtitle=AI+Engineer+%C2%B7+Full-Stack+Developer&amp;logo=https%3A%2F%2Fraw.githubusercontent.com%2FEthanRodrigues001%2FEthanRodrigues001%2Fmain%2Flogo-mark-muted.png&amp;mode=dark&amp;theme=slate&amp;align=left&amp;image=https%3A%2F%2Fres.cloudinary.com%2Fdhyvtqkof%2Fimage%2Fupload%2Ff_auto%2Fq_auto%2FPoster_1_lzltdi.png&amp;overlay=0.4" width="100%" />
</p>

<p align="center">
  <a href="https://ethan-rodrigues-portfolio-1fu1.vercel.app/"><img alt="Portfolio" src="https://shieldcn.dev/badge/Portfolio-000000.svg?logo=vercel&amp;logoColor=fff&amp;variant=branded&amp;brand=vercel&amp;size=xs" /></a>
  <a href="https://www.linkedin.com/in/ethan-rodrigues25/"><img alt="LinkedIn" src="https://shieldcn.dev/badge/LinkedIn-0A66C2.svg?logo=ri:RiLinkedinBoxFill&amp;logoColor=fff&amp;variant=branded&amp;size=xs" /></a>
  <a href="https://twitter.com/EthanRo97737635"><img alt="X" src="https://shieldcn.dev/badge/X-000000.svg?logo=x&amp;logoColor=fff&amp;variant=branded&amp;brand=x&amp;size=xs" /></a>
  <a href="mailto:ethanrodrigues25@gmail.com"><img alt="Email" src="https://shieldcn.dev/badge/Email-EA4335.svg?logo=gmail&amp;logoColor=fff&amp;variant=branded&amp;brand=gmail&amp;size=xs" /></a>
  <a href="https://cal.com/ethan-rodrigues"><img alt="Book a call" src="https://shieldcn.dev/badge/Book%20a%20call-292929.svg?logo=caldotcom&amp;logoColor=fff&amp;variant=branded&amp;brand=caldotcom&amp;size=xs" /></a>
</p>

# やあ, I'm Ethan 🐼

I'm an AI engineer and full-stack developer, in my final year of Computer Engineering at FCRIT, Navi Mumbai. Most of what I build these days has an LLM in it: agents that call tools and change real data, inside TypeScript, Next.js and Postgres apps.

I also build *with* AI: Claude Code and Codex are part of my daily workflow, and I work across Claude, GPT and Gemini models depending on the job.

- 🤖 Model-agnostic agents on the Vercel AI SDK, with the limits that keep them safe: quotas, step caps, human approval
- 🚢 Research intern at IISER Mohali (2025-26): fuel-consumption models for a Kamsarmax bulk carrier on ~83k rows of real telemetry, XGBoost at R² 0.98
- 🦀 Rust services (Axum, Tokio) and Tauri desktop apps
- ⚙️ GitHub Actions release pipelines, signed auto-updates, Docker deploys
- 📬 Co-founded [LetterStack](https://letterstack.site) with [Krish Pinto](https://github.com/krishpinto): open source, with paying customers
- 🧩 Built LYX UI, a shadcn-based React component library
- 🎨 UI/UX design in Figma, as a hobby
- 🎧 Off the keyboard: music and anime

## 🤖 What I build with AI

- **Agents inside products.** [LetterStack](https://github.com/krishpinto/Letterstack)'s email editor has an agent that edits the document through typed tools. Tool calls run in the browser so edits are instant, while the server keeps the API key, per-org quotas, a usage ledger and a hard step ceiling.
- **Tool-calling agents with memory.** [eve-agent-framework](https://github.com/EthanRodrigues001/eve-agent-framework): a model-agnostic agent on Vercel's Eve framework where each new skill is one typed tool file, with notes persisted in Neon Postgres, usable from a web UI, an HTTP API or a terminal REPL.
- **Durable agent workflows.** Career OS (in progress): multi-step agent runs on Workflow DevKit that survive restarts and can be replayed, with an approval gate before anything is sent to the outside world.
- **LLM features that ship.** AI roadmap generation in [Blingo](https://blingo2-0.vercel.app/), AI health summaries from uploaded prescriptions in [HealthSync](https://vybe-coders-health-sync.vercel.app), and an AI schema visualiser with Upstash rate limiting.
- **Classic ML.** At IISER Mohali I modelled a Kamsarmax bulk carrier's fuel use from real telemetry: XGBoost hit R² 0.98, and synthetic data cut its error by 17%. Served over FastAPI as [shipfuel-ai](https://shipfuel-ai.vercel.app/). Also PyTorch/Keras demand forecasting explained with SHAP and LIME.
- **Agentic dev workflow.** Claude Code and Codex every day. [Typeset](https://github.com/EthanRodrigues001/Typeset) even writes LAYOUT.md index files so agents can find their way around a notes workspace.

## 🚀 Featured work

| Project | What it is | Stack |
| --- | --- | --- |
| [**LetterStack**](https://letterstack.site) | Open-source email campaign SaaS I co-founded (~72k lines, paying customers). I built the AI editing agent and Razorpay invoicing ([repo](https://github.com/krishpinto/Letterstack)) | Next.js · AI SDK · Neon · AWS SES · Razorpay |
| [**eve-agent-framework**](https://github.com/EthanRodrigues001/eve-agent-framework) | Extensible, model-agnostic agent with persistent memory | Eve · AI SDK · Neon |
| [**Typeset**](https://github.com/EthanRodrigues001/Typeset) | Windows Markdown app; 5 signed, auto-updating releases via GitHub Actions | Tauri · Rust · Next.js · CodeMirror |
| [**Moss**](https://github.com/EthanRodrigues001/Moss) | Overleaf-style LaTeX editor with a Rust compile service on Docker | Next.js · Supabase · Rust (Axum) · Docker |
| [**LYX UI**](https://lyx-ui.vercel.app/) | shadcn/ui-based component library + docs | Next.js · Fumadocs · Motion |
| [**Blingo**](https://blingo2-0.vercel.app/) | AI project-roadmap generator for hackathon teams | Next.js · Gemini · Appwrite · React Flow |
| [**shipfuel-ai**](https://shipfuel-ai.vercel.app/) | Ship fuel-consumption prediction from the IISER research (R² 0.98) | FastAPI · XGBoost · Next.js |

## 🧰 Tech stack

**Languages**<br/>
<img alt="TypeScript" src="https://shieldcn.dev/badge/TypeScript-3178C6.svg?logo=typescript&amp;logoColor=fff&amp;variant=branded&amp;brand=typescript&amp;size=xs" />
<img alt="Rust" src="https://shieldcn.dev/badge/Rust-000000.svg?logo=rust&amp;logoColor=fff&amp;variant=branded&amp;brand=rust&amp;size=xs" />
<img alt="Python" src="https://shieldcn.dev/badge/Python-3776AB.svg?logo=python&amp;logoColor=fff&amp;variant=branded&amp;brand=python&amp;size=xs" />
<img alt="JavaScript" src="https://shieldcn.dev/badge/JavaScript-F7DF1E.svg?logo=javascript&amp;logoColor=fff&amp;variant=branded&amp;brand=javascript&amp;size=xs" />
<img alt="SQL" src="https://shieldcn.dev/badge/SQL-4169E1.svg?logo=postgresql&amp;logoColor=fff&amp;variant=branded&amp;brand=postgresql&amp;size=xs" />

**Frontend**<br/>
<img alt="React" src="https://shieldcn.dev/badge/React-61DAFB.svg?logo=react&amp;logoColor=fff&amp;variant=branded&amp;brand=react&amp;size=xs" />
<img alt="Next.js" src="https://shieldcn.dev/badge/Next.js-000000.svg?logo=nextdotjs&amp;logoColor=fff&amp;variant=branded&amp;brand=nextdotjs&amp;size=xs" />
<img alt="Tailwind CSS" src="https://shieldcn.dev/badge/Tailwind%20CSS-06B6D4.svg?logo=tailwindcss&amp;logoColor=fff&amp;variant=branded&amp;brand=tailwindcss&amp;size=xs" />
<img alt="shadcn/ui" src="https://shieldcn.dev/badge/shadcn/ui-000000.svg?logo=shadcnui&amp;logoColor=fff&amp;variant=branded&amp;brand=shadcnui&amp;size=xs" />
<img alt="Motion" src="https://shieldcn.dev/badge/Motion-0055FF.svg?logo=framer&amp;logoColor=fff&amp;variant=branded&amp;brand=framer&amp;size=xs" />
<img alt="Zod" src="https://shieldcn.dev/badge/Zod-3E67B1.svg?logo=zod&amp;logoColor=fff&amp;variant=branded&amp;brand=zod&amp;size=xs" />

**Backend & systems**<br/>
<img alt="Node.js" src="https://shieldcn.dev/badge/Node.js-5FA04E.svg?logo=nodedotjs&amp;logoColor=fff&amp;variant=branded&amp;brand=nodedotjs&amp;size=xs" />
<img alt="Axum" src="https://shieldcn.dev/badge/Axum-000000.svg?logo=rust&amp;logoColor=fff&amp;variant=branded&amp;brand=rust&amp;size=xs" />
<img alt="Tokio" src="https://shieldcn.dev/badge/Tokio-000000.svg?logo=rust&amp;logoColor=fff&amp;variant=branded&amp;brand=rust&amp;size=xs" />
<img alt="FastAPI" src="https://shieldcn.dev/badge/FastAPI-009688.svg?logo=fastapi&amp;logoColor=fff&amp;variant=branded&amp;brand=fastapi&amp;size=xs" />
<img alt="WebAssembly" src="https://shieldcn.dev/badge/WebAssembly-654FF0.svg?logo=webassembly&amp;logoColor=fff&amp;variant=branded&amp;brand=webassembly&amp;size=xs" />
<img alt="Socket.IO" src="https://shieldcn.dev/badge/Socket.IO-010101.svg?logo=socketdotio&amp;logoColor=fff&amp;variant=branded&amp;brand=socketdotio&amp;size=xs" />
<img alt="Razorpay" src="https://shieldcn.dev/badge/Razorpay-0C2451.svg?logo=razorpay&amp;logoColor=fff&amp;variant=branded&amp;brand=razorpay&amp;size=xs" />

**Data**<br/>
<img alt="PostgreSQL" src="https://shieldcn.dev/badge/PostgreSQL-4169E1.svg?logo=postgresql&amp;logoColor=fff&amp;variant=branded&amp;brand=postgresql&amp;size=xs" />
<img alt="Neon" src="https://shieldcn.dev/badge/Neon-00E599.svg?logo=neon&amp;logoColor=fff&amp;variant=branded&amp;brand=neon&amp;size=xs" />
<img alt="MongoDB" src="https://shieldcn.dev/badge/MongoDB-47A248.svg?logo=mongodb&amp;logoColor=fff&amp;variant=branded&amp;brand=mongodb&amp;size=xs" />
<img alt="Drizzle ORM" src="https://shieldcn.dev/badge/Drizzle%20ORM-C5F74F.svg?logo=drizzle&amp;logoColor=fff&amp;variant=branded&amp;brand=drizzle&amp;size=xs" />
<img alt="Supabase" src="https://shieldcn.dev/badge/Supabase-3FCF8E.svg?logo=supabase&amp;logoColor=fff&amp;variant=branded&amp;brand=supabase&amp;size=xs" />
<img alt="Firebase" src="https://shieldcn.dev/badge/Firebase-FFCA28.svg?logo=firebase&amp;logoColor=fff&amp;variant=branded&amp;brand=firebase&amp;size=xs" />
<img alt="Redis" src="https://shieldcn.dev/badge/Redis-FF4438.svg?logo=redis&amp;logoColor=fff&amp;variant=branded&amp;brand=redis&amp;size=xs" />

**Desktop & mobile**<br/>
<img alt="Tauri" src="https://shieldcn.dev/badge/Tauri-24C8D8.svg?logo=tauri&amp;logoColor=fff&amp;variant=branded&amp;brand=tauri&amp;size=xs" />
<img alt="Electron" src="https://shieldcn.dev/badge/Electron-47848F.svg?logo=electron&amp;logoColor=fff&amp;variant=branded&amp;brand=electron&amp;size=xs" />
<img alt="Expo" src="https://shieldcn.dev/badge/Expo-000020.svg?logo=expo&amp;logoColor=fff&amp;variant=branded&amp;brand=expo&amp;size=xs" />
<img alt="React Native" src="https://shieldcn.dev/badge/React%20Native-61DAFB.svg?logo=react&amp;logoColor=fff&amp;variant=branded&amp;brand=react&amp;size=xs" />
<img alt="WXT extensions" src="https://shieldcn.dev/badge/WXT%20extensions-4285F4.svg?logo=googlechrome&amp;logoColor=fff&amp;variant=branded&amp;brand=googlechrome&amp;size=xs" />

**AI & ML**<br/>
<img alt="Vercel AI SDK" src="https://shieldcn.dev/badge/Vercel%20AI%20SDK-000000.svg?logo=vercel&amp;logoColor=fff&amp;variant=branded&amp;brand=vercel&amp;size=xs" />
<img alt="Claude" src="https://shieldcn.dev/badge/Claude-D97757.svg?logo=claude&amp;logoColor=fff&amp;variant=branded&amp;brand=claude&amp;size=xs" />
<img alt="OpenAI" src="https://shieldcn.dev/badge/OpenAI-000000.svg?logo=false&amp;variant=branded&amp;size=xs" />
<img alt="Gemini" src="https://shieldcn.dev/badge/Gemini-8E75B2.svg?logo=googlegemini&amp;logoColor=fff&amp;variant=branded&amp;brand=googlegemini&amp;size=xs" />
<img alt="scikit-learn" src="https://shieldcn.dev/badge/scikit--learn-F7931E.svg?logo=scikitlearn&amp;logoColor=fff&amp;variant=branded&amp;brand=scikitlearn&amp;size=xs" />
<img alt="XGBoost" src="https://shieldcn.dev/badge/XGBoost-337AB7.svg?logo=xgboost&amp;logoColor=fff&amp;variant=branded&amp;brand=xgboost&amp;size=xs" />
<img alt="PyTorch" src="https://shieldcn.dev/badge/PyTorch-EE4C2C.svg?logo=pytorch&amp;logoColor=fff&amp;variant=branded&amp;brand=pytorch&amp;size=xs" />

**CI/CD & infra**<br/>
<img alt="AWS" src="https://shieldcn.dev/badge/AWS%20(SES%2C%20SNS)-232F3E.svg?logo=false&amp;variant=branded&amp;size=xs" />
<img alt="GitHub Actions" src="https://shieldcn.dev/badge/GitHub%20Actions-2088FF.svg?logo=githubactions&amp;logoColor=fff&amp;variant=branded&amp;brand=githubactions&amp;size=xs" />
<img alt="Docker" src="https://shieldcn.dev/badge/Docker-2496ED.svg?logo=docker&amp;logoColor=fff&amp;variant=branded&amp;brand=docker&amp;size=xs" />
<img alt="Vercel" src="https://shieldcn.dev/badge/Vercel-000000.svg?logo=vercel&amp;logoColor=fff&amp;variant=branded&amp;brand=vercel&amp;size=xs" />
<img alt="Render" src="https://shieldcn.dev/badge/Render-000000.svg?logo=render&amp;logoColor=fff&amp;variant=branded&amp;brand=render&amp;size=xs" />
<img alt="Vite" src="https://shieldcn.dev/badge/Vite-646CFF.svg?logo=vite&amp;logoColor=fff&amp;variant=branded&amp;brand=vite&amp;size=xs" />
<img alt="Vitest" src="https://shieldcn.dev/badge/Vitest-6E9F18.svg?logo=vitest&amp;logoColor=fff&amp;variant=branded&amp;brand=vitest&amp;size=xs" />

### ⚙️ How I ship

- **Tagged releases → signed desktop builds.** In [Typeset](https://github.com/EthanRodrigues001/Typeset), pushing a `v*` tag runs a GitHub Actions workflow that sets up Node and the Rust toolchain, builds the Tauri app on Windows, signs it for the auto-updater with keys kept in repo secrets, and publishes a GitHub Release that installed copies update from.
- **Containerised Rust service.** [Moss](https://github.com/EthanRodrigues001/Moss) runs a LaTeX compile backend written in Rust (Axum + Tokio). It ships as a Docker image on Render as infrastructure-as-code (`render.yaml`), with health checks, upload limits and compile timeouts.
- **Deploy automation.** Vercel preview and production deploys on every project, plus a GitHub Actions deploy hook that works around Vercel's single-owner build limit on team repos.
- **Quality gates.** TypeScript strict mode, ESLint/Biome, Vitest + Testing Library, Zod at API boundaries.

## 📈 Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://shieldcn.dev/chart/github/commits/EthanRodrigues001.svg?bg=transparent&amp;border=false&amp;color=ffffff&amp;mode=dark" />
    <img alt="Lifetime commits" src="https://shieldcn.dev/chart/github/commits/EthanRodrigues001.svg?bg=transparent&amp;border=false&amp;color=18181b&amp;mode=light" />
  </picture>
</p>
