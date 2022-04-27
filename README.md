# Flexlate After-Conflict Action

Official Flexlate Github Action to be used after resolving merge conflict PRs

## Inputs

- `branch_name`: The flexlate-templates branch name that was used in resolving the merge conflict. Defaults to the branch name of the PR.
- `gh_token`: The Github token to use for authentication
- `main_branch`: The main branch for the repository. Defaults to `master`.

## Outputs

## Examples

## Development Status

This project uses [semantic-release](https://github.com/semantic-release/semantic-release) for versioning.
Any time the major version changes, there may be breaking changes. If it is working well for you, consider
pegging to the current major version, e.g. `flexlate-after-conflict-action@v1`, to avoid breaking changes. Alternatively,
you can always point to the most recent stable release with the `flexlate-after-conflict-action@latest`.

## Developing

Clone the repo and then run `npm install` to set up the pre-commit hooks.

## Author

Created by Nick DeRobertis. MIT License.
