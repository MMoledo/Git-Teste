# Arquivo de Teste de Versionamento

Este projeto atua como nossa "Caixinha de Areia" para o aprendizado prático dos comandos do Git. Sob a orientação do Lucas, estamos explorando, de maneira desordenada, o impacto e os resultados dos comandos do Git para entender profundamente cada função.

### Comandos Básicos do Git
- `git init`: Inicializa um novo repositório Git local.
- `git add .`: Adiciona todos os arquivos modificados no diretório atual ao próximo commit.
- `git commit -m "mensagem desejada"`: Registra alterações nos arquivos rastreados com uma mensagem de commit explicativa.

### Configuração do Usuário
- `git config --global user.email "you@example.com"`: Associa seu e-mail ao Git, sincronizando com o GitHub.
- `git config --global user.name "Your Name"`: Define seu nome de usuário no Git para identificação de autor.

### Trabalhando com Branches
- `git branch -M main`: Renomeia a branch atual para `main`.
- `git branch`: Lista todas as branches locais ou cria uma nova branch.
- `git push -u origin main`: Envia a branch `main` local para o repositório remoto e configura o rastreamento.

### Gerenciamento de Repositório Remoto
- `git remote add origin url-do-repositorio-no-github`: Conecta seu repositório local ao remoto no GitHub.
- `git remote rm origin`: Remove a conexão com o repositório remoto especificado.

### Sincronização e Atualização
- `git fetch`: Busca as atualizações de todas as branches do repositório remoto.
- `git pull --rebase`: Atualiza a branch local com mudanças do repositório remoto, reescrevendo o histórico local.
- `git pull origin master`: Puxa as atualizações da branch `master` remota para a branch local.
- `git merge --continue`: Continua o processo de merge após a resolução de conflitos.
- `git pull origin master --rebase`: Combina `fetch` e `rebase` da branch `master` remota na branch local.

### Merge vs Rebase
- **Merge**: Atualiza a branch atual com as alterações de outra (geralmente a `master`).
- **Rebase**: Aplica os commits de uma branch em cima de outra, resultando em um histórico linear.

### Trocando de Branch
- `git checkout login`: Muda para a branch `login`.

### Histórico e Logs
- `git reflog`: Mostra um log de operações, como commits e checkouts.
- `git log --decorate --oneline --graph --all`: Exibe o histórico de commits de todas as branches de forma gráfica e resumida.

### Desfazendo Alterações
- `git reset <hash do commit>`: Reverte o estado do repositório para um commit específico.
- `git commit --amend`: Modifica a mensagem do último commit.
- `git revert <hash do commit>`: Cria um novo commit que desfaz as alterações introduzidas pelo commit especificado.

### Resolução de Conflitos
- `git rerere`: Reusa resoluções de conflitos anteriores ao encontrar conflitos semelhantes.

Lembre-se de que os arquivos e mensagens de commit aqui são para propósitos educacionais e não devem ser levados a sério! ;)
