# Fit for Devops


This repository is for understanding Git Concepts for Devops

Git for Beginners: A Friendly, Step-by-Step Guide

Hey there! Welcome to the world of Git—your new best friend for managing code. Think of Git like a super-organized notebook that tracks every change you make to your project. If you mess up, no worries—Git helps you go back in time!

Let’s walk through a real-world example: You’re working on a website, and you want to use Git to keep track of your progress.

Step 1: Install Git & Set It Up
First, download Git from git-scm.com. Once installed, open your terminal (Command Prompt, Git Bash, or Terminal) and introduce yourself to Git:

Run: git config --global user.name "Your Name"
Run: git config --global user.email "your.email@example.com"

This is like signing your name on your notebook so Git knows who’s making changes.

Step 2: Start a New Project (or Use an Existing One)
Let’s say you have a folder called my-website. Navigate to it in your terminal:

Run: cd my-website

Now, tell Git to start tracking this folder:

Run: git init

This creates an invisible .git folder that stores all your project’s history.

Step 3: Make Changes & Save Them (Commit)
You add a new file, index.html, with some basic HTML. To save this in Git:

Check what’s changed:
Run: git status

Git will say, “Hey, you have a new file called index.html that I’m not tracking yet!”

Tell Git to track the file:
Run: git add index.html

Or use git add . to add all new/changed files.

Permanently save (commit) the changes:
Run: git commit -m "Added homepage HTML"

The -m is a short message describing what you did. Be clear, like a sticky note!

Step 4: Connect to GitHub (Your Online Backup)
Now, let’s store your project on GitHub so you don’t lose it if your computer crashes.

Create a new repository on GitHub (click the + button in the top-right).

Copy the repository URL (looks like https://github.com/your-username/my-website.git).

Link your local project to GitHub:
Run: git remote add origin https://github.com/your-username/my-website.git

Push (upload) your code:
Run: git push -u origin main

Now your code is safely on GitHub! The -u means “remember this link for next time.”

Step 5: Work on a New Feature (Using Branches)
You want to add a “Contact” page without messing up your working website. Branches let you work on separate versions.

Create & switch to a new branch:
Run: git checkout -b contact-page

Now you’re in a safe space to experiment!

Make changes (add contact.html).

Commit them:
Run: git add contact.html
Run: git commit -m "Added contact page"

Push the branch to GitHub:
Run: git push -u origin contact-page

Merge it back into main (your live website):

Go to GitHub, open a Pull Request (PR), review, and merge.

Or, locally:
Run: git checkout main
Run: git merge contact-page
Run: git push origin main

Recap of Key Commands

git init → Start tracking a folder

git add [file] → Stage changes for commit

git commit -m "message" → Save changes permanently

git push → Upload to GitHub

git pull → Download latest changes

git checkout -b [name] → Create & switch to a new branch

git merge [branch] → Combine changes into current branch

Final Tips

Commit often (like saving a game).

Write clear commit messages (e.g., “Fixed navbar bug” not “Made changes”).

Use branches for new features (keeps main clean).

You’re now ready to use Git daily! If you get stuck, just Google or ask—every developer has been there.

Want to practice? Try this:

Create a repo, add a file, commit, and push.

Make a branch, edit the file, merge it back.

Happy coding!

—Your Friendly Git Mentor
