<div align="center">
  <a href="https://movingbytes.dev">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=27&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=620&lines=Agent+Systems+Architect;Local-First+%2B+Ops-Native+Agents;Observable+%E2%80%A2+Human-Accountable" alt="Typing SVG">
  </a>
</div>

<h1 align="center">Jay — Agent Systems Architect</h1>

<p align="center">
  <a href="https://movingbytes.dev"><img src="https://img.shields.io/badge/-Portfolio-0366d6?style=flat&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:jay@movingbytes.dev"><img src="https://img.shields.io/badge/-Contact-f66a0a?style=flat&logo=minutemailer&logoColor=white" alt="Contact"></a>
  <a href="https://github.com/jayjz"><img src="https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub"></a>
</p>

I build **local-first agent systems** and **ops tooling** that run under real constraints (consumer GPUs, field connectivity, human review).  
Background: 10+ years HVAC / construction operations leadership + current focus on agent architecture, control planes, and edge systems.

**Core principles:** Observable • Interruptible • Human-Accountable • Local-First • Reality-Grounded

---

## Current Focus (August 2026)

| Project | What it actually is | Maturity |
|---------|---------------------|----------|
| **[aetherforge](https://github.com/jayjz/aetherforge)** | Hardware-aware safety + control plane for local AI agents on consumer GPUs (FastAPI, Economic Gatekeeper, thermal/VRAM circuit breakers). Mock path fully verified; real Fast-Swap / KV survival on 8 GB is still research. | Wedge A (verified Mock + safety) |
| **[unhinged-agent](https://github.com/jayjz/unhinged-agent)** | Thin-client private voice note assistant. ESP32-S3-BOX-3B edge + RTX 4060 host (FastAPI WebSocket, Silero VAD, faster-whisper, local Qwen GGUF, barge-in FSM). Browser mock complete; physical hardware pending. | Phase 1 Software PoC |
| **[hvac-ops-agent](https://github.com/jayjz/hvac-ops-agent)** + **[truck-ready-hvac](https://github.com/jayjz/truck-ready-hvac)** | Multi-agent HVAC operations co-pilot (dispatch, inventory, AR, risk) + offline pre-departure parts checklist. Built from real trades experience. Streamlit demos + synthetic/fallback data. | Phase 1 demo / usable pilot tools |
| **[agentville](https://github.com/jayjz/agentville)** | Local simulation environment for multi-agent coordination experiments (Windows 95 aesthetic). Portfolio / research piece. | Simulation / portfolio |

---

## Why the hybrid matters

Most agent demos ignore the messy realities of field operations and limited hardware. I start from those constraints:

- 8 GB VRAM budgets and thermal limits
- Offline / intermittent connectivity for technicians
- Human review before irreversible actions (AR write-offs, parts orders, schedule changes)
- Traceable execution paths so operators can trust (or override) the system

This is not “AI toys.” It is tooling shaped by years of running crews and fixing broken processes.

---

## Tech I actually use day-to-day

**Agent & orchestration:** LangGraph, custom FastAPI control planes, FSMs, tool registries  
**Local inference:** Ollama, llama.cpp / GGUF, faster-whisper, Silero VAD  
**Ops & data:** Streamlit, Pydantic, MongoDB (optional), pure domain engines  
**Edge / hardware:** ESP32 / ESPHome (in progress), RTX 4060 class GPUs  
**Web:** Vanilla high-performance frontends, Next.js when needed

---

## Contact

- Portfolio: [movingbytes.dev](https://movingbytes.dev)
- Email: jay@movingbytes.dev
- GitHub: [@jayjz](https://github.com/jayjz)

Open to collaborations on local-first agents, ops automation for trades, and systems that stay accountable under real constraints.
