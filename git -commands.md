
# Comprehensive Git Commands Guide

This document provides detailed explanations, use cases, examples, and interview questions for essential Git commands.

---

## 1. `git status`
**Description**: Displays the state of the working directory and staging area.

**Use Case**: To check which files have been modified, added, or deleted before committing.

**Example**:
```bash
git status
````

**Interview Question**:

* What does `git status` show?
* How does `git status` help during development?

---

## 2. `git add`

**Description**: Adds changes in the working directory to the staging area.

**Use Case**: To stage modified files for the next commit.

**Example**:

```bash
git add file.txt         # Adds a specific file
git add .                # Adds all changes in current directory
```

**Interview Question**:

* What happens when you use `git add .`?

---

## 3. `git commit`

**Description**: Records changes to the repository with a message.

**Use Case**: To save staged changes into the local repository.

**Example**:

```bash
git commit -m "Fixed login bug"
```

**Interview Question**:

* What's the difference between `git commit` and `git commit -m`?

---

## 4. `git push`

**Description**: Uploads local repository content to a remote repository.

**Use Case**: To share local changes with collaborators.

**Example**:

```bash
git push origin main
```

**Interview Question**:

* What happens when you `git push` without pulling the latest changes first?

---

## 5. `git log`

**Description**: Shows the commit history.

**Use Case**: To view previous commits and their messages.

**Example**:

```bash
git log
```

**Interview Question**:

* How can you limit the number of logs shown?

---

## 6. `git reset`

**Description**: Undoes changes by resetting the index and working directory.

**Use Case**: To undo commits or unstage files.

**Example**:

```bash
git reset HEAD~1           # Resets the last commit
```

**Interview Question**:

* What is the difference between `--soft`, `--mixed`, and `--hard` reset?

---

## 7. `git revert`

**Description**: Creates a new commit that undoes the changes of a previous commit.

**Use Case**: To safely undo a commit without rewriting history.

**Example**:

```bash
git revert a1b2c3d
```

**Interview Question**:

* When would you use `git revert` over `git reset`?

---

## 8. `git show`

**Description**: Displays information about a specific commit.

**Use Case**: To see changes introduced by a specific commit.

**Example**:

```bash
git show a1b2c3d
```

**Interview Question**:

* What information can you find using `git show`?

---

## 9. `.gitignore`

**Description**: Specifies intentionally untracked files to ignore.

**Use Case**: To exclude temporary files, logs, or build outputs from being tracked.

**Example** (`.gitignore` file):

```
node_modules/
*.log
.env
```

**Interview Question**:

* Why would you use a `.gitignore` file in a project?

---

## 10. `git clean`

**Description**: Removes untracked files from the working directory.

**Use Case**: To remove generated files or temporary content.

**Example**:

```bash
git clean -f
```

**Interview Question**:

* What does `git clean -fd` do?

---

## 11. `git flow`

**Description**: A branching model for Git, including features, releases, and hotfixes.

**Use Case**: To maintain a well-defined workflow for development.

**Example**:

```bash
git flow init
git flow feature start login-page
git flow feature finish login-page
```

**Interview Question**:

* How does `git flow` help in managing project releases?

---

# Summary of Interview Questions

1. Explain the output of `git status`.
2. Difference between `git add .` and `git add filename`.
3. What is staged vs committed?
4. Why use `git push`?
5. How to undo a commit safely?
6. What is the difference between `git revert` and `git reset`?
7. What does `.gitignore` do?
8. Explain `git clean -fd`.
9. When to use `git show`?
10. How does `git flow` improve team collaboration?

---

# End of Document


