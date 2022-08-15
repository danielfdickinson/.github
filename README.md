# .github

GitHub 'community health' repository for danielfdickinson

## Metadata

### Status

[![pre-commit.ci
status](https://results.pre-commit.ci/badge/github/danielfdickinson/.github/main.svg)](https://results.pre-commit.ci/latest/github/danielfdickinson/.github/main)

## Interacting with danielfdickinson

### Docs (under the `docs` folder)

|        File        | Status | Purpose | Notes |
|--------------------|--------|---------|-------|
| [CODE_OF_CONDUCT.md](docs/CODE_OF_CONDUCT.md) | sparse | Expectations in interactions between myself, contributors, and collaborators | This can wait until participation is not so sparse |
| [CONTRIBUTING.md](docs/CONTRIBUTING.md) | sparse | How others can contribute | Should really be per-repo, but this will serve until old but non-archived repositories get their own file |
| FUNDING.yml | not present | Display a sponsor button with information of funding options for my open source projects | Need to research funding options first |
| [SECURITY.md](docs/SECURITY.md) | sparse | Instructions for how to report a security vulnerability in a project | Just my public email for now |
| [SUPPORT.md](docs/SUPPORT.md) | sparse | How to get help with my projects | Mostly Discussions for now |

### Issue and pull request templates and configuration

Not present, yet. Given the variety of repositories I have, this probably needs
to be managed per-repo.

## Getting help, discussing, and/or modifying

* [Support and general questions](docs/SUPPORT.md)
* [Bugs and feature requests](docs/SUPPORT.md)
* [Contributing modifications](docs/CONTRIBUTING.md)
* [Reporting security issues][docs/SECURITY.md)

### Code of conduct

[A very basic code of conduct](docs/CODE_OF_CONDUCT.md)

-------

## Notes

### Note 1

Uses [EditorConfig][edconf] for an editor neutral default styling

* Defaults to [using tabs where possible for accessibility
reasons][tabaccess]
* `root = false` so that the user can set their preferred (or required for
accessibility reasons) rendering of the tabs via a `.editorconfig` file in
a higher level directory, or their home directory. Not doing this defeats
the purpose of using tabs vs. spaces.
* `tab_width` is **not** set in this repository so that the user's config
will be used. (See above).

### Note 2

'We' is the 'royal we' (because we don't like saying 'I' a lot and often we
want speak in the first person), and 'I' am
[@danielfdickinson](https://github.com/danielfdickinson).

### Note 3

We use [CSpell][cspell] with [pre-commit][precommit] to catch spelling and other
silly mistakes when committing to this
(<https://github.com/danielfdickinson.github>) repository.

-------

[cspell]: https://cspell.org
[edconf]: https://editorconfig.org/
[precommit]: https://pre-commit.com
[tabaccess]: https://www.brycewray.com/posts/2022/06/accessibility-argument-tabs-spaces/
