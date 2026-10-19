# Repository guidance

## Pull request merge convention

- **Default to Squash and merge** for pull requests where the commits are all part of the same feature, bug fix, refactor, maintenance task, or other cohesive change. Use a single, descriptive squash commit title and summary so `main` stays readable.
- Do not mix unrelated work into one pull request solely to squash it. Split genuinely independent changes into separate PRs; preserve individual commits only when their separate history has a concrete value (for example, separately revertible migrations).
- Before merging, confirm the required checks have passed and verify the PR's final diff. Do not rewrite shared or published history just to retroactively squash it.
