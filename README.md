# Base Template Repository

> A base template repository that all other template repos can inherit from to ensure tooling consistency

## Table of Contents

- [Base Template Repository](#base-template-repository)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [Supported Tooling](#supported-tooling)

## About

This is a template repository that is intended to be inherited by other template repositories *to ensure consistent common tool deployment across languages*.

This will also support *optional* tooling that services like GitHub offer in order to provide repository owners access to these features without them having to discover it themselves.

## Supported Tooling

The following common tooling is supported:

- [VS Code Dev Containers](.devcontainer/devcontainer.json)
- [GitHub](.github/)
  - See [this post](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file) for more information
  - [GitHub Discussion Templates](https://docs.github.com/en/discussions/managing-discussions-for-your-community/syntax-for-discussion-category-forms)
  - [GitHub Issue Templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository)
  - [GitHub Pull Request Templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/creating-a-pull-request-template-for-your-repository)
  - [GitHub Actions](https://docs.github.com/en/actions/writing-workflows)
- [Pre-Commit](.pre-commit-config.yaml)
- [Docker](Dockerfile)
- [Make](Makefile)
