# answer1
git version 2.31.1.windows.1

# answer2
diff.astextplain.textconv=astextplain    
filter.lfs.clean=git-lfs clean -- %f     
filter.lfs.smudge=git-lfs smudge -- %f   
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Pramita
user.email=pt670520@ohio.edu
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
:


# answer3
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone             Clone a repository into a new directory
   init              Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add               Add file contents to the index
   mv                Move or rename a file, a directory, or a symlink
   restore           Restore working tree files
   rm                Remove files from the working tree and from the index
   sparse-checkout   Initialize and modify the sparse-checkout

examine the history and state (see also: git help revisions)
   bisect            Use binary search to find the commit that introduced a bug
   diff              Show changes between commits, commit and working tree, etc
   grep              Print lines matching a pattern
   log               Show commit logs
   show              Show various types of objects
   status            Show the working tree status

grow, mark and tweak your common history
   branch            List, create, or delete branches
   commit            Record changes to the repository
   merge             Join two or more development histories together
   rebase            Reapply commits on top of another base tip
   reset             Reset current HEAD to the specified state
   switch            Switch branches
   tag               Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch             Download objects and refs from another repository
   pull              Fetch from and integrate with another repository or a local branch
   push              Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
    
#  answer4
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md
  
#  answer5
  On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md


# answer6
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

 # answer7
    [master (root-commit) 12771e6] Initial commit
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
 create mode 100644 answers.md 


  # answer8
 commit 12771e6c3d7c2bb03e38228669ee1971ae464f17 (HEAD -> master)
Author: Pramita <pt670520@ohio.edu>
Date:   Tue May 11 18:26:23 2021 -0400

# answer9
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean


 # answer10
There was no changes seen in local file.
On branch main Your branch is up to date with 'origin/main'
nothing to commimit, working tree clean
 
 # answer11 
 To https://github.com/pt670520/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/pt670520/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
 
 # answer12
 We can see changes made in local file.
 remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 726 bytes | 38.00 KiB/s, done.
From https://github.com/pt670520/git-lab
   18c1cd1..7b89cc5  main       -> origin/main
Updating 18c1cd1..7b89cc5
Fast-forward
 README.md | 4 +++-
 1 file changed, 3 insertions(+), 1 deletion(-)
 remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 726 bytes | 38.00 KiB/s, done.
From https://github.com/pt670520/git-lab
   18c1cd1..7b89cc5  main       -> origin/main
Updating 18c1cd1..7b89cc5
Fast-forward
 README.md | 4 +++-
 1 file changed, 3 insertions(+), 1 deletion(-)
 we can see changes.
 remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 726 bytes | 38.00 KiB/s, done.
From https://github.com/pt670520/git-lab
   18c1cd1..7b89cc5  main       -> origin/main
Updating 18c1cd1..7b89cc5
Fast-forward
 README.md | 4 +++-
 1 file changed, 3 insertions(+), 1 deletion(-)

# answer13
    Directory: C:\Users\pramisha\OneDrive\Desktop\New Folder\CS2400\git-lab_2


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         5/13/2021   5:56 PM            302 .gitignore
-a----         5/13/2021   5:56 PM             11 README.md




