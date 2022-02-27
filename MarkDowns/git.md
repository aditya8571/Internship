# Git Commands

## 1. Add Command

The git add command adds a change in the working directory to the 
staging area. It tells Git that you want to include updates to a 
particular file in the next commit. However, git add doesn't really 
affect the repository in any significant way—changes are not actually 
recorded until you run git commit .

***Command***

    git add .

    git add filename

Output Screen :

![Add command](/home/aditya/Pictures/add-commit)

## 2. Commit

Adding commits keep track of our progress and changes as we work. 
Git considers each commit change point or "save point". It is a point in 
the project you can go back to if you find a bug, or want to make a change.

***Command***

    git commit -m "message"

Output Screen:

![Commit command](/home/aditya/Pictures/add-commit)

## 3. Config Command

The git config command is a convenience function that is used to set Git configuration values on a global or local project level.

***Command***

    git config --global user.name "your Name"

    git config --global user.email "youremail@gmail.com"

Output Screen :

![Config Command](/home/aditya/Pictures/config)

## 4. Clone Command


Usage. git clone is primarily used to point to an existing repo and make a clone or copy of that repo at in a new directory, at another location.

***Command***

    git clone <url>

    git clone <SSH>

Output Screen: 

![clone Command](/home/aditya/Pictures/clone)

## 5. Checkout Command
The git checkout command lets you navigate between the branches created by git branch . Checking out a branch updates the files in the working directory to match the version stored in that branch, and it tells Git to record all new commits on that branch.

***Command***

    git checkout <new branch>

**New Branches**

Additionally, The git checkout command accepts a -b argument that acts as a convenience method which will create the new branch and immediately switch to it. You can work on multiple features in a single repository by switching between them with git checkout.

    git checkout -b <new branch>

**Deleting a branch**

    git branch -d <branch name>

    git branch -D <branch name>

Output Screen :

![checkout command](/home/aditya/Pictures/checkout)

