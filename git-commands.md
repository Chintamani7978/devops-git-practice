# Git Commands Reference

This document contains Git commands I am learning during my DevOps journey.

---

## Setup & Configuration

### git --version
Checks installed Git version.

Example:
git --version

### git config --global user.name
Sets global username for commits.

Example:
git config --global user.name "Your Name"

### git config --global user.email
Sets global email for commits.

Example:
git config --global user.email "your-email@example.com"

---

## Repository Initialization

### git init
Initializes a new Git repository.

Example:
git init

---

## Viewing Status

### git status
Shows current state of working directory and staging area.

Example:
git status
---

## Basic Workflow

### git add
Stages changes to be committed.

Example:
git add filename

### git commit
Creates a snapshot of staged changes.

Example:
git commit -m "your message"


---

## Viewing Changes

### git diff
Shows changes between working directory and staging area.

Example:
git diff

### git log
Shows commit history.

Example:
git log

### git log --oneline
Shows compact commit history.

Example:
git log --oneline


---

## Branch Information

### git branch
Lists branches.

Example:
git branch

This line was added directly on GitHub.
## Feature Login
Login functionality notes.

Hotfix directly on main.

Signup feature structure.

Minor improvement on main.

Profile page layout.
Fix typo in profile.
Improve formatting.
<<<<<<< HEAD
Add profile validation



Hotfix change 1
Hotfix change 2
Hotfix change 3


=======
Add profile validation.
>>>>>>> d75643a (Add profile feature (squashed commit

## GitHub CLI (gh)

gh auth login
gh auth status
gh repo create
gh repo clone
gh repo view
gh repo list
gh repo delete



gh issue create
gh issue list
gh issue view
gh issue close
gh label create
