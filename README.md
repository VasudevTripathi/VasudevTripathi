<div align="center">
  <!-- Dynamic Hero Header SVG -->
  <a href="https://github.com/VasudevTripathi">
    <img src="./assets/telemetry/header.svg" width="100%" alt="Vasudev Tripathi — AI & Systems Engineer" />
  </a>
</div>

<p align="center">
  <a href="#about"><b>[ ABOUT ]</b></a> &nbsp;&nbsp;
  <a href="#now"><b>[ NOW ]</b></a> &nbsp;&nbsp;
  <a href="#stack"><b>[ STACK ]</b></a> &nbsp;&nbsp;
  <a href="#projects"><b>[ PROJECTS ]</b></a> &nbsp;&nbsp;
  <a href="#systems"><b>[ SYSTEMS ]</b></a> &nbsp;&nbsp;
  <a href="#telemetry"><b>[ TELEMETRY ]</b></a> &nbsp;&nbsp;
  <a href="#connect"><b>[ CONNECT ]</b></a>
</p>

---

<a name="about"></a>
<div align="center">
  <!-- Interactive-feeling Engineering Console SVG -->
  <img src="./assets/telemetry/status_console.svg" width="100%" alt="Engineering Status Console" />
</div>

<br />

<a name="now"></a>
### ⚡ NOW :: ACTIVE PRIORITIES

```text
┌─────────────────────────────────────────────────────────────────────────────────────────┐
│ OPERATIONAL FOCUS                                                              ● ACTIVE │
├─────────────────────────────────────────────────────────────────────────────────────────┤
│ BUILDING   :: LogSense-AI — Autonomous AI log parsing & local PII sanitization engine   │
│ STUDYING   :: OS Heap Allocation Routines, Dynamic Memory Fragmentation & C++17         │
│ EXPLORING  :: Civora Compliance OS — Topological Step Schedulers & Graph Resolution      │
│ OBJECTIVE  :: Engineering high-reliability, zero-leakage, low-overhead software systems │
└─────────────────────────────────────────────────────────────────────────────────────────┘
```

<div align="center">
  <!-- High-level Metric Cards SVG -->
  <img src="./assets/telemetry/metrics.svg" width="100%" alt="Core Engineering Metrics" />
</div>

---

<a name="stack"></a>
### 💻 TECHNICAL STACK MATRIX

| Domain | Engineering Tooling & Core Stack |
| :--- | :--- |
| **Languages** | `C++17` &nbsp;`Python 3.12+` &nbsp;`JavaScript (ES6+)` &nbsp;`C` &nbsp;`SQL` &nbsp;`Bash` |
| **AI / Machine Learning** | `OpenAI API` &nbsp;`Rule-Based Root Cause Engines` &nbsp;`Log Analytics` &nbsp;`NumPy` &nbsp;`PII Redaction` |
| **Backend & Systems** | `FastAPI` &nbsp;`RESTful APIs` &nbsp;`C++ Priority Queues` &nbsp;`SQLite` &nbsp;`Graph Dependency Resolution` |
| **Frontend & Web** | `React` &nbsp;`Vanilla CSS Design Systems` &nbsp;`Glassmorphism` &nbsp;`Vite` &nbsp;`HTML5/CSS3` |
| **Environment & Infrastructure** | `Linux (Ubuntu / Hyprland)` &nbsp;`Git` &nbsp;`GCC / Clang` &nbsp;`Jupyter` &nbsp;`Postman` |

<details>
<summary><b>🔍 Expand Detailed Tech Stack Specs & Architecture Tooling</b></summary>

<br />

#### Core Systems & Paradigms
- **Memory & Allocation**: Heap fragmentation simulation, memory layout analysis, First-Fit / Best-Fit / Worst-Fit allocators.
- **Data Structures**: Priority queues with multi-tier tie-breaking, topological sort graphs, dynamic programming critical path arrays.
- **Privacy & Security Layer**: Local regex and pattern-matching sanitizers for stripping credentials, JWTs, IPs, and PII prior to external API transmission.
- **Web Architectures**: Stateless client-side URL encoding for instant state sync, REST API design with strict FastAPI Pydantic schema validation.

</details>

---

<a name="projects"></a>
### 🚀 FEATURED PROJECTS

#### 01. [LogSense-AI](https://github.com/VasudevTripathi/LogSense-AI)
> **Autonomous AI Log Parsing & Root Cause Diagnostic Platform**

* **Overview:** Autonomous incident diagnosis system built to parse unstructured system logs, extract error patterns, and run diagnostic root-cause analyses using AI models.
* **Security Architecture:** Features a local **PII and credential redaction layer** that intercepts log streams and sanitizes sensitive fields (tokens, passwords, IP addresses) before invoking external LLM diagnostic endpoints.
* **Engineering Highlights:** Includes 26 automated unit tests, 8 production REST endpoints, and a rule-based root cause engine fallback.
* **Tech Stack:** `FastAPI` · `Python` · `React` · `SQLite` · `OpenAI API` · `Pytest`

---

#### 02. [TriageCare](https://github.com/VasudevTripathi/TriageCare)
> **Emergency Room Patient Triage Simulator & C++ Priority Engine**

* **Overview:** Clinical operations simulator designed to prioritize, rank, and track emergency room patient streams under high capacity.
* **Architecture:** Core **C++17 priority-queue engine** ranking patients by clinical severity with arrival-time tie breaking, synchronized to a stateless Web UI via encoded URL state parameters.
* **Engineering Highlights:** Dual-channel parity testing between C++ queue logic and React UI, zero-backend state requirement.
* **Tech Stack:** `C++17` · `JavaScript` · `Vanilla CSS` · `React` · `Vercel`
* **Links:** [Repository](https://github.com/VasudevTripathi/TriageCare) · [Live Demo](https://triage-care.vercel.app)

---

#### 03. [Civora Compliance OS](https://github.com/VasudevTripathi)
> **Enterprise Deterministic Compliance Engine & Workflow Generator**

* **Overview:** Deterministic decision layer that converts complex, multi-variable regulatory requirements into structured step-by-step compliance execution roadmaps.
* **Architecture:** Uses **topological step scheduling**, dynamic programming critical path calculation, and condition dependency graph resolution to resolve step statuses (`AVAILABLE` / `BLOCKED`).
* **Tech Stack:** `Python` · `FastAPI` · `Graph Algorithms` · `Dynamic Programming`

---

#### 04. [Dynamic Memory Management Visualizer](https://github.com/VasudevTripathi/Dynamic-Memory-Management-Visualizer)
> **Interactive OS Memory Allocation & Heap Fragmentation Simulator**

* **Overview:** Low-level interactive visualizer illustrating operating system dynamic memory allocation strategies and heap fragmentation behavior.
* **Algorithms Implemented:** First Fit, Best Fit, Worst Fit, and Next Fit allocation routines with live memory block visualizers.
* **Tech Stack:** `C++` · `JavaScript` · `CSS` · `HTML`

---

#### 05. [Numerical Foundations (NumPy Core)](https://github.com/VasudevTripathi?tab=repositories)
> **Vectorized Computing & Matrix Math Kernel**

* **Overview:** Exploratory implementation of numerical linear algebra operations, array vectorization benchmarks, and multi-dimensional matrix operations.
* **Tech Stack:** `Python` · `NumPy` · `Jupyter Notebooks`

---

<a name="systems"></a>
### ⚙️ BUILDING SYSTEMS :: OPERATING PHILOSOPHY

```text
01. UNDERSTAND THE FAILURE MODE BEFORE WRITING CODE
    Map out edge cases, rate limits, data leakage risks, and heap boundary conditions prior to implementation.

02. PREFER DETERMINISTIC ARCHITECTURES
    Core logic should remain predictable and inspectable. AI components should enrich telemetry, not replace core invariants.

03. TREAT PRIVACY & DATA SANITIZATION AS A HARD CONSTRAINT
    Never send raw user data to third-party APIs. Sanitize, redact, and verify locally before external calls.

04. BUILD AUTOMATED VERIFICATION ALONGSIDE FEATURES
    A feature without automated tests is technical debt. Ship unit tests with every pull request.
```

---

<a name="telemetry"></a>
### 📊 GITHUB TELEMETRY DASHBOARD

<div align="center">
  <!-- Custom Language Distribution SVG -->
  <img src="./assets/telemetry/languages.svg" width="100%" alt="Language Distributions & Kernels" />
</div>

<br />

<div align="center">
  <!-- Live GitHub Stats & Top Languages Cards -->
  <img src="./assets/telemetry/github_stats.svg" width="48%" alt="Vasudev's GitHub Analytics" />
  &nbsp;
  <img src="./assets/telemetry/top_langs.svg" width="48%" alt="Top Used Languages" />
</div>

<br />

<div align="center">
  <!-- Telemetry Cadence SVG -->
  <img src="./assets/telemetry/activity.svg" width="100%" alt="System Telemetry & Activity Cadence" />
</div>

---

<a name="connect"></a>
### 📬 CONNECT & CONTACT

<div align="center">
  <p>
    <a href="https://www.linkedin.com/in/vasudevtripathi">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    &nbsp;&nbsp;
    <a href="mailto:vasudevtripathi006@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    &nbsp;&nbsp;
    <a href="https://github.com/VasudevTripathi">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
  </p>
  
  <p font-family="monospace">
    <sub><b>SYSTEM STATUS :: NOMINAL &nbsp;|&nbsp; VASUDEV TRIPATHI &copy; 2026</b></sub>
  </p>
</div>
