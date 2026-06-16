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
MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (main)
$ git status
On branch main
Your branch is up to date with 'exercise1/main'.

nothing to commit, working tree clean

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (main)
$ git checkout dev
Switched to branch 'dev'
Your branch is up to date with 'exercise1/dev'.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/team-page)
$ git add team.html

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/team-page)
$ git status
On branch ft/team-page
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   team.html


MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/team-page)
$ git commit -m "feature at team page"
[ft/team-page 90db648] feature at team page
 1 file changed, 1 insertion(+), 1 deletion(-)

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/team-page)
$ git pust --set-upstream exercise1 ft/team-page
git: 'pust' is not a git command. See 'git --help'.

The most similar command is
        push

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/team-page)
$ git push --set-upstream exercise1 ft/team-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 289 bytes | 144.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: 
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/mathewkenyi07/Git-exercise/pull/new/ft/team-page
remote: 
To https://github.com/mathewkenyi07/Git-exercise.git
 * [new branch]      ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'exercise1/ft/team-page'.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/team-page)
$ git checkout dev
Switched to branch 'dev'
Your branch is up to date with 'exercise1/dev'.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git branch
* dev
  ft/bundle-2
  ft/service-redesign
  ft/team-page
  main

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git checkout dev
Already on 'dev'
Your branch is up to date with 'exercise1/dev'.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (dev)
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/contact-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'exercise1/ft/team-page'.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/team-page)
$ git log
commit 90db648afa9016475bb9425016631e538d624faf (HEAD -> ft/team-page, exercise1/ft/team-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:03:20 2026 +0200

    feature at team page

commit af2593dc149b6647b2036e348739985dc2c69d01 (exercise1/dev, ft/contact-page, dev)
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 11:49:33 2026 +0200

    added service in dev branch

commit 036c57034214c680c76677d9d6a7ef1b8868a8a0
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 10:13:29 2026 +0200
:
commit 90db648afa9016475bb9425016631e538d624faf (HEAD -> ft/team-page, exercise1/ft/team-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:03:20 2026 +0200

    feature at team page

commit af2593dc149b6647b2036e348739985dc2c69d01 (exercise1/dev, ft/contact-page, dev)
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 11:49:33 2026 +0200

    added service in dev branch

:
commit 90db648afa9016475bb9425016631e538d624faf (HEAD -> ft/team-page, exercise1/ft/team-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:03:20 2026 +0200

    feature at team page

commit af2593dc149b6647b2036e348739985dc2c69d01 (exercise1/dev, ft/contact-page, dev)
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 11:49:33 2026 +0200

    added service in dev branch

commit 036c57034214c680c76677d9d6a7ef1b8868a8a0
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 10:13:29 2026 +0200
:
commit 90db648afa9016475bb9425016631e538d624faf (HEAD -> ft/team-page, exercise1/ft/team-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:03:20 2026 +0200

    feature at team page

commit af2593dc149b6647b2036e348739985dc2c69d01 (exercise1/dev, ft/contact-page, dev)
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 11:49:33 2026 +0200

    added service in dev branch

:
commit 90db648afa9016475bb9425016631e538d624faf (HEAD -> ft/team-page, exercise1/ft/team-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:03:20 2026 +0200

    feature at team page

commit af2593dc149b6647b2036e348739985dc2c69d01 (exercise1/dev, ft/contact-page, dev)
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 11:49:33 2026 +0200

    added service in dev branch

commit 036c57034214c680c76677d9d6a7ef1b8868a8a0
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 10:13:29 2026 +0200
:
commit 90db648afa9016475bb9425016631e538d624faf (HEAD -> ft/team-page, exercise1/ft/team-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:03:20 2026 +0200

    feature at team page

commit af2593dc149b6647b2036e348739985dc2c69d01 (exercise1/dev, ft/contact-page, dev)
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 11:49:33 2026 +0200

    added service in dev branch

:
commit 90db648afa9016475bb9425016631e538d624faf (HEAD -> ft/team-page, exercise1/ft/team-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:03:20 2026 +0200

    feature at team page

commit af2593dc149b6647b2036e348739985dc2c69d01 (exercise1/dev, ft/contact-page, dev)
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 11:49:33 2026 +0200

    added service in dev branch

commit 036c57034214c680c76677d9d6a7ef1b8868a8a0
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 10:13:29 2026 +0200

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

$ git cherry-pick  90db648afa9016475bb94250166
$ 

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/contact-page)
$ git log
commit af2593dc149b6647b2036e348739985dc2c69d01 (HEAD -> ft/contact-page, exercise1/dev, dev)
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 11:49:33 2026 +0200

    added service in dev branch

commit 036c57034214c680c76677d9d6a7ef1b8868a8a0
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 10:13:29 2026 +0200

    bundle one done

commit ea4df4618c8a1700242a2b4944311033b5c9b0a5
Author: matt <mathewkenyi47@gmail.com>
Date:   Wed Jun 10 12:42:38 2026 +0200

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/contact-page)
$ git status
On branch ft/contact-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        contact.html

nothing added to commit but untracked files present (use "git add" to track)

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/contact-page)
$ git add .

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/contact-page)
$ git commit -m "feat: add contact page"
[ft/contact-page aa80736] feat: add contact page
 1 file changed, 12 insertions(+)
 create mode 100644 contact.html

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/contact-page)
$ git push
fatal: The current branch ft/contact-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream exercise1 ft/contact-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/contact-page)
$  git push --set-upstream exercise1 ft/contact-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 445 bytes | 74.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/mathewkenyi07/Git-exercise/pull/new/ft/contact-page
remote: 
To https://github.com/mathewkenyi07/Git-exercise.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'exercise1/ft/contact-page'.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/contact-page)
$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/faq-page)
$ git add .

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/faq-page)
$ git commit -m "feat: faq page"
[ft/faq-page 9d6d380] feat: faq page
 1 file changed, 12 insertions(+)
 create mode 100644 faq.html

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/faq-page)
$ git push
fatal: The current branch ft/faq-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream exercise1 ft/faq-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/faq-page)
$  git push --set-upstream exercise1 ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 432 bytes | 432.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/mathewkenyi07/Git-exercise/pull/new/ft/faq-page
remote: 
To https://github.com/mathewkenyi07/Git-exercise.git
 * [new branch]      ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'exercise1/ft/faq-page'.

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/faq-page)
$ git log
commit 9d6d38017b1a621aa3d2fee9e19d179a23e02606 (HEAD -> ft/faq-page, exercise1/ft/faq-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:50:29 2026 +0200

    feat: faq page

commit aa80736be78380cc90e0a77e58fdd97e228e0538 (exercise1/ft/contact-page, ft/contact-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:46:15 2026 +0200

    feat: add contact page

commit af2593dc149b6647b2036e348739985dc2c69d0:
commit 9d6d38017b1a621aa3d2fee9e19d179a23e02606 (HEAD -> ft/faq-page, exercise1/ft/faq-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:50:29 2026 +0200

    feat: faq page

commit aa80736be78380cc90e0a77e58fdd97e228e0538 (exercise1/ft/contact-page, ft/contact-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:46:15 2026 +0200

    feat: add contact page

commit af2593dc149b6647b2036e348739985dc2c69d01 (exercise1/dev, dev)
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 11:49:33 2026 +0200
:
commit 9d6d38017b1a621aa3d2fee9e19d179a23e02606 (HEAD -> ft/faq-page, exercise1/ft/faq-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:50:29 2026 +0200

    feat: faq page

commit aa80736be78380cc90e0a77e58fdd97e228e0538 (exercise1/ft/contact-page, ft/contact-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:46:15 2026 +0200

    feat: add contact page

commit af2593dc149b6647b2036e348739985dc2c69d01 (exercise1/dev, dev)
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 11:49:33 2026 +0200
:
commit 9d6d38017b1a621aa3d2fee9e19d179a23e02606 (HEAD -> ft/faq-page, exercise1/ft/faq-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:50:29 2026 +0200

    feat: faq page

commit aa80736be78380cc90e0a77e58fdd97e228e0538 (exercise1/ft/contact-page, ft/contact-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:46:15 2026 +0200

    feat: add contact page

commit af2593dc149b6647b2036e348739985dc2c69d0:
commit 9d6d38017b1a621aa3d2fee9e19d179a23e02606 (HEAD -> ft/faq-page, exercise1/ft/faq-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:50:29 2026 +0200

    feat: faq page

commit aa80736be78380cc90e0a77e58fdd97e228e0538 (exercise1/ft/contact-page, ft/contact-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:46:15 2026 +0200

    feat: add contact page

commit af2593dc149b6647b2036e348739985dc2c69d01 (exercise1/dev, dev)
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 11:49:33 2026 +0200
:
commit 9d6d38017b1a621aa3d2fee9e19d179a23e02606 (HEAD -> ft/faq-page, exercise1/ft/faq-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:50:29 2026 +0200

    feat: faq page

commit aa80736be78380cc90e0a77e58fdd97e228e0538 (exercise1/ft/contact-page, ft/contact-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:46:15 2026 +0200

    feat: add contact page

commit af2593dc149b6647b2036e348739985dc2c69d01 (exercise1/dev, dev)
Author: matt <mathewkenyi47@gmail.com>
Date:   Mon Jun 15 11:49:33 2026 +0200
:
commit 9d6d38017b1a621aa3d2fee9e19d179a23e02606 (HEAD -> ft/faq-page, exercise1/ft/faq-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:50:29 2026 +0200

    feat: faq page

commit aa80736be78380cc90e0a77e58fdd97e228e0538 (exercise1/ft/contact-page, ft/contact-page)
Author: matt <mathewkenyi47@gmail.com>
Date:   Tue Jun 16 10:46:15 2026 +0200

    feat: add contact page

commit af2593dc149b6647b2036e348739985dc2c69d0

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/faq-page)
$ git revert af2593dc149b6647b2036e348739985dc2c69d01
hint: Waiting for your editor to close the file... 
[ft/faq-page 9c7101f] Revert "added service in dev branch"
 1 file changed, 19 deletions(-)
 delete mode 100644 service.html

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/faq-page)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 281 bytes | 281.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/mathewkenyi07/Git-exercise.git
   9d6d380..9c7101f  ft/faq-page -> ft/faq-page

MATHEW@Matt MINGW64 ~/Desktop/Bundle1 Exercise1 (ft/faq-page)
$ 
```

### Exercise 2


























