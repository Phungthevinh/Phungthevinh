<div align="center">

<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:1a1a2e,100:16213e&height=220&section=header&text=Phung%20The%20Vinh&fontSize=48&fontColor=e0e0e0&animation=fadeIn&fontAlignY=35&desc=Systems%20Engineer%20%7C%20Rust%20%7C%20Security%20%7C%20AI&descSize=18&descAlignY=55&descColor=8892b0" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=64FFDA&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=80&lines=Building+systems+where+every+millisecond+matters+%E2%9A%A1;Rust+%F0%9F%A6%80+%7C+Zero-Trust+%F0%9F%94%92+%7C+AI-Native+%F0%9F%A4%96)](https://github.com/Phungthevinh)

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
    role: "System & AI-Native Software Engineer",
    focus: vec![
        "High-Performance Backend Systems",
        "Zero-Trust Security Architecture", 
        "AI-Integrated Infrastructure",
        "Community Safety Technology",
    ],
    philosophy: "Code that protects lives must never crash.",
};
```

I build **mission-critical systems** in Rust where **performance**, **safety**, and **reliability** aren't features — they're requirements. From API gateways handling millions of requests to emergency rescue platforms where every millisecond counts.

---

## 🛠️ Tech Arsenal

<div align="center">

| Domain | Stack |
|:---|:---|
| **Languages** | ![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white) ![JavaScript](https://img.shields.io/badge/JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) |
| **Backend** | ![Axum](https://img.shields.io/badge/Axum-E6522C?style=for-the-badge&logo=rust&logoColor=white) ![Tokio](https://img.shields.io/badge/Tokio-FF7200?style=for-the-badge&logo=rust&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white) |
| **Mobile** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) |
| **Security** | `Zero-Trust Mesh` · `Ed25519` · `AES-256-GCM` · `JWT` · `mTLS` |
| **AI/ML** | `ONNX Runtime (tract)` · `Semantic Caching` · `NLP` · `MCP` |
| **DevOps** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) |

</div>

---

## 🏆 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🚨 [Beacon — SOS Rescue Ecosystem](https://github.com/Phungthevinh/SOS-Rescue-Ecosystem)

<sup>🦀 Rust · 📱 Flutter · 🗄️ PostgreSQL · 📡 Redis Geo</sup>

**Mạng lưới cứu hộ khẩn cấp cộng đồng** — biến mọi smartphone thành lá chắn sinh tồn.

- 🔴 Nút SOS 1-chạm → thông báo 5 người thân + radar cộng đồng 500m
- 📡 Redis Geospatial radar < 2ms response
- 🔐 Blackbox recording với AES-256-GCM E2E encryption
- 🔋 Background tracking < 2% pin/ngày
- 📞 Twilio SMS/Voice + FCM push (vượt chế độ im lặng)

> *"Trong tình huống khẩn cấp, mỗi giây đều là sự sống còn."*

</td>
<td width="50%" valign="top">

### 🛡️ [Zero Trust Gateway](https://github.com/Phungthevinh/zero_trust_gateway)

<sup>🦀 Rust · ⚡ Axum · 🧠 AI · 🔒 Zero-Trust</sup>

**Cổng kiểm soát bảo mật API Zero-Trust** tích hợp AI Semantic Cache hiệu năng cao.

- 🔐 Zero-Trust architecture: "Never trust, always verify"
- 🧠 AI Semantic Cache — truy vấn tương tự trả kết quả cached bằng ONNX models
- ⚡ Sub-millisecond latency trên Axum + Tokio async runtime
- 🔑 Ed25519 cryptographic identity mesh
- 📊 Vector similarity search cho intelligent caching

> ⭐ *Dự án có star — được cộng đồng quan tâm*

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ [Rust Gateway](https://github.com/Phungthevinh/rust_gateway)

<sup>🦀 Rust · 🌐 HTTP · 🔄 Proxy</sup>

**API Gateway** thuần Rust — nền tảng nghiên cứu kiến trúc gateway hiệu năng cao.

- 🔄 Reverse proxy với load balancing
- 🛡️ Middleware pipeline cho auth & rate limiting
- 📈 Xử lý concurrent connections hiệu quả
- 🧱 Foundation cho zero_trust_gateway

> *Dự án tiền thân, đặt nền móng cho Zero Trust Gateway.*

</td>
<td width="50%" valign="top">

### 👥 [WebAPI Personnel](https://github.com/Phungthevinh/webAPI_Personnel)

<sup>💜 C# · 🌐 .NET Core · 🗄️ SQL Server</sup>

**API quản lý nhân sự & KOI** — hệ thống enterprise backend với .NET Core.

- 📋 RESTful API cho quản lý nhân viên
- 🔐 Authentication & Authorization
- 🗄️ Entity Framework Core + SQL Server
- 📊 CRUD operations với validation

> *Full-stack enterprise solution với C# .NET ecosystem.*

</td>
</tr>
</table>

---

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Phungthevinh&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=64ffda&icon_color=64ffda&text_color=c9d1d9&ring_color=64ffda" height="180"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Phungthevinh&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=64ffda&text_color=c9d1d9&langs_count=6" height="180"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Phungthevinh&theme=tokyonight&hide_border=true&background=0d1117&ring=64ffda&fire=ff6b6b&currStreakLabel=64ffda" height="180"/>

</div>

---

## 🗺️ What I'm Building

```
  2025                      2026                       →  Future
    │                         │                            │
    ▼                         ▼                            ▼
 ┌──────────┐          ┌───────────┐              ┌──────────────┐
 │ .NET API │─────────►│Zero Trust │─────────────►│   BEACON     │
 │ Systems  │          │ Gateway   │              │  SOS Rescue  │
 └──────────┘          │ + AI Cache│              │  Ecosystem   │
                       └───────────┘              └──────────────┘
  Enterprise             Security &                Community
  Backend                AI Infrastructure         Safety Platform
```

---

<div align="center">

### 💬 Let's Connect

*I'm open to collaboration on **Rust systems programming**, **security infrastructure**, and **community safety tech**.*

[![GitHub](https://img.shields.io/badge/GitHub-Phungthevinh-181717?style=for-the-badge&logo=github)](https://github.com/Phungthevinh)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:1a1a2e,100:16213e&height=120&section=footer" width="100%"/>

</div>
