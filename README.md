<div align="center">

# Jay

### AI systems engineering · evaluation · reliable agent infrastructure

I build systems for **verifiable AI decisions under real-world constraints** — where evidence, uncertainty, time, state, cost, and authority are part of correctness.

[Portfolio](https://www.jaysystems.dev) · [GitHub](https://github.com/jayjz) · [Email](mailto:jay@jaysystems.dev)

</div>

---

## Current focus

My work centers on a systems question:

> **How do we make AI systems cheaper and more autonomous without making their behavior less measurable or trustworthy?**

I explore that through agent evaluation, selective model routing, deterministic verification, constrained inference, security tooling, and reproducible research infrastructure.

The recurring architecture is:

```text
task
→ bounded execution
→ evidence
→ verification
→ confidence / risk
→ accept, abstain, or escalate
```

I prefer systems that expose uncertainty, preserve failures, separate proposal from authority, and leave enough evidence for independent evaluation.

## Featured work

### [TEMPER](https://github.com/jayjz/TEMPER)

**Research into specialist models, calibrated abstention, verification, and selective escalation**

TEMPER studies whether recurring bounded decisions handled by general-purpose models can progressively move to smaller specialized models while preserving system-level reliability.

The current research measures predictive quality, calibration, selective risk, compute, latency, and ultimately **cost per verified correct decision**.

**Python · scikit-learn · calibration · selective prediction · reproducible experimentation**

---

### [CipherLoop](https://github.com/jayjz/CipherLoop) → [TraceForge](https://github.com/jayjz/TraceForge)

**Evidence-producing security agent + independent evaluator**

CipherLoop combines sandboxed tool execution, bounded context, deterministic compression, static analysis, AST-backed validation, and durable trajectory evidence.

TraceForge independently evaluates those artifacts without trusting the producing agent, checking provenance, integrity, source locations, and reproducibility.

**Python · LangGraph · Docker · Semgrep · AST analysis · provenance · evaluation infrastructure**

> Build agents that leave enough evidence to be independently evaluated.

---

### [SHAD0W](https://github.com/jayjz/SHAD0W)

**Deterministic quantitative research infrastructure**

SHAD0W separates market observations, information availability, strategy proposals, execution eligibility, lifecycle state, transaction costs, evaluation, and risk authority.

Its purpose is not to make trading claims. It is to make temporal leakage, invalid execution assumptions, and unsupported conclusions difficult to express.

**temporal systems · simulation · event ordering · risk boundaries · immutable evidence**

---

### [Crossinghouse](https://github.com/jayjz/crossinghouse)

**Task routing, deterministic verification, and selective escalation**

Crossinghouse explores when inexpensive execution can handle a task locally, when deterministic verification can establish success, and when uncertainty should trigger escalation to more capable models.

Its current foundation is a provider-neutral typed kernel for task contracts, routing, bounded execution, verification, lifecycle transitions, and escalation decisions.

**typed contracts · routing · verification · escalation · model economics**

## Other systems

| Project                                                                       | Focus                                                                                           |
| ----------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| [AetherForge](https://github.com/jayjz/aetherforge)                           | Hardware-aware admission control, backpressure, and resource governance for local inference     |
| [Evidence Strategy Skills](https://github.com/jayjz/evidence-strategy-skills) | Controlled experiments for determining whether Agent Skills measurably improve decisions        |
| [Unhinged Agent](https://github.com/jayjz/unhinged-agent)                     | Cancellable local voice pipeline with WebSockets, VAD → STT → LLM → TTS, and barge-in           |
| [Sightglass](https://github.com/jayjz/sightglass)                             | Agent control plane with state streaming, human approval boundaries, and operator observability |
| [Fracture](https://github.com/jayjz/fracture)                                 | Failure injection and recovery research for graph-based agents                                  |
| [Truck Ready HVAC](https://github.com/jayjz/truck-ready-hvac)                 | Offline-oriented field software built from real HVAC/construction workflow constraints          |

## Engineering principles

```text
make the contract explicit
→ isolate authority
→ preserve evidence
→ test failure paths
→ measure behavior
→ keep the claim no larger than the proof
```

* **Evidence over demos**
* **Verification independent of generation**
* **Explicit uncertainty and abstention**
* **Determinism where it improves trust**
* **Fail-closed critical boundaries**
* **Complexity must earn its place**
* **Human authority remains visible**

## Technical focus

**Python · TypeScript · SQL · FastAPI · Pydantic · LangGraph · Docker · PostgreSQL · Redis · WebSockets · SSE · GitHub Actions · Ollama · llama.cpp**

Current areas: **AI evaluation · agent infrastructure · selective prediction · calibration · backend/platform engineering · local inference · security · deterministic systems**

## Background

I came to software after more than a decade in HVAC and construction operations.

That experience still shapes how I engineer systems: incomplete information, constrained resources, unreliable connectivity, operator handoffs, and failure states are normal operating conditions—not edge cases.

B.B.A., University of Massachusetts Lowell.

---

[**jaysystems.dev**](https://www.jaysystems.dev) · [**github.com/jayjz**](https://github.com/jayjz) · [**jay@jaysystems.dev**](mailto:jay@jaysystems.dev)
