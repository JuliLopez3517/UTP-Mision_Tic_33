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

-<strong>git init</strong> (se realiza una sola vez, esto con la finalidad de añadir el proyecto a git)
-<strong>git add .</strong> <i>or</i> <strong>git add nombre-archivo</strong> (adicionar los
archivos al stage area)
-<strong>git commit -m" "</strong> (guardar los archivos que están en el stage are  con un comentario)
-git push origin main (subir los cambios al repositorio github/gitlab)
-<strong>git status</strong>(verificar los archivos que están dentro del stage area)
-<strong>git log</strong> (visualizar los commits de nuestro proyecto)
-<strong>git branch</strong> (visualizar las ramas de nuestro proyecto)
-<strong>git log --oneline</strong> (visualizar commits y ramas del proyecto)
-<strong>git branch nombre rama</strong> (crear nueva rama)
-<strong>git checkout nombre-rama</strong> (cambiar de rama)
-<strong>git merge nombre-rama</strong> (unir commits de dos ramas)



# Config
- start-ssh-agent (Habilitar agente ssh en windows)
- git config --global user.email "distriartez@gmail,com"
- git config --global user.name " Julian"

### Tools
- Fig -> autoComplete
