# Git exercise Project

<<<<<<< HEAD
## Bundle 1 

### Exercise 1 & 2

```bash 
=======
## Bundle 1

### Exercise 1 and 2

```bash
>>>>>>> dev
 
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
<<<<<<< HEAD
=======

>>>>>>> dev
```

## Bundle 2

<<<<<<< HEAD
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


=======
### Exercise 1


 
>>>>>>> dev
