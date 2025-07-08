# Comandos Git

## Comandos Básicos
- `git init`: Inicializa um novo repositório Git.
- `git clone <repository-url>`: Clona um repositório existente.
- `git status`: Verifica o status do diretório de trabalho e da área de stage.
- `git add <file>`: Adiciona um arquivo à área de stage.
- `git add .`: Adiciona todos os arquivos à área de stage.
- `git commit -m "mensagem do commit"`: Realiza um commit com uma mensagem.
- `git push`: Envia as alterações para o repositório remoto.
- `git pull`: Busca e mescla as alterações do repositório remoto.

## Branches
- `git branch`: Lista todas as branches.
- `git branch <nome-da-branch>`: Cria uma nova branch.
- `git checkout <nome-da-branch>`: Troca para uma branch diferente.
- `git merge <nome-da-branch>`: Mescla uma branch na branch atual.
- `git branch -d <nome-da-branch>`: Deleta uma branch.

## Repositórios Remotos
- `git remote -v`: Lista os repositórios remotos.
- `git remote add <nome> <url>`: Adiciona um novo repositório remoto.
- `git remote remove <nome>`: Remove um repositório remoto.

## Visualização do Histórico
- `git log`: Visualiza o histórico de commits.
- `git log --oneline`: Visualiza o histórico de commits em uma linha por commit.

## Desfazendo Alterações
- `git reset --hard HEAD`: Desfaz todas as alterações no diretório de trabalho e na área de stage.
- `git checkout -- <file>`: Desfaz as alterações em um arquivo específico.
- `git revert <commit>`: Cria um novo commit que desfaz as alterações de um commit anterior.

## Stashing
- `git stash`: Salva temporariamente as alterações e limpa o diretório de trabalho.
- `git stash apply`: Aplica as alterações salvas.

## Tags
- `git tag`: Lista todas as tags.
- `git tag <nome-da-tag>`: Cria uma nova tag.
- `git push origin <nome-da-tag>`: Envia uma tag para o repositório remoto.

## Configuração
- `git config --global user.name "Seu Nome"`: Define o nome de usuário global para os commits do Git.
- `git config --global user.email "seu.email@exemplo.com"`: Define o email global para os commits do Git.
