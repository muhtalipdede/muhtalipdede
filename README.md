# Muhtalip Dede

Senior Software Engineer at **[Wingie Enuygun Group](https://www.wingie.com/)**, based in Istanbul.

Mathematical Engineering graduate (Honors) from Yıldız Technical University. Currently pursuing an MSc with a thesis on **low-light image enhancement using diffusion models**.

9+ years building scalable backend and platform systems across travel, vehicle finance, tourism, IoT, and SaaS. Active in open source and the Turkish developer community.

**Languages:** Turkish, English

---

## Currently

- Building **WingieOne**, Wingie Enuygun Group’s B2B travel platform
- Building **[Coppergate](https://github.com/coppergateai/coppergate)** — autonomous multi-agent Survivor arena ([coppergate.ai](https://coppergate.ai))
- Developing **[kprompt](https://github.com/kprompt/kprompt)** — an open-source AI Kubernetes CLI ([kprompt.ai](https://kprompt.ai))
- Researching diffusion models for low-light image enhancement (MSc thesis)

---

## Tech Stack

| Area | Technologies |
|------|--------------|
| **Languages** | C#, TypeScript, Python, Go |
| **Frameworks & Tools** | .NET, Node.js, React Native, Entity Framework, LangChain, Cursor |
| **Infrastructure** | Docker, Kubernetes, Helm, ArgoCD, Pulumi, Jenkins |
| **Cloud** | AWS, GCP, Azure |
| **Data & Messaging** | MSSQL, MySQL, PostgreSQL, MongoDB, Redis, Kafka, RabbitMQ, Firebase |
| **Observability & Platform** | Prometheus, Grafana, OpenTelemetry, ELK Stack, OpenShift, API Gateway, BFF |
| **Architecture** | Microservices, event-driven systems, CI/CD, GitOps |

---

## Experience Highlights

### WingieOne — B2B Travel Platform
Wingie Enuygun Group’s B2B platform for travel partners and agency workflows.

- Designing and delivering scalable backend services for booking, inventory, and partner integrations
- Operating high-traffic travel systems with a focus on reliability and operability

### BiletDukkani — Travel Assistant Platform
- Built **SEGGY**, an AI travel assistant integrating ChatGPT, LangChain, and Gemini
- Migrated monolith modules to microservices (.NET 8, Node.js)
- Introduced Kafka-based messaging; deployed on Azure and GCP with Kubernetes

### Datapad — Analytics Dashboard
- Founding engineer of a mobile analytics product (500 Istanbul–funded)
- Provisioned and deployed microservices with Pulumi and ArgoCD
- Stack: React Native, MongoDB, Firebase

### Petimle — Pet Health Tracking
- Built a cross-platform mobile app for vet consults, vaccinations, and reminders
- Pitched the product and secured investment for continued development

### VosVos / Zebra / Doğuş
- Delivered credit systems and legacy migrations with C# and Entity Framework
- Moved workloads to containerized microservices with Redis, RabbitMQ, and ELK-based observability

---

## Open Source

### [Coppergate](https://github.com/coppergateai/coppergate) — Autonomous Multi-Agent Arena

[![Stars](https://img.shields.io/github/stars/coppergateai/coppergate?style=flat&logo=github)](https://github.com/coppergateai/coppergate/stargazers)
[![License](https://img.shields.io/badge/license-MIT-blue)](https://github.com/coppergateai/coppergate/blob/main/LICENSE)

Agents compete inside a **Survivor arena**; fitness (tests, CI, critic, policy, budget) decides who ships. You set the goal, the policy, and the kill-switch.

[coppergate.ai](https://coppergate.ai) · [Org](https://github.com/coppergateai)

| Capability | What it does |
|------------|--------------|
| **Compete** | Multiple contenders work the same outcome in parallel |
| **Select** | Fitness evidence promotes winners; losers lose budget |
| **Ship** | Survivors move forward; production stays policy-gated |
| **Wedge** | GitHub-native fitness — issue → verified PR (CI + cost + Accept) |
| **Self-host** | MIT, Docker Compose, bring your own keys |

```bash
git clone https://github.com/coppergateai/coppergate.git
cd coppergate
cp .env.selfhost.example .env.selfhost
docker compose -f docker-compose.selfhost.yml --env-file .env.selfhost up -d --build
```

---

### [kprompt](https://github.com/kprompt/kprompt) — AI Kubernetes CLI

[![Release](https://img.shields.io/github/v/release/kprompt/kprompt?logo=github)](https://github.com/kprompt/kprompt/releases/latest)
[![Stars](https://img.shields.io/github/stars/kprompt/kprompt?style=flat&logo=github)](https://github.com/kprompt/kprompt/stargazers)
[![License](https://img.shields.io/badge/license-Apache--2.0-blue)](https://github.com/kprompt/kprompt/blob/main/LICENSE)

Natural language compiles into a **reviewable plan**; nothing mutates the cluster until you approve.

[kprompt.ai](https://kprompt.ai) · [Examples](https://github.com/kprompt/kprompt-examples) · [Discussions](https://github.com/kprompt/kprompt/discussions)

| Capability | What it does |
|------------|--------------|
| **Intent compiler** | English → typed plan (actions, risk, hard denies). Wipe-class prompts are refused. |
| **Plan before apply** | Interactive `y/N` or explicit `--approve` for mutate, Helm, and day-2 ops. |
| **Observe agent** | Namespace watch → incidents → gated Slack/webhook. Autopilot is propose-only; heuristic mode runs offline with zero LLM spend. |
| **Day-2 integrations** | Helm, Prometheus, OpenTelemetry, Grafana, and GitOps under one approval loop. Local BYOK — your kubeconfig and your LLM keys. |
| **CI-ready** | `--output json` PlanResult for automation gates. Providers: OpenAI, Anthropic, Gemini, Groq, Ollama. |

```bash
curl -fsSL https://kprompt.ai/install | bash
# brew install kprompt/tap/kprompt

kprompt "scale api to 10"                 # plan only
kprompt "scale api to 10" --approve
kprompt agent run -n payments --health --heuristic
```

Offline walkthrough (kind + deliberate failures, no API key): [kprompt-examples](https://github.com/kprompt/kprompt-examples)

---

## Apps

Independent iOS & Android apps — local-first, no ads, no account required.

| App | Platforms |
|-----|-----------|
| **[Don't Blink](https://apps.apple.com/app/dont-blink-tap-dont-tap/id6805209467)** — tap / don't tap reaction game | [App Store](https://apps.apple.com/app/dont-blink-tap-dont-tap/id6805209467) · [Google Play](https://play.google.com/store/apps/details?id=com.muhtalipdede.dontblink) |
| **[Swipe Merge Colors](https://apps.apple.com/app/swipe-merge-colors/id6806599894)** — color merge puzzle, no numbers | [App Store](https://apps.apple.com/app/swipe-merge-colors/id6806599894) · [Google Play](https://play.google.com/store/apps/details?id=com.muhtalipdede.mergecolors) |

Developer pages: [App Store](https://apps.apple.com/developer/muhtalip-dede/id1583166446) · [Google Play](https://play.google.com/store/apps/dev?id=6862159926694466208) · [Portfolio apps](https://muhtalipdede.github.io/apps)

---

## Academic & Innovation

- **ISIF 2020 Gold Medal** — thermal sensor–based healthtech innovation
- **Patent** — Contactless Temperature Monitoring System
- **TÜBİTAK 2209-A** research grant recipient
- **Innovation Awards** — Doğuş Teknoloji (2018, 2019)

---

## Community

Co-founder of **[The Coderverse](https://thecoderverse.com/)** — live coding on [YouTube](https://www.youtube.com/@thecoderverse), open-source collaboration, and tech talks for Turkish developers.

---

## Contact

- [Portfolio](https://muhtalipdede.github.io)
- [GitHub](https://github.com/muhtalipdede)
- [LinkedIn](https://www.linkedin.com/in/muhtalipdede/)
- [X](https://x.com/muhtalipdede)
- [Medium](https://muhtalipdede.medium.com/)
- [App Store](https://apps.apple.com/developer/muhtalip-dede/id1583166446)
- [Google Play](https://play.google.com/store/apps/dev?id=6862159926694466208)
- [coppergate.ai](https://coppergate.ai) · [Org](https://github.com/coppergateai)
- [kprompt.ai](https://kprompt.ai) · [Org](https://github.com/kprompt)
- [The Coderverse](https://thecoderverse.com/) · [YouTube](https://www.youtube.com/@thecoderverse)
- [Repositories](https://github.com/muhtalipdede?tab=repositories)

---

> “Empty your mind, be formless, shapeless, like water… Be water, my friend.”
