# github

Arquivo de comando de Git Github
Github:
Configuração do git 
git config --global user.name "Fabiano de Barros Silva "
git config -- global user.email "fabiano00760@yahoo.com"

para saber o email e o nome 
git config user.name 
git config user.email

para saber tudo 
git config --list

Para entra numa pastar 
cd git-course

Para criar uma pastar (mkdir + nome da pasta)
mkdir git-course

Iniciar no diretório padrão --cd-to-home.

git init - Inicia o projeto git.

ls -la (mostra o diretorio chamado git).

ls ( entra dentro do diretorio git)

cd .git(abri esse diretorio git )

cd .. (no windows para voltar uma pasta )


Para criar um Aquivo Readme
vi readme.md 
para editar o arquivo aperta a tecla i para entra no modo insert 
(#Github)
Aperte a tecla Esc : w (para salvar) q ( para sair)
para editar novamente  vi Readme.md aperto i para editar insert

git status (para ver o estatus de seu repositorio )

git add - adiciona no git (utilizar git add . para adicionar tudo ou *.extensao para adicionar tudo daquela extensão)

git commit -m "mensagem"- Adiciona os arquivos no git

.gitignore - Criar um arquivo com este nome e adicionar os arquivos/diretórios que não queira que suba no git.

git commit -a -m "mensagem" - Pula a etapa do add

git diff --staged - mostra as mudanças feitas no arquivo 

git log - mostra os logs de todos os commits feitos no projeto

git log -p - além de mostrar os logs, mostra também o que foi adicionado (git log + git diff)

git log -p -1 (ou n) - mostra a quantidade especificadas de log

git log --pretty=oneline - mostra o log apenas em 1 linha

git commit --amend -m "msg(edit)" - serve para editar o commit atual

git reset HEAD (arquivo) - Para remover o arquivo da área de commit

git checkout -- (arquivo) - Desfaz as modificações

git rm (arquivo) - Remove um arquivo

git tag - Lista as tags

git tag -a nometag -m "msg" - cria uma tag anotada e define uma mensagem.

git tag -a nometag hash - cria uma tag na hash(id) informada

git checkout nometag - vê os arquivos na tag informada (troca de branch)

git tag -d nometag - Apaga a tag informada

git branch nomebranch - Cria um novo branch

git checkout nomebranch - Muda pro branch desejado

git checkout -b nomebranch - Cria e altera para o branch criado

git merge nomebranch - combina as informações do branch informado com o atual

git init --bare - Iniciar um repositório em uma máquina virtual

git clone file:////repositório nomepasta - Clona o repositório da rede e altera o nome da pasta ou não

git remote - mostra o nome do servidor remoto

git push servidor_remoto servidor_master - envia os arquivos do servidor principal ao remoto

git pull servidor_remoto servidor_master - recebe os arquivos (automaticamente faz um "merge")

git fetch servidor_remoto nova_branch  - recebe os arquivos sem o merge

git shortlog  - para ver o nome da pessoa q commitou quais foram os autores 

git shortlog -sn- mostra a quantidade de commit e o nome da pessoa q commitou 

git log -  mostra o commit o autor e a data e hora qual bresh pra qual bresh 

