# Alisina Karimi

Turin, Italy.

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=24&pause=900&color=A78BFA&center=true&vCenter=true&width=640&height=50&lines=Go+%C2%B7+systems+%C2%B7+data+%C2%B7+tools;I+read+the+logs;I+measure+the+slow+path;PostgreSQL+%C2%B7+queues+%C2%B7+integrations;agents+%C2%B7+security+%C2%B7+privacy)](https://alisinadevelo.github.io)

</div>

I build things to find out what happens at the edges: when a dependency is slow, a peer
disappears, a source file moves, a model changes, or a result needs to be explained later.

The repositories are the point. The short version is below; the details live in tests, fixtures,
benchmarks, and docs.

[Portfolio](https://alisinadevelo.github.io) · [Email](mailto:alisinakarimi.2003@gmail.com) · [LinkedIn](https://www.linkedin.com/in/alisina-karimi-43a834224/)

```go
package main

type Workbench struct {
    Current   string
    Questions []string
}

func main() {
    _ = Workbench{
        Current: "Go services, Rust experiments, and tools for reading systems",
        Questions: []string{
            "where did the latency go?",
            "what happens when this dependency is down?",
            "can the next person explain the result?",
        },
    }
}
```

## GitHub snapshot

<!-- STATS:START -->
`4,655` contributions in the last year · `33` original public repositories · `31` stars across them · `53` followers
<!-- STATS:END -->

<sub>Updated weekly from GitHub's API. A profile snapshot, not a performance claim.</sub>

## The shelf

### Working systems

- [**StreamHive**](https://github.com/AliSinaDevelo/StreamHive): Go content-addressed storage over TCP/TLS, with framing, peer identity, replication, repair, durable stores, and metrics.
- [**Chatster**](https://github.com/AliSinaDevelo/Chatster): a real-time Go WebSocket system with SQLite history, bounded client queues, rate limits, metrics, and a React client.
- [**news-api**](https://github.com/AliSinaDevelo/news-api): a TypeScript/Express service built around caching, upstream failures, request coalescing, OpenAPI, telemetry, and deployment.
- [**Quorabust**](https://github.com/AliSinaDevelo/Quorabust): a Python duplicate-detection service that carries a model from training through serving, lineage, drift checks, and load testing.
- [**Forge**](https://github.com/AliSinaDevelo/md-files): an installable Claude Code and Codex toolkit made of agents, skills, commands, policy hooks, and evals.

### Newer tools

- [**LOOM**](https://github.com/AliSinaDevelo/LOOM) · pre-alpha: local-first Rust/Tauri retrieval over text and Markdown, with SQLite FTS5, BLAKE3 hashes, and exact source anchors.
- [**CARTOGRAPH**](https://github.com/AliSinaDevelo/CARTOGRAPH) · pre-alpha: a compiler-backed TypeScript architecture analyzer with deterministic graph snapshots, semantic Git diffs, evidence-linked reports, and policy boundaries.
- [**GHOSTRACE**](https://github.com/AliSinaDevelo/GHOSTRACE) · fixture-only: a local macOS causal event journal with explicit gaps, bounded provenance, and evidence-backed explanations.

## A few receipts

The useful numbers are in behavior, outcomes, and shipped scope:

- **Work:** a MariaDB to PostgreSQL migration improved critical query performance by 3x to 10x and reduced infrastructure cost by about 60%.
- **Chatster:** the local fan-out harness delivered every message at 25 and 50 concurrent clients; p99 delivery latency was 5.7 ms and 57 ms respectively.
- **LOOM:** the synthetic retrieval fixture recovered all 3 expected sources at rank one with anchor precision 1.0.
- **StreamHive:** a 3-node Compose acceptance demo converges after durable restart and repairs a deleted blob through anti-entropy.
- **Forge:** 20 agents, 25 skills, and 22 commands packaged for Claude Code, Codex, and OpenCode, with policy hooks around the dangerous edges.

These are tied to a documented fixture, demo, or migration context; they are not promises about every environment.

## Private shelf

I also work on private research around agent security, detection replay, evidence handling,
post-quantum transport, network measurement, federated learning, privacy accounting, MPC, and
traffic analysis. The names stay private until there is a result worth publishing.

I contribute to open source when the problem is concrete, including work around Go, databases,
migration tooling, and developer tools.

## Tools I touch

Go · Rust · Python · TypeScript · PHP · SQL

PostgreSQL · SQLite · Redis/Valkey · AWS · Terraform · Docker · Kubernetes · Prometheus · OpenTelemetry

The list is intentionally incomplete. The repositories are a better description of how I work.
