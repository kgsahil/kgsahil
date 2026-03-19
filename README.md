### 👨‍💻 About Me
I am a **Systems Engineer** with **4+ years of institutional experience** at **UBS**, building the backbone of **Apex** (Repo Trading System). My specialization lies in **low-latency architecture**, **lock-free concurrency**, and **market data processing**.

Currently, I am pivoting deeper into the **HFT & Crypto infrastructure** space, building open-source tools that bring institutional-grade performance to retail APIs.

* 🔭 **I’m currently building:** A high-performance, lock-free **Kraken WebSocket SDK** using the Reactor Pattern, and contributing to open-source **Rust** agentic trading tools.
* ⚡ **Specialty:** Migrating legacy systems to **C++20**, optimizing with **Perf/GDB**, and designing zero-copy pipelines.
* 🏦 **Domain:** Fixed Income, Repo Trading, STP Automation, Order Book Microstructure, and Market Data Distribution.

### 🛠 Tech Stack
| Domain | Technologies |
| :--- | :--- |
| **Languages** | ![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white) |
| **System Design** | Lock-free Queues (SPSC), Shared Memory, Zero-Copy, Reactor Pattern, OOP Design Patterns |
| **Tools & Ops** | Git, CMake, GDB, Perf, Autosys, Docker, CI/CD (GitLab) |
| **Data & Messaging** | IBM MQ, SQL, FIX/SWIFT Protocols, WebSockets |

### 🚀 Engineering Highlights

#### 🏆 **Winner: Kraken Forge Hackathon**  **The Project:** [`kgsahil/kraken-sdk`](https://github.com/kgsahil/kraken-sdk)
* **Tech:**  C++20, WebSockets, Zero-Copy Architecture, Reactor Pattern, SPSC Queue, Boost Beast and many more.
* **Key Impact:**
    * Secured 1st place by architecting a HFT grade system with ample of configuration handed to User and no-where to be found features in one bundled SDK.
    * Solved the missing link for the Kraken shared primitives pool. It's the first Kraken sdk built with C++ performance using their Websocket v2 API.

#### 🏦 **Apex Repo Trading System @ UBS** (2021 - 2025)
* **The System:** A high-availability platform for Fixed Income & Security markets.
* **My Role:** Core Backend Developer.
* **Key Impact:**
    * Engineered lock-free components to reduce latency in trade ingestion pipelines.
    * Built low-latency message parsing infrastructure for ION/ECN gateways and SWIFT confirmations.
    * Orchestrated critical trade reconciliation and STP automation utilizing Autosys and IBM MQ.
    * Led zero-downtime deployments and complex system migrations.

#### 🏎️ **Limit Order Book & Matching Engine**
* **Repo:** [`kgsahil/Orderbook`](https://github.com/kgsahil/Orderbook)
* **Tech:** C++20, STL, CMake.
* **Details:** A bare-metal financial order book implementing strict **Price-Time Priority** (FIFO) matching.
* **Features:**
    * Designed for ultra-low latency with `O(1)` complexity for best-bid/ask lookups.
    * Implemented lock-free order management structures to bypass mutex bottlenecks.
    * Architected with strict OOP principles (Factory, Observer) for modular execution.

#### 🛠️ **Git from Bits Up**
* **Tech:** C++20.
* **Details:** A clean-room implementation of the Git version control system from scratch.
* **Features:** Implements `init`, `add` (SHA-1 hashing), `commit` (tree objects), and `checkout` (graph traversal) strictly without utilizing `libgit2`.

---

### 📊 GitHub Stats
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kgsahil&show_icons=true&theme=dark&hide_border=true&count_private=true" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kgsahil&layout=compact&theme=dark&hide_border=true" height="150" alt="languages graph" />
</div>

---

<div align="center">
  <sub>Let's talk latency.</sub><br>
  <a href="mailto:sahilgupta.17299@gmail.com">sahilgupta.17299@gmail.com</a> | <a href="https://www.linkedin.com/in/kgsahil/">LinkedIn</a>
</div>
