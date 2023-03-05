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


MAKE CHANGES


$git log - lists version history of the current branch
$ git diff [first-branch] [second-branch] - shows content difference between two branches
$ git show [commit] - outputs metadat and content changes of the specified commit.
$ git add [file] - snapshots the file in preparation for versioning
$ gitcommit -m ["descriptive message"] - Records file snapshots permanently in version history


REDO COMMITS
Erase mistakes craft replacement history

$ git reset [commit] - Undoesall commits after [commit], preserving changes locally
git reset --hard [commit] - Discards all history and hanges back to the specified commit

GLOSSARY
git: an open source, distributed version-control system.
GitHub: a platform for hosting and collaborting on Git repositories.
commit: a Git object, a snpshot of your entire repository compressed into a SHA
branch : a lightweight movable pointer to a commit
clone: a local version of a repository, including all commits and branches.
remote: a common repository on GitHub that all team members use to exchange their changes.
fork: a copy of a repository on GitHub owned by a different user
pull request: a place to compare and discuss the differences introduced on a branch with reviews, comments, integrated tests, and more
HEAD: representing your current working directory, the HEAD pointer can be moved to different branches, tags, or commits
when using 'git checkout'
