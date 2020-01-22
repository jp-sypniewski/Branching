## Branching

### Basic Git Commands
* `git init` - create local repo
* `git add` - add modified files to index (staging)
* `git commit -m "message"` - commit to a local repo
* `git status` - see status of local repo
* `git log` - view commit log
* `git remote add origin URL` - add remote repository

### Basic Branching
* `git branch` - show branches, current branch
* `git branch branchName` - create new branch with `branchName`
* `git checkout branchName` - check out branch `branchName`
* `git checkout -b branchName` - check out and create `branchName`
* `git pull origin branchName` - pull remote branch `branchName`
* `git pull origin master` - pull remote master into local branch to resolve conflicts
