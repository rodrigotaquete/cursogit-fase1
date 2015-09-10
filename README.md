#Arquivo READEM.md

##Curso de Git - Fase 1 do Projeto

Após criar o repositório no GitHub, foram realizados os seguintes processos:

* Abrir o Git Bash;
* Criar um repositório novo:
1. **mkdir cursogit-fase1** - criando um pasta;
2. **cd cursogit-fase1** - entrando na pasta criada;
3. **git init** - inicializando o repositório;
* Criar o arquivo README.md:
1. **vim README.md** - criando e editando o arquivo;
* Commitando o arquivo README.md:
1. **git add README.md** - passando o arquivo para o status "Ghanges to be committed";
2. **git commit README.md -m "Commitando o arquivo README.md"** - commitando o arquivo;
* Conectando o repositório remoto com o repositório local
1. **git remote add origin "https://github.com/rodrigotaquete/cursogit-fase1" - conecta o repositório local ao repositório remoto;
* Enviando o arquivo para o repositório remoto:
1. **git push origin master** - envia os arquivo do branch master para o repositório; 
