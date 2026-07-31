<h1 align="center">Hi, I'm Franklin 👋</h1>

<p align="center">
  <b>MSc Machine Intelligence @ ETH Zürich</b> · Co-founder & CPO @ <b>Velari</b><br/>
  Shipping AI-agent systems · researching privacy-preserving ML
</p>

<p align="center">
  <a href="https://blog.tranie.org"><img src="https://img.shields.io/badge/Blog-000000?style=flat-square&logo=firefox&logoColor=white" alt="Blog" /></a>
  <a href="https://www.linkedin.com/in/franklin-tranie"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://arxiv.org/abs/2509.01253"><img src="https://img.shields.io/badge/Paper-B31B1B?style=flat-square&logo=arxiv&logoColor=white" alt="arXiv" /></a>
  <a href="mailto:franklin.tranie@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

I like working where research meets a shipped product — currently splitting my time between an MSc in Machine Intelligence at ETH Zürich and building things real people use. Before Zurich: a CS bachelor's at EPFL, FHE research in the SaCS lab, and medical imaging at MIT's Jameel Clinic. Most of what I do sits somewhere between **applied ML**, **systems**, and **privacy**.

### ✍️ Writing

I keep field notes at **[blog.tranie.org](https://blog.tranie.org)** on models, coding agents, and the economics underneath.

- **[AI for Software Engineers: The July 2026 Field Guide](https://blog.tranie.org/ai-for-software-engineers/)** — the models, the coding agents, the Python stack, the economics, and the mental models that make it click. Plus a syllabus of the canonical reading. *(~35 min)*
- **[The Engineering Playbook: Cheap-at-Scale Agentic Engineering](https://blog.tranie.org/engineering-playbook/)** — a survey of the tooling and patterns that keep agentic systems fast, correct, and cheap, with the trade-offs stated plainly.
- **[AI Explained to My Lawyer Mom](https://blog.tranie.org/ai-explained-to-my-lawyer-mom/)** — what these machines actually are, how they fail, where your files go, and why Europe keeps writing rules for an industry it doesn't own. *(~20 min)*
- **[Claude Code: The Engineer's Guide](https://blog.tranie.org/claude-code-guide/)** — a 21-page deck from first session to worktrees, hooks, and headless CI, ending in a seven-day ramp.

### 🚀 What I'm building

**🏢 Velari** — Co-founder & CPO. Turns a complex investment thesis into a researched, outreach-ready target list for PE firms and search funds. The matching pipeline reads European registry financials, ownership data, and the public web to catch signals static databases miss (recurring revenue, founder-led, end markets). It runs 1,000 concurrent screening agents, evaluates a company for about **$0.015** against 20–40 minutes of analyst time, and hits **94.4%** per-criterion accuracy on a 1,050-judgment European benchmark — ahead of GPT-5.6 Sol (87.5%) and Claude Opus 5 (82.7%). On one top-10 PE firm's niche software thesis it surfaced **15** qualified targets where three leading platforms, Grata included, returned zero.

**🔐 [Supersayan](https://github.com/supersayan-labs/supersayan)** — A Python library that converts arbitrary PyTorch models into hybrid-FHE equivalents behind a three-line API, with fast ciphertext packing and GPU-parallel kernels. Companion implementation for the paper below.

**📱 [Splice](https://github.com/franklintra/splice)** — A cross-platform, open-source iOS sideloader. Installs apps with a free Apple cert and runs a background daemon that re-signs them before they expire, on Linux, Windows, macOS, even headless on a Raspberry Pi.

**🩺 ClarityCare.ai** — Contract AI/software engineering. Reengineered the agent architecture to drop redundant LLM calls at no accuracy cost, worth a **60×** throughput gain (10 cases/hour → 10 cases/minute), and put a Celery orchestration layer with priority queues in front of provider rate limits.

**🗣️ Opera Groupe** — Voice agents for a property-inspection app: spoken observations auto-fill reports and computer vision classifies damage. Used daily by dozens of field operators.

### 🔬 Research

- **Hybrid FHE** *(EPFL SaCS Lab)* — co-designed **Safhire**, which removes server-side bootstrapping by offloading non-linearities to the client, reaching **~10× lower latency** than Orion, the state-of-the-art encrypted-inference baseline. Co-lead author on *[Practical and Private Hybrid ML Inference with Fully Homomorphic Encryption](https://arxiv.org/abs/2509.01253)*, under review at USENIX Security '26.
- **Medical imaging** *(MIT CSAIL / Jameel Clinic)* — improved the Sybil lung-cancer prediction model for low-dose CT, raising **AUC from 0.76 to 0.85**, and built a dose-modulated layer that transfers competence across scan doses. Now in clinical testing at a partner hospital in Italy.

### 🛠️ Tech I reach for

<p>
  <img src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
</p>

`Python` · `PyTorch` · `C/C++` · `CUDA` · `TypeScript` · `FastAPI` · `React` · `Docker` · `PostgreSQL` · `Celery` · `Cloudflare Workers` — plus a soft spot for FHE and anything that involves making slow things fast.

---

<p align="center">
  <i>Always happy to talk about ML, privacy, or startups.</i><br/>
  <sub>Latest writing at <a href="https://blog.tranie.org">blog.tranie.org</a>.</sub>
</p>
