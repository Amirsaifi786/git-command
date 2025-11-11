🧠 Git Commands Guide
🌀 Clone an existing repository
git clone "https://github.com/Amirsaifi786/billmanagement.git"

⚙️ Initialize a new Git repository
git init


Then make any file changes and check the status:

git status

👤 Configure your Git username and email
git config --global user.name "Amir Saifi"
git config --global user.email "amirsaifi637577@gmail.com"

🔐 Push with personal access token

When prompted for authentication during git push,
use your GitHub personal access token instead of a password.
Example:

Token: 763F-258E


(Then click Authorize when GitHub asks.)

💾 Commit your changes
git add .
git commit -m "Your commit message"

🚀 Push changes to GitHub
git push origin main


If pushing for the first time:

git push -u origin main

🧰 Create a new repository on the command line
echo "# mymobile-softeware" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Amirsaifi786/mymobile-softeware.git
git push -u origin main

📦 Push an existing repository from your local project
git remote add origin https://github.com/Amirsaifi786/mymobile-softeware.git
git branch -M main
git push -u origin main

⚠️ Force push (overwrite remote content)

If you want to completely replace remote content with your local project:

git push origin main --force

🔁 Continue rebase (if merge conflicts occur)
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
