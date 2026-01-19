# Simulation Logs Dataset

This folder contains logs generated from AIC simulation environments.

Simulation logs are treated as **primary research data**, not auxiliary artifacts.

## Contents

Typical logs include:
- scenario identifiers
- system state transitions
- scheduler decisions
- trust level changes
- ethical evaluations
- execution outcomes (approve / refuse / rollback)

Logs are expected to be time-ordered and immutable.

## Format Guidelines

Logs should be stored in:
- JSON
- CSV
- or other structured, machine-readable formats

Each log file must document:
- simulation configuration
- software version or commit hash
- policy snapshot identifier

## Usage

Simulation logs are used for:
- post-hoc analysis
- behavioral reproducibility
- failure mode classification

Logs must not be filtered to remove undesirable outcomes.
