# Live Status

**Last public update:** 2026-10-27

```
HelixMind            : Operational (v1.2)
MFR-Cognition        : STABLE  v4.2.254  — workflow pins restored; CI still blocked by account billing
AetherMind           : Operational — cycle actions SHA-pinned
SovereignEvolution   : Active (v1.44) — daily actions SHA-pinned
Public Core Pro      : 2.1.41-pro (MIT, zero dependency)
Shared contracts     : RFC-0001 schemas (public handbook)
```

Verified signals (evidence-based):
- Public Core: `VERSION = "2.1.41-pro"` on repository main (product constant in version.py). Recent improvements: CLI regression fixed (full argument parser and demo() restored after accidental removal during magic-number extraction in v2.1.40-pro); named constants retained (CONFLICT_SECOND_THRESHOLD, STABLE_CONFIDENCE_THRESHOLD, FALLBACK_VARIANCE, VARIANCE_FLOOR, CI_Z_SCORE, PRIOR_STRENGTH, OPPOSITION_FACTOR, INDEPENDENCE_FACTOR). No numerical change to results, fingerprints, or status decisions. 38 unit tests pass. mypy --strict clean. All analysis outputs satisfy analysis.schema.json. Version aligned across version.py, pyproject.toml, and README. Latest CI run success on default branch (multi-Python 3.10–3.13 tests, mypy --strict, version consistency).
- AGENTS.md present with long-horizon section and current review footer.
- Private engines: SHA-pinned workflow PRs merged. Local suites verified per prior PRs. GitHub Actions jobs on private repos remain blocked by account billing / spending limit. Local verification does not replace CI.
- AGENTS.md (Project Engineering Constitution including long-horizon priority) is present across FathiMind, Core Pro, public-signals, and private engines.
- Decision traces remain private; only redacted status is published here.

Not claimed here:
- Numeric HelixMind score (e.g. 100/100).
- Exact wall-clock proof of every scheduled job outside observed Actions runs.
- Current green status for private-repo CI (billing block active).

No secrets, tokens, hostnames, or private state files are published in this repository.
