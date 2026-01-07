# CoSiLoN - LAb

( (Co)nstruction (Si)ite (Lo)cal (N)etwork - Lab)

This repository contains a laboratory project focused on building and evaluating
an isolated network using Raspberry Pi–based edge devices.
The network's aim isto represent a local construction site network, which is used 
(with different hardware) in reality.


The project explores how distributed edge nodes can communicate and operate
in a controlled, offline-capable environment, with a strong emphasis on
system design, infrastructure, and traceable technical decisions.

This repository represents an evolving technical project and serves as a
hands-on environment for experimenting with edge systems and networked devices.
It is not intended to represent a finished or production-ready system.

---

## Motivation & Approach

I enjoy developing systems where software does not exist in isolation,
but interacts with real hardware and real-world constraints.

This project is driven by the goal of:
- understanding how isolated networks behave in practice
- designing clear and maintainable system structures
- combining infrastructure, edge software, and experimentation in a transparent way

Technologies are chosen deliberately and used where they are meaningful and
controllable. The focus is on clarity, robustness, and understanding rather than
on completeness or feature breadth.

Learning and experimentation are explicit parts of the process and are treated
as first-class aspects of system development.

---

## Project Scope

The primary goals of this project are:

- designing and operating an isolated network
- connecting and coordinating multiple Raspberry Pi–based edge devices
- experimenting with messaging and communication patterns (e.g. MQTT)
- documenting architectural and technical decisions
- building a reproducible environment for system-level experimentation

The project prioritizes **system understanding, traceability, and controlled
iteration** over performance tuning or production optimization.

---

## Repository Structure

```text
docs/            Conceptual and technical documentation
infrastructure/  Network, messaging, and deployment-related setup
edge/            Software running on Raspberry Pi edge devices
ml/              Experimental machine learning components (optional)
tools/           Supporting tools and helper scripts

