# Contributing

Thank you for your interest in contributing! Please read and understand this guide before creating an issue
or pull request.

## Etiquette

This project is open source, and as such, the maintainer gives their free time to build and maintain it.
The code is freely available in the hope that it will be useful to other developers.

Please be considerate when raising issues or presenting pull requests. Respect the maintainer's decision,
and do not be upset if your submission is not accepted.

## First-time Contributors

New to open source? Welcome! Look for issues labeled `good first issue` —
they are beginner-friendly and a great way to start.

## Before You Start

### Before filing an issue

- Attempt to replicate the problem to ensure it wasn't a coincidental incident
- Check existing issues to make sure your bug or feature request isn't already reported
- Check pull requests to ensure the fix or feature isn't already in progress

### Before submitting a pull request

- Check the codebase to ensure your feature doesn't already exist
- Check pull requests to ensure another person hasn't already submitted it

## Commit Message Convention

We use [Conventional Commits](https://www.conventionalcommits.org/) for clear history and automated changelog
generation.

### Format

```
<type>: <description>

[optional body]
```

### Types

| Type       | Description                  |
|------------|------------------------------|
| `feat`     | New feature                  |
| `fix`      | Bug fix                      |
| `docs`     | Documentation changes        |
| `style`    | Code style (formatting)      |
| `refactor` | Code refactoring             |
| `test`     | Adding or updating tests     |
| `chore`    | Maintenance, dependencies    |
| `ci`       | CI/CD changes                |

### Examples

```bash
feat: add dark mode support
fix: resolve authentication issue
docs: update installation instructions
chore: update dependencies
```

### AI Assistant Prompt

For IDE AI assistants (Cursor, Copilot, PhpStorm AI), use this prompt to generate commit messages:

```text
Generate a commit message for the given code changes.

Rules:

1. Format: `<type>: <description>` (Conventional Commits)
   - Header (first line): max 72 characters
   - Body lines: max 100 characters

2. Type must be one of:
   - feat: New feature
   - fix: Bug fix
   - perf: Performance improvement
   - refactor: Code refactoring (no new feature, no bug fix)
   - docs: Documentation only
   - style: Formatting, no code change
   - test: Adding or updating tests
   - chore: Maintenance, dependencies
   - ci: CI/CD changes

3. Description: short, imperative, lowercase, no period at end

4. Body (optional): explain "what" and "why", not "how"

5. Breaking changes: add `!` after type, e.g. `feat!: remove deprecated API`

Output only the raw commit message, no introductory text.
```

## Pull Request Guidelines

### PR Title

Use conventional commit format for the PR title.

### Checklist

- [ ] Commit messages follow Conventional Commits
- [ ] Code follows project coding standards
- [ ] Tests pass (if applicable)
- [ ] Changes are documented (if needed)

## Bug Reports

When reporting bugs, please include:

- Project version
- Environment (OS, language version)
- Steps to reproduce
- Expected vs. actual behavior
- Error messages or logs

## Feature Requests

When requesting features, consider:

- Is this useful to other users, not just you?
- Does it fit the project's scope and goals?
- Can you help implement it?

## Security

Found a security vulnerability? Do not open a public issue.
See [SECURITY.md](SECURITY.md) for responsible disclosure.

Thank you for contributing!
