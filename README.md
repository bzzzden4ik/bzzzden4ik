# Hi, I'm Kirill Dorofeev 👋

<p align="left">
  <a href="https://github.com/bzzzden4ik">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=1B4773&width=550&lines=Systems+%26+Backend+Engineer;High-Load+Architecture+Designer;Data+Ingestion+Pipelines+Builder;Low-Level+Internals+Enthusiast" alt="Typing SVG" />
  </a>
</p>

> **Core Philosophy:** I believe that exceptional backend engineering exists at the intersection of hardware limitations and algorithmic efficiency. I don't just consume high-level abstractions — I reverse-engineer them to understand how they interact with the OS kernel.

---

### 🛠 Technical Ecosystem & Competencies

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>⚡ Languages & Core Runtimes</h4>
      <img src="https://img.shields.io/badge/Go_(Golang)-00ADD8?style=flat-square&logo=go&logoColor=white" /> <code>Goroutines</code> <code>Channels</code> <code>Worker Pools</code> <code>gRPC / Protobuf</code><br/>
      <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" /> <code>Memory Allocation</code> <code>STL Containers</code> <code>Pointers</code> <code>RAII</code><br/>
      <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" /> <code>Advanced Typing</code> <code>Generics</code><br/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" /> <code>ES6+ Asynchronous Engines</code>
    </td>
    <td width="50%" valign="top">
      <h4>⚙️ Infrastructure & DevOps (CI/CD)</h4>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <code>Containerization</code> <code>Docker Compose</code> <code>K8s Basics</code><br/>
      <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" /> <code>Reverse Proxy</code> <code>Load Balancing</code> <code>SSL/TLS Hardening</code><br/>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" /> <code>Kernel Parameter Tuning</code> <code>Bash Scripting</code> <code>VPS/VDS</code><br/>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" /> <code>CI/CD Pipelines Automation</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>📦 Backend Frameworks & Storage Layers</h4>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" /> <code>V8 Engine Internals</code> <code>Event Loop Architecture</code><br/>
      <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" /> <code>RESTful API Design</code> <code>Custom Middleware Layers</code><br/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /> <code>B-Tree Indexing</code> <code>ACID Compliance</code> <code>WAL Tuning</code><br/>
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" /> <code>Distributed Caching</code> <code>In-Memory Message Queues</code><br/>
      <img src="https://img.shields.io/badge/Message_Queues-💡?style=flat-square&color=660066" /> <code>RabbitMQ / Event-Driven Architecture</code>
    </td>
    <td width="50%" valign="top">
      <h4>📱 Client-Side, Streaming & Observability</h4>
      <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" /> <code>Low-Latency Bi-directional Streams</code><br/>
      <img src="https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black" /> <code>Cross-Platform Native Engineering</code><br/>
      <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" /> <code>Over-The-Air (OTA) Deployment Pipelines</code><br/>
      <img src="https://img.shields.io/badge/State_Management-⚛️?style=flat-square&color=007ACC" /> <code>Zustand / Redux Toolkit Architecture</code><br/>
      <img src="https://img.shields.io/badge/Observability-📊?style=flat-square&color=FF6B6B" /> <code>Prometheus & Grafana Metrics</code> <code>Structured Logging (Zap)</code>
    </td>
  </tr>
</table>

---

### 🧠 Low-Level Maturity & Engineering Deep-Dive

I avoid treating frameworks as magic black boxes. My engineering decisions are driven by internal mechanics:
* **Database Internals:** Proficient in analyzing query execution plans, structuring efficient `B-Tree` indexes, and managing the physical disk bottlenecks associated with synchronous transaction commits (`fsync` over WAL logs).
* **Concurrency & Parallelism:** Designing thread-safe, concurrent services using Go's native primitives. Experienced in preventively resolving race conditions, memory leaks, and deadlocks while tuning workload distribution across CPU cores via the Go scheduler runtime.
* **Infrastructure as Code Culture:** Production environments must be reproducible and immutable. I isolate microservices via Docker multi-stage builds, enforce strict network routing policies through Nginx configs, and treat deployment as a self-healing automated loop.

---

### 📚 Core Computer Science Reading

*I study fundamental university-level computer science literature cover-to-cover to build deep architectural intuition:*

<table width="100%">
  <tr>
    <td width="25%"><b>Distributed Systems</b></td>
    <td><i>Designing Data-Intensive Applications</i> — Martin Kleppmann<br/><code>Data models, replication, partitioning, distributed consensus, transactions.</code></td>
  </tr>
  <tr>
    <td width="25%"><b>Algorithmic Maturity</b></td>
    <td><i>Introduction to Algorithms</i> — T. Cormen, C. Leiserson, R. Rivest, C. Stein<br/><code>Complexity bounds, advanced data structures, graph theory, dynamic programming.</code></td>
  </tr>
  <tr>
    <td width="25%"><b>Systems Programming</b></td>
    <td><i>Computer Systems: A Programmer's Perspective</i> — R. Bryant, D. O'Hallaron<br/><code>Virtual memory architecture, linker mechanics, machine-level code optimization.</code></td>
  </tr>
  <tr>
    <td width="25%"><b>Software Craftsmanship</b></td>
    <td><i>Clean Code & Clean Architecture</i> — Robert C. Martin<br/><code>SOLID design patterns, decoupled boundaries, long-term maintainability metrics.</code></td>
  </tr>
</table>

---

### 📬 Connect with me

[![Telegram](https://img.shields.io/badge/Telegram-26A69A?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/bzzzden4ik)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kadorofeev4eu@gmail.com)

---

<p align="center">
  <img src="https://i.gifer.com/84OP.gif" alt="Chill Pixel Sakura" width="100%" />
</p>

<p align="right">
  <img src="https://komarev.com/ghpvc/?username=bzzzden4ik&color=1b4773&style=flat-square&label=DASHBOARD+VIEWS" alt="Profile Views" />
</p>
