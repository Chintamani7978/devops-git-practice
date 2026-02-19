# Day 22 – Understanding Git Workflow

## 1. What is the difference between `git add` and `git commit`?

`git add` moves changes from the working directory into the staging area.

`git commit` takes everything in the staging area and creates a permanent snapshot in the repository history.

So:
Working Directory → (git add) → Staging Area → (git commit) → Repository


## 2. What does the staging area do? Why doesn't Git commit directly?

The staging area acts like a preparation zone.

It allows me to:
- Select specific files
- Select partial changes
- Review changes before committing

Git does not commit directly because it gives control over what exactly goes into each commit. This helps create clean and meaningful commit history.


## 3. What information does `git log` show?

`git log` shows:
- Commit hash
- Author name
- Date and time
- Commit message

It shows the history of the project in reverse chronological order.


## 4. What is the `.git/` folder and what happens if you delete it?

The `.git/` folder contains:
- All commits
- Branch information
- Configuration
- Object database

It is the brain of the repository.

If I delete `.git/`, the folder stops being a Git repository. All version history is permanently lost.


## 5. What is the difference between working directory, staging area, and repository?

Working Directory:
Where I edit files normally.

Staging Area:
Temporary area where changes are prepared before committing.

Repository:
The permanent history of committed snapshots stored inside `.git/`.

## Difference between git fetch and git pull

git fetch:
Downloads changes from remote repository but does NOT merge them.

git pull:
Downloads changes AND automatically merges them into the current branch.

git pull = git fetch + git merge


