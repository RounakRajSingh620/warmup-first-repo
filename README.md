# Git
Git is a version control system that tracks changes to your code over time.
It lets developers collaborate, store history, and revert or merge changes easily.

# Basic Git Concepts:
1. Staging - Selecting which files you want to commit or save. (cmd: git add file.js)
2. Commit -	Save a snapshot of your project at a specific point in time. (cmd: git commit -m "added new feature")
3. Push - Send your commits from your local system to GitHub. (cmd:	git push origin main)
4. Pull - Get the latest updates from GitHub to your local system. (cmd: git pull origin main)
5. Merge - Combine code from one branch into another. (cmd:	git merge feature/login)

# Branching Strategies
1. main - It is used for stable production code.
2. dev - It is an active development phase like integration branch where new features are tested and develope together.
3. feature - It is used as a temporary branches for each new features or bugs fix and then if all good then the feature get merged. Example:(feature/login).

Git solve major problem in collaborative dev environment like 
- It prevent overwriting of others code.
- It shows all the tracks i.e who changed what and when.
- It helps to rollback easy if any bug or error occurs with thte help of staging tracks(untracked, tracked, modified, staged, checkpoints). 
- It helps to work simultaneously on multiple features and it also integrates with github for collaboration and reviews.
- It helps to keep our code clean and organised with the structures flows (gitflow or github flow).