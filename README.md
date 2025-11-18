# The Product Security Handbook

This repository contains the source for the Product Security Handbook, which is built using [MkDocs](https://www.mkdocs.org/)
and the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme.

## Development Setup

### Python

This site uses [mkdocs-material](https://squidfunk.github.io/mkdocs-material/). It is recommended to use a virtual
environment to manage dependencies.

To install dependencies, run:

```bash
pip install -r requirements/local.txt
```

### Running Locally

To run the site locally, use the following command:

```bash
mkdocs serve --livereload
```

### Pre-commit

Pre-commit is included in the local requirements file. If you'd like an alternative installation method, visit the
[pre-commit](https://pre-commit.com/#install) website for installation instructions.

To install the git hooks, run the following command:

```bash
pre-commit install
```

To manually run the pre-commit hooks against all files, use:

```bash
pre-commit run --all-files
```

## Submitting Changes

This repo follows a git trunk-based development workflow. Branches should be created from the `main` branch, and pull
requests should be made against `main`. When submitting changes, please ensure that your commits are signed.

### Github Commit Signing

Signed commits are required for this repository. Please refer to the following resources for guidance on signing your commits:

- [troyfontaine Signing Git Commits on MacOS](https://gist.github.com/troyfontaine/18c9146295168ee9ca2b30c00bd1b41e?permalink_comment_id=3660126)
- [https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits](https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits)
- [https://docs.github.com/en/authentication/managing-commit-signature-verification/telling-git-about-your-signing-key](https://docs.github.com/en/authentication/managing-commit-signature-verification/telling-git-about-your-signing-key)
