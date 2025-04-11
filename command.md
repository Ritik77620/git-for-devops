🔧 Step 1: What Is Git?
Git is a version control system. It helps you track changes in your code and collaborate with others.

📁 Step 2: Set Up Git (One Time Only)
Set your identity:

git config --global user.name "Your Name"

git config --global user.email "you@example.com"

🧪 Step 3: Start a New Project
Create a folder: mkdir my-project

Enter it: cd my-project

Initialize Git: git init

This makes it a Git repository.

📄 Step 4: Create and Track Files
Create a file: touch index.html

Check status: git status

Stage it: git add index.html

Save with message: git commit -m "Add index.html"

🌀 Step 5: Make Changes and Save Again
Edit the file using any text editor like vim index.html

Check status: git status

Stage changes: git add index.html

Commit again: git commit -m "Update index.html content"

🌿 Step 6: Use Branches (For Features)
Create a new branch: git branch feature-login

Switch to it: git checkout feature-login

Or do both in one: git checkout -b feature-login

🔄 Step 7: Merge Changes
Switch back to main: git checkout main

Merge the feature: git merge feature-login

🔍 Step 8: See the History
Check commit history in short form: git log --oneline

🧹 Step 9: Undo / Restore
Undo a staged file: git restore --staged filename

Restore a file's content: git restore filename

🧠 Bonus Git Commands
git diff shows file changes

git stash hides uncommitted work temporarily

git clone <url> clones a remote repo

git pull brings latest changes

git push uploads your code

✅ Summary of a Daily Git Workflow
Make changes to your files

Stage the changes: git add .

Commit: git commit -m "Your message"

Push: git push origin branch-name
