# Contributing

## Team workflow
Create features from develop. Use lowercase names with hyphens: `feature/catalog-page`, `feature/login-form`, `feature/contact-page`. Create urgent production fixes from main as `hotfix/footer-phone`.

Use at least two meaningful commits per feature. Prefix messages with `feat:`, `fix:`, `style:` or `docs:`. Keep each commit focused on one change.

After initial setup, do not commit directly to main or develop. Open a pull request with a clear title, description and test instructions. Merge features into develop with **Create a merge commit**, not squash or rebase. Request a real teammate review; never approve your own work or claim reviews that have not happened.

## Pull request checklist
- Correct base and compare branches.
- Only intended files changed; descriptive commits.
- Pages open without errors; links and forms work.
- Keyboard access and responsive layout checked.
- Teammate review completed from their own account.

## Hotfix and release
Merge the hotfix into main and back into develop. Release tested develop through a PR into main, then tag the release commit `v1.0.0` and push the tag.

Preserve all remote feature and hotfix branches until grading. Require a PR for main in repository branch protection settings; capture that rule for the lab evidence.
