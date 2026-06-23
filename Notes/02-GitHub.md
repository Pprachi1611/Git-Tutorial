# 🌐 GitHub Fundamentals

## What is GitHub?

GitHub is a cloud platform used to host Git repositories.

---

## Git vs GitHub

| Git | GitHub |
|------|--------|
| Version Control System | Cloud Hosting Platform |
| Installed Locally | Runs Online |
| Tracks Changes | Stores Repositories |

---

## Connect Local Repository to GitHub

```bash
git remote add origin <repository-url>
```

Example:

```bash
git remote add origin https://github.com/username/repository.git
```

Verify:

```bash
git remote -v
```

---

## Push Code

First Push:

```bash
git push -u origin main
```

Regular Push:

```bash
git push origin main
```

---

## Clone Repository

```bash
git clone <repository-url>
```

Example:

```bash
git clone https://github.com/username/repository.git
```

---

## Pull Changes

```bash
git pull origin main
```

Downloads latest changes from GitHub.

---

## Workflow

```text
Developer
    ↓ Push
 GitHub
    ↑ Pull
Developer
```