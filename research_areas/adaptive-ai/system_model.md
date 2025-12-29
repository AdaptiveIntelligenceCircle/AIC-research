# Research Area: Adaptive AI

This document defines the **Adaptive AI research program** within AIC-research.
It corresponds to the folder `research_areas/adaptive_ai/` and formally specifies its scope, assumptions, models, and links to implementation.

---

## File: `system_model.md`

### System Components

An adaptive system is modeled as:

* **State (S)**: internal configuration and memory
* **Context (C)**: external observations and constraints
* **Policy (P)**: decision logic
* **Supervisor (H)**: human or rule-based oversight
* **History (Hₜ)**: trace of past states and actions

Adaptation is represented as:

Pₜ₊₁ = Adapt(Pₜ, Sₜ, Cₜ, Hₜ)

### Constraints

* Adaptation must be traceable
* Previous policies must be recoverable
* Supervisor override must exist

---

## Closing Statement

Adaptive AI in AIC-research is not about making systems smarter at all costs.

It is about making **change itself a governed, inspectable, and reversible operation**.

If adaptation cannot be controlled, it should not occur.
