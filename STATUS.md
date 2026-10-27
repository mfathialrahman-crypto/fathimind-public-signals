# Live Status

**Last public update:** 2026-10-27

```
HelixMind            : Operational (v1.2)
MFR-Cognition        : STABLE  v4.2.254  — workflow pins restored; CI still blocked by account billing
AetherMind           : Operational — cycle actions SHA-pinned
SovereignEvolution   : Active (v1.44) — daily actions SHA-pinned
Public Core Pro      : 2.1.42-pro (MIT, zero dependency)
Shared contracts     : RFC-0001 schemas (public handbook)
```

Verified signals (evidence-based):
- Public Core: `VERSION = "2.1.42-pro"` on repository main (product constant in version.py). Recent improvements: `--evidence-file` now accepts documented object format (with question, prior_belief, alternatives) in addition to bare array; CLI prefers explicit args then file values. 39 unit tests pass. Coverage ~69% on core module. No change to analysis logic, fingerprints, or numerical results for array format. Version aligned across version.py, pyproject.toml, and README. Latest CI success on default branch.
- AGENTS.md present with long-horizon section and current review footer.
- Private engines: SHA-pinned workflow PRs merged. Local suites verified per prior PRs. GitHub Actions jobs on private repos remain blocked by account billing / spending limit. Local verification does not replace CI.
- AGENTS.md (Project Engineering Constitution including long-horizon priority) is present across FathiMind, Core Pro, public-signals, and private engines.
- Decision traces remain private; only redacted status is published here.

Not claimed here:
- Numeric HelixMind score (e.g. 100/100).
- Exact wall-clock proof of every scheduled job outside observed Actions runs.
- Current green status for private-repo CI (billing block active).

No secrets, tokens, hostnames, or private state files are published in this repository.
