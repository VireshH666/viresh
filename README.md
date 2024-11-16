#lab 9
BLDEA-CSE@DESKTOP-02RM63H MINGW64 ~ (cs1)
$ cd ..

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /c/Users
$ cd ..

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /c
$ cd ..

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /
$ cd d:

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d
$ mkdir vir

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d
$ git init
Reinitialized existing Git repository in D:/.git/

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d
$ cd vir

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir
$ git init
Initialized empty Git repository in D:/vir/.git/

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ nano z.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ git add z.c
warning: in the working copy of 'z.c', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ git commit -m "1"
[master (root-commit) 39a6135] 1
 1 file changed, 1 insertion(+)
 create mode 100644 z.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ nano z.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ git add z.c
warning: in the working copy of 'z.c', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ git commit -m "2"
[master 2306884] 2
 1 file changed, 1 insertion(+)

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ nano z.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ git add z.c
warning: in the working copy of 'z.c', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ git commit -m "2"
[master c00a68b] 2
 1 file changed, 1 insertion(+)

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ nano z.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ git add z.c
warning: in the working copy of 'z.c', LF will be replaced by CRLF the next time Git touches it
BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ git commit -m "2"
[master 18c9a4c] 2
 1 file changed, 1 insertion(+)

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ nano z.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ git add z.c
warning: in the working copy of 'z.c', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ git commit -m "2"
[master 46306a8] 2
 1 file changed, 1 insertion(+)

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ git log
commit 46306a8c8f3f4f9bc802a28be757f471ddcdb927 (HEAD -> master)
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:55:43 2024 +0530

    2

commit 18c9a4cea3de456e81d5f88c4930f6dbb998e318
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:55:30 2024 +0530

    2

commit c00a68bc5f364f299ae35beb5e069ca889352e35
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:55:18 2024 +0530

    2

commit 2306884ce2a54e614fb322e84a6567b98599fcf2
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:54:59 2024 +0530

    2

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$  git log 2306884ce2a54e614fb322e84a6567b98599fcf2
commit 2306884ce2a54e614fb322e84a6567b98599fcf2
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:54:59 2024 +0530

    2

commit 39a6135359e9f1a2aff8385548f4da80ab3225a9
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:54:47 2024 +0530

    1

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$  git show 2306884ce2a54e614fb322e84a6567b98599fcf2
commit 2306884ce2a54e614fb322e84a6567b98599fcf2
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:54:59 2024 +0530

    2

diff --git a/z.c b/z.c
index ce01362..d0e08a8 100644
--- a/z.c
+++ b/z.c
@@ -1 +1,2 @@
 hello
+hi
#lab 11
BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ git log -5
commit 46306a8c8f3f4f9bc802a28be757f471ddcdb927 (HEAD -> master)
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:55:43 2024 +0530

    2

commit 46306a8c8f3f4f9bc802a28be757f471ddcdb927 (HEAD -> master)
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:55:43 2024 +0530

    2

commit 18c9a4cea3de456e81d5f88c4930f6dbb998e318
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:55:30 2024 +0530

    2

commit c00a68bc5f364f299ae35beb5e069ca889352e35
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:55:18 2024 +0530

    2

commit 2306884ce2a54e614fb322e84a6567b98599fcf2
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:54:59 2024 +0530

    2
#lab 12
BLDEA-CSE@DESKTOP-02RM63H MINGW64 ~ (cs1)
$  cd ..

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /c/Users
$  cd ..

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /c
$  cd ..

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /
$  cd d:

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d
$ cd vir

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ git revert 46306a8c8f3f4f9bc802a28be757f471ddcdb927
On branch master
nothing to commit, working tree clean

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ git log
commit ae2b4432d185f248b4f42789b8981d5064c8e341 (HEAD -> master)
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:12:00 2024 +0530

    Revert "2"

    This reverts commit 46306a8c8f3f4f9bc802a28be757f471ddcdb927.

commit 46306a8c8f3f4f9bc802a28be757f471ddcdb927
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:55:43 2024 +0530

    2

commit 18c9a4cea3de456e81d5f88c4930f6dbb998e318
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:55:30 2024 +0530

    2

commit c00a68bc5f364f299ae35beb5e069ca889352e35
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:55:18 2024 +0530

    2

commit 2306884ce2a54e614fb322e84a6567b98599fcf2
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:54:59 2024 +0530

    2

commit 39a6135359e9f1a2aff8385548f4da80ab3225a9
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 09:54:47 2024 +0530

    1

