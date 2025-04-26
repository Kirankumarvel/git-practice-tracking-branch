
# Git Practice: Tracking Branch

Welcome to the **Git Practice: Tracking Branch** repository!  
This project is designed to help you understand and practice how Git tracking branches work between your local and remote repositories.

---

## 📚 Topics Covered
- Initializing a Git repository
- Creating and pushing local branches
- Setting upstream (tracking) branches
- Handling `git pull` and `git push` errors
- Resolving merge and rebase conflicts
- Best practices for branch management

---

## 🚀 Commands Practiced

### Initialize Repository
```bash
git init
```

### Create a Branch and Switch
```bash
git checkout -b branch-name
```

### Set Upstream (Tracking Branch)
```bash
git push -u origin branch-name
```

### Rebase Changes
```bash
git pull --rebase origin main
```

### Handle Merge Conflicts
(Resolve conflicts manually, then stage changes and continue rebasing)
```bash
git add .
git rebase --continue
```

### Delete a Branch
```bash
git branch -d branch-name        # Delete locally
git branch -D branch-name        # Force delete locally
```

---

## 🎯 Goal
The goal is to gain confidence in:
- Managing local and remote branches in Git
- Handling conflicts effectively
- Understanding the life cycle of a branch, from creation to merging or deletion

---

## 📂 Project Structure
- **README.md** — Project description and guide
- **Practice files** — Example files such as `login.txt`, conflict examples, etc.

---

## 📢 Note
This repository is for educational and practice purposes only.  
Feel free to fork it and try your own experiments!

---

## 🛠 Author
**Kiran Kumar**  
GitHub: [@kirankumarvel](https://github.com/kirankumarvel)
```
