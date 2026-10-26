# Live Status

**Last public update:** 2026-10-26

```
HelixMind            : Operational (v1.2)
MFR-Cognition        : STABLE  v4.2.254  — workflow pins restored; CI still blocked by account billing
AetherMind           : Operational — cycle actions SHA-pinned
SovereignEvolution   : Active (v1.44) — daily actions SHA-pinned
Public Core Pro      : 2.1.38-pro (MIT, zero dependency)
Shared contracts     : RFC-0001 schemas (public handbook)
```

Verified signals (evidence-based):
- Public Core: `VERSION = "2.1.38-pro"` on repository main (product constant in version.py). Recent improvements: extracted CI_Z_SCORE named constant (previously magic 1.96) for approximate 95% CI clarity; previous PRIOR_STRENGTH, OPPOSITION_FACTOR extractions and O(n) multi-claim optimization. No numerical change to results, fingerprints, or status decisions. CLI invalid-weight robustness retained (exit code 2). Version-consistency CI job present. 38 unit tests pass. All analysis outputs satisfy analysis.schema.json. Docs aligned to version.py SSOT.
- Latest Core Pro CI: success on default branch (multi-Python 3.10-3.13 tests, mypy --strict, version consistency). AGENTS.md present with long-horizon section.
- Private engines: SHA-pinned workflow PRs merged. Local suites verified per prior PRs. GitHub Actions jobs on private repos remain blocked by account billing / spending limit. Local verification does not replace CI.
- AGENTS.md (Project Engineering Constitution including long-horizon priority and 2026-10-26 review footer) is present across FathiMind, Core Pro, public-signals, and private engines.
- Decision traces remain private; only redacted status is published here.

Not claimed here:
- Numeric HelixMind score (e.g. 100/100).
- Exact wall-clock proof of every scheduled job outside observed Actions runs.
- Current green status for private-repo CI (billing block active).

No secrets, tokens, hostnames, or private state files are published in this repository.
