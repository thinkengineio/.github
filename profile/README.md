<p align="center">
  <img src="https://raw.githubusercontent.com/thinkengineio/.github/main/profile/thinkengine-logo.png" alt="ThinkEngine" width="160" />
</p>

<h2 align="center">AI-Powered Security Operations Platform</h2>

<p align="center">
  <a href="https://thinkengine.io">Platform</a> &nbsp;·&nbsp;
  <a href="https://docs.thinkengine.io">Docs</a> &nbsp;·&nbsp;
  <a href="https://sleuthgraph.io">Sleuthgraph</a>
</p>

---

### What We Build

**ThinkEngine** is a security operations platform that pairs AI-driven triage and remediation with endpoint monitoring, vulnerability scanning, and dynamic application security testing.

| Product | Description |
|---------|-------------|
| **ThinkEngine Platform** | Multi-tenant SecOps dashboard — correlation engine, GRC (risks, evidence, controls), threat intel, real-time AI chat with Sofia, credential vault, cost tracking. |
| **Sentinel** | Endpoint security agent (Go). 12 modules — CIS hardening, vulnerability scanning, file integrity, network analysis, auth audit, container audit, threat detection, secrets scanning, MITRE ATT&CK simulation (19 techniques). |
| **Darius** | Dynamic Application Security Testing scanner (Go). Web app fuzzing, authenticated crawling, HTML reporting — single binary, no external dependencies. |
| **Sleuthgraph** | Open-source attack-surface mapping and reconnaissance toolkit. [sleuthgraph.io](https://sleuthgraph.io) |

---

### Key Repositories

| Repo | Stack | Description |
|------|-------|-------------|
| [`agent-orchestrator`](https://github.com/thinkengineio/agent-orchestrator) | Python · Next.js · PostgreSQL · Redis | Core platform — AI agents, dashboard API, web UI |
| [`sentinel-maas`](https://github.com/thinkengineio/sentinel-maas) | Go | Endpoint agent — 12 security modules, cross-platform |
| [`darius`](https://github.com/thinkengineio/darius) | Go | DAST scanner — single binary, embedded engine |
| [`docs`](https://github.com/thinkengineio/docs) | TypeScript | Documentation site — [docs.thinkengine.io](https://docs.thinkengine.io) |

---

### Platform at a Glance

```
12 security modules           19 MITRE ATT&CK techniques      4 tiers (Free / Pro / Pro Max / Enterprise)
Multi-layer auth chain        AES-256-GCM tenant encryption   AI remediation workflows
Real-time Sofia AI chat       DAST + endpoint scanning        Homebrew tap distribution
```

---

### Tech Stack

`Python` · `Go` · `TypeScript` · `Next.js 15` · `React 19` · `PostgreSQL 16` · `Redis 7` · `Docker` · `Terraform` · `OCI` · `Cloudflare` · `Auth0`

---

### Security

See our [Security Policy](https://github.com/thinkengineio/agent-orchestrator/blob/main/SECURITY.md) for vulnerability reporting.

**License:** [Business Source License 1.1](https://github.com/thinkengineio/agent-orchestrator/blob/main/LICENSE) — converts to Apache 2.0 after 4 years.

<p align="center">
  <sub>2026 ThinkEngine.io</sub>
</p>
