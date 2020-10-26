git checkout -b develop -->  створення нової гілки

git checkout branch_name --> команда переходить на гілку branch_name 




polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend
$ git clone git@github.com:yuriipolichenko/resume.git
Cloning into 'resume'...
warning: You appear to have cloned an empty repository.

polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend
$ ls
puzataHata/  resume/  resume1/

polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend
$ cd resume

polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend/resume (master)
$ ls

polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend/resume (master)
$ git che
checkout      cherry        cherry-pick

polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend/resume (master)
$ git checkout -b develop^C

polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend/resume (master)
$ git checkout -b develop
Switched to a new branch 'develop'

polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend/resume (develop)
$ git status
On branch develop

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        css/
        fonts/
        ico/
        img/
        index.html
        logo/
        maket/
        readme.txt

nothing added to commit but untracked files present (use "git add" to track)

polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend/resume (develop)
$ git add .
warning: CRLF will be replaced by LF in css/banner.css.
The file will have its original line endings in your working directory
warning: CRLF will be replaced by LF in css/header.css.
The file will have its original line endings in your working directory
warning: CRLF will be replaced by LF in css/reset.css.
The file will have its original line endings in your working directory
warning: CRLF will be replaced by LF in css/style.css.
The file will have its original line endings in your working directory
warning: CRLF will be replaced by LF in index.html.
The file will have its original line endings in your working directory
warning: CRLF will be replaced by LF in readme.txt.
The file will have its original line endings in your working directory

polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend/resume (develop)
$ git status
On branch develop

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   css/banner.css
        new file:   css/header.css
        new file:   css/reset.css
        new file:   css/style.css
        new file:   fonts/Lobster_1_4.otf
        new file:   ico/resume ico.png
        new file:   img/banerBase.png
        new file:   img/banerLayer_4.png
        new file:   index.html
        new file:   logo/logo.PNG
        new file:   maket/resume.png
        new file:   readme.txt


polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend/resume (develop)
$ git commit -m "Added firs step for create VC"
[develop (root-commit) 945faed] Added firs step for create VC
 12 files changed, 224 insertions(+)
 create mode 100644 css/banner.css
 create mode 100644 css/header.css
 create mode 100644 css/reset.css
 create mode 100644 css/style.css
 create mode 100644 fonts/Lobster_1_4.otf
 create mode 100644 ico/resume ico.png
 create mode 100644 img/banerBase.png
 create mode 100644 img/banerLayer_4.png
 create mode 100644 index.html
 create mode 100644 logo/logo.PNG
 create mode 100644 maket/resume.png
 create mode 100644 readme.txt

polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend/resume (develop)
$ git status
On branch develop
nothing to commit, working tree clean

polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend/resume (develop)
$ git push origin develop^C

polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend/resume (develop)
$ git add .git add .
fatal: pathspec 'add' did not match any files

polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend/resume (develop)
$ git push origin develop
Enumerating objects: 20, done.
Counting objects: 100% (20/20), done.
Delta compression using up to 12 threads
Compressing objects: 100% (16/16), done.
Writing objects: 100% (20/20), 2.70 MiB | 1.13 MiB/s, done.
Total 20 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:yuriipolichenko/resume.git
 * [new branch]      develop -> develop

polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend/resume (develop)
$ ^C

polic@DESKTOP-P4HTRL2 MINGW64 /e/frontend/resume (develop)
$
