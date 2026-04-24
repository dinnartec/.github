# dinnartec/.github

Organization-wide defaults for [Dinnartec](https://github.com/dinnartec).

This repository is a special one — GitHub applies its contents as defaults to every other repository in the `dinnartec` organization that does not provide its own version.

## Contents

| Path | Purpose |
|------|---------|
| [`profile/README.md`](./profile/README.md) | Public landing shown on `github.com/dinnartec` |
| [`.github/pull_request_template.md`](./.github/pull_request_template.md) | Default PR template for every org repo |
| [`.github/ISSUE_TEMPLATE/`](./.github/ISSUE_TEMPLATE/) | Default issue templates (bug, feature) |
| [`CONTRIBUTING.md`](./CONTRIBUTING.md) | Contribution guide |
| [`SECURITY.md`](./SECURITY.md) | Vulnerability reporting policy |
| [`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md) | Community guidelines |
| [`.github/dependabot.yml`](./.github/dependabot.yml) | Dependabot config for this repo |

## How GitHub resolves defaults

For any file type supported by GitHub (issue templates, PR templates, `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md`, `SUPPORT.md`, `FUNDING.yml`), GitHub looks up the file in this order for a given repo:

1. The repo's own `.github/` folder
2. The repo's root
3. The repo's `docs/` folder
4. This `.github` repo's `.github/` folder (fallback)
5. This `.github` repo's root (fallback)
6. This `.github` repo's `docs/` folder (fallback)

Any repo that needs a specific override just adds its own file — it takes precedence automatically.
