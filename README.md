<div align="center">

# Jay

### AI systems engineering · evaluation · reliable agent infrastructure

I build systems where **evidence, uncertainty, time, state, and authority are part of correctness.**

[Portfolio](https://www.jaysystems.dev) · [GitHub](https://github.com/jayjz) · [Email](mailto:jay@jaysystems.dev)

</div>

---

## What I work on

Most of my recent work asks some version of the same question:

> **How do we make increasingly autonomous AI systems cheaper and more capable without making their behavior harder to measure, reproduce, or control?**

I approach that through evaluation infrastructure, deterministic verification, selective prediction, constrained execution, local inference, and explicit authority boundaries.

A recurring pattern is:

```text
observation
→ bounded decision
→ authority
→ evidence
→ independent verification
→ accept, abstain, or escalate
```

I prefer systems that preserve failures, expose uncertainty, separate proposal from authority, and leave enough evidence for someone other than the producing system to evaluate what happened.

## Selected systems

### [SHAD0W](https://github.com/jayjz/SHAD0W)

**Causal quantitative research and execution infrastructure**

A deterministic research system built around the idea that **time is part of correctness**.

SHAD0W separates observations, information availability, strategy proposals, execution eligibility, lifecycle state, transaction costs, risk authority, and evaluation. Current work includes reproducible market-data contracts, chronological simulation, quote-side execution economics, independent paper-risk authorization, Alpaca live-data shadowing, and fail-closed broker recovery design.

```text
data → features → strategy → causal timeline
     → independent risk → execution → reconciliation → evaluation
```

The goal is not to make trading claims. It is to make temporal leakage, invalid execution assumptions, and unsupported conclusions difficult to express.

**Python · typed domain contracts · causal simulation · risk boundaries · immutable evidence**

---

### [TEMPER](https://github.com/jayjz/TEMPER)

**Specialist models, calibrated abstention, verification, and selective escalation**

TEMPER studies whether recurring bounded decisions handled by expensive general-purpose models can progressively move to smaller specialized models without sacrificing measurable system-level reliability.

Its north-star question is:

> **What is the cost per verified correct decision?**

The research infrastructure freezes dataset identity, splits, model revisions, seeds, predictions, manifests, and evidence before stronger claims are allowed.

Current work has established the research foundation and reproducible B0/B1/B2 baselines for EXP-0001. Calibration, abstention, selective routing, and system-level economics remain experimental rather than assumed.

**Python · PyTorch · scikit-learn · calibration · selective prediction · reproducible experimentation**

---

### [CipherLoop](https://github.com/jayjz/CipherLoop) → [TraceForge](https://github.com/jayjz/TraceForge)

**Evidence-producing security agent + independent evaluator**

CipherLoop explores reliable tool-using agents under constrained context, privacy, and execution boundaries.

It combines sandboxed execution, deterministic compression, static analysis, AST-backed validation, durable trajectories, and source-backed evidence.

TraceForge is deliberately separate: it evaluates produced artifacts without importing or trusting the producing agent.

```text
agent execution
→ durable trajectory
→ evidence contract
→ independent ingestion
→ provenance / integrity checks
→ evaluation
```

The core principle:

> **Build agents that leave enough evidence to be independently evaluated.**

**Python · LangGraph · Docker · Semgrep · AST analysis · provenance · evaluation infrastructure**

---

### [AetherForge](https://github.com/jayjz/aetherforge)

**Resource governance for autonomous agents on consumer hardware**

AetherForge treats local compute as an explicitly governed resource rather than an unlimited implementation detail.

The control plane sits between agents and inference engines and makes admission, queue, economic, context, and thermal constraints machine-readable.

Verified work includes deterministic strategy admission, economic rejection, thermal locking, queue saturation, and structured failure responses under mock isolation.

```text
agent request
→ resource state
→ admission policy
→ accept / reject / defer
→ observable reason
```

The longer-term problem is reliable autonomous inference on hardware where VRAM, latency, temperature, and concurrency are real constraints.

**Python · FastAPI · admission control · backpressure · local inference · resource governance**

## Selected experiments & tools

| Project                                                                       | Question                                                                                                                                                  |
| ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [thelight](https://github.com/jayjz/thelight)                                 | How should causal research, typed model assistance, durable PAPER execution, and broker reconciliation interact without giving a model trading authority? |
| [Crossinghouse](https://github.com/jayjz/crossinghouse)                       | When can inexpensive execution + deterministic verification replace a more capable model, and when should the system escalate?                            |
| [Evidence Strategy Skills](https://github.com/jayjz/evidence-strategy-skills) | Do reusable agent procedures measurably improve decisions, or merely add prompting complexity?                                                            |
| [Unhinged Agent](https://github.com/jayjz/unhinged-agent)                     | How should a local voice pipeline handle cancellation, barge-in, and asynchronous state?                                                                  |
| [Sightglass](https://github.com/jayjz/sightglass)                             | What should an operator be able to observe and approve while an agent is running?                                                                         |
| [Fracture](https://github.com/jayjz/fracture)                                 | How do graph-based agents fail and recover under deliberately injected faults?                                                                            |
| [Truck Ready HVAC](https://github.com/jayjz/truck-ready-hvac)                 | What does offline-first field software look like when designed from actual trade-work constraints?                                                        |

## Engineering principles

```text
make the contract explicit
→ isolate authority
→ preserve evidence
→ test failure paths
→ measure behavior
→ keep the claim no larger than the proof
```

* Evidence over demos
* Verification independent of generation
* Explicit uncertainty and abstention
* Determinism where it improves trust
* Fail-closed critical boundaries
* Time and state are part of correctness
* Complexity has to earn its place
* Human authority remains visible

## Working stack

**Python · TypeScript · SQL · FastAPI · Pydantic · LangGraph · Docker · PostgreSQL · Redis · WebSockets · SSE · GitHub Actions · Ollama · llama.cpp**

Current areas:

**AI evaluation · agent infrastructure · backend/platform engineering · selective prediction · local inference · security · deterministic systems**

## Background

I came to software after more than a decade working in HVAC and construction operations.

That experience still shapes how I build systems: incomplete information, constrained resources, unreliable connectivity, operator handoffs, and failure states are normal operating conditions—not edge cases.

B.B.A., University of Massachusetts Lowell.

---

<div align="center">

[**jaysystems.dev**](https://www.jaysystems.dev) · [**github.com/jayjz**](https://github.com/jayjz)

</div>
