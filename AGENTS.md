# Repository Instructions

This repository is owned by the Botetourt GitHub identity.

## Git Identity

Use these local git settings when committing here:

```bash
git config user.name baron-de-botetourt
git config user.email 262460446+baron-de-botetourt@users.noreply.github.com
```

The `origin` remote should use the Botetourt SSH host alias:

```bash
git remote set-url origin github-botetourt:baron-de-botetourt/pipes.git
```

The default branch is `main`.

## Commit Workflow

- Run `git status --short --branch` before staging.
- Inspect changes before committing.
- Stage only files that belong to the requested task.
- Use concise, imperative commit messages.
- Push with `git push` once `main` is tracking `origin/main`.

