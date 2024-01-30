#Desafio-Branching

david@Acer_ND MINGW64 ~
$ cd OneDrive/Documentos/00.repositorio/DESAFIO\ BRANCHING/

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING
$ git clone https://github.com/daap06/Desafio-Branching.git
Cloning into 'Desafio-Branching'...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING
$ git clone --branch development https://github.com/daap06/Desafio-Branching.git
fatal: destination path 'Desafio-Branching' already exists and is not an empty directory.

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING
$ git clone --branch development https://github.com/daap06/Desafio-Branching.git
Cloning into 'Desafio-Branching'...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING
$ cd Desafio-Branching-main/

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-main (main)
$ cd ..

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING
$ cd Desafio-Branching-dev/

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-dev (development)
$ cd ..

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING
$ cd Desafio-Branching-main/

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-main (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html
        style.css

nothing added to commit but untracked files present (use "git add" to track)

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-main (main)
$ git add .
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'style.css', LF will be replaced by CRLF the next time Git touches it

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-main (main)
$ git commit -m "first commit"
[main 1e521f4] first commit
 2 files changed, 81 insertions(+)
 create mode 100644 index.html
 create mode 100644 style.css

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-main (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.15 KiB | 1.15 MiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/daap06/Desafio-Branching.git
   9770ecb..1e521f4  main -> main

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-main (main)
$ cd ../Desafio-Branching-dev/

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-dev (development)
$ git status
On branch development
Your branch is up to date with 'origin/development'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html
        style.css

nothing added to commit but untracked files present (use "git add" to track)

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-dev (development)
$ git add .
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'style.css', LF will be replaced by CRLF the next time Git touches it

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-dev (development)
$ git commit -m "first commit"
[development 1758ccd] first commit
 2 files changed, 81 insertions(+)
 create mode 100644 index.html
 create mode 100644 style.css

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-dev (development)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.15 KiB | 1.15 MiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/daap06/Desafio-Branching.git
   9770ecb..1758ccd  development -> development

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-dev (development)
$ git status
On branch development
Your branch is up to date with 'origin/development'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html
        modified:   style.css

no changes added to commit (use "git add" and/or "git commit -a")

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-dev (development)
$ git add index.html

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-dev (development)
$ git commit -m "Se actualiza url de imagen que estaba rota"
[development e5dcaf8] Se actualiza url de imagen que estaba rota
 1 file changed, 1 insertion(+), 1 deletion(-)

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-dev (development)
$ git add style.css
warning: in the working copy of 'style.css', LF will be replaced by CRLF the next time Git touches it

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-dev (development)
$ git commit -m "Se incrementa tamaño de la imagen en un 5%"
[development 152d5b2] Se incrementa tamaño de la imagen en un 5%
 1 file changed, 1 insertion(+), 1 deletion(-)

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-dev (development)
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 762 bytes | 762.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
To https://github.com/daap06/Desafio-Branching.git
   1758ccd..152d5b2  development -> development

david@Acer_ND MINGW64 ~/OneDrive/Documentos/00.repositorio/DESAFIO BRANCHING/Desafio-Branching-dev (development)
$ ls
README.md  index.html  style.css
