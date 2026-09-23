# renovate-automerge-sandbox

A throwaway repo to demonstrate safe auto-merging of dependency PRs.

Rules the auto-merge workflow enforces before merging a PR:
- CI must be fully green
- not a major version bump
- no merge conflicts

Major bumps and anything with red/pending CI are left open for a human.
