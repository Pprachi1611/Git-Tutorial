# 📘 Git Basics

## What is Git?

Git is a Distributed Version Control System (DVCS) used to track changes in files and collaborate with other developers.

---

## Why Use Git?

✅ Tracks changes

✅ Maintains project history

✅ Supports collaboration

✅ Allows rollback

✅ Supports branching and merging

---

## Initialize Repository

```bash
git init
```

Creates a new Git repository.

Example:

```bash
mkdir project
cd project
git init
```

---

## Check Repository Status

```bash
git status
```

Shows:

- Modified files
- Staged files
- Current branch

---

## Add Files

Add one file:

```bash
git add index.html
```

Add all files:

```bash
git add .
```

---

## Commit Changes

```bash
git commit -m "Added homepage"
```

Creates a snapshot of the project.

---

## View Commit History

```bash
git log
```

Short version:

```bash
git log --oneline
```

Example:

```text
86bd8de Updated homepage
d86ad5b Version 2
636134e Initial commit
```

---

## Restore Changes

Restore one file:

```bash
git restore index.html
```

Restore all files:

```bash
git restore .
```

Used to discard local changes.