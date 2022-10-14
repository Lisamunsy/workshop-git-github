# Workshop : __Git & Github__
 <p style="text-align: center;">animated by Laurine, Lindsay and Lisa</p>
 
## ➛ Target
We created this workshop to help you understand some of the fundamental and core concepts of git & github.
Here is a cheatsheet to summarize what we just introduced you to.

## ➛ Installation

- Create a folder named 'Workshop-Git-Github'
- Open your bash terminal at this location
- clone this repository using `git clone https://github.com/Lisamunsy/workshop-git-github.git . `

## ➛ Content
### Bash
Line command | Action 
:---:|---
pwd | print working directory
cd | change directory
ls | list directory content
mkdir | create a new folder
touch | create a new file

### Git

Line Command | action | comments
--------------------- | --- |---
`git init` | initialize a local repo
`git add <fileName>` <br/> `git add .` | index selected files in the staging area 
`git commit -m "Relevant comment"` | generate a snapshop of the index file. It is stored in the local repository  
` git clone <url>` | create a local repository connected to a remote one
`git remote add <remoteName> <url>` | connect a local repository to a remote.
`git push -u <remoteName> <branch>` <br/> `git push --set-upstream <repoName> <branch>` | upload your commited files to a remote repository on the specified branch
`git branch <branchName>` | create a new branch
`git branch -m new-name`| rename a branch | -m stands for --move
`git checkout <branch>` | switch to the specified branch
`git fetch <remote> <branch>` | fetch the specifies remote's copy of the current branch 
`git merge <branch>` | merge one or multiple branch into the current branch
`git pull <remote> <branch>`| fetch the specified branch from the remote, then merge it into the local copy

### Best practices

When using Git and Github, carefully follow the following recommendations:
 - Rename the branch master to main
 - Never work on the main branch, always use a *develop* branch
 - Each commit should have a detailled relevant message that summarize what was done.
 - Create a README.md to present your project and how to install it
 - Always push and commit before you close your computer after a day of work

### Lego Activity 

The steps of our Lego activity are summarized in the file "Git_et_GitHub_branches_et_merge.pdf".



