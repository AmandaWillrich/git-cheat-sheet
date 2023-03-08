# GIT + GITHUB Cheat Sheet

## Branch Commands

| **Comando** | **O que faz** |
| --- | --- | 
| **git branch new-branch** | Cria nova branch com o nome *new-branch* |
| **git checkout -b new-branch** | Cria nova branch e navega para dentro da branch |
| **git checkout main** | Muda o código atual para a branch principal |
| **git branch -d new-branch** | Deleta a *new-branch* |
| **git branch** | Lista todos os branches criados
| **git branch -v** | Lista os branches criados com logs de commit
| **git push origin new-branch** | Criando um branch remoto com o mesmo nome
| **git pull origin main** | Download dos arquivos do repositório remoto para o local
| **git fetch origin** | Download de todas as branches remotas
| **git merge new-branch** | Realiza merge entre os branches

## Stash

| **Comando** | **O que faz** |
| --- | --- | 
| **git stash** | Cria um stash, salva temporariamente as modificações
| **git stash list** | Lista todos os stashes criados
| **git stash apply** | Volta ao último stash
| **git stash branch my-branch** | Cria um branch a partir de um stash

## Github

| **Comando** | **O que faz** |
| --- | --- |
| **git --version** | Verifica a versão instalada
| **git config --global user.name "your-name"** | Configura seu nome
| **git config --global user.email "your-email"** | Configura seu e-mail
| **git remote add origin "https link"** | Sincroniza o repositório local com o remoto
| **git remote -v** | Verifica os arquivos enviados
| **git init** | Inicia um repositório local
| **git clone "ssh://git@github.com/[username]/[repository]** | Cria uma cópia do repositório

## Log

| **Comando** | **O que faz** |
| --- | --- |
| **git log** | Exibe o histórico dos últimos commits
| **git log -p -3** | Exibe o histórico com diff dos últimos 3 commits
| **git log --author=usuario** | Exibe histórico de um determinado autor

## Arquivos

| **Comando** | **O que faz** |
| --- | --- |
| **git add .** | Adiciona todos os arquivos ou diretórios modificados
| **git add my_app.py** | Adiciona somente o arquivo *my_app.py*
| **git add my_directory** | Adiciona somente o diretório *my_directory*
| **git add -f my_app_gitignore.py** | Adiciona arquivo que está no .gitignore
| **git rm my_archive.txt** | Remove arquivo
| **git rm -r directory** | Remove diretório
| **git commit -m "my message"** | Commit dos arquivos com mensagem