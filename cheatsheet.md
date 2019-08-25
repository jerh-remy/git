# Cheatsheet for commonly used git commands

*touch* **(file name)**

* This is used to create a file with the given file name in the current working directory

*git init* **(project name)**

* Creates a new local repository with the specified name.

*git clone* **(repository url)**

* Downloads a project and its entire version history

*git add* **(file name)**

* Prepares a file to be committed by adding it to the local staging area.

*git status*

* Gives the list of  all new or modified files to be committed.

*git diff*

* Shows the differences in files that are not yet staged.

*git commit -m **"a descriptive message"***

* This makes the staged files available to be pushed.

*git branch*

* This lists all local branches in the current repository.

*git branch **(branch name)***

* This is used to create a new branch.

*git checkout **(branch name)***

* This is used to switch to the specified branch and update the working directory.

*git merge **(branch name)***

* This merges the specified branch to master.

*git branch -d **(branch-name)***

* This deletes the specified branch.

*git push -u origin master*

* This pushes all local branch commits to the online repository.

*git pull*

* This is used to download content from remote repository and incorporate those changes in the local repository.

*git rm --cached **(file name)***

* This removes the file from version control but preserves the file locally

*git config --global user.name "(**user name**)"*

* Used to set the username you want attached to commits

*git config --global user.email "(**email address**)"*

* Used to set the email you want attached to commits.
