# Live Status

**Last public update:** 2026-10-23

```
HelixMind            : Operational (v1.2)
MFR-Cognition        : STABLE  v4.2.254  — workflow pins restored; CI still blocked by account billing
AetherMind           : Operational — cycle actions SHA-pinned
SovereignEvolution   : Active (v1.44) — daily actions SHA-pinned
Public Core Pro      : 2.1.19-pro (MIT, zero dependency)
Shared contracts     : RFC-0001 schemas (public handbook)
```

Verified signals (evidence-based):
- Public Core: `VERSION = "2.1.19-pro"` on repository main (product constant in version.py; packaging 2.1.19). Independence factor unified to single constant 0.6 (fixes prior 0.6/0.7 inconsistency in deduplication vs belief update). Unit tests pass (32 tests). Insufficient-evidence reports include fingerprint and question; pure-Python validate_report() contract checker present; all analysis outputs satisfy analysis.schema.json. Empty-question validation added in 2.1.17-pro. Public docs (README badge/text) aligned to SSOT on 2026-10-23.
- Latest Core Pro CI: success (run 39888634090) for the 2.1.19-pro push on main.
- Private engines: SHA-pinned workflow PRs merged on 2026-10-23 (MFR-Cognition #14, HelixMind #1, AetherMind #2, SovereignEvolution #1). Local suites verified per PR descriptions. GitHub Actions jobs on private repos remain blocked by account billing / spending limit ("job was not started because recent account payments have failed or your spending limit needs to be increased"). Local verification does not replace CI.
- Decision traces remain private; only redacted status is published here.
- AGENTS.md (Project Engineering Constitution, including long-horizon priority) is present and identical across public and private engines.

Not claimed here:
- Numeric HelixMind score (e.g. 100/100).
- Exact wall-clock proof of every scheduled job outside observed Actions runs.
- Current green status for private-repo CI (billing block active).

No secrets, tokens, hostnames, or private state files are published in this repository.
