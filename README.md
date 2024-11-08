# Base Template Repository

> A base template repository that all other *template repos* can inherit from to
> ensure tooling consistency

## Table of Contents

- [Base Template Repository](#base-template-repository)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [Supported Tooling](#supported-tooling)
    - [Visual Studio Code](#visual-studio-code)
      - [Development Containers](#development-containers)
    - [GitHub](#github)
      - [Discussion Templates](#discussion-templates)
      - [Actions](#actions)
      - [Issue Templates](#issue-templates)
      - [Pull Request Templates](#pull-request-templates)

## About

This is a template repository that is intended to be inherited by other template
repositories *to ensure consistent common tool deployment across languages*.

This will also support *optional* tooling that services like GitHub offer in
order to provide repository owners access to these features without them having
to discover it themselves.

Additionally, while projects can leverage this template or its content, this
template is primarily intended to build other templates off of it.

## Supported Tooling

### Visual Studio Code

#### Development Containers

- File: [.devcontainer/devcontainer.json](.devcontainer/devcontainer.json)
- Documentation:
  [https://containers.dev/implementors/json_reference](https://containers.dev/implementors/json_reference)
- Base image: [alpine:latest](https://hub.docker.com/_/alpine/)
- Extensions:
  - [CodeSnap](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap)
  - [File Tree Generator](https://marketplace.visualstudio.com/items?itemName=Shinotatwu-DS.file-tree-generator)
  - [Markdown All In One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
  - [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
  - [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
  - [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
  - [Makefile Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.makefile-tools)
  - [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

### GitHub

- File(s): [.github/](.github/)
- Documentation:
  [https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
- Features
  - [Citations](CITATION.cff)
  - [Code Of Conduct](.github/CODE_OF_CONDUCT.md)
  - [Code Owners](.github/CODEOWNERS)
  - [Contributing Guide](.github/CONTRIBUTING.md)
  - [Funding](.github/FUNDING.yml)
  - [Governance](.github/GOVERNANCE.md)
  - [Security](.github/SECURITY.md)
  - [Support](.github/SUPPORT.md)

#### Discussion Templates

- File(s): [.github/DISCUSSION_TEMPLATE/](.github/DISCUSSION_TEMPLATE/)
- Documentation:
  [https://docs.github.com/en/discussions/managing-discussions-for-your-community/creating-discussion-category-forms](https://docs.github.com/en/discussions/managing-discussions-for-your-community/creating-discussion-category-forms)
-

#### Actions

- File(s): [.github/actions/](.github/actions/)

#### Issue Templates

- File(s): [.github/ISSUE_TEMPLATE/](.github/ISSUE_TEMPLATE/)

#### Pull Request Templates

- File(s): [.github/PULL_REQUEST_TEMPLATE/](.github/PULL_REQUEST_TEMPLATE/)

- [Pre-Commit](.pre-commit-config.yaml)

- [Docker](Dockerfile)

- [Make](Makefile)

- [Repository Citations](CITATION.cff)

- [Markdown Lint](.markdownlint.json)

- [MD Format](.mdformat.toml)

- [rad](.rad)
