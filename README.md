# 📦 GitHub Assignment 
**Question 1: Project Initialization & First Push**

## 🎯 Objective
Set up a new Git project and push it to a remote repository.

## 📘 Scenario

You are starting a new Python project. You need to:

* Track your code using Git
* Push your project to a remote repository (GitHub)

---

## 🛠️ Steps & Commands

### 📁 1. Create Project Folder
Open VS code -> Create a project folder 
```VS Code Terminal
mkdir Git_Github_Assignment
cd Git_Github_Assignment
```

---

### 🔧 2. Initialize Git Repository

```bash
git init
```

**Output:**

```
<img width="817" height="56" alt="image" src="https://github.com/user-attachments/assets/ff11c9e2-1d82-4538-8825-3e53ad6b8d5c" />

```

---

### 📝 3. Create Python File
create a new file and name it app.py

```bash
echo "print('Hello World')" > app.py
```

---

### 🔍 4. Check Git Status

```bash
git status
```

**Output:**

```
On branch master

No commits yet

Untracked files:
  app.py
```

---

### ➕ 5. Stage the File

```bash
git add app.py
```

---

### 💾 6. Commit the File

```bash
git commit -m "Initial commit: added app.py"
```

**Output:**

```
1 file changed, 1 insertion(+)
create mode 100644 app.py
```

---

### 🌐 7. Create Remote Repository

* Go to GitHub
* Create a new repository
* Copy the repository URL

Example:

```
https://github.com/your-username/Github_Assignment.git
```

---

### 🔗 8. Add Remote Repository

```bash
git remote add origin https://github.com/your-username/Github_Assignment.git
```

---

### 🔎 9. Verify Remote Configuration

```bash
git remote -v
```

**Output:**

```
origin https://github.com/your-username/Github_Assignment.git (fetch)
origin https://github.com/your-username/Github_Assignment.git (push)
```

---

### 🚀 10. Push Code to Remote Repository

```bash
git branch -M main
git push -u origin main
```

**Output:**

```
Branch 'main' set up to track remote branch 'main'
```

---

## ✅ Result

* Local repository initialized
* File tracked and committed
* Remote repository connected
* Code successfully pushed to GitHub

---

## 📌 Conclusion

This exercise demonstrates the basic Git workflow:

* Initializing a repository
* Tracking files
* Committing changes
* Connecting to a remote repository
* Pushing code to GitHub

---
