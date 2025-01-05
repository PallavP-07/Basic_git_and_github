# GitHub Commands Reference

This document serves as a quick reference guide for common GitHub commands and their usage.

---

## Git Setup

### Configure Git for the First Time:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Check Git Configuration:
```bash
git config --list
```

---

## Basic Git Commands

### Initialize a Git Repository:
```bash
git init
```

### Clone a Repository:
```bash
git clone <repository_url>
```

### Check the Status of Your Repository:
```bash
git status
```

### Add Files to Staging:
```bash
git add <file_name>
```

To add all files:
```bash
git add .
```

### Commit Changes:
```bash
git commit -m "Commit message"
```

### Push Changes to Remote Repository:
```bash
git push origin <branch_name>
```

### Pull Changes from Remote Repository:
```bash
git pull origin <branch_name>
```

### Check Commit History:
```bash
git log
```

---

## Branch Management

### Create a New Branch:
```bash
git branch <branch_name>
```

### Switch to a Branch:
```bash
git checkout <branch_name>
```

### Create and Switch to a New Branch:
```bash
git checkout -b <branch_name>
```

### Merge a Branch:
```bash
git merge <branch_name>
```

### Delete a Branch:
```bash
git branch -d <branch_name>
```

---

## Working with Remote Repositories

### Add a Remote Repository:
```bash
git remote add origin <repository_url>
```

### List Remote Repositories:
```bash
git remote -v
```

### Remove a Remote Repository:
```bash
git remote remove <remote_name>
```

---

## Advanced Commands

### Stash Changes:
```bash
git stash
```

### List Stashes:
```bash
git stash list
```

### Apply a Stash:
```bash
git stash apply
```

### Delete a Stash:
```bash
git stash drop
```

### Reset to a Specific Commit:
```bash
git reset --hard <commit_hash>
```

### View Differences:
```bash
git diff
```

### Undo the Last Commit:
```bash
git reset --soft HEAD~1
```

---

## Helpful Tips

- **Ignore Files:** Use a `.gitignore` file to specify files and directories to ignore.
- **Track a File:** Use `git add` to start tracking a file.
- **Resolve Merge Conflicts:** Edit conflicting files manually, then commit changes.

---

For more detailed documentation, refer to the [official Git documentation](https://git-scm.com/doc).
