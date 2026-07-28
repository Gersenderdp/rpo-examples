# OpenProof — RPO Examples

> **OpenProof is the probative infrastructure. TruthX Engine is the deterministic structuring engine powering it. RPO is the Registered Probative Object it produces.**

This repository contains public examples of **Registered Probative Objects (RPOs)**.

They demonstrate how fragmented evidence can be transformed into structured, traceable and machine-verifiable records for human review.

## Role in the architecture

| Component | Role |
|---|---|
| **TruthX Engine** | Structures heterogeneous evidence through a controlled, deterministic pipeline. |
| **RPO** | Preserves the resulting record, its sources, transformations, reservations and integrity data. |
| **OpenProof** | Provides the probative infrastructure and verification layer. |

**Processing chain:**

`Evidence → TruthX Engine → RPO → OpenProof validation`

## What these examples demonstrate

Each example illustrates how an RPO can preserve:

- source references and evidence provenance;
- chronology and structured relationships;
- explicit transformations and reasoning steps;
- reservations, uncertainties and unresolved contradictions;
- integrity data for subsequent verification;
- a clear separation between evidence, analysis and decision.

## Example domains

The repository currently illustrates several high-stakes contexts:

- HR decision governance;
- institutional crisis response;
- audit traceability.

These examples are demonstrators. They do not contain final institutional, legal or judicial determinations.

## Explore the simulator

A public simulator is available here:

[OpenProof RPO Simulator](https://rpo.openproof.net/simulator.html)

The simulator illustrates the construction of a structured probative record. The deterministic structuring function belongs to **TruthX Engine**; OpenProof provides the surrounding probative infrastructure and validation layer.

## Official specification

The canonical public RPO specification is maintained here:

[openproof-net/rpo-spec-v0.1](https://github.com/openproof-net/rpo-spec-v0.1)

## Scope and limits

These examples demonstrate structure, traceability and verifiability.

They do **not**:

- establish that an allegation is true;
- determine the legal weight of evidence;
- replace investigation, expertise or adversarial review;
- make institutional, judicial or governance decisions.

**Automation supports judgment. It does not replace authority or accountability.**

## Related repositories

- [RPO Specification](https://github.com/openproof-net/rpo-spec-v0.1) — canonical public specification.
- [RPO Reference](https://github.com/Gersenderdp/rpo-reference) — reference implementation of the specification.
- [OpenProof Validator](https://github.com/Gersenderdp/openproof-validator) — conformity and integrity validation tools.

## Maintainer

Maintained by [Gersende de Parcey](https://github.com/Gersenderdp), founder of TruthX and builder of OpenProof.
