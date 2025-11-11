formatted as a professional README.md file (Markdown style) — you can copy and paste this directly into your README.md file 👇

# 🧠 Git Commands Guide

This guide provides essential Git commands for managing repositories efficiently.

---

## 🌀 Clone an Existing Repository

```bash
git clone "https://github.com/Amirsaifi786/billmanagement.git"

⚙️ Initialize a New Git Repository
git init


Then make any file changes and check the status:

git status

👤 Configure Your Git Username and Email
git config --global user.name "Amir Saifi"
git config --global user.email "amirsaifi637577@gmail.com"

🔐 Push with Personal Access Token

When prompted for authentication during git push,
use your GitHub personal access token instead of a password.

Example:

Token: 763F-258E


(Then click Authorize when GitHub asks.)

💾 Commit Your Changes
git add .
git commit -m "Your commit message"

🚀 Push Changes to GitHub
git push origin main


If pushing for the first time:

git push -u origin main

🧰 Create a New Repository on the Command Line
echo "# mymobile-softeware" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Amirsaifi786/mymobile-softeware.git
git push -u origin main

📦 Push an Existing Repository from Your Local Project
git remote add origin https://github.com/Amirsaifi786/mymobile-softeware.git
git branch -M main
git push -u origin main

⚠️ Force Push (Overwrite Remote Content)

If you want to completely replace remote content with your local project:

git push origin main --force

🔁 Continue Rebase (If Merge Conflicts Occur)
git rebase --continue


Then push again:

git push origin main

✅ Summary
Action	Command
Clone repo	git clone <url>
Initialize repo	git init
Add changes	git add .
Commit changes	git commit -m "message"
Push to GitHub	git push origin main
Set upstream	git push -u origin main
Force push	git push origin main --force
🧑‍💻 Author

Amir Saifi
📧 Email: amirsaifi637577@gmail.com

🌐 GitHub: github.com/Amirsaifi786


---
