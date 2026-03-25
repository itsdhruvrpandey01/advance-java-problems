# 🛠️ Git & GitHub Commands Guide

This document contains commonly used Git commands and best practices for working with branches, commits, and repositories.

---

## 🚀 Basic Setup

```bash
git clone <repo-url>        # Clone repository
git status                  # Check current status
git add .                   # Stage all changes
git commit -m "message"     # Commit changes
git push                    # Push to remote
```

---

## 🌿 Branching

```bash
git checkout -b dev                 # Create and switch to dev branch
git checkout -b feature/xyz         # Create feature branch
git checkout main                   # Switch to main
git branch                          # List branches
```

---

## 🔄 Sync with Remote

```bash
git pull origin main                # Pull latest changes
git push -u origin dev              # Push and set upstream
git fetch origin                    # Fetch latest without merging
```

---

## 🔀 Merge

```bash
git checkout main
git merge dev                       # Merge dev into main
git push origin main
```

---

## ⚠️ Reset & Force (Advanced)

```bash
git reset --hard main               # Reset branch to match main
git push origin dev --force         # Force push (use carefully)
```

---

## ✍️ Commit Message Convention

### Format

```bash
type: short description
```

### Types

* feat → new feature
* fix → bug fix
* refactor → code improvement
* chore → setup/config
* docs → documentation

### Examples

```bash
feat: add lru cache implementation
fix: resolve concurrency issue
refactor: optimize rate limiter logic
docs: add git command guide
chore: initial project setup
```

---

## 📌 Best Practices

* Use **small and meaningful commits**
* One feature per branch
* Never commit directly to `main`
* Use clear branch names (feature/, bugfix/)
* Avoid vague messages like "done" or "changes"

---
