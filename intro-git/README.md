# Introduction to git

echo "# UTP-Mision_Tic_33" >> README.md

# orden inicial

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:JuliLopez3517/UTP-Mision_Tic_33.git
git push -u origin main

# Basic commands

-git init
-<strong>git add .</strong> <i>or</i> <strong>git add nombre-archivo</strong> (adicionar los
archivos al stage area)
-<strong>git commit -m" "</strong> (guardar los archivos que están en el stage are  con un comentario)
-git push origin main (subir los cambios al repositorio github/gitlab)
-<strong>git status</strong>(verificar los archivos que están dentro del stage area)

# Config
- start-ssh-agent (Habilitar agente ssh en windows)
- git config --global user.email "distriartez@gmail,com"
- git config --global user.name " Julian"
