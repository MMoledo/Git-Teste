# Arquivo de Teste de Versionamento 
Este projeto está servindo como nossa "Caixinha de Areia" para aprender os comandos do Git!
Seguindo a trilha proposta pelo Lucas, nós estamos fazendo a maior bagunça aqui a fim de aprender todas as causas e efeitos dos comandos apresentados. 
<br>git init = serve para inicializar o repositório 

git add . = serve para adicionar todos os arquivos no projeto

git commit -m "mensagem desejada" = serve para  registrar alterações em um ou mais arquivos no seu branch.

git config --global user.email "you@example.com" = colocar email do git hub para sincronizar

git config --global user.name "Your Name" = definir um nome de usuario

git branch -M main
O comando “git branch” cria novas branches. Mas também pode funcionar como uma forma 
de verificar as ramificações já existentes. Depois de criar uma, você precisa de um “push” para subir essa ramificação.

O comando git remote add origin url-do-repositorio-no-github é o utilizado para 
conectar seu repositório local ao repositório remoto no Github.

git remote rm origin = serve para apagar o diretorio remoto da maquina

git fetch = Comandos e opções do git fetch git fetch <remote> Busque todas as ramificações no repositório. 
Este comando também baixa todos os commits e arquivos necessários do outros repositórios

git push -u origin main = serve para enviar os commits feitos localmente para o github

git pull --rebase

git pull origin master

git merge --continue

git pull origin master --rebase

quando usar o rebase e o merge

merge vai utilizar muito pra atualizar a minha branch na master

rebase resolve individualmente cada conflito

 git checkout login = serve pra trocar a branch que esta sendo mechida	

reflog = referencias do git atualizadas no repositorio

git log --decorate --oneline --graph --all

git reset (hash do commit para qual voce quer voltar) = serve para voltar pro commit que desejamos

git commit --amend = serve para alterar a mensagem do ultimo commit

resolver bug = pegar o hash do commit que deu o bug e usar o git revert

git revert = vai pegar tudo que fez em um commit especifico e criar um novo commit removendo as alterações

git rerere = guarda as soluções de rebase ja feitas

</br>
Ps.: Não levem a sério os arquivos e os títulos das commits! ;)