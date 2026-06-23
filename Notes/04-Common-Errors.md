# ⚠️ Common Git Errors

---

## Error 1

```text
src refspec master does not match any
```

### Cause

Trying to push master while current branch is main.

### Solution

```bash
git push origin main
```

---

## Error 2

```text
remote contains work that you do not have locally
```

### Cause

GitHub has commits missing locally.

### Solution

```bash
git pull origin main
git push origin main
```

---

## Error 3

```text
fatal: not a git repository
```

### Cause

Not inside a Git repository.

### Solution

```bash
cd repository-folder
git status
```

---

## Error 4

```text
fatal: you must specify path(s) to restore
```

### Cause

Running:

```bash
git restore
```

without specifying a file.

### Solution

```bash
git restore index.html
```

or

```bash
git restore .
```

---

## Error 5

```text
Updates were rejected because the remote contains work that you do not have locally
```

### Cause

Remote repository is ahead of local repository.

### Solution

```bash
git pull origin main
git push origin main
```

---

## Best Practices

✅ Commit frequently

✅ Pull before pushing

✅ Use meaningful commit messages

✅ Create branches for features

✅ Keep README updated