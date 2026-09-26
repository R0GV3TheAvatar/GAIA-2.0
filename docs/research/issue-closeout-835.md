# Closeout — #835 CI lock

Existing blockers already on main:
- `.github/workflows/canon-integrity.yml`
- `.github/workflows/canon-proof-gate.yml`

This PR adds `.github/workflows/tablet-validation.yml` as the named #835 wrapper. It runs the same two scripts.

Honest leftover: GitHub branch-protection required-check box is owner-only. No PR comment bot. No separate `validate-tablets` binary from #813 (that script was never landed as that name).
#798 stays open.
