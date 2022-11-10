# Flexlate After-Conflict Action

Official Flexlate Github Action to be used after resolving merge conflict PRs

This action is not intended to be used directly. It is used by the
[Flexlate After-Merge Action](https://github.com/nickderobertis/flexlate-merge-action)
to merge the `flexlate-templates-` branch from the merge conflict resolution PR into
the feature branch and open a new PR into the main branch.

## Inputs

- `branch_name`: The flexlate-templates branch name that was used in resolving the merge conflict. Defaults to the branch name of the PR.
- `gh_token`: The Github token to use for authentication
- `main_branch`: The main branch for the repository. Defaults to `master`.

## Development Status

This project uses [semantic-release](https://github.com/semantic-release/semantic-release) for versioning.
Any time the major version changes, there may be breaking changes. If it is working well for you, consider
pegging to the current major version, e.g. `nickderobertis/flexlate-after-conflict-action@v1`, to avoid breaking changes. Alternatively,
you can always point to the most recent stable release with the `nickderobertis/flexlate-after-conflict-action@latest`.

## Developing

Clone the repo and then run `npm install` to set up the pre-commit hooks.

## Author

Created by Nick DeRobertis. MIT License.
