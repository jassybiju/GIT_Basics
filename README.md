# 🧠 Git Commands Cheat Sheet

This repository contains a categorized list of commonly used Git commands, helpful for beginners and intermediate developers alike. Git is a distributed version control system used for tracking changes in source code during software development.

---

## 🟢 Beginner Level – Daily Usage

These commands help you get started with Git and handle daily tasks:

| Command | Description |
|--------|-------------|
| `git init` | Start a new Git repository. |
| `git clone <repo-url>` | Copy a repository from GitHub or other sources. |
| `git status` | Check current changes, staging area, and branch. |
| `git add <file>` or `git add .` | Stage file(s) for commit. |
| `git commit -m "message"` | Commit staged changes with a message. |
| `git log` | View commit history. |
| `git diff` | See unstaged or staged changes. |
| `git rm <file>` | Remove a file from the repository. |

---

## 🟡 Intermediate Level – Team Collaboration & History

These are useful when collaborating with a team or managing branches and project history:

| Command | Description |
|--------|-------------|
| `git branch` | List local branches. |
| `git checkout <branch>` | Switch to a different branch. |
| `git checkout -b <new-branch>` | Create and switch to a new branch. |
| `git merge <branch>` | Merge changes from one branch into another. |
| `git pull` | Fetch and merge changes from remote to local. |
| `git push` | Push your local commits to a remote repository. |
| `git stash` | Temporarily save uncommitted changes. |
| `git stash pop` | Reapply stashed changes. |
| `git reset --hard` | Discard all local changes (dangerous if misused). |
| `git revert <commit>` | Create a new commit that undoes a specific commit. |

---

## 🔵 Bonus – Useful but Less Frequent

Advanced or rarely used commands that are good to know:

| Command | Description |
|--------|-------------|
| `git remote -v` | View remote URL(s). |
| `git fetch` | Download changes from remote without merging. |
| `git tag <tagname>` | Mark a specific point in history (e.g., releases). |
| `git rebase <branch>` | Reapply commits from one branch onto another (advanced history rewrite). |
| `git cherry-pick <commit>` | Apply a specific commit from another branch. |
| `git log --oneline --graph` | Visual history for understanding branches. |

---

## 📚 Learning Resources

- [Pro Git Book (free)](https://git-scm.com/book/en/v2)
- [GitHub Docs](https://docs.github.com/en/get-started/using-git)
- [Git Cheatsheet by GitHub](https://education.github.com/git-cheat-sheet-education.pdf)

---

## ✅ Contribution

Feel free to contribute to this list by opening a pull request or creating an issue.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

