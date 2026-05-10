# Riven Trust Center (pointer)

The Riven Trust Center is hosted at https://trust.rivenai.io and served from the
static site scaffold in `riven-infra/traefik/static-sites/trust/`.

This directory holds the source of truth for the *content* shown on the public
trust page (controls, subprocessors, FAQ entries) so the riven-docs build can
generate a mirror at `/trust` for offline review.

## Source of truth
- Controls: riven-infra/traefik/static-sites/trust/data/controls.json
- Subprocessors: riven-infra/traefik/static-sites/trust/data/subprocessors.json
- Policies: riven-platform/docs/policies/

## Honesty rules
- Never claim certifications we do not hold.
- Mark in-progress items as `status: in_progress` with target date.
- Subprocessors list must be kept current; adding one requires a doc PR + customer notice per policy.
