# Research Area: Adaptive AI

This document defines the **Adaptive AI research program** within AIC-research.
It corresponds to the folder `research_areas/adaptive_ai/` and formally specifies its scope, assumptions, models, and links to implementation.

---

## File: `mapping_to_code.md`

### AIC Integration

This research area maps directly to:

* `AIC/modules/behavior/`
* `AIC/modules/control/`
* `AIC/runtime/rollback_engine`

### IBCS Integration

* `runtime/behavior_sandbox.cpp`
* `runtime/reaction_loop.cpp`

### Verification

Each adaptation mechanism must:

* Emit traces
* Support rollback
* Be testable via simulation in `experiments/`

---

## Closing Statement

Adaptive AI in AIC-research is not about making systems smarter at all costs.

It is about making **change itself a governed, inspectable, and reversible operation**.

If adaptation cannot be controlled, it should not occur.
