# Directory Contents

This document describes the purpose and expected contents of each
top-level directory in this repository.

It serves as a reference for contributors and as a long-term reminder
of how the project is structured and intended to evolve.

---

## docs/

Conceptual and technical documentation related to the project.

Typical contents:
- system architecture descriptions and diagrams
- documented design and architecture decisions
- experiment notes and observations
- rationale behind technical choices and trade-offs

The documentation provides deeper technical context for the codebase
and complements the public project website.

---

## infrastructure/

Infrastructure-related code and configuration.

Typical contents:
- isolated network setup (addressing, routing, firewalling)
- MQTT broker configuration
- provisioning and deployment scripts
- reproducibility notes and environment setup instructions

The focus is on creating a controlled and repeatable environment
for the edge devices.

---

## edge/

Software intended to run on the Raspberry Pi edge devices.

Typical contents:
- node communication logic
- message handling and routing
- local coordination and control logic
- interaction with sensors or simulated inputs
- configuration and startup scripts

The code prioritizes robustness, clarity, and maintainability.

---

## ml/

Optional and exploratory machine learning–related components.

Typical contents:
- data preparation utilities
- experimental training pipelines
- inference prototypes
- non-final evaluation helpers

All ML-related work in this directory is considered experimental
and subject to change.

---

## tools/

Supporting tools and helper scripts used during development.

Typical contents:
- simulators for edge nodes or messaging
- test and debugging utilities
- data generators
- maintenance and automation scripts

These tools support experimentation but are not core system components.
