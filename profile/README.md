<div align="center">

# AlgoVoi

**Self-hosted, post-quantum, offline-verifiable infrastructure for regulated records and agent payments.**

[Website](https://algovoi.co.uk) · [Documentation](https://docs.algovoi.co.uk) · [Store](https://api.algovoi.co.uk/suite-store) · [@algovoi](https://x.com/algovoi)

</div>

---

AlgoVoi Ltd builds infrastructure that runs entirely on your own machines, stays verifiable
without us in the trust path, and is signed for the post-quantum era. Everything ships under a
one-time perpetual licence, air-gap capable, signed with **Falcon-1024** and **ML-DSA-65**, and
verifiable **offline** against a published public key.

## Two product lines

### 🗄️ Verifiable Compliance Suite
A self-hosted, air-gap-capable estate for long-term regulated records and compliance evidence
(health, insurance, defence). Write-once, tamper-evident, content-addressed archive with
post-quantum signatures, RFC-3161 timestamps, legal holds, and offline verification. A
self-hosted alternative to managed cloud preservation such as Preservica and Arkivum.
→ [Overview](https://algovoi.co.uk/verifiable-compliance-suite.html) · [Docs](https://docs.algovoi.co.uk/verifiable-compliance-suite)

### 💳 Multi-protocol agent payment gateway
Chain-agnostic agent payment negotiation: an x402 facilitator running **x402, AP2, A2A and MPP**
across seven chains, where every settlement produces a signed, offline-verifiable receipt an auditor
recomputes offline with stock open-source tools. Operator custody, no phone-home. Run it three
ways: hosted pay-as-you-go, hosted multi-tenant, or self-hosted.
→ [Payment gateway](https://algovoi.co.uk/payment-gateway.html) · [Docs](https://docs.algovoi.co.uk/payment-rails-sqlite)

## Featured open source (Apache-2.0)

- [**avm-proofpack**](https://github.com/chopmob-cloud/avm-proofpack) — A Python library for
  offline Algorand and Voi state-proof verification: portable, recomputable transaction evidence.
- [**algovoi-rfc9421-verifier**](https://github.com/chopmob-cloud/algovoi-rfc9421-verifier) —
  RFC 9421 HTTP Message Signatures verifier (PyPI + npm).
- [**algovoi-key-credential-binding**](https://github.com/chopmob-cloud/algovoi-key-credential-binding) —
  Key-credential binding for agent payments, with RFC 9421 conformance vectors (PyPI + npm).
- [**algovoi-jcs-conformance-vectors**](https://github.com/chopmob-cloud/algovoi-jcs-conformance-vectors) —
  Cross-implementation JCS (RFC 8785) canonicalisation conformance vectors.
- [**AlgoVoi-Platform-Adapters**](https://github.com/chopmob-cloud/AlgoVoi-Platform-Adapters) —
  MCP adapters for the AlgoVoi platform (listed on Glama).

## What makes the estate different

- **Post-quantum by default** — Falcon-1024 and ML-DSA-65 (FIPS 204) signatures, so evidence stays verifiable for decades.
- **Offline-verifiable** — receipts and records recompute from their own bytes under RFC 8785 (JCS) and SHA-256; no vendor, no node required.
- **Operator custody** — your keys, your funds, your evidence, on your own servers.
- **Perpetual licence** — one-time, no subscription, no per-record fee.

---

<div align="center">
<sub>AlgoVoi Ltd · <a href="https://algovoi.co.uk">algovoi.co.uk</a> · Standards: RFC 8785 · RFC 9421 · RFC 3161 · FIPS 204</sub>
</div>
