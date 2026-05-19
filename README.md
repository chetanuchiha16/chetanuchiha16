<div align="center">

  [![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=1000&color=89B4FA&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Chetan+%F0%9F%91%8B;Backend+%26+Systems+Engineer;Rust+%7C+Go+%7C+Python+%7C+FastAPI;Building+things+that+actually+scale.)](https://git.io/typing-svg)

</div>

---

<table border="0">
  <tr>
    <td width="58%" valign="top">

### 💫 About Me

- 🎓 **B.E. Computer Science** @ JSS Academy of Technical Education, Bengaluru
- ⚙️ Building production-grade systems with **Go**, **Rust**, **FastAPI** & **Next.js**
- 🦀 Systems programming in **Rust** — PyO3 bindings, Rayon parallel processing
- 🧩 Clean Architecture advocate — DDD, RBAC, and type-safe API design
- 🐧 **Fedora** daily driver | ⚔️ **DSA grind** in **C++**
- 🚀 Obsessed with perf: benchmarks, k6 load tests, N+1 hunts

### 🛠 Tech Stack

<p>
  <img src="https://img.shields.io/badge/Go-89B4FA?style=flat-square&logo=go&logoColor=11111B" />
  <img src="https://img.shields.io/badge/Rust-FAB387?style=flat-square&logo=rust&logoColor=11111B" />
  <img src="https://img.shields.io/badge/Python-A6E3A1?style=flat-square&logo=python&logoColor=11111B" />
  <img src="https://img.shields.io/badge/TypeScript-89DCEB?style=flat-square&logo=typescript&logoColor=11111B" />
  <img src="https://img.shields.io/badge/C++-B4BEFE?style=flat-square&logo=c%2B%2B&logoColor=11111B" />
</p>
<p>
  <img src="https://img.shields.io/badge/FastAPI-94E2D5?style=flat-square&logo=fastapi&logoColor=11111B" />
  <img src="https://img.shields.io/badge/Next.js-1E1E2E?style=flat-square&logo=next.js&logoColor=CDD6F4" />
  <img src="https://img.shields.io/badge/React-89DCEB?style=flat-square&logo=react&logoColor=11111B" />
</p>
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-89B4FA?style=flat-square&logo=postgresql&logoColor=11111B" />
  <img src="https://img.shields.io/badge/Redis-F38BA8?style=flat-square&logo=redis&logoColor=11111B" />
  <img src="https://img.shields.io/badge/Docker-74C7EC?style=flat-square&logo=docker&logoColor=11111B" />
  <img src="https://img.shields.io/badge/SQLAlchemy-CBA6F7?style=flat-square&logo=sqlalchemy&logoColor=11111B" />
</p>

### 📫 Connect

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-89B4FA?style=flat-square&logo=linkedin&logoColor=11111B)](https://linkedin.com/in/chetan-kishor-c-g)
[![LeetCode](https://img.shields.io/badge/-LeetCode-FAB387?style=flat-square&logo=LeetCode&logoColor=11111B)](https://leetcode.com/u/chetankishor16/)
[![GitHub](https://img.shields.io/badge/-GitHub-CDD6F4?style=flat-square&logo=github&logoColor=11111B)](https://github.com/chetanuchiha16)

   </td>
   <td width="42%" valign="center" align="center">
     <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="100%" />
   </td>
  </tr>
</table>

---

### 🚀 Featured Projects

---

#### 🎓 [AcaTrack](https://github.com/chetanuchiha16/acatrack) · [Live ↗](https://acatrack.vercel.app)
*Full-Stack Academic Performance Analytics Platform*

Full-stack academic ERP with RBAC, AI-driven insights, and automated university data ingestion. Replaced a Flask monolith with FastAPI, achieving a **32× throughput increase** (1.84 → 59.6 RPS) verified by k6.

- 🦀 **Rust PDF Engine** (PyO3 + Rayon): **8.06× faster** PDF parsing — 21.78 min → 2.70 min for 1,308 PDFs, 35% lower memory
- ⚡ **Redis caching** for expensive computations + N+1 query elimination → avg response 2,840 ms → **158 ms**
- 🕷️ **Selenium** scraper for automated university result ingestion
- 🔐 RBAC: Student, Parent, Mentor, Admin portals with role-specific dashboards
- 🌐 Multi-language support: English, Hindi, Kannada · **HeyAPI** generated TypeScript SDK

`FastAPI` `React` `Rust` `PyO3` `Rayon` `PostgreSQL` `Redis` `Docker` `Supabase` `SQLAlchemy`

---

#### ⚙️ [Go Production Blueprint](https://github.com/chetanuchiha16/go-play)
*Pragmatic Clean Architecture in Go*

Production-ready Go backend template with strict Clean Architecture, OpenAPI-driven development, and full test coverage via the **"Aura" hierarchy** (Handler → Service Interface → Store Interface).

- 📄 **OpenAPI-first**: spec → server stubs auto-generated via `oapi-codegen`
- 🗄️ **Type-safe DB**: `sqlc` generates Go from raw SQL · `pgx/v5` for connection pooling
- 🧪 **Full test suite**: unit tests with `Mockery` mocks + integration tests against real DB
- 📚 **Swagger UI** at `/docs` · **CI** via GitHub Actions · live-reload with `Air`
- 📋 **Zerolog** structured logging · **Viper** config management

`Go` `PostgreSQL` `sqlc` `pgx` `Docker` `OpenAPI` `oapi-codegen` `Mockery` `Zerolog`

---

#### 🦀 [IrisBridge](https://github.com/chetanuchiha16/iris-bridge)
*High-Performance Rust Image Processing Library with Python Bindings*

Rust library for ML data pipelines. Processes image batches in parallel and returns results as NumPy arrays — zero-copy, ML-ready output with structured tracing out of the box.

- ⚡ **Rayon** `par_iter` for multi-core parallel batch processing across all available CPU cores
- 🐍 **PyO3** bindings: call Rust natively from Python as `iris_bridge_py`
- 🖼️ Auto-resize to **224×224** (Lanczos3) + normalize pixel values to `[0, 1]`
- 📦 Returns `Array3<f32>` → Python `np.ndarray` directly, eliminating serialization overhead
- 🔍 **`#[instrument]`** spans for span-level timing diagnostics via `tracing`

`Rust` `PyO3` `Rayon` `NumPy` `ndarray` `tracing`

---

<details>
<summary><b>🧪 Go Quests — Concurrency Patterns Lab</b></summary>
<br/>

[go-quests](https://github.com/chetanuchiha16/go-quests) is a hands-on deep-dive into Go concurrency primitives — built from scratch, intentionally broken, and fixed with documented reasoning.

- **Chat Server**: TCP multi-client broadcast server. Progressed from naive goroutine slices (race conditions, stale slice copies) → `sync.Mutex`-guarded state
- **Worker Pool**: Fan-out / Fan-in pipeline — basic WaitGroup → per-worker output channels → `fanIn` merger
- Each trial ships with a `mistakes.md` documenting the exact bug and fix

`Go` `goroutines` `channels` `sync.Mutex` `WaitGroup` `fan-out/fan-in`

</details>

---

### 📊 Stats & Activity

<p align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=chetanuchiha16&layout=compact&theme=catppuccin_mocha&hide_border=true" height="165px" />
  <img src="https://github-readme-stats-fast.vercel.app/api/streak/?username=chetanuchiha16&theme=catppuccin_mocha&hide_border=true" height="165px" />
</p>

<p align="center">
  <a href="https://leetcode.com/u/chetankishor16/">
    <img src="https://leetcard.jacoblin.cool/chetankishor16?theme=dark&font=Baloo%202&ext=stats" width="400" alt="LeetCode Stats" />
  </a>
</p>

---
