# Contributing Guide

## How to Contribute

To contribute effectively to this project, please follow these steps:

1. Create a descriptive branch name (e.g., `feature/user-model`).
2. Implement your changes following the code and Git standards.
3. Ensure your code works correctly and passes all tests.
4. Open a Pull Request and reference the related issue (e.g., `Closes #123`).

## Code Standards

...

## Git

### Flow Branching Strategy

We follow the Git Flow model:

- **main:** production-ready code
- **develop:** base for integration
- **feature/\*:** new features (branched off develop)
- **release/\*:** pre-production releases (branched off develop)
- **hotfix/\*:** emergency fixes in production (branched off main)
- **bugfix/\*:** minor fixes (branched off develop)

### Commit Message Format

Follow the Conventional Commits format:

Types:

- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Code style (formatting, missing semi-colons, etc)
- `refactor`: Code change that neither fixes a bug nor adds a feature
- `test`: Adding or updating tests
- `chore`: Maintenance

Example:

```
git commit -m "feat: implement login with email and password"
```

### Pull Request Guidelines

- Target branch: always develop
- Use the provided Pull Request Template
- Include clear description and related issue number
- Ensure your code is tested and passes all checks
- Prefer smaller, focused PRs
