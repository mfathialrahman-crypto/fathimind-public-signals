# Live Status

**Last public update:** 2026-10-19

```
HelixMind            : Operational (v1.2)
MFR-Cognition        : STABLE  v4.2.246  — Tests + scheduled Cognitive Cycle: success
AetherMind           : Operational
SovereignEvolution   : Active (v1.44)
Public Core Pro      : 2.1.14-pro (MIT, zero dependency)
Shared contracts     : RFC-0001 schemas (public handbook)
```

Verified signals (evidence-based):
- Public Core: `VERSION = "2.1.14-pro"` on repository main (product constant in mfr_core_pro.py; packaging 2.1.14). All 20 unit tests pass locally and in CI matrix (Python 3.10-3.13). Full implementation restored after truncation; `to_fathimind_decision()` mapper, conflict threshold, CLI `--decision` and evidence-file supported.
- Latest Core Pro CI: success (matrix tests + demo + strict mypy) — see Actions run for the 2.1.14-pro restore.
- MFR-Cognition: `version.py` reports 4.2.246; latest Tests and scheduled Cognitive Cycle workflows on main conclude success.
- Decision traces remain private; only redacted status is published here.
- AGENTS.md (Project Engineering Constitution, including long-horizon priority) is present and identical across public and private engines.

Not claimed here:
- Numeric HelixMind score (e.g. 100/100).
- Exact wall-clock proof of every scheduled job outside observed Actions runs.

No secrets, tokens, hostnames, or private state files are published in this repository.
