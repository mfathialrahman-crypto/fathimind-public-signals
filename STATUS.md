# Live Status

**Last public update:** 2026-11-11

```
HelixMind            : Operational (v1.2)
MFR-Cognition        : STABLE  v4.2.256  — expanded host metrics, hardened redaction
AetherMind           : Operational — cycle actions SHA-pinned
SovereignEvolution   : Active (v1.44) — daily actions SHA-pinned
Public Core Pro      : 2.1.59-pro (MIT, zero dependency) — type-safe ClaimStat TypedDict, mypy --strict clean, 42 tests
Shared contracts     : RFC-0001 schemas (public handbook)
```

Verified signals (evidence-based):
- Public Core: `VERSION = "2.1.59-pro"` on repository main (product constant in version.py). CHANGELOG documents type-safety (ClaimStat TypedDict) and prior competing_claims fix. Independent local verification: 42/42 tests passed, mypy --strict clean. Decision-contract fields present. Alternatives included in content-addressable fingerprint. Pure-Python report validator present. Zero-dependency MIT package. Version consistency gate between version.py and pyproject.toml reliable. README version badge and text aligned.
- AGENTS.md present with long-horizon section and current review footer across HQ, Core-Pro, and public-signals.
- Private engines: versions aligned per FathiMind handbook (Helix v1.2, Cognition v4.2.256, Aether v1.3, Evolution v1.44). Local suites verified in prior cycles. GitHub Actions on private repos may be affected by account billing limits; local verification does not replace CI.
- Decision traces remain private; only redacted status is published here.

Not claimed here:
- Numeric HelixMind score (e.g. 100/100).
- Exact wall-clock proof of every scheduled job outside observed Actions runs.
- Unverified CI green status for private-repo workflows under billing constraints.

No secrets, tokens, hostnames, or private state files are published in this repository.
