#Anotações de comandos git

##Principais comandos

###git init
Para iniciar um repositório local, ele cria um arquivo .git
###git status
Para verificar o status do seu projeto
###git clone "nome do repositorio"
Para clonar um repositorio remoto
###git add . ou git add * ou git add "nome do arquivo"
Adiciona todos os arquivos no container.
###git commit -m "menssagem"
Pega todas as atualizações e coloca no container para ser enviado ao repósitorio remoto.
###git pull
Sincroniza o repósitorio remoto com o local, puxando tudo que estiver no repositorio remoto.
###git push -u origin
Envia tudo do repósitorio local para o remoto.
###git log
Verifica todas as alterações
###git log --oneline
verifica de forma mais simplificada as atualização
###ls
Para exibir o que esta dentro do diretorios
###ls -a 
Para exibir arquivos ocultos
###touch "nome do arquivo"
Esse comando você pode criar arquivos pelo  git bash
###git log --graph
Mostra o desenho do grafo criado e suas ramificações
###git branch
Para localizar o ramo que o arquivo se encontra
###git checkout "e os 7 ultimos caracteres"
Esse comando é para retornar o código para a versão anterior
###git checkout master ou main
Esse comando retorna o arquivo para versão final caso tenha retornado para verssão anterior. Ou retorna o arquivo para o seu ramo anterior.
###git diff
Mostra o que foi alterado no arquivo
###git checkout "nome do arquivo"
Para desfazer o que foi modificado.
###git reset HEAD
Para remover o contúedo do container
###git checkout -b "nome  do arquivo"
Para criar uma nova ramificação além da master
###git log --oneline --graph --all
Esse comando você conseguirar visualizar a ramificação dos ramos.
###git merge "nome do ramo"
Para fazer uma fusão dos ramos
###git merge --abort
Para abortar a fusão dos ramos
###git remote
Verifica se possui um repositorio remoto.



