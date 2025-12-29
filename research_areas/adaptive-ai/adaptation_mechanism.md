# Research Area: Adaptive AI

This document defines the **Adaptive AI research program** within AIC-research.
It corresponds to the folder `research_areas/adaptive_ai/` and formally specifies its scope, assumptions, models, and links to implementation.

---

## File: `adaptation_mechanisms.md`

### Classes of Adaptation

1. **Rule-Based Adaptation**

   * Explicit condition → action updates
   * High controllability, low flexibility

2. **Probabilistic Adaptation**

   * Bayesian updates
   * Confidence-aware adjustments

3. **Hybrid Adaptation**

   * Deterministic core + probabilistic tuning
   * Implemented via Lua/C++ boundaries in AIC

### Non-Goals

* End-to-end neural policy replacement
* Unbounded self-modification

---

## Closing Statement

Adaptive AI in AIC-research is not about making systems smarter at all costs.

It is about making **change itself a governed, inspectable, and reversible operation**.

If adaptation cannot be controlled, it should not occur.
