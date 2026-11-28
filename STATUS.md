# Live Status

**Last public update:** 2026-11-28

```
HelixMind            : Operational (v1.2)
MFR-Cognition        : STABLE  v4.2.257  — expanded host metrics, hardened redaction
AetherMind           : Operational — cycle actions SHA-pinned
SovereignEvolution   : Active (v1.44) — daily actions SHA-pinned
Public Core Pro      : 2.1.80+pro (MIT, zero dependency) — CLI stdin support + argparse, pure-Beta CI, status fix for weak top-claim, CI green, mypy --strict clean, 34 tests, 99% coverage
Shared contracts     : RFC-0001 schemas (public handbook)
```

Verified signals (evidence-based):
- Public Core: `VERSION = "2.1.80+pro"` on repository main (product constant in version.py). Version sources aligned (version.py + pyproject.toml + README badge). Decision-contract fields present. Pure-Python report validator present. Zero-dependency MIT package. README version badge and text aligned. AGENTS.md review footer refreshed. Pure Beta posterior CI calculation applied (no double-counted sqrt(n)). Status decision corrected so weak top claim (mean < 0.55, evidence_count < 2) yields INSUFFICIENT_EVIDENCE. CLI: `--json` accepts `-` or omitted for stdin; switched to argparse. Fingerprint type-guard regression present. Coverage gate ≥90% enforced in CI. 34 tests passed, 99% coverage, mypy --strict clean.
- AGENTS.md present with long-horizon section and current review footer across HQ, Core-Pro, and public-signals.
- Private engines: versions aligned per FathiMind handbook (Helix v1.2, Cognition v4.2.257, Aether v1.3, Evolution v1.44). Local suites verified in prior cycles. GitHub Actions on private repos may be affected by account billing limits; local verification does not replace CI.
- Decision traces remain private; only redacted status is published here.

Not claimed here:
- Numeric HelixMind score (e.g. 100/100).
- Exact wall-clock proof of every scheduled job outside observed Actions runs.
- Unverified CI green status for private-repo workflows under billing constraints.
- Exact current test count without fresh local run in this cycle.

No secrets, tokens, hostnames, or private state files are published in this repository.
