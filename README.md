### I build the platform your AI product runs on.

Principal software engineer · applied AI & cloud platforms · Toronto.
Multi-tenant AI SaaS, inference economics and cloud infrastructure — production systems, not demos. 15+ years shipping end to end.

**[Book a 30-min call](https://ismail.kattakath.com/)** · [LinkedIn](https://www.linkedin.com/in/ismailkattakath) · [Hugging Face](https://huggingface.co/ismailkattakath)

---

#### What I own for you

| | Mandate | In practice |
|---|---|---|
| 01 | **The AI platform beneath the model** | Provider-abstracted inference (LiteLLM gateway), cost governance with a real kill-switch, RAG observability |
| 02 | **The multi-tenant SaaS backbone** | Tenant isolation you can prove (Cognito), AI usage metering and billing (Stripe), Aurora Serverless v2 |
| 03 | **The cloud and the release path** | AWS CDK / Terraform, keyless GitHub OIDC deploys, staging as a required gate, zero-downtime migrations |

#### Results from production work

- **~25% lower cost, ~40% lower latency** — multi-GPU inference serving on vLLM / Kubernetes
- **99.5% platform uptime** · **100k+ users served** · **80+ app vendors** on pipelines I built
- Most of this lives in private client repos — the contribution graph below counts it.

#### Open work worth a look

| Repo | What it shows |
|---|---|
| [kattakath/nix-config](https://github.com/kattakath/nix-config) | A whole fleet (Mac, Raspberry Pi server, VMs, devcontainer) declared in one Nix mono-repo — CI gates, IaC (terranix), secrets, observability |
| [kattakath/skills](https://github.com/kattakath/skills) | Claude Code plugins and skills I build and use daily — agent tooling, guardrails, MCP |
| [kattakath/.github](https://github.com/kattakath/.github) | A shared CI landing system: one required gate, merge queue, reusable workflows across repos |
| [ismailkattakath/scrape-harness](https://github.com/ismailkattakath/scrape-harness) | A site-agnostic, approval-gated scraping harness (Playwright / Crawlee, Python, Nix) |
| [ismailkattakath/agentic-jobseek](https://github.com/ismailkattakath/agentic-jobseek) | An agentic pipeline with an evidence gate: pgvector RAG over git history, every claim backed by a source |
| [kattakath/ircc-whatsapp-bot](https://github.com/kattakath/ircc-whatsapp-bot) | Corrective RAG (LangGraph + pgvector) answering immigration questions from official sources only |

**Stack:** Python · TypeScript · FastAPI · Next.js · AWS (Lambda, CDK, Cognito, Aurora) · GCP · Kubernetes · vLLM · LiteLLM · pgvector · Nix

Open to principal / staff roles and to contract engagements → **[ismail.kattakath.com](https://ismail.kattakath.com/)**
