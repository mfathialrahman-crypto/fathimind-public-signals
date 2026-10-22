# Live Status

**Last public update:** 2026-10-22

```
HelixMind            : Operational (v1.2)
MFR-Cognition        : STABLE  v4.2.253  — version advanced; recent CI under observation; local suite verified
AetherMind           : Operational
SovereignEvolution   : Active (v1.44)
Public Core Pro      : 2.1.18-pro (MIT, zero dependency)
Shared contracts     : RFC-0001 schemas (public handbook)
```

Verified signals (evidence-based):
- Public Core: `VERSION = "2.1.18-pro"` on repository main (product constant in version.py; packaging 2.1.18). Unit tests pass in CI matrix (Python 3.10-3.13). Insufficient-evidence reports include fingerprint and question; pure-Python validate_report() contract checker present; all analysis outputs satisfy analysis.schema.json. Empty-question validation added in 2.1.17-pro. Public docs (README badge/text) aligned to SSOT on 2026-10-22.
- Latest Core Pro CI: success (matrix tests + demo + strict mypy) — see Actions runs on main (e.g. run 39761848415).
- MFR-Cognition: `version.py` reports `VERSION = "4.2.253"`. Recent Tests and scheduled Cognitive Cycle workflows on main concluded failure (investigation ongoing for Actions environment). Local full suite verified 2026-10-22: pytest 93% coverage (cov-fail-under=90 passed), ruff (I001,E,F,W), mypy strict on core modules, bandit -ll all clean. Console script version check passes.
- Decision traces remain private; only redacted status is published here.
- AGENTS.md (Project Engineering Constitution, including long-horizon priority) is present and identical across public and private engines.

Not claimed here:
- Numeric HelixMind score (e.g. 100/100).
- Exact wall-clock proof of every scheduled job outside observed Actions runs.
- Current green status for MFR-Cognition CI (see Actions; local verification does not replace CI).

No secrets, tokens, hostnames, or private state files are published in this repository.
