<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:172554,100:0f766e&height=220&section=header&text=LECODEV&fontSize=64&fontColor=ffffff&fontAlignY=36&desc=AI%20Infrastructure%20%7C%20Systems%20%7C%20Security%20%7C%20Developer%20Tools&descAlignY=61&descSize=18&descColor=cbd5e1&animation=fadeIn" />

# lecodev-26

**I build systems around AI — gateways, agents, security engines, developer tools and infrastructure.**

<a href="https://github.com/lecodev-26">
<img src="https://img.shields.io/badge/GitHub-lecodev--26-0f172a?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="mailto:lecodevv@gmail.com">
<img src="https://img.shields.io/badge/Contact-Email-0f766e?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<br><br>

<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
<img src="https://img.shields.io/badge/Rust-DEA584?style=flat-square&logo=rust&logoColor=111827" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=111827" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Termux-000000?style=flat-square&logo=termux&logoColor=white" />

<br><br>

<img src="https://komarev.com/ghpvc/?username=lecodev-26&style=flat-square&color=0f766e&label=PROFILE+VIEWS" />

</div>

---

## ⚡ What I actually build

I like the layer **between software and infrastructure** — the part that makes systems useful, controllable and resilient.

My current work revolves around:

- **AI gateways & LLM infrastructure**
- **Agents, memory and tool execution**
- **Security & cryptographic systems**
- **Backend and distributed infrastructure**
- **Local-first / self-hosted software**
- **Developer tooling and MCP**
- **Systems experiments on Linux / Android / Termux**

I prefer building the machinery behind the product rather than another thin wrapper around an API.

---

## 🚀 Projects

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ SentinelFlow

**AI Gateway / LLM Control Plane**

OpenAI-compatible infrastructure for multi-provider AI systems.

Routing, provider failover, policy enforcement, AI FinOps, security, observability, tenants, quotas and event processing.

**Go · PostgreSQL · Redis · Docker · Kubernetes**

<a href="https://github.com/lecodev-26/sentinelflow">
<img src="https://img.shields.io/badge/EXPLORE-0f766e?style=for-the-badge&logo=github&logoColor=white" />
</a>

</td>
<td width="50%" valign="top">

### 🧠 Cerebro Zero

**Cognitive AI / Model Runtime**

An open-source cognitive AI platform built around a unified runtime, memory, planning, tools, security, APIs and a reproducible path toward its own trained language model.

**Python · NumPy · Transformers · RL · Termux**

<a href="https://github.com/lecodev-26/cerebro-zero">
<img src="https://img.shields.io/badge/EXPLORE-2563eb?style=for-the-badge&logo=github&logoColor=white" />
</a>

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🔐 NEXUS-Q

**Post-Quantum Security Engine**

Rust-based security infrastructure for protecting data, keys and identities, with key lifecycle management, authenticated encryption, credentials, audit trails, policy enforcement and hardware abstraction.

**Rust · PQC · Crypto · RISC-V · Android**

<a href="https://github.com/lecodev-26/nexus-q">
<img src="https://img.shields.io/badge/EXPLORE-7c3aed?style=for-the-badge&logo=github&logoColor=white" />
</a>

</td>
<td width="50%" valign="top">

### 🧞 Genie

**AI Skill + MCP**

A lightweight Akinator-style AI skill that uses adaptive questioning to identify whatever the player is thinking about.

It also includes a minimal remote MCP server for compatible AI clients.

**Markdown · TypeScript · MCP**

<a href="https://github.com/lecodev-26/genie">
<img src="https://img.shields.io/badge/EXPLORE-d97706?style=for-the-badge&logo=github&logoColor=white" />
</a>

</td>
</tr>

<tr>
<td width="50%" valign="top">

### ⚙️ AXIOM

**Universal Programming Language & Systems Ecosystem**

A general-purpose programming language and technology ecosystem built around a small visible syntax and a deep semantic model, with a long-term path toward its own compiler, runtime, ABI and self-hosting toolchain.

**Python · Rust · Compiler · Runtime · Systems**

<a href="https://github.com/lecodev-26/axiom">
<img src="https://img.shields.io/badge/EXPLORE-0f766e?style=for-the-badge&logo=github&logoColor=white" />
</a>

</td>
</tr>
</table>

---

## 🧪 Other work

### 🌩️ Nuvora

An experimental project in the portfolio. Kept deliberately lightweight here while the implementation evolves.

<a href="https://github.com/lecodev-26/nuvora"><img src="https://img.shields.io/badge/VIEW%20REPO-334155?style=for-the-badge&logo=github&logoColor=white" /></a>

### 📡 Arc

I also contribute to **Arc**, an open SQL-native time-series database focused on high-throughput telemetry, Parquet storage and analytical SQL.

<a href="https://github.com/Basekick-Labs/arc"><img src="https://img.shields.io/badge/ARC-BASEKICK%20LABS-0f172a?style=for-the-badge&logo=github&logoColor=white" /></a>

---

## 🧩 How the projects connect

```text
                         AI SYSTEMS
                              │
          ┌───────────────────┼───────────────────┐
          │                   │                   │
          ▼                   ▼                   ▼
   SentinelFlow          Cerebro Zero          Genie
   LLM gateway           Cognitive AI          MCP / Skill
          │                   │                   │
          └───────────────────┼───────────────────┘
                              │
                              ▼
                    Systems & Security
                              │
                    ┌─────────┴─────────┐
                    ▼                   ▼
                 NEXUS-Q              Arc
              crypto / identity    telemetry / data
```

The common thread is simple:

> **Build the infrastructure that lets software do more — without hiding the engineering underneath.**

---

## 🛠️ Stack

| Area | Tools |
|---|---|
| **Languages** | Go · Rust · Python · TypeScript · SQL |
| **AI** | LLMs · Agents · Transformers · RAG · Memory · Reinforcement Learning |
| **Backend** | HTTP · REST · APIs · PostgreSQL · Redis |
| **Infrastructure** | Docker · Kubernetes · CI/CD · Observability |
| **Security** | Post-quantum cryptography · Key management · Policy · Audit |
| **Systems** | Linux · Android · Termux · RISC-V · self-hosting |
| **AI tooling** | MCP · SDKs · developer tooling |

---

## 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/lecodev-26/lecodev-26/gh-pages/github-contribution-grid-snake-dark.svg" width="95%" alt="GitHub contribution snake" />

---

## 🧭 What I'm Interested In

```text
AI Infrastructure
│
├── LLM Gateways
├── Provider Routing & Failover
├── Rate Limiting & Resilience
├── Caching & Streaming
├── Observability
│
├── Agent Systems
│   ├── Tool Use
│   ├── Memory
│   ├── Planning & Reasoning
│   └── Local-First Execution
│
├── Machine Learning From Scratch
│   ├── Autograd
│   ├── Transformers
│   ├── Embeddings
│   └── Reinforcement Learning
│
└── Systems Engineering
    ├── Rust & C
    ├── Microkernels & IPC
    ├── Android / Termux
    └── Developer Tooling
```

---

## 🤝 Open to

**AI infrastructure · systems engineering · security · backend architecture · developer tooling · interesting open-source projects**

If you're building something technically ambitious, I'm interested.

<div align="center">

<a href="mailto:lecodevv@gmail.com">
<img src="https://img.shields.io/badge/EMAIL-Contact%20me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

&nbsp;

<a href="https://github.com/lecodev-26?tab=repositories">
<img src="https://img.shields.io/badge/ALL%20REPOSITORIES-0f172a?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br><br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:172554,100:0f766e&height=130&section=footer" />

</div>
