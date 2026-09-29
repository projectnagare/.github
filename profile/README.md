# Project Nagare

**An open, programmable operating system for a fully digital bank.**

Nagare asks a simple question:

> If a bank were built from zero today — without branch-era assumptions, legacy core constraints, monolithic banking software, or AI bolted on after the fact — what would it look like?

We are building that stack from first principles.

## The core ideas

- **The bank is the branch.**
- **Everything is a plugin.**
- **The kernel stays small.**
- **Financial truth is deterministic.**
- **AI is an actor — and AI actors are plugins.**
- **Permissions are task-level.**
- **External applications and financial infrastructure connect through plugins.**
- **Simulation and production share one architecture.**
- **Consumer and Business are independently deployable bank distributions.**
- **Institutional is the bank's own operating view.**
- **Internal banking software should be as carefully designed as consumer software.**
- **All major Project Nagare decisions are logged centrally in nagare-home.**

## What we are building

Nagare is intended to become:

- a digital-bank operating system
- a continuously running synthetic bank
- a synthetic external financial ecosystem
- Consumer and Business banking distributions
- Institutional banking systems for treasury, risk, finance, compliance, fraud and operations
- a hosted sandbox where builders can use a complete fake bank
- a bank-in-waiting that can move from simulated integrations to production integrations without changing its fundamental architecture

## Repositories

### [nagare-home](https://github.com/projectnagare/nagare-home)
The central idea home: Constitution, architecture, major decisions, RFCs, roadmap and project vocabulary.

### [nagare-design-system](https://github.com/projectnagare/nagare-design-system)
Nagare's visual system, tokens, icons, UI packages and design study.

More repositories will appear as clear capability boundaries emerge. We deliberately avoid creating empty repositories simply to mirror an architecture diagram.

## Build philosophy

Nagare is architecture-led.

New capabilities should be introduced behind stable contracts, implementations should remain replaceable, AI should never become a privileged path through the bank, and financial truth must remain deterministic.

The project is designed so that a synthetic deployment and a future licensed deployment can share the same banking architecture.

---

Project Nagare is an experimental open-source banking project. It is not a licensed bank and does not provide real banking services.
