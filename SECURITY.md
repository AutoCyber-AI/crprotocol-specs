# Security Policy

## Reporting a Security Vulnerability

If you discover a security vulnerability in the CRP specification or reference implementation, please report it **privately** before any public disclosure.

**Email:** [security@crprotocol.io](mailto:security@crprotocol.io)

Please include:
- A description of the vulnerability
- Which specification(s) or implementation component(s) are affected
- Potential impact assessment
- If known, a suggested mitigation or fix

We will acknowledge your report within **3 business days** and provide a remediation timeline within **10 business days**.

## Scope

This repository contains **specification documents only**. Security issues in the specifications include:

- Protocol-level weaknesses in the CRP header definitions
- HMAC or provenance chain vulnerabilities in CRP-SPEC-011
- Safety Policy bypass vectors in CRP-SPEC-006
- Regulatory compliance gaps in CRP-SPEC-010 or CRP-SPEC-015

Security issues in the reference implementation (`crp` Python package, CRP Comply, CRP Gateway) should also be reported to [security@crprotocol.io](mailto:security@crprotocol.io).

## Disclosure Policy

We follow coordinated disclosure. We ask that you allow us a reasonable remediation period before any public disclosure.

**Organisation:** AutoCyber AI Pty Ltd  
**Contact:** security@crprotocol.io
