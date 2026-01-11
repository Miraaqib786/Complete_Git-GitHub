# Complete Git & GitHub Tutorial (Beginner to Advanced)

Complete end-to-end tutorial on Git and GitHub, starting from absolute basics and going up to advanced workflows used in real-world software development.

---

## Table of Contents
1. Introduction to Version Control
2. What is Git?
3. What is GitHub?
4. Installing Git
5. Basic Git Configuration
6. Understanding Git Workflow
7. Creating a Git Repository
8. Basic Git Commands
9. Working with Branches
10. Merging & Resolving Conflicts
11. GitHub Basics
12. Pushing Code to GitHub
13. Cloning & Forking Repositories
14. Pull Requests (PRs)
15. Undoing Changes
16. Git Tags & Releases
17. Git Ignore (.gitignore)
18. Stashing in Git
19. Git Rebase
20. Git Cherry-pick
21. Git Logs & History
22. Collaboration Workflow
23. GitHub Issues & Projects
24. GitHub Actions (CI/CD Intro)
25. Best Practices
26. Common Git Errors & Fixes
27. Interview Questions

---

## 1️⃣ Introduction to Version Control
Version Control Systems (VCS) help track changes in files over time.

### Why Version Control?
- Track history
- Collaboration
- Backup
- Experiment safely

Examples:
- Git (Distributed)
- SVN (Centralized)

---

## 2️⃣ What is Git?
Git is a **distributed version control system** created by **Linus Torvalds**.

### Features
- Fast
- Distributed
- Secure (SHA-1)
- Branching & Merging

---

## 3️⃣ What is GitHub?
GitHub is a **cloud-based hosting service** for Git repositories.

### Git vs GitHub
| Git | GitHub |
|---|---|
| Tool | Platform |
| Local | Cloud |
| CLI | Web UI |

---

## 4️⃣ Installing Git

### Windows
Download from: https://git-scm.com

Verify installation:
```bash
git --version
```

### Linux
```bash
sudo apt install git
```

### macOS
```bash
brew install git
```

---

## 5️⃣ Basic Git Configuration
```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

Check config:
```bash
git config --list
```

---

## 6️⃣ Understanding Git Workflow

```
Working Directory → Staging Area → Local Repo → Remote Repo
```

---

## 7️⃣ Creating a Git Repository

```bash
git init
```

Check status:
```bash
git status
```

---

## 8️⃣ Basic Git Commands

### Add files
```bash
git add file.txt
git add .
```

### Commit
```bash
git commit -m "Initial commit"
```

### View history
```bash
git log
```

---

## 9️⃣ Working with Branches

### Create branch
```bash
git branch feature1
```

### Switch branch
```bash
git checkout feature1
git switch feature1
```

### Create & switch
```bash
git checkout -b feature2
```

---

## 🔟 Merging & Resolving Conflicts

### Merge branch
```bash
git checkout main
git merge feature1
```

### Conflict Resolution
- Edit conflicted files
- Remove markers
- Commit again

---

## 1️⃣1️⃣ GitHub Basics

### Create Repository
1. Login to GitHub
2. Click **New Repository**
3. Copy repo URL

---

## 1️⃣2️⃣ Pushing Code to GitHub

```bash
git remote add origin https://github.com/username/repo.git
git branch -M main
git push -u origin main
```

---

## 1️⃣3️⃣ Cloning & Forking

### Clone
```bash
git clone https://github.com/user/repo.git
```

### Fork
- Creates copy in your GitHub account

---

## 1️⃣4️⃣ Pull Requests (PRs)

Steps:
1. Create branch
2. Push branch
3. Open PR
4. Review & Merge

---

## 1️⃣5️⃣ Undoing Changes

### Discard changes
```bash
git checkout -- file.txt
```

### Reset commit
```bash
git reset --hard HEAD~1
```

---

## 1️⃣6️⃣ Git Tags & Releases

```bash
git tag v1.0
git push origin v1.0
```

---

## 1️⃣7️⃣ .gitignore File

Example:
```
__pycache__/
node_modules/
.env
```

---

## 1️⃣8️⃣ Git Stash

```bash
git stash
git stash pop
```

---

## 1️⃣9️⃣ Git Rebase

```bash
git rebase main
```

Used for clean commit history.

---

## 2️⃣0️⃣ Git Cherry-pick

```bash
git cherry-pick <commit-hash>
```

---

## 2️⃣1️⃣ Git Logs & History

```bash
git log --oneline --graph --all
```

---

## 2️⃣2️⃣ Collaboration Workflow

1. Fork repo
2. Clone fork
3. Create branch
4. Commit
5. Push
6. Create PR

---

## 2️⃣3️⃣ GitHub Issues & Projects

- Bug tracking
- Feature requests
- Kanban boards

---

## 2️⃣4️⃣ GitHub Actions (CI/CD Intro)

Example workflow:
```yaml
name: CI
on: [push]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
```

---

## 2️⃣5️⃣ Best Practices

- Commit often
- Write clear messages
- Use branches
- Pull before push

---

## 2️⃣6️⃣ Common Git Errors & Fixes

### Error: rejected push
```bash
git pull --rebase
```

### Detached HEAD
```bash
git checkout main
```

---

## 2️⃣7️⃣ Interview Questions

1. Difference between git merge & rebase?
2. What is HEAD?
3. What is fork vs clone?
4. What is stash?
5. Explain Git workflow

---
## Conclusion

You now have **complete Git & GitHub knowledge** from beginner to advanced level. This README can be used for:
- Learning
- Teaching
- Lab manuals
- Interview preparation

---
### 👨‍🏫 Prepared by: **Aaqib Rashid Mir**
DS & AI Trainer | Data Science| Guru Nanak Institutions Technical Campus

⭐ Happy Coding! ⭐
