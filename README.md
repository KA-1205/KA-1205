<h1 align="center">Hi, I'm Kartik Arora 👋</h1>

<p align="center"><strong>AI/ML undergraduate · Backend systems · Computer vision &amp; LLM applications</strong></p>

<p align="center">I take ideas from a rough sketch to a working demo, moving between models, APIs, and interfaces.</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ka1205"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&amp;logo=linkedin&amp;logoColor=white" alt="Connect on LinkedIn" /></a>
  <a href="https://leetcode.com/u/ka-1205/"><img src="https://img.shields.io/badge/LeetCode-Practice-FFA116?style=flat-square&amp;logo=leetcode&amp;logoColor=black" alt="LeetCode practice" /></a>
</p>

I build with teams under hackathon deadlines and keep working on what makes those prototypes useful, explainable, and testable. My current focus is strengthening my deep learning fundamentals while building computer vision and LLM-powered applications.

## 🚀 Featured builds

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/KA-1205/Ex-Vero">Ex-Vero</a></h3>
      <p align="center"><strong>Offline memory that reconnects with a fleet</strong></p>
      <p><strong>I led the build</strong> of a team project for devices to store and search text and image facts offline. It combines Qdrant Edge, dense and BM25 retrieval, on-device RAG, and delta sync with a hub that surfaces conflicting reports.</p>
      <p><strong>Run it:</strong> Docker supplies the local edge node and supporting services. Device hardware and network conditions are emulated.</p>
      <p><strong>Evidence:</strong> <a href="https://github.com/KA-1205/Ex-Vero#architecture">Architecture</a> · <a href="https://github.com/KA-1205/Ex-Vero/tree/main/tests">Tests</a> · <a href="https://github.com/KA-1205/Ex-Vero/blob/main/src/edge_node/benchmark.py">Benchmark code</a> · <a href="https://github.com/KA-1205/Ex-Vero/blob/main/results/crash_safety.json">Recorded crash test</a></p>
      <p align="center"><strong>Python · FastAPI · Qdrant · Ollama</strong></p>
      <p align="center"><a href="https://github.com/KA-1205/Ex-Vero#quick-start">Run locally →</a> · <a href="https://ex-vero.vercel.app">Hosted UI →</a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/KA-1205/Panchnama">Panchnama</a></h3>
      <p align="center"><strong>Field media you can trace back to evidence</strong></p>
      <p><strong>I led the build</strong> of a team project for signing field media at capture and verifying uploads. It connects before/after evidence, versioned ML models, and reports with a hash-chained audit trail.</p>
      <p><strong>Scope:</strong> Capture app, API, dashboard, and ML service. Upload, search, and manual-audit latency budgets remain targets requiring staging evidence.</p>
      <p><strong>Evidence:</strong> <a href="https://github.com/KA-1205/Panchnama/blob/main/docs/architecture/ARCHITECTURE.md">Architecture</a> · <a href="https://github.com/KA-1205/Panchnama/tree/main/apps/api/src/services">Services and tests</a> · <a href="https://github.com/KA-1205/Panchnama/blob/main/apps/api/src/routes/search-perf.integration.test.ts">Search harness</a> · <a href="https://github.com/KA-1205/Panchnama/actions">CI runs</a></p>
      <p align="center"><strong>TypeScript · Fastify · Expo · Supabase</strong></p>
      <p align="center"><a href="https://github.com/KA-1205/Panchnama/blob/main/ENVIRONMENT.md">Setup →</a> · <a href="https://panchnama-phi.vercel.app">Hosted dashboard →</a></p>
    </td>
  </tr>
</table>

> [!NOTE]
> The links above point to source, test suites, and recorded artifacts. They do not establish current test passes or production performance. Ex-Vero's full workflow needs a running edge node; Panchnama's latency targets need staging measurements.

## 🧩 More engineering work

- **[Prometheus](https://github.com/KA-1205/prometheus)** — contributed to a team fraud-detection prototype using synthetic transactions, XGBoost, graph models, and weakness-directed retraining. [Evaluation script](https://github.com/KA-1205/prometheus/blob/main/scripts/baseline_eval.py) · [Holdout enforcement](https://github.com/KA-1205/prometheus/blob/main/src/blue/splits.py). Evaluation reporting is being reviewed; synthetic results do not establish real-world fraud performance.
- **[SIH 2026 · Sanchar Saṅgaṇaka](https://github.com/KA-1205/SIH-2026)** — contributed to a team prototype for detecting threats in one-way network traffic and streaming alerts to an operator console. [Evaluation materials](https://github.com/KA-1205/SIH-2026/tree/main/evaluation).
- **[Cerberus](https://github.com/KA-1205/Cerberus)** — a tool-registry vetting prototype with an API, static scanner, and signed-verdict pipeline. Default sandbox checks are simulated, and the dashboard defaults to mock data; the optional Docker path provisions a test container. [Sandbox implementation](https://github.com/KA-1205/Cerberus/blob/main/api/app/sandbox.py) · [Dashboard mode](https://github.com/KA-1205/Cerberus/blob/main/dashboard/lib/api/service.ts).

<details>
<summary><strong>Interface experiments and earlier prototypes</strong></summary>

- **[LenderCheck](https://github.com/KA-1205/LenderCheck)** — a React simulation of a Telegram loan-app verification flow. Four scripted scenarios; no verification backend.
- **[The Second Shift](https://github.com/KA-1205/The-Second-Shift)** — a career re-entry coach concept using mock data; the Gemini and FastAPI backend is planned.
- **[PROVCHAIN](https://github.com/KA-1205/GSC)** — a publishing provenance hackathon prototype. See the repository for its scope and implementation.

</details>

<details>
<summary><strong>Hackathon selections</strong></summary>

- Code Cubicle 6.0 (Geek Room) — selected among 15 teams.
- Pixels to Products Cloudinary AI Hackathon 2026 (HackIndia) — selected among 10 teams.
- FAR AWAY 2026 (Zuup) — selected internationally.
- Google's Build with Gemini — advanced to Round 2.
- UX Voyage (NSUT) — advanced to Round 2.

</details>

## 🛠️ What I work with

**Languages & interfaces:** Python, TypeScript, React, Expo  
**AI & backend:** PyTorch, FastAPI, Fastify, Qdrant, Ollama  
**Infrastructure:** Docker, Supabase, Cloudinary

## 📫 Let's connect

Interested in AI/ML, backend systems, or a project like these? [Connect with me on LinkedIn](https://www.linkedin.com/in/ka1205).
