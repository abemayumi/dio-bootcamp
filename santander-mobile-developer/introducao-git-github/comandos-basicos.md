## Alguns Comandos Básicos

Utilizado no Git Bash



1. Inicializar para o git  começar a gerenciar e *versionalizar* o repositório

​			**git init**

2. Configuração inicial do repositório

​			**git config --global user.email "*email_cadastrado_no_github*"**

​			**git config --global user.name *usuario_no_ github***

3. Status dos arquivos

   ​	**git status**

4. Salvar alterações para área de *staging*

   ​	git add *  *(tudo)*

   ​	**git add *nome-do-arquivo*** *(arquivo especifico)*

   ​	**git commit -m "descrição da alteração"**

   

   ### Enviar do repositório local para o Remoto

   - Depois de criar o repositório no gitHub, copiar o endereço criado e no git bash, digitar:

     **git remote add origin *link_repositorio_criado_no_gitHub***	

   - Listar os repositórios cadastrado

   ​		**git remote -v**

   - Enviar para o remoto

     **git push origin master**

   - 

     



