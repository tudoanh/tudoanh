# Do Anh Tu

**Senior Python / AI Systems Engineer**
*LLM agents · RAG · workflow automation (n8n) · browser automation · production AI workflows on Django/FastAPI*

tudoanh.fl@gmail.com | +84 394 970 010 | Vietnam (GMT+7)
GitHub: [github.com/tudoanh](https://github.com/tudoanh) | LinkedIn: [linkedin.com/in/doanhtu](https://linkedin.com/in/doanhtu)

Senior engineer with **10+ years of production Python** and 3 years deep in **autonomous multi-agent systems**. Shipped production coding agents that triage bugs, implement fixes, write tests, and submit PRs with zero human coding — developers only review. Fluent in **node-based workflow automation** (n8n, ComfyUI) and code-level orchestration (LangGraph, Celery) — I build the same automation both as visual node graphs and as production code. Full-stack AI experience: LLM orchestration, RAG pipelines, agent tooling (MCP), multi-tenant SaaS, billing, and security hardening. **Daily US-Eastern overlap, 9:30am–1:30pm ET** — live standups and pairing in your morning, async delivery while you sleep.

## Technical Skills

- **Python (10+ yrs):** Django, DRF, FastAPI, Flask, Celery, Channels/WebSockets · also Elixir, Go, JavaScript, SQL
- **AI / LLM:** agent orchestration (Claude Code, Codex, Gemini CLI), MCP servers & tooling, LangChain/LangGraph, RAG (pgvector + Cohere reranking), LiteLLM, llama.cpp, Transformers/HuggingFace, PyTorch
- **Workflow automation:** n8n (node-based workflows, webhooks, credentials), ComfyUI node pipelines · self-built visual workflow builder · code-level orchestration with LangGraph & Celery
- **Data & infra:** PostgreSQL, Redis, SQLite · Docker/Compose, GitHub Actions CI/CD, self-hosted runners · AWS, Azure, GCP, Hetzner, DigitalOcean, fly.io, Cloudflare
- **Automation:** Playwright, Selenium, Scrapy, FFmpeg · Stripe billing integrations

## Experience

### Independent AI Systems R&D — self-directed
*May 2026 – Present*

- Built and operate a **production research-to-publish content pipeline** (Django/Wagtail + Celery + multi-step LLM agents): editorial brief → automated deep web research → cited draft → human approval → scheduled publish, running daily on live infrastructure.
- Built a **10-source job-market crawler fleet** (Scrapy/Playwright) with deduplication, scoring, and Telegram alerting over a 1,700+ listing dataset.
- Designed reusable **autonomous dev-loop tooling** (spec-driven agent iteration with automated review gates) used to ship the above systems solo at team-level velocity.

### Technical Lead & AI Systems Architect — AsianInnovativeHub (CoFounder platform)
*Jun 2024 – Apr 2026*

CoFounder: a multi-tenant AI platform giving startups and SMEs AI-powered coding workspaces, automated deployments, and white-label SaaS infrastructure across APAC.

- Led the evolution from chat assistants to a **full autonomous coding workspace**: four orchestrated coding agents (Claude Code, Gemini CLI, OpenCode, Codex) on cloud VMs with live dev-server preview, browser automation, semantic code search (RAG: pgvector + Cohere reranking), and 6 MCP tool servers — non-technical users build and deploy real applications through natural language.
- Built a **visual, node-based workflow builder** so non-technical users compose multi-agent workflows over the same tool layer the coding agents use — the same node/trigger/data-flow paradigm as n8n, built in-house. Also shipped a **node-based media-generation pipeline on ComfyUI** for the platform.
- Pioneered three internal **autonomous engineering systems** that turned the dev process from human-executed into human-reviewed:
  - **Ralph** — Telegram-driven dev loop: picks up bug reports, reproduces, fixes, writes tests, submits PRs — zero human coding.
  - **OpenClaw** — always-on lead-developer agent monitoring GitHub issues & Sentry; triages and fixes autonomously with Claude Code + Codex peer review, TDD methodology, git-worktree isolation.
  - **Gastown** — multi-agent orchestration (Architect → Developer → Tester → Reviewer) handling complex features end-to-end with automated review feedback loops.
- Architected a **secure two-stage deployment pipeline**: agents push to Gitea; an isolated deploy VM ships to Cloudflare Pages / Azure App Service via Redis job queues — white-label domain routing, webhook dedup, credential isolation.
- Built the **complete billing layer**: Stripe subscription tiers, per-minute VM compute billing, LiteLLM API spend tracking, credit rollover, white-label billing isolation for multiple partner orgs on shared infrastructure.
- Led **security hardening across 150+ endpoints** (RBAC, JWT, upload content validation, SVG XXE/XSS sanitization, rate limiting, shell-injection prevention, ORM query audit); established **11K+ automated tests** and 10 CI/CD workflows on self-hosted infra.
- Mentored junior engineers; reported to the executive team and managed external partner relationships.

### Django Backend Developer (Contract) — AI training platform (under NDA)
*Feb 2023 – Apr 2024*

- Built backend services for an end-to-end AI training platform: LLM-powered data crawlers, auto-annotation, and auto-training workflows.
- Wrote training, inference, logging, and model-serving APIs; supported CV (classification, segmentation) and NLP/LLM workloads with HuggingFace.
- Cut build, training, and crawl times via caching and multithreading; shipped Dockerized deployments with a fully remote team.

### Technical Lead — DavinoSoft
*Oct 2020 – Jan 2023*

- Led outsourced blockchain projects: P2P/OTC trading platforms and cryptocurrency exchanges.
- Built exchange backends with Django + web3.js, real-time updates via Django Channels; shipped dApps with React, Solidity, Vyper.
- Set up GitHub Actions quality gates and auto-deploys; wrote team development guidelines; advised clients directly and trained junior engineers.

### Django Developer — Evano (online file converter)
*Apr 2020 – Sep 2020*

- Built conversion APIs (Django REST + Postgres) around FFmpeg/ImageMagick transcoding pipelines; deployed and scaled on Kubernetes/Podman; integrated Stripe and PayPal.

### Django Developer — Coinhe.io (cryptocurrency exchange)
*Aug 2018 – Nov 2019*

- Built exchange backend APIs (Django REST, Celery/Redis); kept services fast and stable under attack conditions (DDoS defense, caching, DB optimization); ELK-stack observability; unit testing with FactoryBoy.

### Freelance Python Developer — Upwork
*Feb 2016 – Dec 2017*

- Delivered crawling systems (Scrapy), BTC/ETH transaction monitors, and Django web apps for international clients.

## Community & Speaking

- **Mentor, [Pymi.vn](https://pymi.vn) — Vietnam's largest Python learning community** (2015 – present, 10 years): mentored hundreds of beginners into working Python developers; improved course materials; organized community events and managed the online community.
- **Meetup speaker:** [Scrapy + Django-REST + ReactJS](https://www.youtube.com/watch?v=4ZmInPAEQRM) (2018) · [Django FTW — performance & best practices](https://www.youtube.com/watch?v=uuQ5lk9ycr0) (2019)
- **CTF player:** [ctftime.org/team/175619](https://ctftime.org/team/175619)

## Selected Projects

- **[thueai.com](https://thueai.com)** — production Django/Wagtail platform with the autonomous research-to-publish content pipeline described above.
- **[subly.xyz](https://subly.xyz)** — AI media & document translator (video/audio/image/documents) with context-aware translation.
- **[rankclaw.com](https://rankclaw.com)** — free AI-powered security skills audit platform.

*Blog: [doanhtu.com](https://doanhtu.com)*
