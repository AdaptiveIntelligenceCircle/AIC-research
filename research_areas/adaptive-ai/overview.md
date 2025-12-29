# Research Area: Adaptive AI

This document defines the **Adaptive AI research program** within AIC-research.
It corresponds to the folder `research_areas/adaptive_ai/` and formally specifies its scope, assumptions, models, and links to implementation.

---

## File: `overview.md`

### Scope

Adaptive AI in AIC-research studies **systems that modify their behavior over time while remaining controllable, auditable, and reversible**.

This research explicitly avoids defining adaptation as purely gradient-based learning.
Instead, adaptation is treated as a **system-level property** emerging from interaction between state, context, policy, and governance.

### Key Questions

* What does it mean for a system to adapt responsibly?
* How can adaptation occur without irreversible drift?
* Where should adaptation be constrained or refused?

---

## Closing Statement

Adaptive AI in AIC-research is not about making systems smarter at all costs.

It is about making **change itself a governed, inspectable, and reversible operation**.

If adaptation cannot be controlled, it should not occur.
