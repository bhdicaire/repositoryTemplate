# ![Logo](docs/header.png "Logo")

![GitHub Stars](https://img.shields.io/github/stars/bhdicaire/repositoryTemplate?style=flat-square&logoColor=186ADE&labelColor=3E5462&color=C25100)
![GitHub forks](https://img.shields.io/github/forks/bhdicaire/repositoryTemplate?style=flat-square&logoColor=186ADE&labelColor=3E5462&color=C25100)
![GitHub Last Commit](https://img.shields.io/github/last-commit/bhdicaire/repositoryTemplate?style=flat-square&logoColor=186ADE&labelColor=3E5462&color=C25100)
![GitHub licence](https://img.shields.io/github/license/bhdicaire/repositoryTemplate?style=flat-square&logoColor=186ADE&labelColor=3E5462&color=C25100)

This repository is a _template_ you can [use](https://github.com/bhdicaire/repositoryTemplate/generate) to start new projects with a consistent structure and [batteries included](docs/bestPractices.md).

## :notebook_with_decorative_cover: Ingredients

<details>
<summary>Standard community files</summary>

Setup contributing guidelines to help collaborators make meaningful, useful contributions to a project:

* [Code of conducts](.github/CODE_OF_CONDUCT.md) adapted from the [Contributor Covenant, version 3.0](https://www.contributor-covenant.org/version/3/0/) to ensure that no manual changes are required per project
* [Code owners](.github/CODEOWNERS): lists the project's maintainers to specific areas of the codebase
* [Contributing](.github/CONTRIBUTING.md): reporting bugs & issues, and submitting pull requests based on [Github Flow](https://docs.github.com/en/get-started/using-github/github-flow)
* [Governance](.github/GOVERNANCE.md): describe how decisions are made and how contributions are managed
* [License](.github/LICENSE.md): it uses a [MIT License](https://choosealicense.com/licenses/mit/)
* [Maintainers](.github/MAINTAINERS.md): lists the project's maintainers and how to contact them
* [Security](.github/SECURITY.md): provide public instructions for reporting security issues

</details>
<details>
<summary>GitHub issue and PR templates for bugs, features, docs, and questions</summary>

* [Config](.github/ISSUE_TEMPLATE/config.yml): customize the issue template chooser
* [Labels](.github/labels.yml): add labels for type (bug, feature, docs), status (in progress, blocked), and priority
* [Pull request template](.github/PULL_REQUEST_TEMPLATE.md): explain how contributors can keep pull requests small and focused
* [Support](.github/SUPPORT.md): explain how contributors can get help

* Issue templates:
    1. [Bug](.github/ISSUE_TEMPLATE/bug.yml)
   2. [Documentation including README.md](.github/ISSUE_TEMPLATE/docs.yml)
   3. [Feature request](.github/ISSUE_TEMPLATE/feature.yml)
   4. [Question or support Request](.github/ISSUE_TEMPLATE/support.yml)
   5. [Report a security vulnerability](.github/SECURITY.md)

</details>

<details>
<summary>More opinionated configurations</summary>

* [.editorconfig](.editorconfig): helps maintain consistent coding styles across various editors and IDEs  [:link:source](https://editorconfig.org/)
* [.gitattributes](.gitattributes): control how GitHub shows diffs and calculates repository languages [:link:source](https://git-scm.com/docs/gitattributes) 
* [.gitignore](.gitignore): keep sensitive or unnecessary files out of the repository [:link:source](https://git-scm.com/docs/gitignore)
* [.markdownlint.yml](.markdownlint.yml): style checker and lint tool for Markdown/CommonMark files [:link:source](https://github.com/DavidAnson/markdownlint)
* [CHANGELOG.md](CHANGELOG.md): maintain a change log following [Keep a Changelog](https://keepachangelog.com/en) format
* [package.json](package.json): information about the repository and required node.js modules [:link:source](https://docs.npmjs.com/cli/v11/configuring-npm/package-json)

</details>

## :rocket: Deployment

[Click](https://github.com/bhdicaire/repositoryTemplate/generate) to create a new repository with _this_ template
<details>
<summary>Customize based based on best practices</summary>

* [ ] Change the project description
  ![projectDescription screenshot](docs/projectDescription.png)
* [ ] Update the [standard community files](https://github.com/bhdicaire/repositoryTemplate/blob/main/docs/bestPractices.md#standard-community-files)
  * [ ] Review `.github/LICENSE.md`
  * [ ] Review `.github/CODE_OF_CONDUCT.md`
  * [ ] Review `.github/GOVERNANCE.md`
  * [ ] Review `.github/CONTRIBUTING.md`
  * [ ] Update `.github/MAINTAINERS.md`
  * [ ] Update `.github/CODEOWNERS`
  * [ ] Update `.github/SECURITY.md`
  * [ ] Configure the `private vulnerability reporting` in the [GitHub UI](../../settings/security_analysis)
* [ ] Update the [Issues & PRs](https://github.com/bhdicaire/repositoryTemplate/blob/main/docs/bestPractices.md#issues--prs)
  * [ ] Review `.github/SUPPORT.md`
  * [ ] Review `.github/ISSUE_TEMPLATE/config.yml`
  * [ ] Review `.github/ISSUE_TEMPLATE/bug.yml`
  * [ ] Review `.github/ISSUE_TEMPLATE/docs.yml`
  * [ ] Review `.github/ISSUE_TEMPLATE/feature.yml`
  * [ ] Review `.github/ISSUE_TEMPLATE/support.yml`
  * [ ] Review `.github/SECURITY.md`
  * [ ] Review `.github/labels.yml`
  * [ ] Review `.github/PULL_REQUEST_TEMPLATE.md`
* [ ] Update [Opinionated configurations](https://github.com/bhdicaire/repositoryTemplate/blob/main/docs/bestPractices.md#opinionated-configurations)
  * [ ] Review `.editorconfig`
  * [ ] Review `.markdownlint.yml`
  * [ ] Review `package.json`
  * [ ] Review `CHANGELOG.md`
  * [ ] Review `.gitignore`
  * [ ] Review `.gitattributes`
* [ ] Update [Documentation](https://github.com/bhdicaire/repositoryTemplate/blob/main/docs/bestPractices.md#documentation-readmemd)
  * [ ] Update `README.md`
    * [ ] Design  `docs/header.png`  
    * [ ] Select [badges](docs/badges.md)
    * [ ] Select [emojis](docs/emojis.md) supported by GitHub
    * [ ] Update the project tree, I'm using `tree -a --filesfirst -I .git`
  * [ ] Design and upload `docs/socialMedia.png`
  * [ ] Review `docs/bestPractices.md`
* [ ] Review [GitHub Accounts and Organisations settings](https://github.com/bhdicaire/repositoryTemplate/blob/main/docs/bestPractices.md#github-accounts-and-organisations)
 * [ ] Strong and unique passwords
 * [ ] Enforce two-factor authentication
 * [ ] Use SSH Keys for authentication and commit signing
 * [ ] Enable push protection to prevent committing secrets
 * [ ] Assign at least two owners per organization to ensure continuity 
</details>

## 🌲 Project tree

```text
.
├── .editorconfig
├── .gitattributes
├── .gitignore
├── .markdownlint.yml
├── CHANGELOG.md
├── README.md
├── package.json
├── .github
│   ├── CODEOWNERS
│   ├── CODE_OF_CONDUCT.md
│   ├── CONTRIBUTING.md
│   ├── GOVERNANCE.md
│   ├── LICENSE.md
│   ├── MAINTAINERS.md
│   ├── PULL_REQUEST_TEMPLATE.md
│   ├── SECURITY.md
│   ├── SUPPORT.md
│   ├── labels.yml
│   ├── ISSUE_TEMPLATE
│   │   ├── bug.yml
│   │   ├── config.yml
│   │   ├── docs.yml
│   │   ├── feature.yml
│   │   └── support.yml
│   └── workflows
│       └── labels.yml
└── docs
    ├── badges.md
    ├── bestPractices.md
    ├── emojis.md
    ├── header.png
    ├── permanentLinks.png
    ├── projectDescription.png
    ├── repoPrivateReporting.png
    ├── socialMedia.png
    └── userPrivateReporting.png

5 directories, 32 files
```

## Suggestions and improvements are welcome

Pull requests are welcome :grin:

For major changes, please open an issue first to discuss what you would like to change. Refer to the [contribution guidelines](.github/CONTRIBUTING.md) and adhere to this [project's code of conduct](./.github/CODE_OF_CONDUCT.md).

## License

Copyright (c) 2025 Benoît H. Dicaire and licensed under the [MIT license](https://choosealicense.com/licenses/mit/). See [LICENSE.md](.github/LICENSE.md) for more information.
