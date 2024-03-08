# 🖥️ GIT COMMANDS CHEAT SHEET

## Set configuration values for your username and email 
* `git config --global user.name` _YOUR NAME_
* `git config --global user.email` _YOUR EMAIL_

## Set default branch to main
* `git config --global init.default branch main`

## Get help on a command
* `git help` _COMMAND_
* `git` _COMMAND_ `-h`

## Initialize a new git repository
* `git init`

## Clone a repository
* `git clone` _REPOSITORY URL_

## Add a file to the staging area
* `git add "`_FILE_`"`

## Add all file changes to the staging area`
* `git add --all`
* `git add -A`
* `git add .`

## Check the unstaged changes
* `git diff`

## Commit the staged changes
* `git commit -m "`_MESSAGE_`"`

## Reset staging area to the last commit
* `git reset`

## Check the state of the working directory and the staging area
* `git status`

## Remove a file from the index and working directory
* `git rm` _FILENAME_

## Rename a file
* `git mv` _(OLD NAME) (NEW NAME)_

## List the commit history
* `git log`

## List all the local branches
* `git branch`

## Create a new branch
* `git branch` _BRANCH NAME_

## Rename the current branch
* `git branch -m` _NEW BRANCH NAME_

## Delete a branch
* `git branch -d` _BRANCH NAME_

## Switch to another branch
* `git switch` _BRANCH NAME_

## Merge specified branch into the current branch
* `git merge` _BRANCH NAME_

## Create a connection to a remote repository
* `git remote add` _(NAME) (REPOSITORY URL)_

## Push the committed changes to a remote directory
* `git push` _(REMOTE) (BRANCH)_

## Download the content from a remote repository
* `git pull` _REMOTE_