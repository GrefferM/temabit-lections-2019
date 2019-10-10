git init - initializes a new repository with readme.md and .git files;
git status - check for untracked files, to see what is changed in local repository;
git fetch - dowload commits, files, and refs from remote repository to local repository;
git checkout _branch name_ - create new branch from current branch;
git checkout -b _branch name_ - create new branch from current branch and checkout to it;
git branch -d _branch name_ - delete branch;
git add . - stages all files in local repository
git commit -m "commit message here" - create a commit with a message about the commit
git pull - downloads all branches into local repo
git push origin _branch name_ - uploads local _branch name_ branch into remote repository
git merge _branch name_ - merges _branch name_ into current branch
git merge --abort - reset merging
git cherry-pick abcdabcd - copies commits
git stash - cuts changes to stash in order to paste stash back or to another branch
git stash list - shows stashes list
git stash apply stash@{2} - apply stash
git stash drop - apply stash and delete it
git tag -a v0.0.1 -m 'text here' abcabcabc - create tag (with version for example)
git push origin v0.0.1 - push tag
git push origin --tags - push all tags
git show v0.0.1 - show tag
git tag -d v0.0.1 - delete tag
