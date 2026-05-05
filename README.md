<!--
This markdown file can be previewed in VS Code by pressing Ctrl+Shift+V.
-->

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.svg">
    <img src="assets/logo.svg" alt="Ioannis Theodosiadis" width="160">
  </picture>
</p>

<h1 align="center">Software &amp; Systems &mdash; architect and engineer</h1>
<p align="center"><em>security &middot; deployment &middot; open source</em></p>

I pick architectures on purpose. Security and privacy are the floor, not a feature. I prefer open source, self-hosted, and decisions I can defend.

## What I'm building

- **[budget-lens](https://github.com/1oannis/budget-lens)** &mdash; a self-hosted receipt scanner and expense tracker. Financial records shouldn't live on someone else's analytics pipeline.
- **[camunda-compose](https://github.com/1oannis/camunda-compose)** &mdash; full Camunda 8 Self-Managed stack (Web Modeler, backups, the lot) you bring up with one `docker compose up`. Workflow engines shouldn't require a sales call.
- **[EDPO-Project-FS26](https://github.com/cyrilgabriele/EDPO-Project-FS26)** &mdash; event-driven crypto-portfolio platform on Kafka + Spring Boot. Data Integrity, availability and fault tolerance as driving non-functional properties.
- **[homepage](https://github.com/1oannis/homepage)** &mdash; the code behind [1oannis.com](https://1oannis.com).

## What I'm thinking about

Privacy-preserving computation on fuzzy records. SSO architectures in workflow-heavy environments. The information-disorder side of AI in public discourse. Writing thesis-quality systems that stay maintainable after the deadline.

## Decisions I'm willing to defend

> **Postgres over MongoDB** &mdash; unless the data is genuinely document-shaped.
>
> **Keycloak over rolling-your-own auth** &mdash; identity is the boring part you have to get right.
>
> **Docker Compose over Kubernetes** &mdash; until cardinality actually demands otherwise.
>
> **Self-hosted over SaaS** &mdash; where the data is mine.
>
> **Open source over closed** &mdash; unless there's a defensible reason, and "we already pay for it" isn't one.

## Stack &amp; tools

I pick by workload, not by category.

| When | I reach for | Why |
| --- | --- | --- |
| services | Spring Boot &middot; FastAPI | conservative on JVM, fast iteration in Python |
| events | Kafka | persistence and replay built in |
| UI | Next.js &middot; Svelte &middot; Tailwind | static-first, server-only when it matters |
| deploy glue | Ansible &middot; Caddy | reproducible provisioning, TLS without surprises |
| research | Python &middot; PyTorch &middot; Jupyter | optimized for the question, not the deploy |
| simulation | NetLogo | when the system *is* the question |
| writing | Typst | over Word, every time |

Comfortable in Java, Kotlin, Python, TypeScript, C++.

## OSS shoulders I stand on

These shape how I build, not just what I import.

- [Keycloak](https://github.com/keycloak/keycloak) &mdash; IAM done right
- [Camunda](https://github.com/camunda/camunda) &mdash; open BPMN engine
- [Nextcloud](https://github.com/nextcloud/server) &mdash; proof that self-hosted can be a daily driver
- [Postgres](https://www.postgresql.org/) &mdash; the boring database that keeps winning
- [Caddy](https://github.com/caddyserver/caddy) &mdash; TLS by default
- [Ansible](https://github.com/ansible/ansible) &mdash; infra as code without a runtime

## Elsewhere

[1oannis.com](https://1oannis.com) &middot; [LinkedIn](https://www.linkedin.com/in/ioannis-theodosiadis)
