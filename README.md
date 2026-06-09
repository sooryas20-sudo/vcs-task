# VCS Task - Git Commands Practice

## Task Overview
Established a directory with shell scripts, initialized a Git repository,
linked to GitHub, and performed merge, rebase, and stash operations.

## Tech Stack
- Shell (AWS EC2)
- Git / GitHub

## Project Structure
## Git Operations Performed

### 1. Initialize & Push
- Created local directory with shell scripts
- Initialized empty git repository
- Linked to GitHub remote
- Pushed initial commit

### 2. Merge
- Created `feature-branch`
- Added `feature.sh` with new code
- Merged `feature-branch` into `main`
- Result: feature.sh available in main

### 3. Stash
- Modified files without committing
- Used `git stash` to temporarily save changes
- Verified clean working directory
- Restored changes with `git stash pop`

### 4. Rebase
- Created `rebase-branch` from main
- Added commits on both branches
- Rebased `rebase-branch` on top of latest main
- Merged back to main cleanly

## Key Commands Used
| Command | Description |
|---------|-------------|
| `git init` | Initialize empty repository |
| `git add .` | Stage all changes |
| `git commit -m "msg"` | Save changes with message |
| `git push origin main` | Push to GitHub |
| `git checkout -b branch` | Create and switch branch |
| `git merge branch` | Merge branch into current |
| `git stash` | Temporarily save changes |
| `git stash pop` | Restore stashed changes |
| `git rebase main` | Rebase onto main branch |
| `git log --oneline --graph` | View commit history |

## Screenshots
See /screenshots folder for all output proofs.
