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
BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ mkdir kk

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir (master)
$ cd kk

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir/kk (master)
$ git init
Initialized empty Git repository in D:/vir/kk/.git/

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir/kk (master)
$ nano k.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir/kk (master)
$ git add k.c
warning: in the working copy of 'k.c', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir/kk (master)
$ git commit -m "1"
[master (root-commit) a3a04fd] 1
 1 file changed, 1 insertion(+)
 create mode 100644 k.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir/kk (master)
$ git log
commit a3a04fd5306d5989d9645ff8cc8bf920f038e79d (HEAD -> master)
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:25:39 2024 +0530

    1

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/vir/kk (master)
$ git revert a3a04fd5306d5989d9645ff8cc8bf920f038e79d
hint: Waiting for your editor to close the file...       0 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                                                                                                                658622 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                               1161932 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                                                                                                                           1237081 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                                           1289844 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                                                                                                                                       1293877 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                                                       1297649 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                                                       1349482 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                                                       1398036 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
       1445522 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                                                                   1449743 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                                                                   1494382 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                   1539872 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                                                                               1589599 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                               1593554 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                               1632765 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                                                                                           1681268 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                           1685488 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                                                                                                       1728058 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                       1774783 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                                                                                                                   1850137 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                                   15539511 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                                                                                                                                15759784 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
                                                                                 16087113 [sig] bash 346! sigpacket::process: Suppressing signal 18 to win32 process (pid 368)
[master 2462992] Revert "1"
 1 file changed, 1 deletion(-)
 delete mode 100644 k.c

