# Comandos Git
### Arquivos
* <code>git checkout origin/branch -- file</code> Revert o arquivo do jeito que era na branch escolhida
### Branch
* `git pull --all` atualiza todas a branchs locais, e adiciona as novas branchs no local
* <code>git reset --hard origin/branch</code> Tira todos os commits do stage e volta para o estado da branch no remoto
* <code>git branch -d branch</code> Apaga a branch somente local
* <code>git push origin --delete branch</code> Apaga a branch remoto
* <code>git branch <antigo_nome> <novo_novo></code> Renomear branch em qualquer lugar
* <code>git branch <novo_novo></code> Renomear branch dentro da branch
### Commits
* <code>git commit --amend</code> Ajusta informaçes do ultimo commit
* <code>git reset --soft HEAD^</code> Commitar na branch errada e não subiu
* <code>git update-index --assume-unchanged file/directory</code> Esconder um arquivo sem precisar coloca-lo no .gitignore
* <code>git config core.fileMode false</code> Ignorar arquivo do chmod

### Links úteis
* <code>Esconder um arquivo sem precisar coloca-lo no .gitignore</code> https://stackoverflow.com/questions/655243/ignore-modified-but-not-committed-files-in-git
* <code>Apagar branchs, inclusive comando para limpar branchs mergeadas</code> https://stackoverflow.com/questions/6127328/how-can-i-delete-all-git-branches-which-have-been-merged
