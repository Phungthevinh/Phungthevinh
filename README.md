<div align="center">

<!-- HEADER -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:1a1a2e,100:16213e&height=220&section=header&text=Phung%20The%20Vinh&fontSize=48&fontColor=e0e0e0&animation=fadeIn&fontAlignY=35&desc=Systems%20Engineer%20%7C%20Rust%20%7C%20Security%20%7C%20AI&descSize=18&descAlignY=55&descColor=8892b0" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono\&weight=600\&size=22\&duration=3000\&pause=1000\&color=64FFDA\&center=true\&vCenter=true\&multiline=true\&repeat=true\&width=750\&height=80\&lines=Building+reliable+systems+with+Rust+%E2%9A%A1;Systems+%7C+Security+%7C+AI+%7C+Real-Time+Engineering)](https://github.com/Phungthevinh)

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-Phungthevinh-181717?style=for-the-badge\&logo=github)](https://github.com/Phungthevinh)
[![Rust](https://img.shields.io/badge/Rust-Systems%20Programming-000000?style=for-the-badge\&logo=rust\&logoColor=white)](https://www.rust-lang.org/)
[![Security](https://img.shields.io/badge/Security-Zero%20Trust-16213e?style=for-the-badge\&logo=letsencrypt\&logoColor=white)](#)
[![AI](https://img.shields.io/badge/AI%2FML-Systems-1a1a2e?style=for-the-badge\&logo=openai\&logoColor=white)](#)

</div>

---

## 🧬 About Me

```rust
struct Engineer {
    name: &'static str,
    role: &'static str,
    focus: Vec<&'static str>,
    philosophy: &'static str,
}

const VINH: Engineer = Engineer {
    name: "Phùng Thế Vinh",
    role: "Systems & AI-Native Software Engineer",
    focus: vec![
        "High-Performance Backend Systems",
        "Real-Time Data Processing",
        "Zero-Trust Security",
        "AI/ML Infrastructure",
    ],
    philosophy: "Build systems that are reliable, observable, and designed to fail safely.",
};
```

I am a software engineer focused on **Rust, backend systems, security infrastructure, and AI-integrated applications**.

My projects are centered around problems where architecture matters:

* ⚡ **Performance** — low-latency and concurrent systems
* 🧩 **Architecture** — modular, event-driven and maintainable services
* 🔐 **Security** — identity, authentication and Zero-Trust principles
* 🤖 **AI/ML** — integrating intelligent decision systems into production-oriented software
* 📊 **Real-Time Systems** — streaming data, state management and event processing
* 🛡️ **Reliability** — observability, recovery, validation and deterministic behavior

---

## 🛠️ Tech Stack

<div align="center">

| Domain            | Technologies                                                                                                                                                                                                                                                                                                                                                                                                                |
| :---------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Languages**     | ![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge\&logo=rust\&logoColor=white) ![C%23](https://img.shields.io/badge/C%23-239120?style=for-the-badge\&logo=csharp\&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge\&logo=dart\&logoColor=white) |
| **Backend**       | ![Axum](https://img.shields.io/badge/Axum-Rust-E6522C?style=for-the-badge\&logo=rust\&logoColor=white) ![Tokio](https://img.shields.io/badge/Tokio-Async%20Runtime-FF7200?style=for-the-badge\&logo=rust\&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge\&logo=dotnet\&logoColor=white)                                                                                              |
| **Concurrency**   | `Tokio` · `DashMap` · `Arc` · `RwLock` · `Async Channels`                                                                                                                                                                                                                                                                                                                                                                   |
| **Databases**     | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge\&logo=postgresql\&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge\&logo=redis\&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge\&logo=microsoftsqlserver\&logoColor=white)                                                                      |
| **Security**      | `Zero-Trust` · `Ed25519` · `AES-256-GCM` · `JWT` · `mTLS`                                                                                                                                                                                                                                                                                                                                                                   |
| **AI / ML**       | `SmartCore` · `Random Forest` · `ONNX` · `NLP` · `Semantic Search`                                                                                                                                                                                                                                                                                                                                                          |
| **Messaging**     | `Telegram` · `Teloxide` · `WebSocket` · `Tokio mpsc/broadcast`                                                                                                                                                                                                                                                                                                                                                              |
| **DevOps**        | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge\&logo=githubactions\&logoColor=white)                                                                                                                                                                                    |
| **Observability** | `tracing` · `Structured Logging` · `Health Checks` · `Metrics`                                                                                                                                                                                                                                                                                                                                                              |

</div>

---

# 🚀 Featured Projects

<table>
<tr>

<td width="50%" valign="top">

## 📈 [VN30 Real-Time Analyzer](https://github.com/Phungthevinh/bot_vn30)

<sup>🦀 Rust · 📊 Machine Learning · ⚡ Tokio · 🧠 SmartCore · 📡 WebSocket</sup>

A **real-time market analysis system for the VN30 basket**, designed entirely in Rust.

The system processes market data through an event-driven pipeline:

```text
Market Data
     ↓
Normalization
     ↓
State Store
     ↓
Technical Indicators
     ↓
Feature Engineering
     ↓
Machine Learning
     ↓
Risk Engine
     ↓
Signal State Machine
     ↓
Telegram Alerts
```

### Highlights

* 🦀 **100% Rust production engine**
* ⚡ Async event-driven architecture with Tokio
* 🧠 Random Forest inference using SmartCore
* 📊 RSI, MACD, Bollinger Bands, ATR, Beta and return features
* 🧮 Real-time feature extraction
* 🗃️ In-memory state management with DashMap
* 🛡️ Deterministic risk-gating rules
* 🔄 Signal lifecycle state machine
* 📡 Telegram alerts through Teloxide
* ♻️ WebSocket reconnect with exponential backoff + jitter
* 🔍 Model/config/version metadata for auditability
* 🚫 **No automatic order execution**

> Built as a research-oriented real-time analysis platform rather than an autonomous trading system.

</td>

<td width="50%" valign="top">

## 🛡️ [Zero Trust Gateway](https://github.com/Phungthevinh/zero_trust_gateway)

<sup>🦀 Rust · ⚡ Axum · 🔒 Zero-Trust · 🧠 AI</sup>

A Rust-based API security gateway exploring **Zero-Trust architecture, cryptographic identity and intelligent request processing**.

### Highlights

* 🔐 Zero-Trust request validation
* 🔑 Ed25519-based cryptographic identity
* ⚡ Axum + Tokio asynchronous architecture
* 🧠 Semantic caching concepts
* 📊 Vector similarity search
* 🛡️ Authentication and security middleware
* 📈 Low-latency request processing
* 🧩 Modular gateway architecture

> Researching how security and intelligent infrastructure can coexist without sacrificing system performance.

</td>

</tr>

<tr>

<td width="50%" valign="top">

# 🧠 Engineering Interests

```text
                    SOFTWARE ENGINEERING
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
      SYSTEMS          SECURITY            AI/ML
          │                │                │
     ┌────┴────┐      ┌────┴────┐      ┌────┴────┐
     │         │      │         │      │         │
   Rust     Async   Zero-Trust Crypto  Models  Features
     │         │      │         │      │         │
     └────┬────┘      └────┬────┘      └────┬────┘
          │                │                │
          └────────────────┼────────────────┘
                           ▼
                  REAL-TIME SYSTEMS
                           │
                           ▼
                 Reliable Infrastructure
```

I'm particularly interested in:

* 🦀 Rust systems programming
* ⚡ High-concurrency backend architecture
* 📡 Real-time data pipelines
* 🔐 Zero-Trust infrastructure
* 🧠 AI-native software architecture
* 📊 Machine learning systems
* ♻️ Fault tolerance & self-healing systems
* 🔎 Observability and deterministic execution
* 🧮 Low-latency state management

---

# 🗺️ Engineering Journey

```text
2024                  2025                  2026                  Future
 │                     │                     │                       │
 ▼                     ▼                     ▼                       ▼
.NET / Web        Backend Systems       Rust Systems          AI + Systems
 │                     │                     │                       │
 │                     ▼                     ▼                       │
 │                API Architecture     Zero-Trust Gateway          │
 │                                           │                       │
 ▼                                           ▼                       ▼
Enterprise ───────────────────────────► Security ───────────► Intelligent
 Backend                                  Infrastructure        Systems
                                                                     │
                                                                     ▼
                                                            Production-grade
                                                              AI Systems
```

---

# 🔬 Current Focus

### 01 — Rust Systems Engineering

Building deeper expertise in:

```text
Tokio
 ├── Async Runtime
 ├── Channels
 ├── Task Scheduling
 └── Concurrent Services

DashMap
 ├── Concurrent State
 ├── Lock Contention
 └── High-frequency Reads/Writes

Rust
 ├── Ownership
 ├── Lifetimes
 ├── Concurrency
 └── Zero-Cost Abstractions
```

### 02 — Real-Time Market Systems

The `bot_vn30` project is currently an important research direction around:

```text
Market Data
    ↓
Streaming State
    ↓
Feature Engineering
    ↓
Machine Learning
    ↓
Risk Management
    ↓
Signal Generation
    ↓
Observability
```

The focus is on **engineering the system correctly**: data integrity, deterministic behavior, concurrency, model lifecycle, failure handling and auditability.

### 03 — Security Infrastructure

Exploring how Zero-Trust principles can be implemented at the infrastructure level through:

* cryptographic identities
* request authentication
* service-to-service trust
* policy enforcement
* secure API gateways
* observability and audit trails

---

# 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Phungthevinh&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=64ffda&icon_color=64ffda&text_color=c9d1d9&ring_color=64ffda" height="180"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Phungthevinh&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=64ffda&text_color=c9d1d9&langs_count=6" height="180"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Phungthevinh&theme=tokyonight&hide_border=true&background=0d1117&ring=64ffda&fire=ff6b6b&currStreakLabel=64ffda" height="180"/>

</div>

---

# 🧩 Development Philosophy

> **Complex systems should be made understandable.**

I value:

```text
Correctness
    +
Performance
    +
Security
    +
Observability
    +
Maintainability
        ↓
Reliable Software
```

I prefer systems that are:

* **Explicit** rather than magical
* **Observable** rather than opaque
* **Deterministic** where possible
* **Modular** rather than tightly coupled
* **Recoverable** rather than assuming failures won't happen
* **Secure by design** rather than secured as an afterthought

---

# 🤝 Let's Connect

I'm interested in collaborating on:

**Rust systems programming · Backend infrastructure · Security · Real-time systems · AI/ML infrastructure**

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Phungthevinh-181717?style=for-the-badge\&logo=github)](https://github.com/Phungthevinh)

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:1a1a2e,100:16213e&height=120&section=footer" width="100%"/>

</div>
