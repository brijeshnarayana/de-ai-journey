# Learning Log 
## 2026-10-24 — Git + GitHub setup
- Git vs GitHub: Git snapshots locally, GitHub hosts the copy others can see
- Three states: working directory → staging (`git add`) → commit (`git commit`)
- `git push` sends commits to `origin` (the GitHub copy)
- Git tracks files, not folders — empty dirs need a placeholder file
- Repo live: de-ai-journey, structure in place

## 2026-10-25 — Git internals
- A commit = full snapshot of tracked files + author + timestamp + parent pointer
- History is a chain of commits; `git log --oneline` reads it newest-first
- A branch is a movable label on a commit; `HEAD` = where I am now
- `origin/main` = Git's record of GitHub's main; it lags until I push
- `.gitignore` only works on untracked files — ignore before first commit
- Commit messages: imperative, under 50 chars ("Add", not "Adding")
