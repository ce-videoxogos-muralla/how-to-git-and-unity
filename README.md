# how-to-git-and-unity

## Instalar git

1. Instalar en cada equipo seguindo as instruccións: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

## Configurar git
En cada equipo:

1. `git config --global user.name "John Doe"`
2. `git config --global user.email johndoe@example.com`
3. `git config --global init.defaultBranch main`
4. `git lfs install`

## Crear conta en github

1. Rexistrar un usuario en github
2. Configurar a chave ssh para cada equipo que vamos utilizar

# Como configurar un proxecto unity novo con un repositorio novo de git en github

1. Crear o proxecto en unity hub. Importante: o nome do proxecto en minúsculas e substituíndo espacios por guións
2. En git bash: situarnos no directorio e facer `git init`
3. En github: crear un repositorio novo co mesmo nome que o do proxecto, utilizando o .gitignore de unity
4. En git bash, engadimos remoto: `git remote origin <url-do-repo>`
5. Poñemos o remoto como default. En git bash: `git push --set-upstream origin main`
6. Pasamos a stage todos os ficheiros. En git bash: `git add .`
7. Comiteamos os ficheiros no stagging area. En git bash: `git commit -m "Primeiro commit"`
8. Subimos o commit a github. En git bash: `git push`

# Clonar un proxecto unity existente con git e github 

1. En github copiar do botón verde que pon "code" o enderezo https ou ssh. 
2. En git bash, situámonos no directorio onde queremos que se copie o cartafol do proxecto
3. En git bash: `git clone <enderezo>`
