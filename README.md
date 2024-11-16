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

#lab 8
BLDEA-CSE@DESKTOP-02RM63H MINGW64 ~ (cs1)
$ cd ..

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /c/Users
$ cd ..

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /c
$ cd ..

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /
$ cd d:

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d
$ mkdir abc

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d
$ cd abc

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc
$ git init
Initialized empty Git repository in D:/abc/.git/

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (master)
$ nano a.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (master)
$ git add a.c
warning: in the working copy of 'a.c', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (master)
$ git commit -m "1"
[master (root-commit) 459cd3b] 1
 1 file changed, 1 insertion(+)
 create mode 100644 a.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (master)
$ nano a.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (master)
$ git add a.c
warning: in the working copy of 'a.c', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (master)
$ git commit -m "2"
[master 919ae55] 2
 1 file changed, 1 insertion(+)

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (master)
$ git log
commit 919ae55f3acdea768cb2d80f07fec4bedffafaa2 (HEAD -> master)
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:44:35 2024 +0530

    2

commit 459cd3b4c67f223cbbe408586f0960ab3c9de57c
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:44:19 2024 +0530

    1

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (master)
$ git branch fb

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (master)
$ git checkout fb
Switched to branch 'fb'

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (fb)
$ nano a.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (fb)
$ git add a.c
warning: in the working copy of 'a.c', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (fb)
$ git commit -m "3"
[fb 48755d4] 3
 1 file changed, 2 insertions(+)

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (fb)
$ nano a.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (fb)
$ git add a.c
warning: in the working copy of 'a.c', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (fb)
$ git commit -m "4"
[fb cc3925f] 4
 1 file changed, 1 insertion(+), 1 deletion(-)

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (fb)
$ git log
commit cc3925f8f07153f64dcaef503941f1bdf2aafaa5 (HEAD -> fb)
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:45:40 2024 +0530

    4

commit 48755d4641660b639d9f2d9cbcfdbc2ae9331373
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:45:22 2024 +0530

    3

commit 919ae55f3acdea768cb2d80f07fec4bedffafaa2 (master)
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:44:35 2024 +0530

    2

commit 459cd3b4c67f223cbbe408586f0960ab3c9de57c
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:44:19 2024 +0530

    1
w
BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (fb)
$ nano b.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (fb)
$ git add b.c
warning: in the working copy of 'b.c', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (fb)
$ git commit -m "1"
[fb d6b5da6] 1
 1 file changed, 1 insertion(+)
 create mode 100644 b.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (fb)
$ nano b.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (fb)
$ git add b.c
warning: in the working copy of 'b.c', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (fb)
$ git commit -m "2"
[fb cf432ea] 2
 1 file changed, 1 insertion(+)

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (fb)
$ git log
commit cf432eaf5777237a74f618477297abe6a7a18b10 (HEAD -> fb)
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:46:59 2024 +0530

    2

commit d6b5da60a7be281943a76c17317d6caeffba7371
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:46:48 2024 +0530

    1

commit cc3925f8f07153f64dcaef503941f1bdf2aafaa5
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:45:40 2024 +0530

    4

commit 48755d4641660b639d9f2d9cbcfdbc2ae9331373
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:45:22 2024 +0530

    3

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (fb)
$ git log
commit cf432eaf5777237a74f618477297abe6a7a18b10 (HEAD -> fb)
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:46:59 2024 +0530

    2

commit d6b5da60a7be281943a76c17317d6caeffba7371
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:46:48 2024 +0530

    1

commit cc3925f8f07153f64dcaef503941f1bdf2aafaa5
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:45:40 2024 +0530

    4

commit 48755d4641660b639d9f2d9cbcfdbc2ae9331373
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:45:22 2024 +0530

    3

commit 919ae55f3acdea768cb2d80f07fec4bedffafaa2 (master)
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:44:35 2024 +0530

    2

commit 459cd3b4c67f223cbbe408586f0960ab3c9de57c
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:44:19 2024 +0530

    1
(END)
commit cc3925f8f07153f64dcaef503941f1bdf2aafaa5
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:45:40 2024 +0530

    4

commit 48755d4641660b639d9f2d9cbcfdbc2ae9331373
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:45:22 2024 +0530

    3

commit 919ae55f3acdea768cb2d80f07fec4bedffafaa2 (master)
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:44:35 2024 +0530

    2

commit 459cd3b4c67f223cbbe408586f0960ab3c9de57c
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:44:19 2024 +0530

    1
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
(END)
commit cc3925f8f07153f64dcaef503941f1bdf2aafaa5
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:45:40 2024 +0530

    4

commit 48755d4641660b639d9f2d9cbcfdbc2ae9331373
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:45:22 2024 +0530

    3

commit 919ae55f3acdea768cb2d80f07fec4bedffafaa2 (master)
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:44:35 2024 +0530

    2

commit 459cd3b4c67f223cbbe408586f0960ab3c9de57c
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:44:19 2024 +0530

    1
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
(END)
commit cf432eaf5777237a74f618477297abe6a7a18b10 (HEAD -> fb)
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:46:59 2024 +0530

    2

commit d6b5da60a7be281943a76c17317d6caeffba7371
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:46:48 2024 +0530

    1

commit cc3925f8f07153f64dcaef503941f1bdf2aafaa5
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:45:40 2024 +0530

    4

commit 48755d4641660b639d9f2d9cbcfdbc2ae9331373
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:45:22 2024 +0530

    3

commit 919ae55f3acdea768cb2d80f07fec4bedffafaa2 (master)
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:44:35 2024 +0530

    2

commit 459cd3b4c67f223cbbe408586f0960ab3c9de57c
Author: VireshBH <vireshhunasagi134@gmail.com>
Date:   Sat Nov 16 10:44:19 2024 +0530

    1
~
~
~
~
~
~
~

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (fb)
$ git checkout master
Switched to branch 'master'

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (master)
$ ls
a.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (master)
$ git cherry-pick cf432eaf5777237a74f618477297abe6a7a18b10
CONFLICT (modify/delete): b.c deleted in HEAD and modified in cf432ea (2).  Version cf432ea (2) of b.c left in tree.
error: could not apply cf432ea... 2
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (master|CHERRY-PICKING)
$ ls
a.c  b.c

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (master|CHERRY-PICKING)
$ git cherry-pick --abort

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (master)
$ git cherry-pick cf432eaf5777237a74f618477297abe6a7a18b10
CONFLICT (modify/delete): b.c deleted in HEAD and modified in cf432ea (2).  Version cf432ea (2) of b.c left in tree.
error: could not apply cf432ea... 2
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".

BLDEA-CSE@DESKTOP-02RM63H MINGW64 /d/abc (master|CHERRY-PICKING)
$

