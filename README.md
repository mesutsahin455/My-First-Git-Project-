# My first Git Repository

This is my very first repository uploaded on git. Here, I will explain Git terminology.

## git init

We use 'git init' command to 'CREATE AN EMPTY GIT REPOSITORY'

## git status

We use 'git status' command to 'DISPLAY THE STATE OF THE REPOSITORY AND STAGING AREA'. It is possible to see the tracked, untracked files and changes.

## git add .

We use 'git add' command to "ADD A CHANGE IN THE WORKING DIRECTORY TO THE STAGING AREA". It tells Git that you want to include updates to a particular file in the next commit. However, 'git add' doesn't really affect the repository in any significant way , changes are not actually recorded until you run 'git commit'.

## git commit -m "write your message about the changes you made"

We use 'git commit -m "your message here" ' command  to 'MOVE FILES FROM THE STAGING AREA TO A COMMIT'. This command is run after 'git add' , which we use to add files to the staging area. 'git commit -m "message" ' comand creates a snapshot of the changes made to a Git repository which can then be pushed to the main repository when the developer is ready to do so.

## git push

We use 'git push' command to "SEND THE RECENT COMMIT HISTORY FROM OUR LOCAL REPOSITORY UP TO GitHub".

## git pull

We use 'git pull' command to " GRAB ANY CHANGES FROM THE GitHub REPOSITORY AND MERGE THEM INTO OUR LOCAL REPOSITORY".

## git stash 

We use 'git stash' command to "TEMPORARILY STASH CHANGES WE HAVE MADE TO OUR WORKING COPY SO WE CAN WORK ON SOMETHING ELSE, AND THEN COME BACK AND RE-APPLY THEM LATER ON" .

## git log

We use 'git log' utility tool to "REVİEW AND READ A HISTORY OF EVERYTHING THAT THAT HAPPENS TO A REPOSITORY" . 'git log' is a record of commits.

## git branch

We use 'git branch' command to "CREATE, LIST, RENAME, AND DELETE BRANCHES" . WARNING! --> It doesn't let you switch between branches or put a forked history back together again. For this reason, git branch is tightly integrated with the git checkout and git merge commands.

## git checkout

We use 'git checkout' command  to "NAVIGATE BETWEEN THE BRANCHES CREATED BY GIT BRANCH". Checking out a branch updates the files in the working directory to match the version stored in that branch, and it tells Git to record all new commits on that branch.

## git merge 

We use 'git merge' command to "MERGE BRANCHES FROM Git" . 'git merge' command takes the contents of a source branch and integrates it with a target branch