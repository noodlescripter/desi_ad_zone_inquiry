# Contributing

Thanks for contributing — your help makes this project better. This document describes how to contribute, report issues, and submit pull requests.

## Reporting issues
- Use the Bug report or Feature request templates when opening issues.
- Provide clear reproduction steps, environment, and relevant logs or screenshots.

## Development workflow
1. Fork the repository and clone your fork.
2. Create a feature branch from main:
   - git checkout -b my-feature
3. Install dependencies (adjust to your stack):
   - Python example: python -m venv .venv && source .venv/bin/activate && pip install -r requirements.txt
   - Node example: npm install
4. Run tests and linters before committing:
   - pytest or npm test
   - flake8 / eslint as applicable

## Code style
- Follow the existing code conventions.
- Run formatters/linters before committing (black, prettier, eslint, etc.).

## Commit messages
- Use clear, descriptive commit messages.
- Consider the conventional commits style (feat:, fix:, docs:, chore:) to improve changelogs.

## Pull requests
- Open PRs against the main branch.
- In the PR description, include: what changed, why, how to test, and any migration steps.
- Link related issues and assign reviewers if appropriate.

## Large changes
For large or breaking changes, open an issue first to discuss the design before implementing.

## Communication
If you need help or want to propose a large change, open an issue or contact the maintainers.