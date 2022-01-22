# Git
Git is a free and open source distributed version control system, actively maintained open source project originally developed in 2005 by Linus Torvalds

## Acronyms
- VSC: Version control system
- SCM: Source code management
- git: Distrbuted version control system

## How to install `git` :

### Ubuntu
```
 $ sudo apt install git
```
### Fedora
```
 $ sudo dnf install git
```
### Set a git username and email globally
```
$ sudo git config --global user.name “your_user_name”

$ git config --global user.email “your_email”
```
### Confirm that you have set the git details correctly
```
$ git config --global user.name

$ git config --global user.email
```
## What is a repository
A repository is a folder containing a `.git` directory and our projects files that tracks every changes on our project by git.

## Important files in a repository
- `README.md` file
    - Repository details
    - How to use this project
- LICENSE
- `.gitignore` file

------------------------------------------------
## Git state operation
- Working tree  
- Local repository  
- Staginig area  
- Remote repository
-------------------------------------------------



## Git cheatsheet
| command     | Description
|-------------| ------------
|git init  | Initial a new repository
|git add  | Add a file to the staging area. Use in place of the full file path to add all changed files from the current directory down into the directory tree.
|git commit -m | Create a new commit from changes added to the staging area.
|git clone [repoUrl]| Downloads a project with the entire history from the remote repository.
|git status| Displays the status of your working directory. Options include new, staged, and modified files. It will retrieve branch name, current commit identifier, and changes pending commit
|git log | List commit history of current branch. 
|git reset | Switches the current branch to the target reference, leavinga difference as an uncommitted change.
|git reset HARD |  When --hard is used,all changes are discarded.
|git reset HEAD~1 | Going back to the commit before HEAD
|git reset HEAD~2 | Going back two commits before HEAD
|git branch | List all local branches in repository
|git branch baranchName| Create new branch, referencing the current HEAD.
|git checkout branch name | Switch working directory to the specified branch.
|git pull | Fetch changes from the remote and merge current branch with its upstream.
|git push origin | Push local changes to the remote repository.
|git marge | Join two or more development histories together

---------------------------------------------------
## Fork
A fork is a rough copy of a repository. Forking a repository allows you to freely test and debug with changes without affecting the original project. One of the excessive use of forking is to propose changes for bug fixing. To resolve an issue for a bug that you found, you can:
- Fork the repository.
- Make the fix.
- Forward a pull request to the project owner.
--------------------------------------------------
#### Written by Majid Roodi     
[majidroodi.github.io](https://majidroodi.github.io/)  

---------------------------------------------------
This `git_cheatsheet` is a part of DevOps with Saeid class 
(`DWS-DEV-005-git`)  
See more on:  
[www.devops-with-saeid.com](https://devops-with-saeid.com/)
