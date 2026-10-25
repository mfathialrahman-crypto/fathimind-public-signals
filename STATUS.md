# Live Status

**Last public update:** 2026-10-25

```
HelixMind            : Operational (v1.2)
MFR-Cognition        : STABLE  v4.2.254  — workflow pins restored; CI still blocked by account billing
AetherMind           : Operational — cycle actions SHA-pinned
SovereignEvolution   : Active (v1.44) — daily actions SHA-pinned
Public Core Pro      : 2.1.34-pro (MIT, zero dependency)
Shared contracts     : RFC-0001 schemas (public handbook)
```

Verified signals (evidence-based):
- Public Core: `VERSION = "2.1.34-pro"` on repository main (product constant in version.py). Recent improvements: O(n) multi-claim opposition calculation (scalability, no numerical change); CLI `--evidence` invalid-weight handling exits cleanly with code 2 (regression test added); version-consistency CI job enforces version.py / pyproject.toml alignment; 38 unit tests pass covering decision contract mapping, demo path, and validation edge cases. All analysis outputs satisfy analysis.schema.json. Public docs and badges aligned to SSOT.
- Latest Core Pro CI: success on default branch. AGENTS.md present with long-horizon section.
- Private engines: SHA-pinned workflow PRs merged. Local suites verified per prior PRs. GitHub Actions jobs on private repos remain blocked by account billing / spending limit. Local verification does not replace CI.
- AGENTS.md (Project Engineering Constitution including long-horizon priority and 2026-10-25 review footer) is present across FathiMind, Core Pro, public-signals, and private engines.
- Decision traces remain private; only redacted status is published here.

Not claimed here:
- Numeric HelixMind score (e.g. 100/100).
- Exact wall-clock proof of every scheduled job outside observed Actions runs.
- Current green status for private-repo CI (billing block active).

No secrets, tokens, hostnames, or private state files are published in this repository.
