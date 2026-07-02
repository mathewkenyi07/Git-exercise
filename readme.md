# Git exercise Project

## Bundle 1 

### Exercise 1 & 2

```bash 
 
MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git log
commit ea4df4618c8a1700242a2b4944311033b5c9b0a5 (HEAD -> dev, exercise1/dev)
Author: matt <mathewkenyi47@gmail.com>
Date:   Wed Jun 10 12:42:38 2026 +0200

    using git reset

commit dd2dc462aea5357404cff095024d9b9bf1be9b04
Author: matt <mathewkenyi47@gmail.com>
Date:   Wed Jun 10 12:11:03 2026 +0200

    updated the markdown

commit fa69d0801f4a508882e50b4d381b1582afd3160d (exercise1/main, main)
Author: matt <mathewkenyi47@gmail.com>
Date:   Wed Jun 10 10:26:58 2026 +0200

    initial commit
:
commit ea4df4618c8a1700242a2b4944311033b5c9b0a5 (HEAD -> dev, exercise1/dev)
Author: matt <mathewkenyi47@gmail.com>
Date:   Wed Jun 10 12:42:38 2026 +0200

    using git reset

commit dd2dc462aea5357404cff095024d9b9bf1be9b04
Author: matt <mathewkenyi47@gmail.com>
Date:   Wed Jun 10 12:11:03 2026 +0200

    updated the markdown

commit fa69d0801f4a508882e50b4d381b1582afd3160d (exercise1/main, main)
Author: matt <mathewkenyi47@gmail.com>
Date:   Wed Jun 10 10:26:58 2026 +0200

    initial commit
:
commit ea4df4618c8a1700242a2b4944311033b5c9b0a5 (HEAD -> dev, exercise1/dev)
Author: matt <mathewkenyi47@gmail.com>
Date:   Wed Jun 10 12:42:38 2026 +0200

    using git reset

commit dd2dc462aea5357404cff095024d9b9bf1be9b04
Author: matt <mathewkenyi47@gmail.com>
Date:   Wed Jun 10 12:11:03 2026 +0200

    updated the markdown

commit fa69d0801f4a508882e50b4d381b1582afd3160d (exercise1/main, main)
Author: matt <mathewkenyi47@gmail.com>
Date:   Wed Jun 10 10:26:58 2026 +0200

    initial commit
:
commit ea4df4618c8a1700242a2b4944311033b5c9b0a5 (HEAD -> dev, exercise1/dev)
Author: matt <mathewkenyi47@gmail.com>
Date:   Wed Jun 10 12:42:38 2026 +0200

    using git reset

commit dd2dc462aea5357404cff095024d9b9bf1be9b04
Author: matt <mathewkenyi47@gmail.com>
Date:   Wed Jun 10 12:11:03 2026 +0200

    updated the markdown

commit fa69d0801f4a508882e50b4d381b1582afd3160d (exercise1/main, main)
Author: matt <mathewkenyi47@gmail.com>
Date:   Wed Jun 10 10:26:58 2026 +0200

    initial commit

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git log --oneline
ea4df46 (HEAD -> dev, exercise1/dev) using git reset
dd2dc46 updated the markdown
fa69d08 (exercise1/main, main) initial commit

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ 
```

## Bundle 2

### Exercise 1 

```bash
MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git status
On branch ft/bundle-2
nothing to commit, working tree clean

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git status
On branch ft/bundle-2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        service.html

nothing added to commit but untracked files present (use "git add" to track)

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git add service.html

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git status
On branch ft/bundle-2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   service.html


MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git commit -m "create service page"
[ft/bundle-2 dc99673] create service page
 1 file changed, 12 insertions(+)
 create mode 100644 service.html

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git status
On branch ft/bundle-2
nothing to commit, working tree clean

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git push
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream exercise1 ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git push --set-upstream origin ft/bundle-2
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git push --set-upstream exercise1 ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 448 bytes | 448.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/mathewkenyi07/Git-exercise/pull/new/ft/bundle-2
remote: 
To https://github.com/mathewkenyi07/Git-exercise.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'exercise1/ft/bundle-2'.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ 
```
### Exercise 2

```bash 
MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (main)
$ git pull
Already up to date.

$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/service-redesign)
$ git status
On branch ft/service-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        service.html

no changes added to commit (use "git add" and/or "git commit -a")

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/service-redesign)
$ git add .

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/service-redesign)
$ git status
On branch ft/service-redesign
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   readme.md
        new file:   service.html


MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/service-redesign)
$ git commit -m " added service list"
[ft/service-redesign 0c221c7]  added service list
 2 files changed, 197 insertions(+), 1 deletion(-)
 create mode 100644 service.html

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/service-redesign)
$ git push 
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream exercise1 ft/service-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/service-redesign)
$ git push --set-upstream exercise1 ft/service-redesign
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.72 KiB | 881.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/mathewkenyi07/Git-exercise/pull/new/ft/service-redesign
remote: 
To https://github.com/mathewkenyi07/Git-exercise.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'exercise1/ft/service-redesign'.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'exercise1/main'.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (main)
$ git checkout dev
Switched to branch 'dev'
Your branch is up to date with 'exercise1/dev'.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git checkout ft/service-redesign
error: The following untracked working tree files would be overwritten by checkout:
        service.html
Please move or remove them before you switch branches.
Aborting

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git add service.html

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git status
On branch dev
Your branch is up to date with 'exercise1/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   service.html


MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git checkout ft/service-redesign
error: Your local changes to the following files would be overwritten by checkout:
        service.html
Please commit your changes or stash them before you switch branches.
Aborting

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git commit -m "added service in dev branch"
[dev af2593d] added service in dev branch
 1 file changed, 19 insertions(+)
 create mode 100644 service.html

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git push --set-upstream exercise1 dev
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 487 bytes | 487.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/mathewkenyi07/Git-exercise.git
   036c570..af2593d  dev -> dev
branch 'dev' set up to track 'exercise1/dev'.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'exercise1/ft/service-redesign'.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/service-redesign)
$ git checkout dev
Switched to branch 'dev'
Your branch is up to date with 'exercise1/dev'.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git status
On branch dev
Your branch is up to date with 'exercise1/dev'.

nothing to commit, working tree clean

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'exercise1/ft/service-redesign'.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/service-redesign)
$ git merge dev
Auto-merging readme.md
CONFLICT (content): Merge conflict in readme.md
Auto-merging service.html
CONFLICT (add/add): Merge conflict in service.html
Automatic merge failed; fix conflicts and then commit the result.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/service-redesign|MERGING)
$ git add .

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/service-redesign)
$ git merge dev
Already up to date.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/service-redesign)
$ git commit -m "resolved merge conflicts"
On branch ft/service-redesign
Your branch is ahead of 'exercise1/ft/service-redesign' by 5 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/service-redesign)
$ git status
On branch ft/service-redesign
Your branch is ahead of 'exercise1/ft/service-redesign' by 5 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/service-redesign)
$ git push
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 653 bytes | 653.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/mathewkenyi07/Git-exercise.git
   0c221c7..34e974a  ft/service-redesign -> ft/service-redesign

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/service-redesign)
$ 
```

## Bundle 3

### Exercise 1

```bash
MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git status
On branch ft/bundle-2
nothing to commit, working tree clean

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git status
On branch ft/bundle-2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        service.html

nothing added to commit but untracked files present (use "git add" to track)

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git add service.html

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git status
On branch ft/bundle-2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   service.html


MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git commit -m "create service page"
[ft/bundle-2 dc99673] create service page
 1 file changed, 12 insertions(+)
 create mode 100644 service.html

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git status
On branch ft/bundle-2
nothing to commit, working tree clean

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git push
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream exercise1 ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git push --set-upstream origin ft/bundle-2
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ git push --set-upstream exercise1 ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 448 bytes | 448.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/mathewkenyi07/Git-exercise/pull/new/ft/bundle-2
remote: 
To https://github.com/mathewkenyi07/Git-exercise.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'exercise1/ft/bundle-2'.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/bundle-2)
$ 

```

### Exercise 2

