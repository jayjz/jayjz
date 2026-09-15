<div align="center">

# Jay

### Systems engineering for reliable AI, evaluation, and operator tooling

I build software where **evidence, time, state, and authority boundaries** are part of correctness.

[Portfolio](https://www.jaysystems.dev) · [GitHub](https://github.com/jayjz) · [Email](mailto:jay@jaysystems.dev)

</div>

---

## What I work on

My current work sits at the intersection of **agent systems, backend/platform engineering, evaluation, security, and deterministic research tooling**.

I care less about making an agent look autonomous and more about whether the system can answer harder questions:

- What evidence produced this decision?
- Was that evidence actually available at the time?
- What state transition was authorized, and by whom?
- Can the run be reproduced?
- Can an evaluator inspect the result without trusting the producer?

That usually leads me toward explicit contracts, bounded state, failure-aware execution, reproducible tests, and observability that survives beyond the demo.

## Current high-signal work

### [CipherLoop](https://github.com/jayjz/CipherLoop) → [TraceForge](https://github.com/jayjz/TraceForge)

**Evidence-producing security agent + independent trajectory evaluator**

CipherLoop is an experimental hybrid code-auditing agent built around sandboxed tool execution, deterministic compression, AST-backed source-to-sink validation, bounded active context, and append-only trajectory evidence.

TraceForge evaluates those artifacts independently. Its current baseline reproduces two deterministic CipherLoop cases offline, validates provenance and evidence integrity, and keeps evaluator authority outside the agent that produced the run.

**Engineering signal:** Python · LangGraph · Docker · Semgrep · AST analysis · deterministic compression · provenance · evaluation infrastructure · reproducible baselines

> Core thesis: **build agents that leave enough evidence to be independently evaluated.**

---

### [SHAD0W](https://github.com/jayjz/SHAD0W)

**Deterministic quantitative research system focused on causal correctness**

SHAD0W models market observations, feature availability, signal creation, lifecycle state, execution eligibility, slippage, fees, evaluation, and independent paper-risk authority as separate contracts.

A completed-bar signal cannot fill against the same close that created it. Live Alpaca data is translated into provider-neutral domain events for shadow-mode research; live capital remains outside the current system.

**Engineering signal:** temporal correctness · deterministic simulation · event ordering · risk gates · immutable evidence · streaming market data · reproducible research

> Information cannot influence an action until the system models it as available.

---

### [AetherForge](https://github.com/jayjz/aetherforge)

**Hardware-aware admission and safety control plane for local agents**

AetherForge sits between autonomous callers and local inference infrastructure. It exposes resource state, evaluates admission requests, enforces queue/context/thermal boundaries, and returns explicit machine-readable rejection behavior instead of letting agents drive consumer GPUs into failure.

The verified path runs against a mock inference engine; physical fast-swap research remains isolated from the production hot path.

**Engineering signal:** FastAPI · concurrency · admission control · backpressure · resource governance · failure contracts · local inference infrastructure

---

### [Evidence Strategy Skills](https://github.com/jayjz/evidence-strategy-skills)

**Research platform for testing whether Agent Skills measurably improve decisions**

This project treats skills as hypotheses rather than prompt assets. It defines evidence provenance, support/counterevidence relationships, claim states, baseline isolation, held-out evaluation, grader boundaries, and cost accounting before promoting any skill as useful.

Current status is intentionally early: the methodology exists; the first real skill-vs-baseline usefulness experiment has not yet been run.

**Engineering signal:** evaluation design · epistemic contracts · provenance · experimental controls · model portability · reproducible research

## Selected systems

| Project | Focus | What it demonstrates |
|---|---|---|
| [Unhinged Agent](https://github.com/jayjz/unhinged-agent) | Local voice system | FastAPI/WebSockets, VAD → STT → LLM → TTS, cancellable state machine, barge-in, RTX 4060-class local inference |
| [Sightglass](https://github.com/jayjz/sightglass) | Agent control plane | FastAPI, LangGraph state streaming, SSE, human approval gates, local inference, operator observability |
| [Fracture](https://github.com/jayjz/fracture) | Agent failure research | Failure injection, topology-aware state handling, parallel-safe LangGraph reducers, recovery/evaluation foundations |
| [Truck Ready HVAC](https://github.com/jayjz/truck-ready-hvac) | Field software | Typed domain models, pure business logic, offline JSON/PDF workflows, CI, real contractor-oriented UX |

## How I build

```text
inspect the system
→ make the contract explicit
→ isolate authority
→ preserve evidence
→ test adversarial cases
→ measure the behavior
→ keep the claim no larger than the proof
```

A few recurring principles:

- **Evidence over demos.** A successful output matters less than whether the path to it is inspectable.
- **Determinism where it buys trust.** Reproducibility is a feature, especially around evaluation, finance, and security.
- **Fail closed at critical boundaries.** Invalid or stale state should not quietly become authority.
- **Small systems beat ornamental architecture.** Complexity has to earn its place.
- **Human review stays explicit.** High-impact actions should have visible, testable approval boundaries.

## Technical focus

**Languages:** Python · TypeScript/JavaScript · SQL  
**Backend / systems:** FastAPI · LangGraph · Pydantic · WebSockets · SSE · async Python · REST APIs  
**Data / evaluation:** deterministic pipelines · provenance · simulation · experiment design · scikit-learn · Pandas  
**Infrastructure:** Docker · PostgreSQL · Redis · GitHub Actions · Linux · local model runtimes  
**AI / inference:** Ollama · llama.cpp · local tool-calling models · hybrid local/cloud orchestration  
**Security:** sandboxed execution · static analysis · AST validation · OSINT/recon tooling · evidence-backed auditing

## Background

Before moving fully into software, I spent more than a decade in HVAC and construction operations. That background still shapes how I build: systems have to survive incomplete information, constrained resources, real operators, and failure states that do not care about the demo.

I hold a bachelor's degree in Business Administration from UMass Lowell and focus my engineering work on reliable AI systems, backend/platform development, evaluation infrastructure, and applied systems research.

## Contact

- **Portfolio:** [jaysystems.dev](https://www.jaysystems.dev)
- **GitHub:** [github.com/jayjz](https://github.com/jayjz)
- **Email:** [jay@jaysystems.dev](mailto:jay@jaysystems.dev)

---

<sub>
Keywords: AI systems engineering · agent evaluation · backend engineering · platform engineering · Python · FastAPI · LangGraph · Docker · local AI · LLM infrastructure · cybersecurity · deterministic systems · observability · provenance · causal simulation
</sub>
