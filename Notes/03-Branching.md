# 🌿 Git Branching

## What is a Branch?

A branch is an independent line of development.

It allows developers to work on new features without affecting the main code.

---

## Why Use Branches?

- Feature Development
- Bug Fixes
- Testing
- Team Collaboration

---

## View Branches

```bash
git branch
```

Example:

```text
* main
  feature
```

---

## Create Branch

```bash
git branch feature
```

---

## Switch Branch

```bash
git switch feature
```

---

## Create and Switch

```bash
git switch -c feature
```

---

## Branch Workflow

### Step 1

Create Branch

```bash
git switch -c feature
```

### Step 2

Modify files

### Step 3

Commit changes

```bash
git add .
git commit -m "Added new feature"
```

### Step 4

Switch back

```bash
git switch main
```

### Step 5

Merge

```bash
git merge feature
```

---

## Before Merge

```text
main
 |
 A

feature
 |
 A → B
```

---

## After Merge

```text
main
 |
 A → B

feature
 |
 A → B
```

---

## Delete Branch

```bash
git branch -d feature
```

---

## Local vs Remote Branch

Local Branch:

```text
Developer-Main
└── feature
```

Remote Branch:

```bash
git push -u origin feature
```

Visible on GitHub.