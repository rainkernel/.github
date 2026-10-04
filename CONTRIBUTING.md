# Contributing

Thank you for looking under the hood. These projects are small and opinionated, so the fastest way to land a change is to talk first.

## Before you write code

- **Bugs** — open an issue with the bug template: the exact command, the output and what you expected.
- **Features, new attack cases, adapters** — open an issue first so we agree on the shape. A pull request that arrives without an issue may be closed with a pointer to one.
- **Security problems** — never in an issue. See [SECURITY.md](SECURITY.md).

## Pull requests

1. Fork, branch from `main`, one change per pull request.
2. Keep the tests green and add one for what you changed; the repository's README names the commands. CI runs lint, types and tests on every pull request.
3. Write the description for the reviewer: what changed, why, how it was tested.
4. A maintainer reviews within a few working days. Squash-merge is the default.

## Licence and sign-off

By contributing you agree that your contribution is licensed under the repository's licence (Apache-2.0) and that you have the right to submit it. Say so with a `Signed-off-by:` line on each commit (`git commit -s`) — the [Developer Certificate of Origin](https://developercertificate.org).

## Style

Plain language in docs, messages and names; no marketing words. Code style is enforced by each repository's linter — run it before you push.
