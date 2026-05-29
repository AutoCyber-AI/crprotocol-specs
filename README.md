<!-- SPDX-License-Identifier: CC-BY-4.0 -->
<!-- Copyright 2025–2026 AutoCyber AI Pty Ltd / Constantinos Vidiniotis -->

# Context Relay Protocol — Specifications

[![IETF Internet-Draft](https://img.shields.io/badge/IETF%20I--D-draft--vidiniotis--crp--headers-blue)](https://datatracker.ietf.org/doc/draft-vidiniotis-crp-headers/)
[![IANA Registration](https://img.shields.io/badge/IANA-Registration%20Pending-orange)](https://crprotocol.io/standards/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey)](LICENSE)

> **Context Relay Protocol (CRP)** is an open HTTP-header standard for AI context governance. It provides 58 structured safety headers enabling EU AI Act readiness, NIST AI RMF alignment, and auditable AI pipelines — without modifying LLM internals.

## Overview

CRP adds a thin, verifiable governance layer above any AI system:

- **58 standardised HTTP headers** covering safety, provenance, grounding, risk, and compliance
- **Language-agnostic** — works with any LLM, runtime, or AI gateway
- **Standards-track** — active IETF Internet-Draft (`draft-vidiniotis-crp-headers`)
- **Open specification** — CC BY 4.0; anyone may implement

| Resource | Link |
|----------|------|
| Full documentation | [crprotocol.io](https://crprotocol.io) |
| Compliance dashboard | [comply.crprotocol.io](https://comply.crprotocol.io) |
| IETF Internet-Draft | [datatracker.ietf.org/doc/draft-vidiniotis-crp-headers/](https://datatracker.ietf.org/doc/draft-vidiniotis-crp-headers/) |

---

## Specifications in this Repository

| Spec | Title | Status |
|------|-------|--------|
| [CRP-SPEC-001](CRP-SPEC-001-core-protocol.md) | Core Protocol Specification | Stable |
| [CRP-SPEC-002](CRP-SPEC-002-headers.md) | Header Field Specification | Stable |
| [CRP-SPEC-003](CRP-SPEC-003-envelope.md) | Context Envelope & Packing Specification | Stable |
| [CRP-SPEC-004](CRP-SPEC-004-continuation.md) | Window Continuation & DAG Specification | Stable |
| [CRP-SPEC-005](CRP-SPEC-005-dpe.md) | Decision Provenance Engine (DPE) Specification | Stable |
| [CRP-SPEC-006](CRP-SPEC-006-safety-policy.md) | Safety Policy Directive Language | Stable |
| [CRP-SPEC-008](CRP-SPEC-008-dispatch.md) | Dispatch Strategy Specification | Stable |
| [CRP-SPEC-009](CRP-SPEC-009-ckf.md) | Contextual Knowledge Fabric (CKF) Specification | Stable |
| [CRP-SPEC-010](CRP-SPEC-010-regulatory-mapping.md) | Regulatory Controls Mapping | Stable |
| [CRP-SPEC-011](CRP-SPEC-011-audit-trail.md) | Audit Trail & HMAC Chain Specification | Stable |
| [CRP-SPEC-013](CRP-SPEC-013-github-action.md) | GitHub Action & Scanner Specification | Stable |
| [CRP-SPEC-014](CRP-SPEC-014-conformance.md) | Conformance & Test Suite Specification | Stable |
| [CRP-SPEC-015](CRP-SPEC-015-security-privacy.md) | Security & Privacy Specification | Stable |
| [CRP-SPEC-017](CRP-SPEC-017-zero-ckf-mode.md) | Zero-CKF Mode & Progressive Activation | Stable |

### Not Included in this Repository

The following specifications relate directly to the CRP reference implementation and are not published here:

| Spec | Title | Reason |
|------|-------|--------|
| CRP-SPEC-007 | Session Token & State Relay | Reference implementation detail |
| CRP-SPEC-012 | Multi-Agent Safety Protocol | Reference implementation detail |
| CRP-SPEC-016 | Gateway Service Specification | Reference implementation detail |

The reference implementation is available under separate commercial terms. See [crprotocol.io/products](https://crprotocol.io/products/).

---

## Standards Track Status

| Track | Detail | Status |
|-------|--------|--------|
| IETF Internet-Draft | `draft-vidiniotis-crp-headers-00` | ✅ Submitted |
| IANA Header Registration | Ticket #1453152 | ⏳ Pending |
| Trademark | "Context Relay Protocol" | ✅ Filed |
| IETF IPR Disclosure | No-patents declaration | ⏳ Pending |
| WG Adoption Target | HTTPAPI WG / proposed AI-Control WG | 🔜 Future |

---

## Licensing

The specification documents in this repository are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE).

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — implement the specification in software, products, or services

Under the following terms:
- **Attribution** — You must give appropriate credit to AutoCyber AI Pty Ltd and Constantinos Vidiniotis, provide a link to this repository and [crprotocol.io](https://crprotocol.io), and indicate if changes were made.

> The CRP **reference implementation** (the Python `crp` package and CRP Comply service) is separately licensed under the Elastic License 2.0 and is **not** covered by CC BY 4.0.

---

## Contributing

This specification is maintained by **AutoCyber AI Pty Ltd**.

We welcome:
- **Issue reports** — inconsistencies, ambiguities, or errors in the spec text
- **IETF feedback** — responses via the IETF HTTP WG mailing list ([ietf-http-wg@w3.org](mailto:ietf-http-wg@w3.org))

We do **not** accept pull requests at this time. The specification is in a pre-standards-track phase; substantive changes are coordinated through the IETF process. This policy will be revisited upon Working Group formation.

---

## Contact

| | |
|-|-|
| **Organisation** | AutoCyber AI Pty Ltd |
| **Author** | Constantinos Vidiniotis |
| **Website** | [crprotocol.io](https://crprotocol.io) |
| **Compliance** | [comply.crprotocol.io](https://comply.crprotocol.io) |
| **IETF I-D** | [draft-vidiniotis-crp-headers](https://datatracker.ietf.org/doc/draft-vidiniotis-crp-headers/) |

---

*Copyright 2025–2026 AutoCyber AI Pty Ltd. The CRP specification is open; the reference implementation is not.*

