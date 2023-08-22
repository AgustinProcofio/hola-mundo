# hola-mundo
Agustin Procofio

aprocofio@MacBook-Pro-de-Agustin ~ % ls
Applications            Downloads               Music                   archivo.txt             hola-mundo
Desktop                 Library                 Pictures                archivos python         microprocesadores
Documents               Movies                  Public                  archivos.text           proyecto1
aprocofio@MacBook-Pro-de-Agustin ~ % cd hola-mundo 
aprocofio@MacBook-Pro-de-Agustin hola-mundo % cd ..
aprocofio@MacBook-Pro-de-Agustin ~ % ls  
Applications            Downloads               Music                   archivo.txt             hola-mundo
Desktop                 Library                 Pictures                archivos python         microprocesadores
Documents               Movies                  Public                  archivos.text           proyecto1
aprocofio@MacBook-Pro-de-Agustin ~ % ls
Applications            Documents               Library                 Music                   Public                  archivos python         hola-mundo              proyecto1
Desktop                 Downloads               Movies                  Pictures                archivo.txt             archivos.text           microprocesadores
aprocofio@MacBook-Pro-de-Agustin ~ % cd hola-mundo 
aprocofio@MacBook-Pro-de-Agustin hola-mundo % ls
README
aprocofio@MacBook-Pro-de-Agustin hola-mundo % git add readme
aprocofio@MacBook-Pro-de-Agustin hola-mundo % git statu
git: 'statu' is not a git command. See 'git --help'.

The most similar commands are
        status
        stage
        stash
aprocofio@MacBook-Pro-de-Agustin hola-mundo % git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README

nothing added to commit but untracked files present (use "git add" to track)
aprocofio@MacBook-Pro-de-Agustin hola-mundo % git add .
aprocofio@MacBook-Pro-de-Agustin hola-mundo % git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   README

aprocofio@MacBook-Pro-de-Agustin hola-mundo % git commit -m "Commit inicial"
[main de2886d] Commit inicial
 1 file changed, 1 insertion(+)
 create mode 100644 README
aprocofio@MacBook-Pro-de-Agustin hola-mundo % git push
To https://github.com/AgustinProcofio/hola-mundo.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/AgustinProcofio/hola-mundo.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
