# Contributing Guide

## Branch Rules

- Do not push directly to `main`
- Create a new branch for every task
- Branch name format: `type/short-name`

Examples:

- `feat/add-homepage`
- `fix/readme-typo`
- `docs/update-readme`

## Commit Message Rules

Commit format:
type(scope): short message

Scope is optional when not needed.

Examples:

- `feat: add homepage`
- `fix: correct typo in readme`
- `docs: add setup instructions`
- `feat(auth): implement JWT-based login`
- `fix(api): correct response schema for users endpoint`

## Commit Types

- `feat` → new feature
- `fix` → bug fix
- `chore` → maintenance tasks
- `refactor` → code improvement without behavior change
- `docs` → documentation changes
- `style` → formatting/style only
- `test` → tests
- `perf` → performance improvements
- `ci` → CI/CD changes
- `build` → build/dependency changes
- `revert` → revert previous commit

## Pull Request Rules

1. Push your branch to GitHub
2. Open a Pull Request into `main`
3. Add a clear PR title
4. Request review from a teammate
5. Merge only after approval
