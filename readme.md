PS C:\Users\Janaina\Documents\SENAI-LOGICA-PROGRAMACAO\senai-site> git init
Initialized empty Git repository in C:/Users/Janaina/Documents/SENAI-LOGICA-PROGRAMACAO/senai-site/.git/
PS C:\Users\Janaina\Documents\SENAI-LOGICA-PROGRAMACAO\senai-site> git config --global user.name Daniel Teixeira
PS C:\Users\Janaina\Documents\SENAI-LOGICA-PROGRAMACAO\senai-site> git config --global user.email danielteixeiradiasneto@outlook.com
PS C:\Users\Janaina\Documents\SENAI-LOGICA-PROGRAMACAO\senai-site> git add *
PS C:\Users\Janaina\Documents\SENAI-LOGICA-PROGRAMACAO\senai-site> git commit -m "primeira commit"
[master (root-commit) 0c7cfec] primeira commit
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html
 create mode 100644 readme.md
PS C:\Users\Janaina\Documents\SENAI-LOGICA-PROGRAMACAO\senai-site> git remote add origin https://github.com/DanielZTZ/senai-site.git
PS C:\Users\Janaina\Documents\SENAI-LOGICA-PROGRAMACAO\senai-site> git branch -M main
PS C:\Users\Janaina\Documents\SENAI-LOGICA-PROGRAMACAO\senai-site> git status
On branch main
nothing to commit, working tree clean
PS C:\Users\Janaina\Documents\SENAI-LOGICA-PROGRAMACAO\senai-site> git log
commit 0c7cfec1702486071fb91f01f334eb0d1dd52edf (HEAD -> main)
Author: Daniel <danielteixeiradiasneto@outlook.com>
Date:   Sun Sep 12 18:01:11 2021 -0300

    primeira commit
PS C:\Users\Janaina\Documents\SENAI-LOGICA-PROGRAMACAO\senai-site> git commit -m "criando a branch Main"
On branch main
nothing to commit, working tree clean
PS C:\Users\Janaina\Documents\SENAI-LOGICA-PROGRAMACAO\senai-site> git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 234 bytes | 29.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/DanielZTZ/senai-site.git
 * [new branch]      main -> main
PS C:\Users\Janaina\Documents\SENAI-LOGICA-PROGRAMACAO\senai-site>
