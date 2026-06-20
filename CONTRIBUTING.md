# Contributing

Thanks for your interest in contributing! Your help is welcome — whether it's a bug fix, documentation improvement, or a new feature. Please read these guidelines to get started.

## How to file an issue

- Check existing issues and PRs to avoid duplicates.
- Use a clear title and include steps to reproduce, expected vs actual behavior, and any relevant logs or screenshots.
- Label the issue where appropriate (bug, enhancement, docs).

## How to propose changes (Pull Requests)

1. Fork the repository and create a branch from main:
   - Branch name format: `feat/<short-description>` or `fix/<short-description>` or `docs/<short-description>` (kebab-case). Example: `feat/add-auth-endpoints`.
2. Make your changes on the branch. Keep commits small and focused.
3. Follow the commit message conventions below.
4. Push the branch to your fork and open a Pull Request targeting `main` in this repo.
5. In the PR description, explain the problem, the solution, and any migration notes or breaking changes.

## Commit message style

Please use a simple Conventional Commits-style format for commit messages:

```
type(scope?): short summary

optional longer description

BREAKING CHANGE: description (if applicable)
```

- type: `feat`, `fix`, `docs`, `chore`, `refactor`, `test`, `perf`.
- Keep the summary under 72 characters.

## Code style & tests

- Follow the existing code style in the repository (indentation, naming, file layout).
- Add or update tests if you change behavior. Include instructions to run tests in the PR if they are not obvious.
- Run linters/formatters before submitting (e.g., `prettier`, `eslint`, `dart format`, `flutter analyze` depending on the project).

## Reviewing process

- A maintainer will review your PR and may request changes. Please address review comments by pushing additional commits to the same branch.
- Keep PRs focused; large or multi-topic PRs may be broken into smaller ones.

## Localization & Accessibility

- Prefer clear and simple language in UI and docs.
- Consider accessibility (labels, alt text for images) when adding UI content or screenshots.

## License

By contributing, you agree that your contributions will be licensed under the project's MIT License (see LICENSE file).

## Contact

If you need help or want to discuss a larger change before working on it, open an issue or reach out on LinkedIn: https://linkedin.com/in/fatima-nahid-a61294267/

---

Thanks — your contributions make this project better!