# Copilot Instructions

## Branching

- **Never commit directly to `main`.** Always create a feature branch before making changes.
- If you are not already on a feature branch related to your work, create one before doing any work.

## Commits

- Always include the following co-author trailer at the end of every commit message:

  ```
  Co-authored-by: Copilot <223556219+Copilot@users.noreply.github.com>
  ```

- All commit messages **must** follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/#specification) specification. Examples:

  - `feat: add todo list endpoint`
  - `fix: correct date parsing in reminder service`
  - `docs: update README with setup instructions`
  - `chore: configure CI workflow`

## Pull Requests

- PR titles **must** also follow the Conventional Commits spec (e.g., `feat: add todo list endpoint`).
- Always open a PR to merge changes into `main`; do not push directly.
