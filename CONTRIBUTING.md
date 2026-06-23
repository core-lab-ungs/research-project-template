# Contributing to This Project

Thank you for contributing to this CORE Lab UNGS project.

## General Workflow

1. Create an issue describing the proposed change.
2. Create a branch from `main`.
3. Make focused and documented changes.
4. Run the available tests and experiments.
5. Submit a pull request for review.
6. Do not merge changes without approval from a project maintainer.

## Branch Naming

Use descriptive branch names:

- `feature/short-description`
- `fix/short-description`
- `docs/short-description`
- `experiment/short-description`

## Commit Messages

Write concise commit messages using the imperative form.

Examples:

- `Add network traffic parser`
- `Fix dataset preprocessing`
- `Document reproduction procedure`
- `Update experimental configuration`

## Reproducibility

Changes affecting experiments must document:

- software and dependency versions;
- input data;
- configuration parameters;
- random seeds, when applicable;
- expected outputs;
- approximate execution time.

## Data and Security

Do not commit:

- passwords, tokens, credentials, or private keys;
- personal or confidential information;
- restricted or improperly licensed datasets;
- generated files that are too large for Git;
- machine-specific absolute paths.

Use relative paths and provide instructions for obtaining external data.

## Authorship and Attribution

Contributions must be recorded accurately in `AUTHORS.md`.

Participation in the project does not automatically imply authorship of future papers. Publication authorship must reflect substantive intellectual contributions.

## Code Review

Pull requests should be:

- limited to one clear objective;
- documented;
- reproducible;
- reviewed before merging into `main`.
