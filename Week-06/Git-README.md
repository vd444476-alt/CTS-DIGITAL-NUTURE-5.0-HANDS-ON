# Week-05 — Git Hands-On Exercises

Part of the **CTS Digital Nurture 5.0 — Java Full Stack Engineer Track**.

This section covers 5 hands-on Git labs — from initial setup and first commits through branching, merging, conflict resolution, and syncing with a remote repository. All labs were completed against a practice repository (`GitDemo`) using Git Bash on Windows.

---

## Hands-On Labs

| # | Lab | Topic | What It Covers |
|---|---|---|---|
| 1 | Git Configuration & First Commit | Setup | Verifying the Git client install, configuring global `user.name`/`user.email`, setting a default editor, initializing a repository, and making the first tracked commit (`welcome.txt`). |
| 2 | `.gitignore` | Ignoring Files | Creating `.log` files and a `log/` folder, then writing a `.gitignore` so both are excluded from tracking; verifying with `git status` and `git check-ignore`. |
| 3 | Branching & Merging | Clean Merge | Creating a new branch (`GitNewBranch`), committing changes on it, then merging it back into `master`/`main` via a fast-forward merge; visualizing history with `git log --oneline --graph --decorate`. |
| 4 | Conflict Resolution | Merge Conflicts | Deliberately creating divergent changes to the same file (`hello.xml`) on two branches, triggering a merge conflict, and resolving it manually/with a merge tool before committing the resolution. |
| 5 | Cleanup & Push | Sync with Remote | Verifying a clean working tree, pulling any pending remote changes, and pushing all local commits back to the remote repository. |

---

## Concepts Covered Across These Labs

- **Setup:** `git config --global`, default editor integration, `git init`
- **Basic workflow:** `git add`, `git commit`, `git status`, `git push`, `git pull`
- **Ignoring files:** `.gitignore` patterns, `git check-ignore`
- **Branching:** `git branch`, `git checkout` / `git switch`, `git branch -a`, `git branch -d`
- **Merging:** fast-forward merges, `git merge`, `git diff`, `git difftool`
- **Conflict resolution:** reading conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`), `git mergetool`, manual resolution
- **History inspection:** `git log --oneline --graph --decorate --all`
- **Remote sync:** `git remote`, `git fetch`, `git pull`, `git push`

---

## Tools Used

- **Git Bash** (Git for Windows)
- **VS Code** as the configured default editor (`core.editor`)
- **GitHub** as the remote repository host
- P4Merge referenced in the original lab as an optional visual diff/merge tool

---

## How to Reproduce

```bash
git init
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git add <file>
git commit -m "message"
git branch <branch-name>
git checkout <branch-name>
git merge <branch-name>
git push origin main
```
