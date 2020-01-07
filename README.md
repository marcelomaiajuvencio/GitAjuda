![Optional Text](../master/img/GitLogo.png)
# GitAjuda - Lista de comandos


- git config --global user.name "Marcelo Maia Juvencio"
- git config --global user.email "mj_maia@yahoo.com.br"
- git config --global --add merge.tool kdiff3
- git config --global --add mergetool.kdiff3.path "C:\Program Files\KDiff3.exe"
- git config --global --add mergetool.kdiff3.trustExitCode false
- git config --global --list [lista configurações que são global]
- git config -l [lista configurações]
- git init
- git status
- git add nomearquivo
- git add .
- git commit -m "primeiro commit"
- git diff
- git diff --staged
- git diff --cached
- git log
- git log --oneline
- git checkout numeroDoCommit (vai para o commit número nnnnnn - ex.: git checkout df56adf)
- git checkout master
- git checkout nomearquivo (arquivo não add - volta arquivo anterior, alterado ou deletado)
- git reset --hard (volta pro último commit, arquivos criados, não add, não seram removidos, usar git clean -f)
- git clean -f (remove arquivo criado, não add)
- git push (envia para repositorio remoto)
- git pull (traz alterações do diretório remoto para o local)
- git branch (lista branch)
- git branch nomeDaBranch (cria branch)
- git checkout -b nomeDaBranch (cria branch e muda pra branch criada)
- git push -u origin nomeDaBranch (envia branch local para o repositório remoto)
- git branch -d nomeDaBranch (remove a branch local, sem alterações pendentes)
- git branch -D nomeDaBranch (remove a branch local, mesmo com alterações pendentes)
- git tag -a v1.0 -m "primeira tag" (cria tag v1.0)
- git tag (lista tag)
- git push origin v1.0 (envia tag v1.0 para o repositório remoto)
- git commit --amend -m "Nova mensagem" [corrigir mensagem do último commit antes do push]
- git mergetool [faz merge com a ferramenta configurada em merge.tool]
- git reset HEAD~1 [volta um commit na linha do tempo, perde o histórico (antes do push)]
- git cherry-pick --abort [aborta a operação de cherry-pick]
- git cherry-pick afa028d09797339340a56e94059312fb6194f5a2 [cherry-pick do commit afa028... na branch atual]
- git config --get remote.origin.url [mostra endereço remoto configurado]
- git config --unset remote.origin.url [remove configuração de endereço remoto]
- git config --add remote.origin.url http://14733096895@gitlab.prodesp.sp.gov.br/ses/cvs/sivisa.git [adiciona configuração de endereço remoto para o usuário 14733096895]

