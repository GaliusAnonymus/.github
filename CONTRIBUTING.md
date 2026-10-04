# Contributing

Thanks for your interest in Galius Anonymus projects! This guide applies to every repository in the organization that does not ship its own `CONTRIBUTING.md`. A project's own guide always takes precedence. The projects listed in the [organization profile](https://github.com/GaliusAnonymus) currently live on [@RaCzKoViC](https://github.com/RaCzKoViC)'s personal account and have their own rules there.

## Before you start

1. **Check the license.** Not every project accepts outside code. Some, such as The-MinerGuy, are "all rights reserved" and source-available only. If in doubt, open an issue first and ask.
2. **Search existing issues and pull requests** to avoid duplicates.
3. **For anything larger than a small fix, open an issue first** and describe the problem and the approach you have in mind. This saves you from writing code that cannot be merged.
4. **Security problems are never reported in public.** Follow [SECURITY.md](SECURITY.md).

## Reporting bugs and requesting features

Use the issue forms (**New issue → Bug report / Feature request**). For bugs, include:

- what you did, what you expected and what happened instead;
- the version, commit or release you used, plus your OS and environment;
- logs or screenshots, **with secrets, tokens and personal data removed**.

## Pull requests

1. Fork the repository and create a topic branch from the default branch (`main`).
2. Keep each PR focused on one change. Unrelated refactors and formatting changes belong in separate PRs.
3. Follow the existing style of the project. Run its linters and tests locally before pushing.
4. Add or update tests for behaviour changes, and update the docs when user-facing behaviour changes.
5. Use [Conventional Commits](https://www.conventionalcommits.org/) for commit messages and PR titles where the project does, for example `fix(parser): handle empty input`.
6. Fill in the pull request template, including **how to test** the change.
7. CI must be green before review. Maintainers may ask for changes. Please don't force-push over review comments without saying so.

By contributing you agree that your contribution is licensed under the same license as the project you are contributing to, unless the project states otherwise.

## Code of Conduct

Everyone taking part is expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
