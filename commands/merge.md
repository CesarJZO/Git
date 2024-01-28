# Merge

```bash
git merge <branch>
```

> [!TIP]
> Use `--squash` to merge without commit. This can be useful if you want to squash multiple commits into one.

```bash
git merge <branch> --squash
```

> [!WARNING]
> This could lead to conflicts if the branch you are merging has commits that are not in the current branch.
