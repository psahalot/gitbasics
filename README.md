gitbasics
=========

Basic Git commands to help you get started with git.

NOTE : This commands are meant for learning purpose.


// Initialize git repository in directory
git init

// check repo status
git status

// add all files to git repo
git add .

// to add a particular file use following command
git add filename.extension
e.g. git add frontpage.php

// commit changes to repo
git commit -a -m "first commit"

-m : is used for commit message. Mandatory for each commit

// add remote repo
git remote origin https://github.com/username/reponame.git

// push to remote repo
git push origin master
