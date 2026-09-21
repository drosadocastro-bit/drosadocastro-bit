# Daniel Rosado | Nova Labs Research

**Applied AI research focused on trustworthy agentic systems, deterministic authority, reproducible evaluation, and local-first intelligence.**

Nova Labs Research is my independent applied AI lab for building and testing AI systems that preserve evidence, uncertainty, provenance, auditability, and human authority.

My work focuses on a simple question:

> How do we make increasingly capable AI systems remain governable when their reasoning is probabilistic, imperfect, or inconsistent?

I explore architectures where models can reason, retrieve, classify, propose, and assist — while authority, execution boundaries, and consequential decisions remain explicit, testable, and reconstructable.

---

## Current Research Focus

### [CivicGate](https://github.com/drosadocastro-bit/CIVICGATE)

A governed MCP gateway for public federal spending research.

CivicGate separates probabilistic semantic judgment from deterministic authority:

```text
User / Agent
     ↓
Tool proposal
     ↓
Semantic judge + Agent K
     ↓
Deterministic policy
     ↓
PERMIT / DENY / REVIEW_REQUIRED
     ↓
Bounded execution
     ↓
Evidence + provenance + audit
```

Recent work includes live-model evaluation, adversarial fixtures, deterministic preflight controls, execution-state receipts, and offline replay of previously recorded model signals.

A central research idea:

> **CivicGate treats model judgment as replayable evidence rather than authority.**

Recorded semantic signals can be reintroduced into the deterministic Gateway without resampling the model, allowing their effects on review posture and execution boundaries to be measured directly.

**Capability does not create authority.**

---

### [HELM](https://github.com/Nova-Labs-Research/HELM)

A research platform for long-horizon agent reliability, behavioral persistence, recovery, and controlled fault experiments.

HELM studies how agent behavior changes over time when state, capability, context, or strategy is disrupted.

Current themes include:

- long-horizon behavioral persistence
- post-fault recovery
- strategy diversity
- goal reacquisition
- behavioral attractors
- role drift
- replay semantics
- human adjudication
- provider-agnostic evaluation

The throne may be empty. The rules should still know who is king.

---

### [Nova Aegis](https://github.com/Nova-Labs-Research/Nova-Aegis)

An evolving architecture for bounded autonomous systems.

Nova Aegis separates four concerns that are often collapsed into one:

```text
Capability → Permission → Human Review → Execution
```

The model may know how.

Policy decides whether.

Humans decide when required.

Execution does only what was authorized.

Core invariants include:

- capability cannot grant permission
- permission cannot execute
- execution cannot reinterpret policy
- missing authority fails closed
- models cannot self-expand their permissions
- provenance and approval remain independently inspectable

> ****

Design language, not a claim of experimental proof.

---  The goal is not to prove that an agent is “safe,” but to make its behavior measurable under controlled conditions.

### PRAETOR Research Lineage

PRAETOR began as an experimental MCP governance prototype and became a research lineage for deterministic containment, adversarial evaluation, provenance, Agent K, and authority separation.

Its work informed several mechanisms now being tested independently in CivicGate and Nova Aegis.

A recurring principle from PRAETOR:

> **PRAETOR does not self-certify; claims are bounded by tested conditions.**

Research themes include:

- deterministic governance
- semantic judges
- Agent K behavioral evaluation
- adversarial testing
- authority boundaries
- evidence provenance
- reproducible evaluation
- probabilistic governance vs. deterministic authority

Historical failures are preserved rather than retroactively repaired.

---

## Selected Applied Projects

### [Manatuabon](https://github.com/drosadocastro-bit/Manatuabon)

Experimental applied-AI research exploring modular reasoning architectures, bounded inference, and how higher-level system behavior can emerge from independently constrained components.

### [Cortex](https://github.com/drosadocastro-bit/Cortex)

Research-memory architecture focused on uncertainty preservation, contradiction handling, evidence discipline, and reconstructable knowledge.

### [JOI](https://github.com/drosadocastro-bit/JOI)

Local-first AI companion research focused on privacy, append-only memory, supersession, logical forgetting, and inspectable memory state.

### [Coach Luna](https://github.com/drosadocastro-bit/Coach-Luna)

Bilingual mobile fitness assistant exploring human-centered AI guidance, structured exercise generation, media grounding, approval boundaries, and mobile AI integration.

---

## Research Themes

### Trustworthy Agentic Systems

How should reasoning, planning, authority, execution, and human review be separated in agentic systems?

### Deterministic Authority

Which decisions can reasonably remain probabilistic, and which must remain reconstructible, reproducible, and governed by deterministic rules?

### Live-Model Evaluation

How do different models behave under the same contracts, fixtures, authority boundaries, and adversarial conditions?

### Replayable Evidence

Can previously observed model outputs be preserved and replayed through deterministic systems to measure their downstream effects without resampling the model?

### Long-Horizon Reliability

How do agents recover after faults, losses of state, strategy collapse, or long sequences of imperfect decisions?

### Local-First Intelligence

How much useful AI capability can remain private, offline, inspectable, and resilient when cloud connectivity is limited or unavailable?

---

## Research Principles

- **Capability does not create authority.**
- **Evidence before narrative.**
- **Provenance before conclusions.**
- **Human review before consequential action.**
- **Reconstructability before fluency.**
- **Preserve failures before patching them.**
- **Builder ≠ Reviewer ≠ Authority.**
- **Claims must remain bounded by tested conditions.**

A model may search, interpret, classify, or propose.

It should not certify its own correctness, expand its own authority, or silently redefine the conditions under which its output is trusted.

---

## Human-Directed AI Engineering

My projects use AI extensively during development, but models do not act as the sole author, reviewer, and certifier of consequential changes.

The working pattern is:

```text
Human architecture and intent
        ↓
AI-assisted implementation
        ↓
Independent model review
        ↓
Tests and reproducible evidence
        ↓
Human authorization
```

> **Builder ≠ Reviewer ≠ Authority. Human authorization closes the loop.**

AI is part of the engineering process, not a replacement for engineering judgment.

---

## Current Evaluation Philosophy

I am less interested in asking:

> “Did the model pass?”

and more interested in asking:

> “What exactly happened, under which conditions, and can another person reconstruct the result?”

That means preserving:

- failed runs
- disagreement cases
- model variability
- provenance
- test conditions
- configuration fingerprints
- authority decisions
- execution boundaries
- limitations

A failed experiment can be more valuable than a clean demo if it reveals the mechanism responsible for the failure.

---

## What This Is Not

Nova Labs Research is not a production AI safety system, a certification authority, or a claim that any tested architecture guarantees safe behavior.

These repositories are independent research prototypes, experiments, learning artifacts, and engineering studies built using public, synthetic, or appropriately controlled development data.

Results are bounded to the conditions under which they were tested.

No project should be interpreted as replacing qualified human judgment in consequential domains.

---

## Current Direction

I am currently concentrating on:

**governed MCP systems · deterministic authority · agent evaluation · model disagreement analysis · replayable evidence · long-horizon reliability · local-first AI**

---

**Trustworthy agents. Evidence-first systems. Human authority.**
