# Contributing

Thanks for helping out. This guide applies to every repository in app-torq unless a repository has its own.

## Issues

- **Bugs:** use the bug report template and include the version (Settings → About), how you run torq and the steps to reproduce.
- **Ideas:** open a feature request and describe the problem first, then your proposed solution.
- **Vehicle data:** corrections to the catalog, such as the chassis-code table, are very welcome as issues or pull requests.
- **Security issues:** never in public issues; see [SECURITY.md](SECURITY.md).

## Pull requests

1. For anything larger than a small fix, open an issue first so we can agree on the approach.
2. Branch from `main`, keep the change focused, and add or update tests.
3. Run the checks before pushing (in app-torq/torq: `make check`, `make test` and, for UI changes, `make e2e`).
4. User-facing text needs both English and German translations.
5. Describe what changed and why in the pull request.

By contributing you agree that your contribution is licensed under the repository's license.
