GIT_COMMONDS:


git:
 
 # git clone https://bitbucket.pearson.com/scm/kx/mypedia3.git
 # C:\mypedia>git branch
 # C:\mypedia>cd mypedia3
 C:\mypedia\mypedia3>git branch
 C:\mypedia\mypedia3>git checkout release/0.0.10
 C:\mypedia\mypedia3>git branch
 C:\mypedia\mypedia3>git checkout feature/dileep-mark-entry
 C:\mypedia\mypedia3>git pull --rebase origin release/0.0.10
 C:\mypedia\mypedia3>start.
 C:\mypedia\mypedia3>git status
 
 committing: 
 C:\mypedia\mypedia3>git add -u
 C:\mypedia\mypedia3>git status
 C:\mypedia\mypedia3>git commit -m "Decimal Places added for handling roundoff in grade" *
 C:\mypedia\mypedia3>git push
 
 
 Reset:
  $ git reset --hard HEAD~1
 
==>Git Commit process:
Microsoft Windows [Version 10.0.17134.1006]
(c) 2018 Microsoft Corporation. All rights reserved.

C:\Users\Dileep>git
usage: git [--version] [--help] [-C <path>] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.

C:\Users\Dileep>cd\

C:\>mkdir mypedia

C:\>cd mypedia

C:\mypedia>git clone https://bitbucket.pearson.com/scm/kx/mypedia3.git
Cloning into 'mypedia3'...
remote: Enumerating objects: 37971, done.
remote: Counting objects: 100% (37971/37971), done.
remote: Compressing objects: 100% (12327/12327), done.
remote: Total 37971 (delta 19644), reused 35980 (delta 18160) eceiving objects:  99% (37968/37971), 7.86 MiB | 481.00 KiReceiving objects: 100% (37971/37971), 7.86 MiB | 423.00 KiB/s, done.

Resolving deltas: 100% (19644/19644), done.
Checking connectivity... done.

C:\mypedia>git branch
fatal: Not a git repository (or any of the parent directories): .git

C:\mypedia>cd mypedia3

C:\mypedia\mypedia3>git branch
* master

C:\mypedia\mypedia3>git checkout release/0.0.10
Checking out files: 100% (1350/1350), done.
Branch release/0.0.10 set up to track remote branch release/0.0.10 from origin.
Switched to a new branch 'release/0.0.10'

C:\mypedia\mypedia3>git branch
  master
* release/0.0.10

C:\mypedia\mypedia3>git checkout feature/dileep-mark-entry

Branch feature/dileep-mark-entry set up to track remote branch feature/dileep-mark-entry from origin.
Switched to a new branch 'feature/dileep-mark-entry'
-- feature/formulaBuilderExceptionHandling

C:\mypedia\mypedia3>git pull --rebase origin release/0.0.10
From https://bitbucket.pearson.com/scm/kx/mypedia3
 * branch            release/0.0.10 -> FETCH_HEAD
First, rewinding head to replay your work on top of it...
Fast-forwarded feature/dileep-mark-entry to 0ead6ee648e37ff9a7aa1d197a0bb816c48f10a8.

C:\mypedia\mypedia3>start.

C:\mypedia\mypedia3>git status
On branch feature/dileep-mark-entry
Your branch is ahead of 'origin/feature/dileep-mark-entry' by 12 commits.
  (use "git push" to publish your local commits)
nothing to commit, working directory clean

C:\mypedia\mypedia3>git status
On branch feature/dileep-mark-entry
Your branch is ahead of 'origin/feature/dileep-mark-entry' by 12 commits.
  (use "git push" to publish your local commits)
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   backend-api/src/main/java/com/pearson/mypedia/entity/LineItemConfig.java

no changes added to commit (use "git add" and/or "git commit -a")

C:\mypedia\mypedia3>git add -u

C:\mypedia\mypedia3>git status
On branch feature/dileep-mark-entry
Your branch is ahead of 'origin/feature/dileep-mark-entry' by 12 commits.
  (use "git push" to publish your local commits)
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   backend-api/src/main/java/com/pearson/mypedia/entity/LineItemConfig.java


C:\mypedia\mypedia3>git commit -m "Decimal Places added for handling roundoff in grade" *
[feature/dileep-mark-entry 9c57edf] Decimal Places added for handling roundoff in grade
 1 file changed, 4 insertions(+), 3 deletions(-)

C:\mypedia\mypedia3>git push
Counting objects: 11, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (8/8), done.
Writing objects: 100% (11/11), 847 bytes | 0 bytes/s, done.
Total 11 (delta 5), reused 0 (delta 0)
remote:
remote: Create pull request for feature/dileep-mark-entry:
remote:   https://bitbucket.pearson.com/projects/KX/repos/mypedia3/pull-requests?create&sourceBranch=refs/heads/feature/dileep-mark-entry
remote:
To https://bitbucket.pearson.com/scm/kx/mypedia3.git
   92a00d7..9c57edf  feature/dileep-mark-entry -> feature/dileep-mark-entry

C:\mypedia\mypedia3>




==========================Dileep========================

Clone the Git into specific folder JavaCodes, open git bash into javacodes folder and clone here
# Git clone url

# copy your code and paste it into clone folder 'JavaCodes'
# git clone https://github.com/dileepnaduvinamani/Spring_Boot_Mainstream.git
# git status
# git add *
# git commit -m "comment msg"
# git push
