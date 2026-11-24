# Contributing to the soccentric-stm32 organization

Thanks for taking the time to contribute. This project is part of the
[soccentric-stm32](https://github.com/soccentric-stm32) STM32F767ZI baseline and is released under
the MIT License.

## Before you start

- Read [profile/README.md](profile/README.md) for what this repository does and which tooling it needs.
- Report security issues privately, following [SECURITY.md](SECURITY.md), and not
  in a public issue.
- By taking part you agree to the [Code of Conduct](CODE_OF_CONDUCT.md).

## Getting set up

This repository holds no code: it carries the organization profile
(`profile/README.md`) and the default community health files that apply to every
repository in the organization that does not define its own.

## Building and testing

| Command | What it does |
|---|---|
| `n/a` | No build: this repository only holds Markdown files |

Keep the Markdown consistent and the links relative where possible.

## Code style

- Keep the files accurate for the whole organization, not just for one repository.
- Match the wording and the link style of `profile/README.md`.
- Check that the relative links resolve on GitHub.

## Branch and commit conventions

- Branch off `main` and use a short, descriptive kebab-case name, for example
  `fix-spi-timeout` or `add-imx708-autofocus`.
- Write imperative, present-tense commit subjects (`fix:`, `feat:`, `docs:`,
  `refactor:`, `test:`, `build:`), keep them under about 72 characters and explain
  the reason for the change in the body.
- One logical change per commit.

## Pull requests

- Explain what changed and why, and how you tested it (including the board and
  toolchain you used).
- Reference the issue you are fixing (`Fixes #123`).
- Keep the pull request focused; split unrelated changes into separate ones.
- Changes are reviewed by a maintainer of the organization.

## Changelog and releases

- Record user-visible changes under `## [Unreleased]` in
  [CHANGELOG.md](CHANGELOG.md), following
  [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).
- Versions follow [Semantic Versioning](https://semver.org/spec/v2.0.0.html) and
  releases are tagged `vMAJOR.MINOR.PATCH`.

## License

By contributing you agree that your contributions are licensed under the
[MIT License](LICENSE), the same terms as the rest of the project.
