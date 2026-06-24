<!-- Profile README — AliSinaDevelo -->

<div align="center">

# Alisina Karimi

**Software engineer with a systems bias: backend services, data paths, infrastructure, and AI/security tooling.**

[Portfolio](https://alisinadevelo.github.io) ·
[GitHub](https://github.com/AliSinaDevelo) ·
[LinkedIn](https://www.linkedin.com/in/alisina-karimi/) ·
[CV](https://github.com/AliSinaDevelo/AliSinaDevelo/raw/main/cv/AlisinaKarimi-CV.pdf)

Turin, Italy · remote across time zones · currently shipping production systems remotely for an Australia-based commerce company

</div>

```text
alisina@workbench
├─ current: remote production systems for commerce, analytics, billing, and integrations
├─ range: backend services · infra automation · data-heavy products · agent/tooling systems
├─ bias: simple contracts, measured performance, observable failure modes
└─ proof: public repos with tests, docs, containers, metrics, and trade-offs
```

I like the unglamorous parts of software: the query path that stops timing out, the
worker that can be restarted safely, the integration that fails loudly instead of
silently, the README that tells the next engineer what is actually true.

## How To Read The Work

The pinned repos are the entry points. The more interesting part is the pattern across
them:

| Signal | Where it shows up |
|---|---|
| **Production ownership** | Current work: PostgreSQL migration, AWS scaling, Terraform/Packer, CI/CD, BI/reporting, third-party commerce and compliance integrations. |
| **Realtime systems** | Chatster: concurrent WebSocket hub, serialized writes, replay, abuse controls, health checks, metrics, and load-test proof. |
| **API/platform taste** | news-api: validation, caching, upstream timeouts, API keys, OpenAPI, Redis, OpenTelemetry, K8s probes, Docker, SBOM-minded CI. |
| **Systems engineering** | StreamHive: TCP/TLS transport, SHV1 framing, content-addressed storage boundary, connection limits, liveness/readiness/metrics. |
| **AI engineering** | Forge / md-files: specialist agents, progressive-disclosure skills, slash commands, safety hooks, prompt evals, and plugin packaging. |
| **Security depth** | SignalForge: private cross-LLM security lab with adapters, detection replay, scope-aware hooks, DFIR/RE workflows, and evals. |

## Current Frequency

```text
programming       Go · PHP · Python · TypeScript/JavaScript · SQL · C · Java
backend/web       Symfony · Laravel · Express · Django · FastAPI · Gin · REST/OpenAPI · WebSockets · GraphQL
cloud/platform    AWS EC2/ASG/ALB/SQS/ElastiCache/Lambda · Terraform · Packer · Docker · Kubernetes · Linux
data/cache        PostgreSQL · MariaDB/MySQL · SQLite · MongoDB · Redis/Valkey · migrations · query tuning
observability     Prometheus · Grafana · OpenTelemetry · CloudWatch · structured logs · health/readiness probes
delivery          GitHub Actions · rolling deploys · AMIs · Docker Compose · SBOMs · dependency review · release hygiene
ai/tooling        agents · prompt systems · eval harnesses · Claude Code plugins · local model workflows
security          SignalForge · scope-aware hooks · detection replay · DFIR/RE workflows · defensive automation
product surface   React · Vue · dashboards · admin tools · docs that explain the operational contract
```

## Project Notes

**Chatster** is the most direct "can ship backend code" repo. It is small enough to
inspect quickly, but it has the production-adjacent details I care about: graceful
shutdown, health checks, rate limits, logs, metrics, tests, and explicit non-goals.

**StreamHive** is where I play closer to the wire: custom framing, transport concerns,
connection limits, and a clean storage boundary before pretending global replication is
solved.

**news-api** is deliberately ordinary in the best way: an HTTP service with validation,
timeouts, caching, API-key support, observability, Docker, Kubernetes manifests, and CI
that treats the supply chain as part of the product.

**Forge** is my AI-engineering workbench: agents, skills, commands, hooks, and evals
packaged as something installable instead of a pile of prompts in a folder.

**SignalForge** is Forge's larger, private sibling: a cross-LLM security lab with specialist
agents, methodology skills, executable adapters, detection replay, and scope-aware safety
hooks for defensive, DFIR, and reverse-engineering work. Walkthrough available on request.

## Operating Style

- I prefer small, inspectable systems over clever ones.
- I write docs close to the code and keep them honest.
- I treat observability, deployability, and failure behavior as features.
- I like remote work when ownership is clear and the async trail is good.
- Work setup: Italy-based, EU invoicing / EOR friendly, no relocation sponsorship sought.

<div align="center">

```text
read the code · measure first · keep the contract sharp · leave the system easier to run
```

</div>
