# My guide to help me remember how to use Git and GitHub.

## COMMANDS:
`touch [new filename]`

`git init`

`git add [file name]`

`git add .`

`git status`

`git rm --cached [file name]`

`git commit --m [message]`

`git remote add origin [repo url]`

`git push -u origin master`

## INSTRUCTIONS:

To start, make a directory. Then, right click and open Git Bash in the directory.

From here, type `git init`.

To create a file, type `touch [file name]`.

Then, type `git add [file name]`. Alternatively, you can do `git add .` to add all files and directories.
This starts tracking the file.

To check the status of the staging area, type `git status`. This is a dashboard that gives you an overview of your git directory.

To remove files from this staging area, use `git rm --cached [file name]`.
This stops tracking the file.

To lock your changes, type `git commit --m [message]`.
This commits the changes.

## REMOTE REPOSITORY

Go to GitHub.com and initialize a repository, configure it.

Instructions will appear on the screen. Follow them OR follow below.

Type `git remote add origin [repository url]`.

To send your files, type `git push -u origin master`.

This only needs to be done once. Afterwards, you can simply type `git push`.