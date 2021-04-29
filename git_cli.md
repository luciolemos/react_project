
#### 1. Criando o projeto `react_project` com o comando `npx create-react-app react_project`. 
    luciolemos@dev:~/nextlevelweek$ npx create-react-app react_project
    
#### 2. Listando arquivos/diretórios dentro de `nextlevelweek` com o comando `ls -l`.
    luciolemos@dev:~/nextlevelweek$ ls -l
    total 16
    drwxrwxr-x  8 luciolemos luciolemos 4096 abr 27 17:29 podcastr
    drwxrwxr-x 10 luciolemos luciolemos 4096 abr 20 07:14 podcastrnext
    drwxrwxr-x  5 luciolemos luciolemos 4096 abr 29 00:14 react_project
    drwxrwxr-x  6 luciolemos luciolemos 4096 abr 24 13:53 restful
#### 3. Navegando para a raiz do projeto criado:    
    luciolemos@dev:~/nextlevelweek$ cd react_project
#### 4. Listando arquivos/diretorios:
Observe que durante a criação de `react_project` é gerado na raiz do projeto o arquivo oculto `.gitignore`. 


    luciolemos@dev:~/nextlevelweek/react_project$ ls -la
    total 564
    drwxrwxr-x    5 luciolemos luciolemos   4096 abr 29 00:14 .
    drwxrwxr-x    6 luciolemos luciolemos   4096 abr 29 00:11 ..
    -rw-r--r--    1 luciolemos luciolemos    310 abr 29 00:14 .gitignore
    drwxrwxr-x 1047 luciolemos luciolemos  36864 abr 29 00:14 node_modules
    -rw-rw-r--    1 luciolemos luciolemos    817 abr 29 00:14 package.json
    drwxrwxr-x    2 luciolemos luciolemos   4096 abr 29 00:14 public
    -rw-r--r--    1 luciolemos luciolemos   3362 abr 29 00:14 README.md
    drwxrwxr-x    2 luciolemos luciolemos   4096 abr 29 00:14 src
    -rw-rw-r--    1 luciolemos luciolemos 507735 abr 29 00:14 yarn.lock
#### 5. Inicializando com o git, o projeto criado
    luciolemos@dev:~/nextlevelweek/react_project$ git init
    Initialized empty Git repository in /home/luciolemos/nextlevelweek/react_project/.git/
#### 6. Adicionando ao repositório `add .`, todo o projeto
    luciolemos@dev:~/nextlevelweek/react_project$ git add .
#### 7. Realizando o primeiro commit.
    luciolemos@dev:~/nextlevelweek/react_project$ git commit -m "first commit"
    [master (root-commit) 7717d09] first commit
    18 files changed, 11728 insertions(+)
    create mode 100644 .gitignore
    create mode 100644 README.md
    create mode 100644 package.json
    create mode 100644 public/favicon.ico
    create mode 100644 public/index.html
    create mode 100644 public/logo192.png
    create mode 100644 public/logo512.png
    create mode 100644 public/manifest.json
    create mode 100644 public/robots.txt
    create mode 100644 src/App.css
    create mode 100644 src/App.js
    create mode 100644 src/App.test.js
    create mode 100644 src/index.css
    create mode 100644 src/index.js
    create mode 100644 src/logo.svg
    create mode 100644 src/reportWebVitals.js
    create mode 100644 src/setupTests.js
    create mode 100644 yarn.lock
#### 8.    
    luciolemos@dev:~/nextlevelweek/react_project$ git branch -M main
#### 9.     
    luciolemos@dev:~/nextlevelweek/react_project$ git remote add origin https://github.com/luciolemos/react_project.git
    luciolemos@dev:~/nextlevelweek/react_project$ git push -u origin main
    Username for 'https://github.com': luciolemos
    Password for 'https://luciolemos@github.com': 
    Enumerating objects: 22, done.
    Counting objects: 100% (22/22), done.
    Delta compression using up to 4 threads
    Compressing objects: 100% (22/22), done.
    Writing objects: 100% (22/22), 211.62 KiB | 3.92 MiB/s, done.
    Total 22 (delta 0), reused 0 (delta 0), pack-reused 0
    To https://github.com/luciolemos/react_project.git
    * [new branch]      main -> main
    Branch 'main' set up to track remote branch 'main' from 'origin'.
#### 10. Carregando projeto no VSCode.
    luciolemos@dev:~/nextlevelweek/react_project$ code .
    
