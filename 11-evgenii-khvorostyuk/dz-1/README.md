# Basic Git commands #
* `git init`
**initializes a new repository**
* `git clone`
**clones an existing repository**
* `git status`
**checks for untracked files, to see what is changed in local repository**
* `git checkout -b branchName`
**creates new branch from current branch and checkouts to it**
* `git checkout branchName`
**checkouts to the specified branch**
* `git branch -d branchName`
**deletes the specified branch**
* `git add`
**stages files in local repository**
* `git add *`
**stages all files in local repository**  
* `git add .`
**stages all files in local repository (current directory)**
* `git commit -m "commitName"`
**creates commit (-m allowes to write the commitName in terminal without openning vim)**
* `git push origin branchName`
**uploads local specified branch into remote repository**
* `git merge branchName`
**merges specified branch into current one**
* `git fetch`
**fetches information about all branches in remote repository**
* `git pull`
**fetches data from remote branch into current one**