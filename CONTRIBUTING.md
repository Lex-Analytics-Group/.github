# Contributing

Thanks for taking the time to contribute to a Lex Analytics Group project. This guide applies
across all repositories in the [@Lex-Analytics-Group](https://github.com/Lex-Analytics-Group)
organization unless a repository has its own `CONTRIBUTING.md`.

## Before you start

- Read the [Code of Conduct](CODE_OF_CONDUCT.md). Participating means you agree to it.
- **Never** report a security vulnerability as an issue or pull request — follow
  [SECURITY.md](SECURITY.md) instead.
- For anything larger than a bug fix, open an issue first so we can agree on the approach
  before you write code.

## Branches and commits

- `main` is the default branch and should always be deployable.
- Branch from `main` using a descriptive prefix:
  - `feat/<short-description>` — new functionality
  - `fix/<short-description>` — bug fix
  - `chore/<short-description>` — tooling, dependencies, config
  - `docs/<short-description>` — documentation only
- Write commit messages in [Conventional Commits](https://www.conventionalcommits.org/) style:

  ```
  feat(search): add case-number lookup
  fix(auth): reject expired refresh tokens
  chore(deps): bump vite to 5.4.9
  ```

- Keep commits focused. One logical change per commit makes review and rollback far easier.

## Pull requests

1. Rebase or merge the latest `main` into your branch.
2. Make sure the project builds and the tests pass locally.
3. Open the PR against `main` and fill in the pull request template.
4. Link the issue it closes (`Closes #123`).
5. Keep PRs small — under ~400 changed lines where possible. Large PRs get reviewed slowly.
6. Mark the PR as a draft if it is not ready for review.

A PR needs at least one approving review before merge. Squash-merge is the default.

## Code style

- Match the conventions already present in the repository you are editing.
- Run the repository's formatter and linter before pushing (`npm run lint`, `ruff`, etc.).
- Add or update tests for any behaviour you change.
- Update the relevant documentation in the same PR as the code change.

## Secrets and data

- Never commit credentials, API keys, `.env` files, tokens or connection strings.
- Never commit real client data, court records containing personal information, or database
  dumps. Use synthetic or anonymised fixtures in tests.
- If you believe a secret has been committed, treat it as a security incident and follow
  [SECURITY.md](SECURITY.md) — rotating the credential matters more than removing the commit.

## Dependencies

- Prefer well-maintained packages with a compatible licence.
- Pin versions in lockfiles and commit the lockfile.
- Dependabot opens grouped security-update pull requests across this organization; please review
  and merge them promptly rather than letting them accumulate.

## Questions

Open a discussion on the relevant repository, or email
[lexanalyticsgroup@gmail.com](mailto:lexanalyticsgroup@gmail.com).
