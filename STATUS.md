# Live Status

**Last public update:** 2026-10-31

```
HelixMind            : Operational (v1.2)
MFR-Cognition        : STABLE  v4.2.256  — expanded host metrics, hardened redaction
AetherMind           : Operational — cycle actions SHA-pinned
SovereignEvolution   : Active (v1.44) — daily actions SHA-pinned
Public Core Pro      : 2.1.45-pro (MIT, zero dependency) — setup-python v7.1.0 aligned
Shared contracts     : RFC-0001 schemas (public handbook)
```

Verified signals (evidence-based):
- Public Core: `VERSION = "2.1.45-pro"` on repository main (product constant in version.py). 19 unit tests pass on Python 3.10 with 91% coverage (pytest-cov --cov-fail-under=90 now enforced in CI); decision-contract fields (`decision_confidence`, `stability`) and construction-time `prior_belief` validation present; unused imports cleaned; mypy --strict clean; version-consistency CI green. Zero-dependency MIT package. No change to analysis logic or fingerprints.
- AGENTS.md present with long-horizon section and current review footer across HQ, Core-Pro, and public-signals.
- Private engines: versions aligned per FathiMind handbook (Helix v1.2, Cognition v4.2.256, Aether v1.3, Evolution v1.44). Local suites verified in prior cycles. GitHub Actions on private repos may be affected by account billing limits; local verification does not replace CI.
- Decision traces remain private; only redacted status is published here.

Not claimed here:
- Numeric HelixMind score (e.g. 100/100).
- Exact wall-clock proof of every scheduled job outside observed Actions runs.
- Unverified CI green status for private-repo workflows under billing constraints.

No secrets, tokens, hostnames, or private state files are published in this repository.
