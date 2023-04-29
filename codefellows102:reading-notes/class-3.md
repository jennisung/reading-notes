# Reading Notes

# Intro to Git

## What is Version Control?

**Version Control System (VCS)** is a tool that allows you to track any changes you have made to a file(s) by recording these changes. With Version Control, you can revert back to a previous version of a file/project. In addtion, it allows you to keep track of any of the modifications that you've made, who's making the changes, and compare the changes. By utilizing a Version Control System(VCS), it is easy to correct any mistakes.

## What is cloning in Git?

If you'd want to make a copy of a Git repository from a specific server, you may use the clone command. plus the repository's URL to do so.

For example:

> $ git clone https://github.com/test

Whenever you clone a file, you get copies of all versions of all files linked with the project. The resulting command is the creation of a directory called "test", which has the initialized .git directory. This directory contains all the duplicate versions of all the files for the selected project. The command will then checks out the newest version of the project, making it possible to edit.

## The command to check file status

Use the following command to check file status

> $ git status

## What is the command to track and stage files?

Track a single file:

> $ git add filename

Track ALL filles:

> $ git add \*

_Note: By using these commands, the files are then tracked and staged in order to be committed._

## What is the command to take a snapshot of your changed files?

The following command commits a snapshot of any changes made to a file(s)

> $ git commit -a

## What is the command to send your changed files to Github?

To push changes to gitHub

> $ git push origin master
