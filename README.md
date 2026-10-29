<div align="center">

  [![Typing SVG](https://readme-typing-svg.demolab.com?font=Victor+Mono&weight=700&size=28&pause=1200&color=89B4FA&center=true&vCenter=true&width=650&lines=Hey%2C+I'm+Chetan+%F0%9F%91%8B;Systems+%26+Distributed+Backend+Engineer;Building+in+Go%2C+Rust+%26+Python;Low-Latency+%26+Concurrency+Obsessed&style=italic)](https://git.io/typing-svg)

</div>

---

<table border="0">
  <tr>
    <td width="58%" valign="top">

### 💫 About Me

- 🎓 **Computer Science undergrad**
- ⚙️ Building scalable systems with **Go**, **Rust**, **FastAPI** & **Next.js**
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
  <img src="https://img.shields.io/badge/Tokio-F38BA8?style=flat-square&logo=rust&logoColor=11111B" />
  <img src="https://img.shields.io/badge/Rayon-FAB387?style=flat-square&logo=rust&logoColor=11111B" />
  <img src="https://img.shields.io/badge/gRPC-89B4FA?style=flat-square&logo=grpc&logoColor=11111B" />
  <img src="https://img.shields.io/badge/Protobuf-A6E3A1?style=flat-square&logo=google&logoColor=11111B" />
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

### 🌱 Currently Exploring

- 🗄️ Database Storage Internals & LSM-Trees (`Sthirayama`)
- 🌐 Distributed Consensus Protocols (Raft in Go & Rust)
- 🌊 High-Throughput Network Streaming & Concurrency
- 🐧 Linux Internals, eBPF & Kernel Bypass (`io_uring`)
  
### 📫 Connect

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-89B4FA?style=flat-square&logo=linkedin&logoColor=11111B)](https://linkedin.com/in/chetan-kishor-c-g)
[![LeetCode](https://img.shields.io/badge/-LeetCode-FAB387?style=flat-square&logo=LeetCode&logoColor=11111B)](https://leetcode.com/u/chetankishor16/)
[![GitHub](https://img.shields.io/badge/-GitHub-CDD6F4?style=flat-square&logo=github&logoColor=11111B)](https://github.com/chetanuchiha16)
[![Email](https://img.shields.io/badge/-Email-F38BA8?style=flat-square&logo=gmail&logoColor=11111B)](mailto:chetan16ck@gmail.com)

   </td>
   <td width="42%" valign="center" align="center">
     <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="100%" />
   </td>
  </tr>
</table>

---

### 🚀 Featured Projects

---

#### 🎓 [AcaTrack](https://github.com/chetanuchiha16/acatrack) · [Live ↗](https://huggingface.co/spaces/chetanuchiha16/acatrack)
*Full-Stack Academic Analytics Platform & Concurrency Ecosystem*

- ⚡ **32× Throughput Gain** (1.84 → 59.6 RPS, avg latency 2,840 ms → 158 ms) via FastAPI, Redis caching, N+1 query elimination, and DB connection pooling (42 → 5 avg conns) — verified by k6 across 120+ concurrent VUs.
- 🛡️ **Session-Isolated Sandboxing**: Dynamic SQLite environment provisioning per visitor session with automated background garbage collection for concurrent-safe live demo execution.
- 🦀 **Native Ecosystem**: Core ingestion powered by our published [`acatrack-pdf-parser-rs`](https://pypi.org/project/acatrack-pdf-parser-rs/) PyPI package (**38.4× faster**, Rayon parallelization) and a standalone [Wails desktop scraper](https://github.com/chetanuchiha16/result-scraper) (Go + React + headless `chromedp`).

`FastAPI` `React` `PostgreSQL` `Redis` `Rust (PyO3)` `Go (Wails)` `Docker` `Supabase`

---

#### 🗄️ [Sthirayama](https://github.com/chetanuchiha16/sthirayama) `[Active Development]`
*Distributed LSM-Tree Storage Engine in Rust & Go*

- 🧱 **Verified Core Engine (51 passing tests)**: Thread-safe **SkipList memtable** engineered with atomic pointers (`AtomicPtr`), concurrent read/write stress testing, and crash-resilient WAL with log recycling.
- 📦 **SSTables & Compaction**: Immutable disk block format (DataBlock, Index, Footer) paired with a k-way heap merge iterator for background compaction and tombstone garbage collection.
- 🌐 **Distributed Architecture**: gRPC client-server communication with Protobuf serialization; active roadmap includes multi-node partition replication via a Go-based Raft consensus layer.

`Rust` `LSM-Tree` `Tokio` `Rayon` `gRPC` `Protocol Buffers` `Go`

---

#### 🌊 [Metroflow](https://github.com/chetanuchiha16/metroflow)
*High-Throughput Concurrent Log Streaming & Ingestion Pipeline in Go*

- 🚀 **47,000+ Logs/Sec Throughput**: Non-blocking log ingestion streaming structured records over raw TCP into Redis job queues via a fan-out worker pool.
- 🛡️ **Zero-Leak Concurrency**: Solved goroutine memory leaks under high churn using connection-scoped contexts (`context.WithCancel`) and global `sync.WaitGroup` coordination for graceful multi-client termination.
- 💾 **Reliable Persistence**: Consumer worker pool featuring atomic CSV writer flushes and `BLPop` queue synchronization, guaranteeing zero data loss during process termination.

`Go` `Redis` `TCP` `Goroutines` `Channels` `Concurrency` `Benchmarks`

---

#### 🦀 [IrisBridge](https://github.com/chetanuchiha16/iris-bridge)
*High-Performance Rust Image Processing Library with Python Bindings*

- ⚡ **4.3× Parallel Speedup** (273 images/sec vs 62 seq): CPU-parallel batch processing across all cores utilizing Rayon's work-stealing thread pool.
- 🐍 **Zero-Copy Python FFI**: PyO3 bindings (`iris_bridge_py`) compile native Rust into normalized 3D NumPy arrays (`Array3<f32>`) returned directly into Python memory without serialization overhead.
- 🔍 **Production Telemetry**: Structured span-level timing and memory diagnostics instrumented via the `tracing` framework (`#[instrument]`).

`Rust` `PyO3` `Rayon` `NumPy` `ndarray` `tracing`

---

### 📊 Stats & Activity

<p align="center">
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=chetanuchiha16&layout=compact&theme=catppuccin_mocha&hide_border=true&langs_count=5&v=2" height="165px" />
  <img src="https://streak-stats.demolab.com/?user=chetanuchiha16&theme=catppuccin_mocha&hide_border=true" height="165px" />
</p>

<p align="center">
  <a href="https://leetcode.com/u/chetankishor16/">
    <img src="https://leetcard.jacoblin.cool/chetankishor16?theme=dark&font=Baloo%202&ext=stats" width="400" alt="LeetCode Stats" />
  </a>
</p>

---
