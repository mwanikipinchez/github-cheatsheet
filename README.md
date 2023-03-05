# github-cheatsheet
This repository is about basic to advance github cheatsheet

CONFIGURE TOOLING
git config --global user.name "name"
sets the name you want to attach to your commit transactions

git config --global user.email "email"
sets the email you want attached to your commit transaction

git config --global color.ui auto
Enables helpful colorization of command line ouput

CREATE REPOSITORIES
git init - Turn an existing directory into a git repository
git clone - download arepository that already exists om gitHub including all files, commits and branches.


BRANCHES
Branches are an important part of working with Git. Any commits you make you will be made on the branch you are currently "checked out" to.
use git status to see which branch that is.

$ git branch [branch-name] - creates a new branch
$ git checkout [branch-name] - switches to the specified branch and update the working directory
$ git merge [branch] - combines specified branch's history into the current branch
$ git branch -d [branch-name] - Deletes the specified branch

SYNCHRONIZE CHANGES
Synchronize your local repository with the remote repository on GitHub.com

$ git fetch - Downloads all history from the remote tracking branches.
$ git merge - Combines remote tracking branch into current local branch
$ git push - Uploads all local branch commits to GitHub
$git pull - Updates your current local working branch with all new commits from the corresponding remote branch branch on github.
          - '''git pull''' is a combination of '''git fetch ''' and '''git merge'''
