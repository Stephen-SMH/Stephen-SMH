<p align="center"><img src="assets/banner.svg" alt="Soe Moe Htet" width="100%"></p>

<p align="center">
  <a href="https://stephen-smh.github.io/software-engineering-portfolio/en/"><img alt="Engineering" src="https://img.shields.io/badge/Engineering_portfolio-f472b6?style=for-the-badge&logo=astro&logoColor=white"></a>
  <a href="https://stephen-smh.github.io/game-portfolio/"><img alt="Games" src="https://img.shields.io/badge/Game_portfolio-8b5cf6?style=for-the-badge&logo=gamedeveloper&logoColor=white"></a>
  <a href="https://stephen-smh.github.io/desktop-portfolio/"><img alt="Desktop" src="https://img.shields.io/badge/Desktop_portfolio-6366f1?style=for-the-badge&logo=tauri&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/soe-moe-htet-01b411187/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>

```yaml
name:      Soe Moe Htet (Stephen)
role:      Software Engineer · backend, fintech systems, agentic AI
location:  Bangkok, Thailand (UTC+7) · hybrid or remote
education: B.Eng. Software Engineering, KMITL (2022 – 2026)
focus:     correctness under concurrency · production delivery · auditable AI
```

## ⚡ Summary

Full-stack engineer who ships **spec → data model → API → UI → production**. I build money-moving systems where every cent is accounted for (double-entry ledgers, idempotency, outbox, reconciliation), run them on Kubernetes with GitOps and SLOs, and add agentic AI with deterministic guardrails so behaviour stays auditable.

## 💼 Experience

**Forward Deployed Engineer (associate)** · *Tech Links Asia* · Jul 2026 – Present
- Shipped a social media management platform **solo, spec to deploy**: FastAPI / SQLAlchemy API and a React / TypeScript frontend.
- Put **6 platform APIs** (Facebook, Instagram, LinkedIn, TikTok, X, YouTube) behind one service registry, so a new channel plugs in without touching core logic.
- Built an AI copilot into the composer and post editor, and deployed the stack to production with Docker Compose on Render.

**Software Engineer (intern)** · *Smart Shift Solutions* · Dec 2025 – May 2026
- Wrote Kotlin / Spring Boot business modules (config, flow orchestration, position management) for the Supali CRM and DOA platforms, with jOOQ, Flyway and a Next.js frontend.
- Added RBAC and server-side validation to block unauthorized state changes.
- Contributed to **Context Hub**, an agentic RAG tool that answers questions by searching every company repo, and designed an Agno / CopilotKit agent platform with structured I/O and prompt-injection defences.

**QA Automation Engineer (intern)** · *Social.plus* · Jul – Sep 2025
- Wrote and maintained Playwright end-to-end suites for the Social.plus UI Kit, tracking work in Jira and TestMo.

**Earlier, 2020 – 2025:** multi-agent NL→SQL with LlamaIndex and Docker (*Zojump*) · PLC conveyor control with Flask, WebSocket and ZeroMQ (*Clara Robotic*) · Braze SDK in a Flutter app (*Demeter ICT*) · live vehicle geotracking in React (*Sustainity*) · Flutter with Bloc / Cubit (*Frontware*) · internal web systems in React and FastAPI (*Chindwin Crewing*, 2 years)

## 🏗️ Featured systems

| System | What it proves | Stack |
| --- | --- | --- |
| **MPay**: e-wallet simulation, MoMo / ZaloPay style | **Double-entry ledger** where money is never lost or duplicated under concurrency, partner failures and crashes. 20 domain modules (ledger, payments, cards, bill pay, FX, settlement, reconciliation, accounting close, fraud, AML, disputes), a transactional outbox, idempotent postings and holds, **23 ADRs** | Go · PostgreSQL · sqlc · MongoDB · OpenAPI · React · Flutter |
| **YoteShin Platform**: infra for a Myanmar short-drama streaming app | Terraform-managed AWS (S3 presigned uploads → SQS → worker, IAM / OIDC), Kubernetes with **Argo CD GitOps**, Prometheus / Grafana / Loki with SLOs. Runs on k3d locally and on Oracle Cloud | Kubernetes · Terraform · Argo CD · AWS · Grafana |
| **YoteShin Studio**: mobile publishing app | Resumable YouTube uploads that run on the OS background transfer service and pick up from the last byte YouTube received; a film counts as published only once YouTube returns its video ID | Flutter · Riverpod · YouTube Data API |
| [**Migrate Studio**](https://stephen-smh.github.io/migrate-studio/) | Applies SQL migrations, lints risky statements, replays each down on a scratch DB to prove it undoes its up, and detects schema drift | Go · PostgreSQL · React |
| [**LocalGate**](https://github.com/Stephen-SMH/local-llm-gateway) | OpenAI-compatible gateway for local LLMs with retries, circuit breakers, fallback models, API-key RBAC and Redis rate limiting | Python · Redis · Ollama |
| **Food Delivery City** | Every customer, cook and rider is an LLM agent on a 3D map, with Go services talking over RabbitMQ through an outbox | Go · RabbitMQ · Three.js |

<sub>MPay, YoteShin and Food Delivery City are in private repos. I'm happy to walk through the code in an interview.</sub>

## 🧰 Stack

| Layer | Tools |
| --- | --- |
| **Languages** | Go · TypeScript · Python · Kotlin · Swift · Dart |
| **Backend** | FastAPI · Spring Boot · sqlc / jOOQ · OpenAPI · RabbitMQ · ZeroMQ · WebSocket |
| **Data** | PostgreSQL · Redis · MongoDB · Flyway / dbmate migrations |
| **Frontend / mobile** | React · Next.js · Vite · Flutter (Riverpod, Bloc) · Android · iOS |
| **Infra / ops** | Docker · Kubernetes · Terraform · Argo CD · GitHub Actions · AWS · Prometheus · Grafana · Loki · k6 |
| **AI** | RAG · MCP · LlamaIndex · Agno · CopilotKit · Claude API · Ollama |
| **Quality** | Playwright · Go race / integration tests · architecture tests · ADRs |

## 📫 Contact

**soemoehtetstephen@gmail.com** · [LinkedIn](https://www.linkedin.com/in/soe-moe-htet-01b411187/) · [Portfolio](https://stephen-smh.github.io/software-engineering-portfolio/en/) · Open to full-time roles, hybrid or remote.
