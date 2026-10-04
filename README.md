# git-hook-test

## Git hooks

This repository includes git hooks in `.githooks`.

Enable them with:

```bash
git config core.hooksPath .githooks
```

Included hooks:

- `pre-commit`: blocks commits that add `TODO` or `FIXME` in staged changes.
- `commit-msg`: blocks commit messages that start with `WIP` or are shorter than 10 characters.
