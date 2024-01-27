# Branches

## Creating

```bash
git branch <name>
```

## Renaming

```bash
git branch -m <new-name>
```

## Setting upstream

If the branch from GitHub will be changed as well, it needs to be updated from the local repo.

```bash
git branch -m <old_name> <new_name>
git fetch <remote>
git branch -u <remote_name>/<new_name> <new_name>
git remote set-head <remote_name> -a
```

## Merging

```bash
git merge <branch>
```

### Squashing

```bash
git merge --squash <branch>
```
