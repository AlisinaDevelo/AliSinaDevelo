<!-- Profile README — AliSinaDevelo -->

<div align="center">

# Alisina Karimi

**Backend / platform engineer building systems that survive production.**

[Portfolio](https://alisinadevelo.github.io) ·
[GitHub](https://github.com/AliSinaDevelo) ·
[LinkedIn](https://www.linkedin.com/in/alisina-karimi/) ·
[CV](https://github.com/AliSinaDevelo/AliSinaDevelo/raw/main/cv/AlisinaKarimi-CV.pdf)

Turin, Italy · remote across time zones

</div>

```text
alisina@workbench
├─ current: Go services, PostgreSQL migrations, AWS platform work
├─ usually: APIs, data paths, queues, observability, CI/CD
├─ bias: simple systems, explicit contracts, boring reliability
└─ proof: public repos with tests, docs, containers, metrics, and trade-offs
```

I like the unglamorous parts of software: the query path that stops timing out, the
worker that can be restarted safely, the integration that fails loudly instead of
silently, the README that tells the next engineer what is actually true.

## Start Here

| Repo | What to look for |
|---|---|
| [**Chatster**](https://github.com/AliSinaDevelo/Chatster) | Real-time backend surface: Go WebSocket hub, safe concurrent writes, SQLite replay, abuse controls, Prometheus metrics, ops docs. |
| [**news-api**](https://github.com/AliSinaDevelo/news-api) | Production API shape: TypeScript, Express, Redis cache, OpenAPI, rate limits, OpenTelemetry, K8s probes, SBOM/provenance-minded CI. |
| [**StreamHive**](https://github.com/AliSinaDevelo/StreamHive) | Systems lane: Go TCP/TLS transport, SHV1 framing, content-addressed storage interface, health endpoints, pinned-action CI. |
| [**Forge / md-files**](https://github.com/AliSinaDevelo/md-files) | AI devtools: installable Claude Code toolkit with specialist agents, skills, commands, safety hooks, prompt evals, and hook tests. |

## Current Frequency

```text
backend        Go · PHP/Symfony · TypeScript/Node · Python
data           PostgreSQL · MariaDB/MySQL · SQLite · Redis/Valkey
platform       AWS · Terraform · Packer · Docker · Kubernetes · GitHub Actions
signals        Prometheus · Grafana · OpenTelemetry · structured logs
ai tooling     agents · prompt systems · eval harnesses · local model workflows
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

## Operating Style

- I prefer small, inspectable systems over clever ones.
- I write docs close to the code and keep them honest.
- I treat observability, deployability, and failure behavior as features.
- I like remote work when ownership is clear and the async trail is good.

<div align="center">

```text
read the code · measure first · keep the contract sharp · leave the system easier to run
```

</div>
