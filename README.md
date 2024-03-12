# belajarGIT
Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT


ACER@zefanya MINGW64 /c/GIT (master)
$ git clone https://github.com/stevanus28/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

ACER@zefanya MINGW64 /c/GIT (master)
$ git init
Reinitialized existing Git repository in C:/GIT/.git/

ACER@zefanya MINGW64 /c/GIT (master)
$ cd belajarGIT

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-git

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Git.txt


ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git config --global user.email "zefanyapua84@gmail.com"

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git config --global user.name "stevanus28"

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git commit -m "tugasgit"
[Tugas-git 3a2569f] tugasgit
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-git
Updating e7e55be..3a2569f
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 285 bytes | 95.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/stevanus28/belajarGIT.git
   e7e55be..3a2569f  main -> main

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-html

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git config --global user.email "zefanyapua84@gmail.com"

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git config --global user.name "stevanus28"

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git commit -m "tugashtml"
[Tugas-html 572206d] tugashtml
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-html
Updating 3a2569f..572206d
Fast-forward
 Tugas-Html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 316 bytes | 316.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/stevanus28/belajarGIT.git
   3a2569f..572206d  main -> main

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-css

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git config --global user.email "zefanyapua84@gmail.com"

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git config --global user.name "stevanus28"

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git commit -m "tugascss"
[Tugas-css aa22aad] tugascss
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
nothing to commit, working tree clean

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-css
Updating 572206d..aa22aad
Fast-forward
 Tugas-Css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 345 bytes | 345.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/stevanus28/belajarGIT.git
   572206d..aa22aad  main -> main

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-js

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git config --global user.email "zefanyapua84@gmail.com"

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git config --global user.name "stevanus28"

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git commit -m "tugasjs"
[Tugas-js 35401cc] tugasjs
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
nothing to commit, working tree clean

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-js
Updating aa22aad..35401cc
Fast-forward
 Tugas-Js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 279 bytes | 279.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/stevanus28/belajarGIT.git
   aa22aad..35401cc  main -> main

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-midProject

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ it checkout Tugas-midProject
bash: it: command not found

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.email "zefanyapua84@gmail.com"

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.name "stevanus28"

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git commit -m "tugasmidproject"
[Tugas-midProject c28d7fe] tugasmidproject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
nothing to commit, working tree clean

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-midProject
Updating 35401cc..c28d7fe
Fast-forward
 Tugas-MidProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 291 bytes | 291.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/stevanus28/belajarGIT.git
   35401cc..c28d7fe  main -> main

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-php

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git config --global user.email "zefanyapua84@gmail.com"

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git config --global user.name "stevanus28"

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git commit -m "tugasphp"
[Tugas-php 7d686d8] tugasphp
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
nothing to commit, working tree clean

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-php
Updating c28d7fe..7d686d8
Fast-forward
 Tugas-Php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 282 bytes | 282.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/stevanus28/belajarGIT.git
   c28d7fe..7d686d8  main -> main

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-finalProject

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git config --global user.email "zefanyapua84@gmail.com"
ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git config --global user.name "stevanus28"

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git commit -m "tugasfinalproject"
[Tugas-finalProject 2339b86] tugasfinalproject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
nothing to commit, working tree clean

ACER@zefanya MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 7d686d8..2339b86
Fast-forward
 Tugas-FinalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 286 bytes | 286.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/stevanus28/belajarGIT.git
   7d686d8..2339b86  main -> main

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$ ^C

ACER@zefanya MINGW64 /c/GIT/belajarGIT (main)
$
