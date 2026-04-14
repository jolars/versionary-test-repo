# versionary-test-repo

Test repository for trying Versionary simple mode.

## Workflows

- `versionary-check`: runs verify/plan on PRs and main pushes.
- `versionary-release-pr`: runs on each push to `main` (and manual trigger),
  creates/updates a release PR when releasable commits exist.
- `versionary-release`: runs on pushes to `main`, and if the merged commit is
  `chore(release): v*`, creates a git tag and GitHub Release.

## A Bug Fix!

## Major Change! Breaking!
