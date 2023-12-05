# Git Cheatsheet

## Basic Git Commands
|Command|uses|
|:---------|:------ |
|`git init`| Initializes a new Git repository in the current directory.|
|`git clone <repo_url>`| Creates a copy of a remote repository on your local machine.|
|`git add <file>`| Stages a file for the next commit.|
|`git status`| Shows the status of your working directory, including untracked and modified files.
| `git commit -m "Message"`| Commits the staged changes with a descriptive message.
|`git log`| Displays a log of all commits in the current branch.- |`git diff`| Shows the differences between the working directory and the last commit.

## Branching and Merging

|Command|uses|
|:---------|:------|
| `git branch <branch_name>`| Creates a new branch.|
| `git branch`| Lists all the branches in the repository.|
| `git branch -d <branch_name>`| Delete branch.|
| `git checkout <branch_name>`| Switches to the specified branch.|
| `git checkout -b <branch_name>`| Create and switch to a new branch.|
| `git switch <branch_name>`| Switches to the specified branch more user-friendly than *git checkout*|
| `git merge <branch_name>`| Merges changes from the specified branch into the current branch.|
| `git pull`| Fetches changes from a remote repository and merges them into the current branch.|
| `git push`| Pushes your local commits to a remote repository.|

## Remote Repositories
|Command|uses|
|:---------|:------|
| `git remote -v`| Lists all remote repositories associated with your local repository.|
| `git remote add <name> <repository_url>`| Adds a remote repository.|
| `git fetch <remote_name>`| Fetches changes from a specific remote repository.|
| `git push <remote_name> <branch_name>`| Pushes a branch to a specific remote repository.|

<!--## Undoing Changes

- `git reset <file>`| Unstages a file.
- `git reset --hard <commit_hash>`| Resets the repository to a specific commit, discarding all changes after that commit.
- `git revert <commit_hash>`| Creates a new commit that undoes the changes made in a specific commit.-->

## Stashing
|Command|uses|
|:---------|:------|
| `git stash`| Temporarily saves changes that are not ready to be committed.|
| `git stash apply`| Applies the latest stash to the working directory.|
| `git stash list`| Lists all stashes.|
| `git stash pop`| Applies and removes the latest stash.|

## Tags

|Command|uses|
|:---------|:------|
| `git tag`| Lists all tags in the repository.
| `git tag -a <tag_name> -m "Tag message"`| Creates an annotated tag.|
| `git push --tags`| Pushes tags to a remote repository.|

## Git Configuration
|Command|uses|
|:---------|:------|
| `git config --global user.name "Your Name"`| Sets your username for Git|
| `git config --global user.email "your@email.com"`| Sets your email address for Git|

*[for More command click here](https|//ndpsoftware.com/git-cheatsheet.html#loc=index;)*