# Git Important Commands Cheat Sheet

## 1. Git Setup

```bash
git --version
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

## 2. New Project / Repository

```bash
git init
git status
git add .
git commit -m "Initial commit"
```

## 3. Connect Local Project to GitHub

```bash
git remote -v
git remote add origin https://github.com/username/repository.git
git branch -M main
git push -u origin main
```

## 4. Daily Git Workflow

```bash
git status
git add .
git commit -m "Updated project"
git push
```

## 5. Get Latest Code from GitHub

```bash
git pull
```

Or:

```bash
git fetch
git merge
```

## 6. Branch Commands

Show branches:

```bash
git branch
```

Create a branch:

```bash
git branch feature-login
```

Switch branch:

```bash
git switch feature-login
```

Create and switch:

```bash
git switch -c feature-login
```

Delete branch:

```bash
git branch -d feature-login
```

## 7. Merge Branch

```bash
git switch main
git pull
git merge feature-login
git push
```

## 8. Check Changes and History

```bash
git status
git diff
git log
git log --oneline
```

## 9. Undo / Restore Changes

Unstage a file:

```bash
git restore --staged filename
```

Discard changes in a file:

```bash
git restore filename
```

Undo the last commit but keep changes:

```bash
git reset --soft HEAD~1
```

## 10. Clone an Existing Project

```bash
git clone https://github.com/username/repository.git
```

## 11. Remote Commands

Show remote URL:

```bash
git remote -v
```

Add remote:

```bash
git remote add origin https://github.com/username/repository.git
```

Change remote URL:

```bash
git remote set-url origin https://github.com/username/repository.git
```

Remove remote:

```bash
git remote remove origin
```

## 12. Useful Commit Commands

```bash
git commit -m "Add login page"
git commit -m "Fix calculator bug"
git commit -m "Update navbar"
```

## 13. Stash Commands

Temporarily save changes:

```bash
git stash
```

Show stashed changes:

```bash
git stash list
```

Restore latest stash:

```bash
git stash pop
```

## 14. GitHub Push Workflow

```text
Local Project
     ↓
git status
     ↓
git add .
     ↓
git commit -m "message"
     ↓
git push
     ↓
GitHub
```

## 15. Most Important Commands

The commands you should remember first:

```text
git init
git clone
git status
git add
git commit
git push
git pull
git branch
git switch
git merge
git log
git diff
git stash
```

## 16. Simple Developer Workflow

For normal daily development:

```bash
git pull
# Make your changes

git status
git add .
git commit -m "Describe your changes"
git push
```

---

# Quick Revision

| Command | Purpose |
|---|---|
| `git init` | Initialize Git |
| `git clone` | Copy repository |
| `git status` | Check current changes |
| `git add .` | Stage changes |
| `git commit` | Save changes locally |
| `git push` | Send changes to GitHub |
| `git pull` | Get latest changes |
| `git branch` | Manage branches |
| `git switch` | Change branch |
| `git merge` | Merge branches |
| `git log` | View commit history |
| `git diff` | View changes |
| `git stash` | Temporarily save changes |
| `git restore` | Restore files |
| `git remote -v` | Check GitHub remote |
