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

## 6. Init command

The git init command creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository. Most other Git commands are not available outside of an initialized repository, so this is usually the first command you'll run in a new project.

***Command***

    git init

## 7. Log command

The git log command shows a list of all the commits made to a repository. You can see the hash of each Git commit, the message associated with each commit, and more metadata. This command is useful for displaying the history of a repository.

***Command***

    git log

## 8. Merge command

To merge branches locally, use git checkout to switch to the branch you want to merge into. This branch is typically the main branch. Next, use git merge and specify the name of the other branch to bring into this branch. This example merges the jeff/feature1 branch into the main branch.

***command***

    git merge branch1/branch2

## 9. gitignore file

Git ignore files is a file that can be any file or a folder that contains all the files that we want to ignore. The developers ignore files that are not necessary to execute the project. Git itself creates many system-generated ignored files. Usually, these files are hidden files. There are several ways to specify the ignore files. The ignored files can be tracked on a .gitignore file that is placed on the root folder of the repository. No explicit command is used to ignore the file.

***command***

    $ touch .gitignore

    $ cat .gitignore

## 10. gitk command

Gitk is invoked similarly to git log. Executing the gitk command will launch the Gitk UI

***command***

    gitk [<options>] [<revision range>] [--] [<path>…] <revision range>

## 11. Pull Command

The `git pull` command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.

***command***

    git pull <remote name> <branch name>

## 12. Push Command

The `git push` command is used to transfer or push the commit, which is made on a local branch in your computer to a remote repository like GitHub.

***Command***

    git push <remote name> <branch name>

## 13. Remote command

The git remote command lets you create, view, and delete connections to other repositories. Remote connections are more like bookmarks rather than direct links into other repositories.

***commands***

    git remote 

    git remote -v

    git remote add [name] [url]

    git remote remove [name]

## 14. Status command

The git status command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git. Status output does not show you any information regarding the committed project history.

***command***

    git status

## 15. Stash command

Use git stash when you want to record the current state of the working directory and the index, but want to go back to a clean working directory. The command saves your local modifications away and reverts the working directory to match the HEAD commit.

***command***

    git stash