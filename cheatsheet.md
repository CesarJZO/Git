# Cheat sheet

Here you can find the most useful commands

|Command|Description|
|-|-|
|`git clone <url>`|Clone a repository|
|`git status`|Show the status of the repository|
|`git add <file>`|Add a file to the staging area|
|`git commit -m <message>`|Commit the changes|
|`git push`|Push the changes to the remote repository|
|`git pull`|Pull the changes from the remote repository|
|`git log`|Show the commit history|
|`git branch <name>`|Create a new branch|
|`git branch -m <new-name>`|Rename the current branch|
|`git switch <branch>`|Switch to another branch|
|`git diff <branch>`|Show the differences between the current branch and another branch|

## Setup

### Configuring the user

```bash
git config --global user.name <name>
git config --global user.email <email>
```

### Initializing a repository

```bash
git init
git add .
git commit -m "Initial commit"
```

## Workflow

1. Make changes to the files
2. Add the changes to the staging area

```bash
git add <files_set>
```

3. Commit the changes

```bash
git commit
```

1. Sync with the remote repository

```bash
git fetch
git pull
git push
```

## Branches

Create and switch to a new branch

```bash
git switch -c <new_branch>
```

Merge a branch into the current branch

```bash
git merge <other_branch>
```

### Squashing

```bash
git merge --squash <other_branch>
```

## Reviewing

Get the current status

```bash
git status
```

Show the commit history

```bash
git log
```

Get some nice formatting

```bash
git log --oneline --graph
```
