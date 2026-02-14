# 🚀 STANDARD GIT WORKFLOW (TEAM RULES)

---

## 📌 IMPORTANT RULES

- ❌ Never push directly to `main`
- ❌ Never commit on `main`
- ✅ Always work on your own branch
- ✅ Always sync with `main` before pushing

---

## 🪜 STEP-BY-STEP PROCESS

### 1️⃣ Open VS Code
- Open your project folder

---

### 2️⃣ Check Your Current Branch

Run:

git branch

If you see:

* main

Switch to your branch:

git checkout your-branch-name

---

### 3️⃣ Pull Latest Changes from Main (BEFORE Coding)

git pull origin main

---

### 4️⃣ Write Your Code
- Do your development
- Test properly
- Fix errors if needed

---

### 5️⃣ Pull Again Before Pushing (VERY IMPORTANT)

git pull origin main

---

### 6️⃣ Add Your Changes

git add .

---

### 7️⃣ Commit Your Changes

git commit -m "Your meaningful commit message"

Example:

git commit -m "Added diet recommendation component"

---

### 8️⃣ Push to Your Branch (NEVER MAIN)

git push origin your-branch-name

---

## ⚡ QUICK FLOW SUMMARY

git branch  
git checkout your-branch-name  
git pull origin main  
# write code  
git pull origin main  
git add .  
git commit -m "message"  
git push origin your-branch-name  

---

## 🔒 FINAL REMINDER

`main` branch = stable production code.  
Do NOT push directly to it.
