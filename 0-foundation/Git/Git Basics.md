# Git Basics

> Related: [[Introduction to Git]] | [[Setting Up Git]]

## Basic Git Workflow

### Step 1 — Clone repo
```bash
git clone git@github.com:USERNAME/REPO-NAME.git
```

### Step 2 — Files banao/edit karo
```bash
touch hello_world.txt
```

### Step 3 — Staging area mein add karo
```bash
git add filename.txt  # specific file
git add .             # sab files
```

### Step 4 — Commit karo
```bash
git commit -m "descriptive message"
```

### Step 5 — GitHub pe push karo
```bash
git push
```

---

## Status & History
```bash
git status   # kya staged hai, kya nahi
git log      # commit history dekho
```

---

## Important Concepts

- **Staging Area** = "waiting room" — commit se pehle files yahan jaati hain
- **origin** = remote repository ka default naam
- **main** = default branch ka naam
- **Atomic Commit** = ek commit = ek feature/task only

---

## Git Syntax Pattern
`git | action | destination`
- `git add .` = git | add | . (everything)
- `git commit -m "msg"` = git | commit | message
- `git push origin main` = git | push | origin/main

---

## VS Code as Default Editor
```bash
git config --global core.editor "code --wait"
```

> [!summary] Cheatsheet
> clone = add = commit = push
> git status & git log = tumhare best friends 