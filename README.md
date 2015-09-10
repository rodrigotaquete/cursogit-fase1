#Arquivo READEM.md

##Curso de Git - Fase 1 do Projeto

Após criar o repositório no GitHub, foram realizados os seguintes processos:

1. Abrir o Git Bash;
2. Criar um repositório novo:
  * **mkdir cursogit-fase1** - criando um pasta;
  * **cd cursogit-fase1** - entrando na pasta criada;
  * **git init** - inicializando o repositório;
3. Criar o arquivo README.md:
  * **vim README.md** - criando e editando o arquivo;
4. Commitando o arquivo README.md:
  * **git add README.md** - passando o arquivo para o status "Ghanges to be committed";
  * **git commit README.md -m "Commitando o arquivo README.md"** - commitando o arquivo;
5. Conectando o repositório remoto com o repositório local
  * **git remote add origin "https://github.com/rodrigotaquete/cursogit-fase1"** - conecta o repositório local ao repositório remoto;
6. Enviando o arquivo para o repositório remoto:
  * **git push origin master** - envia os arquivo do branch master para o repositório; 
