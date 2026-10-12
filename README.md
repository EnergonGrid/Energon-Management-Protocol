# EMP

**Energon Management Protocol · Energon EVault**

EMP is the economic-management layer of the Energon ecosystem. The **Energon Management Protocol (EMP)** defines the economic framework; **Energon EVault** is the deployed smart-contract component that enforces its own on-chain rules.

These terms are related, but they are not interchangeable.

---

## Purpose

EVault provides the on-chain economic layer for:

- protocol reserves
- supported-asset contribution
- Guardian registration and eligibility
- commit and claim lifecycles
- maturity options
- payout-window controls
- reserve and liability protections
- fee accounting

EVault does not replace the Energon core protocol and does not control Guardian identity, EON maximum supply, EnergonCube ownership rules, or EnergonController progression.

---

## Mainnet Deployment

| Component | Version | Network | Address |
| --- | --- | --- | --- |
| Energon EVault | v5.8.0 | Flare Mainnet · Chain ID 14 | `0x4f4C84321f83f77e95359e16f472b130Ed15EF04` |

The deployed contract and live blockchain state are the source of truth for execution.

---

## Relationship to Energon

The Energon ecosystem is intentionally separated by responsibility.

**Energon Core**
- Energon Token (EON)
- EnergonCube
- EnergonController
- Guardian coherence and deterministic protocol progression

**EMP / EVault**
- reserves
- economic eligibility
- claims
- maturity
- payout limits
- economic safeguards

**EPA / Energon Network**
- project onboarding
- Nodes
- Project Adapters
- Registry-linked services and delivery infrastructure

EMP does not govern the Core or the Network.

---

## Repository Scope

This repository is the dedicated home for the production EMP / EVault system.

Planned repository material includes:

- verified EVault Solidity source
- production ABI
- Flare Mainnet deployment record
- EMP economic-rule documentation
- reserve and payout mechanics
- claim lifecycle documentation
- verified Mainnet testing records

Production source files will only be added from the verified deployment artifacts used for the live contract.

---

## Interfaces and Documentation

The public Energon DApp exposes the EMP interface at:

**https://mint.energon.app/evault**

The EMP reference document is available at:

**https://docs.energon.app/docs/energon-emp.pdf**

Main Energon overview:

**https://github.com/EnergonGrid/EnergonGrid**

---

## Source of Truth

If this repository, the EMP document, an interface, or any other description differs from the deployed implementation, the **deployed contracts and live blockchain state control actual execution**.

Documentation explains the system. It does not override contract law.

---

**EnergonGrid · Flare Mainnet**
