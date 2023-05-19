* Answer 1
git --version
git version 2.40.1

* Answer 2
credential.helper=osxkeychain
user.name=md864519
user.email=md864519@ohio.edu
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true
remote.origin.url=https://github.com/md864519/git-lab.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.main.remote=origin
branch.main.merge=refs/heads/main

* Answer 3
GIT-ADD(1)                        Git Manual                        GIT-ADD(1)

NAME
       git-add - Add file contents to the index

SYNOPSIS
       git add [--verbose | -v] [--dry-run | -n] [--force | -f] [--interactive |
 -i] [--patch | -p]
                 [--edit | -e] [--[no-]all | --[no-]ignore-removal | [--update |
 -u]] [--sparse]
                 [--intent-to-add | -N] [--refresh] [--ignore-errors] [--ignore-
missing] [--renormalize]
                 [--chmod=(+|-)x] [--pathspec-from-file=<file> [--pathspec-file-
nul]]
                 [--] [<pathspec>...]

DESCRIPTION
       This command updates the index using the current content found in the
       working tree, to prepare the content staged for the next commit. It
       typically adds the current content of existing paths as a whole, but
       with some options it can also be used to add content with only part of
       the changes made to the working tree files applied, or remove paths
       that do not exist in the working tree anymore.

* Answer 4
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md
    answers.md

nothing added to commit but untracked files present (use "git add" to track)
michealdebrosse@Micheals-MBP-2 git-lab %

* Answer 5
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	answers.md

nothing added to commit but untracked files present (use "git add" to track)
michealdebrosse@Micheals-MBP-2 git-lab %

* Answer 6 
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   answers.md

* Answer 7
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

* Answer 8
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
michealdebrosse@Micheals-MBP-2 git-lab % git log 
commit f6548c60a11d646d29311d662ebd93b840e6c5ca (HEAD -> main)
Author: Michael DeBrosse <md864519@ohio.edu>
Date:   Fri May 19 16:48:24 2023 -0400

    Initial commit

commit 22d47291d147d43306b4360a56cc355cec1d3589 (origin/main)
Author: Michael DeBrosse <md864519@ohio.edu>
Date:   Fri May 19 15:41:22 2023 -0400

* Answer 9
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

* Answer 10
Michael DeBrosse - CS 2400, Section 100

* Answer 11
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/md864519/git-lab.git'

* Answer 12
The online copy and local copy match

* Answer 13 
.		..		.git		.gitignore	README.md



