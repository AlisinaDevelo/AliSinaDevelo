# Alisina Karimi

Software engineer in Turin, Italy.

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=24&pause=900&color=A78BFA&center=true&vCenter=true&width=640&height=50&lines=Go+%C2%B7+systems+%C2%B7+data+%C2%B7+tools;I+read+the+logs;I+measure+the+slow+path;PostgreSQL+%C2%B7+queues+%C2%B7+integrations;agents+%C2%B7+security+%C2%B7+privacy)](https://alisinadevelo.github.io)

</div>

I work on backend systems and the things around them: data migrations, queues, third-party integrations, observability, and the failure cases that show up after launch.

At work I build and operate Go services, PostgreSQL infrastructure, AWS deployments, and commerce integrations for an Australia-based company. Outside work I build smaller systems to understand protocols, model serving, agent tooling, and security.

[Portfolio](https://alisinadevelo.github.io) · [LinkedIn](https://www.linkedin.com/in/alisina-karimi-43a834224/) · [Email](mailto:alisinakarimi.2003@gmail.com) · [CV](https://github.com/AliSinaDevelo/AliSinaDevelo/raw/main/cv/AlisinaKarimi-CV.pdf)

I work from Turin and regularly collaborate across European, US, and Australian time zones.

```go
package main

type Workbench struct {
    Now       string
    Questions []string
}

func main() {
    _ = Workbench{
        Now: "shipping Go services and untangling production systems",
        Questions: []string{
            "where did the latency go?",
            "what happens when this dependency is down?",
            "can the next person operate it?",
        },
    }
}
```

## Now

- Go services for analytics, billing, asynchronous workflows, and commerce integrations.
- A MariaDB to PostgreSQL migration that improved critical query performance by 3x to 10x and reduced infrastructure cost by about 60%.
- AWS infrastructure with Terraform and Packer, Valkey-backed sessions, SQS workers, health checks, and repeatable deployments.
- Open-source contributions across pgx, Valkey, golang-migrate, and Zed.

## Selected work

- [**StreamHive**](https://github.com/AliSinaDevelo/StreamHive): a Go library for content-addressed storage over TCP/TLS, with framing, peer identity, replication, repair, durable stores, and metrics.
- [**news-api**](https://github.com/AliSinaDevelo/news-api): a TypeScript and Express service where caching, upstream failures, request coalescing, OpenAPI, telemetry, and deployment are part of the design.
- [**Chatster**](https://github.com/AliSinaDevelo/Chatster): a small real-time chat system in Go, with WebSockets, SQLite history, bounded client queues, rate limits, metrics, and a measured load test.
- [**Quorabust**](https://github.com/AliSinaDevelo/Quorabust): a Python duplicate-detection service that carries a model through training, calibration, lineage, serving, drift checks, and load testing.
- [**Forge**](https://github.com/AliSinaDevelo/md-files): an installable Claude Code toolkit with agents, skills, commands, policy hooks, and evaluation tools.

I also keep private work around security-agent workflows, detection replay, evidence handling, post-quantum transport, network measurement, federated learning, privacy accounting, MPC, and traffic analysis. Most of it stays private until there is a result worth showing.

## Tools

Go · Python · TypeScript · PHP · Rust · SQL

PostgreSQL · Redis/Valkey · SQLite · AWS · Terraform · Docker · Kubernetes · Prometheus · OpenTelemetry

The repositories above are a better description of how I work than a complete list of technologies I have touched.
