# Homework 2 — Part 2 Submission

Student name: William Hooper

GitHub username: augiehooper4300-oss

## 1. Git Command Observations

| Command or workflow | What did you observe? | What was the user trying to accomplish? | What problem or risk did it address? |
|----|----------------|--------------------------------------------------|---|
| 1. | git status | lists edited file and showed my current branch | Get a quick overview of where my work stands | Could forget about a changed or new file and end up committing incomplete work.
| 2. | git diff <file>| Shows the exact lines I changed line by line. | See the content of my changes not just which files changed. | Catches mistakes before they get saved |
| 3. | git add <file> | moved my work from the working tree to be staged | Pick which changes go into the next commit. | Prevents mixing unfinished work and lets me verify before it becomes permanent.
| 4. | git log --oneline -3 |Shows my most recent commits, newest first, one per line with ID and message. |  |

## 2. User Needs

### UN-GIT-01 — Understand current changes

> A student developer working on a project needs a way to know which files they have changed since their last saved version, because  unnoticed edits could break the project.

### UN-GIT-02 — Choose what belongs in a saved version

> A student developer working on a shared project needs a way to choose which specific changes belong in the next saved version, because the working tree can mix finished work with stuff that is inconplete.

### UN-GIT-03 — Revisit versions

> A student developer working on a shared project needs a way to keep snapshots of the project at meaningful points, in case they need to recover from mistakes its inmportant the can go back to a later version and see what was changed and why.

## 3. User Requirements

| ID and short title | User requirement | Source user need | Rationale |
|-----------|------------------------|-----------|-----------------------------------------------------------------------------------|
| UR-GIT-01 | View changed files     | UN-GIT-01 | The user needs a fast overview of what they have before deciding what to do next. |
| UR-GIT-02 | Select changes to save | UN-GIT-02 | Keeps unfinished work out of shared history.                                      |
| UR-GIT-03 | Review before saving   | UN-GIT-03 | User needs a last chance to confirm changes.                                      |
| UR-GIT-04 | Review recent history  | UN-GIT-03 | Lets the user confirm the save worked when working with teammates                 |

