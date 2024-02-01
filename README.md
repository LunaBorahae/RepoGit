GIT BASH
Detalle para no perder los cambios en caso de que se me cierre la consola
Carolina@DESKTOP-M7TFQVE MINGW64 /
$ cd /D

Carolina@DESKTOP-M7TFQVE MINGW64 /D
$ cd Escritorio/

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio
$ cd Apoyo\ Desafío\ evaluado\ -\ Branching/

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching
$ git init
Initialized empty Git repository in D:/Escritorio/Apoyo Desafío evaluado - Branching/.git/

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (master)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (master)
$ git add git_landing/
index.html  style.css

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (master)
$ git add git_landing/
index.html  style.css

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (master)
$ git add git_landing/
index.html  style.css

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        git_landing/

nothing added to commit but untracked files present (use "git add" to track)

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (master)
$ git add .
warning: in the working copy of 'git_landing/index.html', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'git_landing/style.css', LF will be replaced by CRLF the next time Git touches it

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   git_landing/index.html
        new file:   git_landing/style.css


Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (master)
$ git commit -m "Cambios de Carolina Carmona"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Carolina@DESKTOP-M7TFQVE.(none)')

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (master)
$ ^C

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (master)
$ git config --global user.email "linacristal11@gmail.com"

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (master)
$ git config --global user.name "Carolina Carmona"

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (master)
$ git commit -m "Cambios de Carolina Carmona"
[master (root-commit) 01b8839] Cambios de Carolina Carmona
 2 files changed, 81 insertions(+)
 create mode 100644 git_landing/index.html
 create mode 100644 git_landing/style.css
Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (master)
$ git remote add origin https://github.com/LunaBorahae/RepoGit.git
Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (master)
$ git branch -M main

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (main)
$ git push -u origin main
Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (main)
$ git add .

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   GIT bash detalle.docx
        new file:   ~$T bash detalle.docx


Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (main)
$ git commit -m "Para iniciar"
[main 8cb9143] Para iniciar
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 GIT bash detalle.docx
 create mode 100644 ~$T bash detalle.docx

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (main)
$ git status
On branch main
nothing to commit, working tree clean

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (main)
$ git push --set-upstream origin main
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 8 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (9/9), 10.74 KiB | 5.37 MiB/s, done.
Total 9 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/LunaBorahae/RepoGit.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (main)
$ git checkout -b development
Switched to a new branch 'development'

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (development)
$ git checkout -b nuevarama
Switched to a new branch 'nuevarama'
Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (nuevarama)
$ git add .
warning: in the working copy of 'git_landing/index.html', LF will be replaced by CRLF the next time Git touches it

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (nuevarama)
$ git add .

Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (nuevarama)
$ git status
On branch nuevarama
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   git_landing/index.html


Carolina@DESKTOP-M7TFQVE MINGW64 /D/Escritorio/Apoyo Desafío evaluado - Branching (nuevarama)
$

