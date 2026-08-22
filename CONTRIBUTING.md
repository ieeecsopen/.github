# Contributing

Thanks for considering a contribution. This document covers how we work.

## Before you start

- **Open an issue first** for anything non-trivial. It's demoralising to write
  a large PR and then learn the approach won't work. A short issue saves that.
- Small fixes — typos, broken links, obvious bugs — go straight to a PR.
- Check existing issues and PRs so we don't duplicate effort.

## Setting up

Each repository documents its own setup in its README. Most are Node projects:

```bash
npm install
npm run dev
```

If a repo's setup instructions don't work, that's a bug — please report it.

## Pull requests

1. Fork, then branch from `main`. Name it for the change: `fix/login-redirect`.
2. Keep the PR focused. One concern per PR reviews far faster.
3. Write a commit message that explains **why**, not just what.
4. Make sure the build passes (`npm run build`) and lint is clean before pushing.
5. Fill in the PR template — especially how you tested the change.

Maintainers aim to respond within a week. We're students; exam periods are slow.
A polite nudge after that is welcome.

## Code style

Match the surrounding code. We don't enforce a house style beyond whatever
linter the repo already has configured.

## What we won't merge

- Changes with no issue or explanation.
- Dependency bumps with no stated reason.
- Formatting-only churn across files you aren't otherwise changing.
- Anything that adds a secret, credential, or API key to the repository —
  including in tests, fixtures, or commented-out code.

## Licence

By contributing you agree your work is licensed under the same terms as the
repository (see each repo's LICENSE file).
