# Contributing

Thanks for contributing! This document describes the recommended workflow for this project.

## Quick start (local development)
- Install dependencies: `npm install`
- Start dev server: `npm run dev` (open http://localhost:3000)
- Build: `npm run build`

## Branches & naming
- Use feature branches: `feature/short-description`
- Use fix branches for bugfixes: `fix/short-description`
- Use chore for maintenance: `chore/short-description`

## Commits
- Use Conventional Commits for clear history: `feat:`, `fix:`, `docs:`, `chore:`, `refactor:`, `test:`
- Example: `git commit -m "feat: add parent dashboard summary card"`

## Pull Requests
- Ensure your branch is up-to-date with `main` before creating a PR
- Provide a clear description of the change and link any related issue
- Add screenshots when applicable (UI changes)
- Add reviewers and request review

## Tests & checks
- Run the dev server and verify there are no console errors
- Lint and test if available (add CI hooks for automated checks in future)

## Git commands (common)
- Create branch: `git checkout -b feature/short-desc`
- Stage: `git add -A`
- Commit: `git commit -m "feat: short description"`
- Push: `git push -u origin feature/short-desc`
- Rebase latest main: `git fetch origin && git rebase origin/main`

## Secrets
- Never commit secrets or `.env` files. Use environment variables or secret managers.

---
If you'd like, I can also set up a PR template or add Husky pre-commit hooks to ensure linting/tests run before commit.