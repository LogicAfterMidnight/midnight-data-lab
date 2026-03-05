# Git Cheat Sheet

## Check project status

```
git status
```

---

## Add files to commit

Add everything:

```
git add .
```

Add specific file:

```
git add filename
```

---

## Commit changes

```
git commit -m "describe what changed"
```

Example:

```
git commit -m "Add pandas analysis script"
```

---

## Push to GitHub

```
git push
```

---

## See commit history

```
git log
```

---

## Undo staged files

```
git reset
```

---

## Fix last commit author

```
git commit --amend --reset-author
```

---

## Typical developer workflow

```
git add .
git commit -m "update"
git push
```
