# dependabot-auto-merge

Generate changesets for Dependabot PRs and auto-merge them if the update type is patch or minor.

- dependabot/fetch-metadata
- checkout
- kt-actions/generate-changesets-dependabot
- commit & push if any changes
- enable auto-merge of the PR

At the moment only npm changes are supported.
