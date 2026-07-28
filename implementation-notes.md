# Implementation notes

- Rebased `trunk` onto `origin/trunk` and kept the local profile text during conflict resolution.
- Replaced the scheduled, write-enabled Hermes updater with a manual, read-only no-op workflow.
- Left the pre-existing untracked files untouched.
- Verified with `git diff --check`, a conflict-marker scan, workflow-source search, and zero LSP diagnostics. `actionlint` is not installed, so its check remains unverified.
