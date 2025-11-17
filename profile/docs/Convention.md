# Branch Naming Convention

## Category

A git branch should start with a category. Pick one of these: feature, bugfix, hotfix, or test.

- **Feature :** is for adding, refactoring or removing a feature
- **Bugfix :** is for fixing a bug
- **Hotfix :** is for changing code with a temporary solution and/or without following the usual process (usually because of an emergency)
- **Test :** is for experimenting outside of an issue/ticket

```bash
git branch <category/reference/description-in-kebab-case>
```

# Commit Naming Convention

## Category

A commit message should start with a category of change. You can pretty much use the following 4 categories for everything: feat, fix, refactor, and chore.

- **Feat :** is for adding a new feature
- **Fix :** is for fixing a bug
- **Refactor :** is for changing code for peformance or convenience purpose (e.g. readibility)
- **Chore :** is for everything else (writing documentation, formatting, adding tests, cleaning useless code etc.)

```bash
git commit -m '<category: do something; do some other things>'
```