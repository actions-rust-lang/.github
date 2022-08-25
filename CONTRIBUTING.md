# Contributing to the `actions-rust-lang` project

The following is a set of guidelines for contributing to `actions-rust-lang`.

## Reporting bugs

Before creating bug reports, please check the GitHub issues list for Action you are using as you might find out that you don't need to create one.
When you are creating a bug report, please include as many details as possible.

1. Use a clear and descriptive title for the issue to identify the problem.
2. Describe the exact steps which reproduce the problem in as many details as possible.
3. Provide specific examples to demonstrate the steps.
    Include links to the workflow files (pointing to the specific commit, and not to the `main`/`master` branch) and attach step logs to the issue (consider enabling [debug logs](https://github.com/actions/toolkit/blob/master/docs/action-debugging.md) first).
4. Describe the behavior you observed after following the steps and point out what exactly is the problem with that behavior.
5. Explain which behavior you expected to see instead and why.

## Feature requests

New ideas are welcomed!\
Feature requests are also tracked as a GitHub issues in the corresponding Action repositories.

Explain the idea and include as much additional details as possible:

1. Use a clear and descriptive title for the issue
2. Describe your motivation and how Rust community could benefit from this change
3. Provide workflow step examples, if applicable
4. Include links to the related tools, alternative implementations or any other information sources

### Backwards compatibility

Please note that maintaining backwards compatibility is important and any changes that require new major version might be postponed untill there are enough changes for a new major release.
