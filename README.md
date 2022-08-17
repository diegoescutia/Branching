## Git and Git Branching Cheat Sheet

some random line

### Basic commands
- git init : initialize current directory with repository
- git add . : adds all new or changed files in current directory to git index, staging them for commit.
- git commit -m "message" : commit staged changes to local repository


### Info commands
- git status :show status of current working directory
- git log :lists commit history
- git log --oneline :list commit history(compact)

### Branch commmands
- git branch :lists local branches, highlights current
- git branch branchName - creates branch called branchName
- git checkout branchName - switch to branch called branchName
- git checkout -b otherBranch - creates a new branch(if it doesnt exists) called otherBranch and simultaneously switches to it.
