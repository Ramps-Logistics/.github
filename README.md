# Ramps-Logistics/.github

Org-wide shared workflows.

- `.github/workflows/dependabot-gate.yml` — fails a PR while the repo has open
  critical or high Dependabot alerts. Repos call it from
  `.github/workflows/dependabot-gate-caller.yml`; the org ruleset requires the
  `dependabot-gate / check` status on default branches.

