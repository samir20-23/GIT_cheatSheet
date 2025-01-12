```markdown
# Git Guide

---

## Clone
```bash
git clone <repository_url>
```

---

## Add
```bash
git add <file_name>
git add .
```

---

## Status
```bash
git status
```

---

## Commit
```bash
git commit -m "Message"
```

---

## Push
```bash
git push origin <branch_name>
```

---

## Pull
```bash
git pull origin <branch_name>
```

---

## Branches
```bash
git branch <branch_name>
git checkout <branch_name>
git checkout -b <branch_name>
git branch
git branch -r
git branch -a
git branch -d <branch_name>
git push origin --delete <branch_name>
```

---

## Remote
```bash
git remote add origin <url>
git remote -v
git remote set-url origin <new_url>
```

---

## Submodules
```bash
git submodule add <url> <dir>
git submodule init
git submodule update
git rm --cached <path>
rm -rf <path>
```

---

## History
```bash
git log
```

---

## Revert
```bash
git checkout <file_name>
git reset --hard
```

---

## Stash
```bash
git stash
git stash apply
```

---

## Delete Local
```bash
rm -rf <dir>
```
```
