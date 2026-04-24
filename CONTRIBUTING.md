# Contributing to Dinnartec projects

Thanks for taking the time to contribute. This guide applies to every repository in the `dinnartec` organization unless a specific repo overrides it.

## Workflow

1. **Branch off `main`** using the format `type/short-description`:
   - `feature/user-auth`
   - `fix/login-redirect`
   - `refactor/extract-api-client`
   - `docs/update-readme`
   - `chore/upgrade-dependencies`
2. **Commit in small, focused units** — each commit should compile and pass tests.
3. **Open a PR** using the [default template](./.github/pull_request_template.md).
4. **One concern per PR** — split if you're mixing a feature with a refactor.
5. **Self-review first** — read your own diff before requesting review.

## Commit messages

We follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/):

```
type: short description

optional body explaining why
```

Types we use:

| Type | For |
|---|---|
| `feat` | A new feature |
| `fix` | A bug fix |
| `refactor` | Code change that neither fixes a bug nor adds a feature |
| `perf` | Performance improvement |
| `docs` | Documentation only |
| `test` | Adding or updating tests |
| `chore` | Tooling, config, dependencies |
| `ci` | CI/CD changes |
| `style` | Formatting only |
| `revert` | Revert a previous commit |

Rules:

- Use imperative mood — "add feature" not "added feature"
- Lowercase type — `feat:` not `Feat:`
- No period at the end
- Subject under 72 characters

## Code review

- Reviewers aim to respond within **2 business days**.
- Merging strategy: **Squash and merge** by default, preserving the PR title as the commit subject.

## Branches

| Branch | Purpose |
|---|---|
| `main` | Production-ready code · protected · requires PR + review |

## Releases

Projects follow [semver](https://semver.org/) (MAJOR.MINOR.PATCH). Refer to a repo's `CHANGELOG.md` (when present) for history.

## Security

Please **do not open public issues for security vulnerabilities**. See our [security policy](./SECURITY.md).
