# Evaluation Dimensions

This document defines the **core evaluation dimensions** of AIC,

independent of the specific model, algorithm, or architecture.

## 1. Behavioral Consistency

Does the system maintain consistent behavior when:

- The environment is noisy?

- Data is missing?

- Goals conflict?

Unexplained instability
is considered a risk indicator.

## 2. Introspective Validity

Does the system's internal explanation:

- Accurately reflect actual behavior?

- Is it consistent over time?

A "nice" but incorrect explanation
is considered a failure.

## 3. Temporal Stability

Is the current behavior still valid after:

- A long period of time?

- Multiple adaptation cycles?

A system that is only stable in the short term
does not meet AIC requirements.

## 4. Human Override Compatibility

Can humans:

- Intervene
- Stop

- Reverse

without causing the system to collapse or react?

## 5. Scope Containment

Does the system spontaneously expand its scope of action beyond its authorized target?

Any behavior exceeding the scope is negatively evaluated.