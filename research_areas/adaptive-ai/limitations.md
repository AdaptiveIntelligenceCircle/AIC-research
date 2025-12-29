# Research Area: Adaptive AI

This document defines the **Adaptive AI research program** within AIC-research.
It corresponds to the folder `research_areas/adaptive_ai/` and formally specifies its scope, assumptions, models, and links to implementation.

---

## File: `limitations.md`

### Known Limitations

* Adaptation increases system complexity
* Long-term behavior is difficult to predict
* Human oversight does not scale trivially

### Explicit Boundaries

Adaptive AI should **not** be deployed in:

* Safety-critical domains without containment
* Environments lacking rollback capability

---

## Closing Statement

Adaptive AI in AIC-research is not about making systems smarter at all costs.

It is about making **change itself a governed, inspectable, and reversible operation**.

If adaptation cannot be controlled, it should not occur.
