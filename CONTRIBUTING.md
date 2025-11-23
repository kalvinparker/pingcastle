## Branching Strategy: Gitflow Workflow

We use the Gitflow model to manage our development lifecycle. All feature development must be done against the 'develop' branch.

**Feature Branches:** Branch from `develop`. Merge back to `develop` via Pull Request.
**Hotfixes:** Branch from `main`. Merge to `main`, then merge immediately to `develop`.

No direct pushes to 'main' or 'develop' are allowed.
