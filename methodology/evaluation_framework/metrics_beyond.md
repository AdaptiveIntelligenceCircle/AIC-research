# Metrics Beyond Accuracy

Accuracy only measures right and wrong under ideal conditions.

AIC requires measures that reflect **real-world reliability**.

## 1. Trust Decay Rate

How quickly or slowly does trust in the system decline when the environment changes?

Trust increases rapidly but collapses quickly
is a dangerous sign.

## 2. Explanation Coherence

Does the system's explanation:

- Have internal consistency?

- Match the behavior that occurred?

## 3. Rollback Success Rate

The percentage of the system that returns to a safe state when a rollback is triggered.

Rollback failure = system failure.

## 4. Intervention Cost

The cost (cognitive, technical, time) of human intervention.

Excessively high costs make overrides merely a formality.

## 5. Error Admission Latency

The time it takes for the system to recognize and admit an error.

The more intelligent the system, this time should be shorter.