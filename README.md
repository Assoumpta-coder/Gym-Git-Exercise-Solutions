# Gym-Git-Exercise-Solutions
## Bundle1
### Exercise1
```bash

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise
$ git init
Initialized empty Git repository in C:/Users/airah/OneDrive/Desktop/GitExercise/.git/

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (master)
$ git branch -m master main

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git branch -m main master

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (master)
$ git branch -m master main

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config advice.addEmptyPathspec false"        

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git add .

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   index.thml


airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git commit -m "Added new files"
[main (root-commit) 2b3e6bc] Added new files
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
 create mode 100644 index.thml

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git remote add origin https://github.com/Assoumpta-coder/Gym-Git-Exercise-Solutions.git

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git push -u origin main
To https://github.com/Assoumpta-coder/Gym-Git-Exercise-Solutions.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Assoumpta-coder/Gym-Git-Exercise-Solutions.git'
hint: Updates were rejected because the remote contains work that you do not      
hint: have locally. This is usually caused by another repository pushing to       
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.   
hint: See the 'Note about fast-forwards' in 'git push --help' for details.        

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main  

upstream, see 'push.autoSetupRemote' in 'git help config'.
upstream, see 'push.autoSetupRemote' in 'git help config'.


airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ ^C


airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git push --set-upstream origin main
To https://github.com/Assoumpta-coder/Gym-Git-Exercise-Solutions.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/Assoumpta-coder/Gym-Git-Exercise-Solutions.git'
hint: Updates were rejected because the tip of your current branch is behind      
hint: its remote counterpart. If you want to integrate the remote changes,        
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.        

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git pull origin main
From https://github.com/Assoumpta-coder/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
fatal: refusing to merge unrelated histories

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main  

upstream, see 'push.autoSetupRemote' in 'git help config'.


airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ ^C


airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git push --set-upstream origin main
To https://github.com/Assoumpta-coder/Gym-Git-Exercise-Solutions.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/Assoumpta-coder/Gym-Git-Exercise-Solutions.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main


airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main


airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git branch --set-upstream-to=origin/<branch> main
bash: branch: No such file or directory

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git add .

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git commit -m 'Halloooo'
[main 913b405] Halloooo
 2 files changed, 12 insertions(+)
 create mode 100644 index.html
 delete mode 100644 index.thml

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git push --set-upstream origin main
To https://github.com/Assoumpta-coder/Gym-Git-Exercise-Solutions.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/Assoumpta-coder/Gym-Git-Exercise-Solutions.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main


airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git stash
No local changes to save

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main


airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git branch --set-upstream-to=origin/<branch> main
bash: branch: No such file or directory

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git remote add origin https://github.com/Assoumpta-coder/Gym-Git-Exercise-Solutions.git
error: remote origin already exists.

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git branch --all
* main
  remotes/origin/main

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git pull origin main --rebase
From https://github.com/Assoumpta-coder/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
Successfully rebased and updated refs/heads/main.

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (main)
$ git checkout -b dev
Switched to a new branch 'dev'

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git checkout -b test
Switched to a new branch 'test'

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (test)
$ git branch -d test
error: cannot delete branch 'test' used by worktree at 'C:/Users/airah/OneDrive/Desktop/GitExercise'

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (test)
$ git branch -d test
error: cannot delete branch 'test' used by worktree at 'C:/Users/airah/OneDrive/Desktop/GitExercise'

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (test)
$ git branch -D test
error: cannot delete branch 'test' used by worktree at 'C:/Users/airah/OneDrive/Desktop/GitExercise'

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (test)
$ git worktree remove C:/Users/airah/OneDrive/Desktop/GitExercise
fatal: 'C:/Users/airah/OneDrive/Desktop/GitExercise' is a main working tree       

error: cannot delete branch 'test' used by worktree at 'C:/Users/airah/OneDrive/Desktop/GitExercise'
error: cannot delete branch 'test' used by worktree at 'C:/Users/airah/OneDrive/Desktop/GitExercise'

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (test)
$ git worktree list
C:/Users/airah/OneDrive/Desktop/GitExercise  287575a [test]

p/GitExercise (test)
$ git --version
git version 2.47.0.windows.2

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (test)
$ git worktree remove
usage: git worktree remove [-f] <worktree>

    -f, --[no-]force      force removal even if worktree is dirty or locked


airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (test)
$ git worktree remove -f
usage: git worktree remove [-f] <worktree>

    -f, --[no-]force      force removal even if worktree is dirty or locked


airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (test)
$ git rev-parse --show-toplevel
C:/Users/airah/OneDrive/Desktop/GitExercise

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (test)
$ git remove worktree -f C:/Users/airah/OneDrive/Desktop/GitExercise
git: 'remove' is not a git command. See 'git --help'.

The most similar command is
        remote

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (test)
$ git worktree remove -f C:/Users/airah/OneDrive/Desktop/GitExercise
fatal: 'C:/Users/airah/OneDrive/Desktop/GitExercise' is a main working tree

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (test)
$ git checkout dev
Switched to branch 'dev'

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git branch -D test
Deleted branch test (was 287575a).

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git add .

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git commit -m "deleted test branch"
On branch dev
nothing to commit, working tree clean

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git push --set-upstream origin dev
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 743 bytes | 123.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/Assoumpta-coder/Gym-Git-Exercise-Solutions/pull/new/dev
remote:
To https://github.com/Assoumpta-coder/Gym-Git-Exercise-Solutions.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
```

### Exercise2

```bash
airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ touch home.html

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git add home.html 

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git stash push -m "home page added to staging area"
Saved working directory and index state On dev: home page added to staging area   

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ touch about.html

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git add about.html 

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git stash push -m "added about to stagi
ng area, ready for next commit"
Saved working directory and index state On dev: added about to staging area, ready for next commit

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ touch team.html

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git add team.html 

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git stash push -m "added team to staging area too"
Saved working directory and index state On dev: added team to staging area too    

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git stash list
stash@{0}: On dev: added team to staging area too
stash@{1}: On dev: added about to staging area, ready for next commit
stash@{2}: On dev: home page added to staging area
:
stash@{0}: On dev: added team to staging area too
stash@{1}: On dev: added about to staging area, ready for next commit
stash@{2}: On dev: home page added to staging area
:

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
gigit stash pop stash@{1}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (d00c17eb0422e4947d4de2eab6782f7b739b706b)

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git stash list
stash@{0}: On dev: added team to staging area too
stash@{1}: On dev: home page added to staging area

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git stash pop stash@{1}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

Dropped stash@{1} (3468ca746643ddd30187c06d4144a43fde9bf41c)

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git stash list
stash@{0}: On dev: added team to staging area too

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html


airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git add home.html 

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        modified:   home.html


airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git commit -m "restored home and about 
files"
[dev daa77c5] restored home and about files
 2 files changed, 13 insertions(+), 3 deletions(-)
 create mode 100644 about.html

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git push origin dev
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.      
Delta compression using up to 4 threads  
Compressing objects: 100% (4/4), done.   
Writing objects: 100% (4/4), 581 bytes | 290.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Assoumpta-coder/Gym-Git-Exercise-Solutions.git
   ee85343..daa77c5  dev -> dev

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git stash pop stash@{0}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped stash@{0} (a6abed6bc99043e7546c60690bd90d6a538cf58b)
airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git reset

airah@Assoumpta MINGW64 ~/OneDrive/Desktop/GitExercise (dev)
$ git reset --hard
HEAD is now at daa77c5 restored home and about files```