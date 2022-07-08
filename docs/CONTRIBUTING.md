# Contributing to this Repository

Reading and following these guidelines will help us make the contribution process easy and effective for everyone involved. It also communicates that you agree to respect the time of the developers managing and developing these projects. We will reciprocate that respect by addressing your issue, assessing changes, and helping you finalize your pull requests.

We want to make contributing to this project as easy and transparent as possible, whether it's:

* Reporting a bug
* Discussing the current state of the code
* Submitting a fix
* Proposing new features

## Quicklinks

- [Contributing to this Repository](#contributing-to-this-repository)
  - [Quicklinks](#quicklinks)
  - [Getting Started](#getting-started)
    - [Issues](#issues)
    - [Report bugs using Github issues](#report-bugs-using-github-issues)
    - [Features](#features)
    - [Pull Requests](#pull-requests)
    - [Commit Message Format](#commit-message-format)
      - [<a name="commit-header"></a>Commit Message Header](#commit-message-header)
        - [Type](#type)
  - [Getting Help](#getting-help)

## Getting Started

Contributions to all our repos are made via Issues and Pull Requests (PRs). A few general guidelines that cover both:

- To report security vulnerabilities, please use see the Contacts page for who to report to
- Search for existing Issues and PRs before creating your own.
- If you've never contributed before, see Teams Agreements for resources and tips on how to get started.

### Issues

Issues should be used to report problems with the library, request a new feature, or to discuss potential changes before a PR is created. When you create a new Issue, a template will be loaded that will guide you through collecting and providing the information we need to investigate.

If you find an Issue that addresses the problem you're having, please add your own reproduction information to the existing issue rather than creating a new one. 

You can file new issues by selecting from our new issue templates and filling out the issue template.

### Report bugs using Github issues
We use GitHub issues to track public bugs. Report a bug by[opening a new issue; it's that easy!

**Great Bug Reports** tend to have:

- A quick summary and/or background
- Steps to reproduce
- What you expected would happen
- What actually happens
- Notes (possibly including why you think this might be happening, or stuff you tried that didn't work)

### Features

We use GitHub issues track Insyts features. All features must be part of the features list on [[Features And Roadmap]]. A feature will contain a number of task to be implemented. These tasks and related documentation/wireframes are **NOT** to be created as independent issues but rather a checklist on each Issue. When submitting a feature request, please try and:
* Be as clear as possible
* Include relevant documentation, wireframes, etc.
* Schedule a brainstorm session with the relevant parties to identify the steps to complete the feature/fix
* For each task under a feature estimate the amount of hours needed to complete the Issue.

### Pull Requests

PRs to our libraries are always welcome and can be a quick way to get your fix or improvement slated for the next release. In general, PRs should:

- Only fix/add the functionality in question **OR** address wide-spread whitespace/style issues, not both.
- Add unit or integration tests for fixed or changed functionality (if a test suite already exists).
- Address a single concern in the least number of changed lines as possible.
- Include documentation in the repo under docs folder.
- Be accompanied by a complete Pull Request description and an update of the CHANGELOG.md file

For changes that address core functionality or would require breaking changes (e.g. a major release), it's best to open an Issue to discuss your proposal first. This is not required but can save time creating and reviewing changes.

In general, we follow

1. Clone the project to your machine
2. Create a branch locally with a succinct but descriptive name (the projects do not allow a push to the main branch)
4. Following any formatting and testing guidelines specific to the repo/project
5. Publish and push your branch
6. Open a PR and request review from any two developers on the repo/project.


### Commit Message Format

*This specification is inspired by and supersedes the [AngularJS commit message format][commit-message-format].*

We have very precise rules over how our Git commit messages must be formatted.
This format leads to **easier to read commit history**.

Each commit message consists of a **header**, a **body**, and a **footer**.


```
<header>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

The `header` is mandatory and must conform to the [Commit Message Header](#commit-header) format.

The `body` is mandatory for all commits except for those of type "docs".
When the body is present it must be at least 20 characters long and must conform to the [Commit Message Body](#commit-body) format.

The `footer` is optional. The [Commit Message Footer](#commit-footer) format describes what the footer is used for and the structure it must have.


#### <a name="commit-header"></a>Commit Message Header

```
<type>: <short summary>
  │             │
  │             └─⫸ Summary in present tense. Not capitalized. No period at the end.
  │       
  │       
  │                          
  │                          
  │                        
  │                          
  │
  └─⫸ Commit Type: build|ci|docs|feat|fix|perf|refactor|test
```

The `<type>` and `<summary>` fields are mandatory


##### Type

Must be one of the following:

* **build**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
* **ci**: Changes to our CI configuration files and scripts (examples: CircleCi, SauceLabs)
* **docs**: Documentation only changes
* **feat**: A new feature
* **fix**: A bug fix
* **perf**: A code change that improves performance
* **refactor**: A code change that neither fixes a bug nor adds a feature
* **test**: Adding missing tests or correcting existing tests

## Getting Help

Please see the contact section for person who can help you with a particular issue or feature