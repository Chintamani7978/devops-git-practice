| Feature                          | git reset                     | git revert                                       |
| -------------------------------- | ----------------------------- | ------------------------------------------------ |
| What it does                     | Moves branch pointer backward | Creates new commit that undoes a previous commit |
| Removes commit from history?     | Yes (rewrites history)        | No (history preserved)                           |
| Safe for pushed/shared branches? | No                            | Yes                                              |
| Modifies commit hashes?          | Yes                           | No                                               |
| Creates new commit?              | No                            | Yes                                              |
| Use case                         | Fix local mistakes            | Undo changes safely in shared branches           |




Differences Explained

git reset

Changes branch pointer

Can delete commits from history

--soft keeps changes staged

--mixed keeps changes unstaged

--hard deletes changes completely

Dangerous if already pushed

Never use reset on shared branches.

git revert

Does not remove commit

Creates a new commit reversing changes

Safe for production branches

Keeps collaboration safe

When to Use What?

Use reset:

For local clean-up

Before pushing

To fix messy commit history

Use revert:

After pushing

On shared branches

In team environments


Git Reset vs Git Revert


| Feature                          | git reset                     | git revert                                       |
| -------------------------------- | ----------------------------- | ------------------------------------------------ |
| What it does                     | Moves branch pointer backward | Creates new commit that undoes a previous commit |
| Removes commit from history?     | Yes (rewrites history)        | No (history preserved)                           |
| Safe for pushed/shared branches? | No                            | Yes                                              |
| Modifies commit hashes?          | Yes                           | No                                               |
| Creates new commit?              | No                            | Yes                                              |
| Use case                         | Fix local mistakes            | Undo changes safely in shared branches           |



Differences Explained
git reset

Changes branch pointer

Can delete commits from history

--soft keeps changes staged

--mixed keeps changes unstaged

--hard deletes changes completely

Dangerous if already pushed

Never use reset on shared branches.

git revert

Does not remove commit

Creates a new commit reversing changes

Safe for production branches

Keeps collaboration safe

When to Use What?

Use reset:

For local clean-up

Before pushing

To fix messy commit history

Use revert:

After pushing

On shared branches

In team environments
