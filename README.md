# Flexlate After-Main Merge Action

Official Flexlate Github Action to merge feature Flexlate branches into main Flexlate branches

## Inputs

- `branch_name`: The name of the base branch that the Flexlate branches were created on. For example
  if you have a branch `template-patches` with corresponding Flexlate branches `flexlate-templates-template-patches`
  and `flexlate-output-template-patches`, then the `branch_name` would be `template-patches`.

## Outputs

## Examples

## Development Status

This project uses [semantic-release](https://github.com/semantic-release/semantic-release) for versioning.
Any time the major version changes, there may be breaking changes. If it is working well for you, consider
pegging to the current major version, e.g. `flexlate-after-main-merge-action@v1`, to avoid breaking changes. Alternatively,
you can always point to the most recent stable release with the `flexlate-after-main-merge-action@latest`.

## Developing

Clone the repo and then run `npm install` to set up the pre-commit hooks.

## Author

Created by Nick DeRobertis. MIT License.
