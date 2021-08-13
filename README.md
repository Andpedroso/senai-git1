
COMANDOS GIT

# git init – cria o repositório no diretório selecionado.
# ls – mostra conteúdo.
# git status – mostra o estado em que estão os arquivos, caso rastreados ou não.
# .gitignore – arquivo criado para adicionar arquivos para serem ignorados.
# git config user.name “” – adiciona nome do desenvolvedor. Caso --global não é apenas local.
# git config user.email “” – adiciona email do desenvolvedor.
# git add nomedoarquivo. – adiciona o arquivo para o monitoramento. Tracked.
# git commit -m “” – finaliza arquivos depois de adicionados para o monitoramento. Snapshot.
# modified – arquivo no monitoramento que é modificado e salvo. git add para atualizar.
# git log – mostra todo o histórico das ações no git. Mostra usuário e id.
# git config core.pager cat – adiciona configuração no repositório para log.
# git log -número – os últimos mostrados na numeração.
# git log --oneline – informações de log em uma linha. Id e mensagem.
# git log --before “XXXX-XX-XX” – mostra log anterior a data escolhida.
# git log --after “XXXX-XX-XX” – mostra log após a data escolhida.
# git log --since=“n days ago” – mostra log de dias atrás.
# q – sai do log.
# git checkout id – sete primeiros dígitos do commit. Vai para o commit do id.
# git checkout master – volta para a cabeça.
# git show – mostra informações do último commit.
# git remote -v – apresenta o nome do repositório.
# git push origin – manda para o repositório original.
# git branch -a – mostra todas as branchs incluindo remotas.
# git fetch – recolhe as branchs.
# gti push origin nomedabranch – encaminha para o repostitório remoto a branch adicionada.
# git push origin nomedoarquivo – encaminha o arquivo para o repositório.
# git mv nomedoarquivo novonome – renomear arquivos.
# git rm nomedoarquivo – remove arquivo do repositório. Pode ser commitado.
# git diff --staged – compara arquivo em staged com a última versão do commit.
# git diff id – compara o do id com o último commit.
# git diff id..id – compara todos os ids entre os colocados, dó último para o mais novo.
# git commit --amend -m “” – corrigindo mensagem. Adiciona arquivo no último commit.
# git restore --staged nomedoarquivo – retira arquivo do add, monitoramento.
# git checkout nomedoarquivo – retorna para a versão anterior do arquivo modificado.
# git reset HEAD --hard – sobrescreve todos os arquivos retirando últimas alterações.
# git reset HEAD^ --hard – volta para o ultimo commit.
# git branch – exibe todos os branchs.
# git branch nomedobranch – cria um novo branch.
# git checkout nomedobranch – muda para o outro branch.
# git branch -d nomedobranch – deleta o branch. D para confirmar.
# git merge nomedobrach – une o branch com o principal.
# git checkout -b novobranch – cria e muda para novo branch.
# git rebase nomedobranch – une arquivos com o branch main.
# pwd – mostra o home.
# git clone home – clona o endereço home de um repositório para diretório de colaborador.
# ls -la – mostra os arquivos ocultos.
# touch nomedoarquivo – cria o novo arquivo no novo diretório.
# git push – encaminha o diretório para o repositório original. Para Bare-repository.
# git fetch – baixa os arquivos para o diretório trabalhado.
# git rebase – o novo arquivo é adicionado.
# git pull – encaminha os arquivos para o repositório remoto.
# git init --bare – cria repositório vazio.
# git clone endereçohome-bare . – clona repositório vazio.
# cat config – mostra informações de configuração do repositório.
# cd nomedapasta – acessa a pasta.
# git tag nomedatag (ex v1.0) – cria uma tag que pode ser o projeto final.
# git tag – mostra as tags existentes no repositório.
# git push origin nomedatag – no repostiório da tag encaminha a tag para repositório remoto.
# git checkout nomedatag – muda para a tag escolhida.
# git switch -c nomedabrachtag – vai para o branch da tag. Merge e push origin para nova tag.
# git remote add origin endereçodorepositórioremoto – para adicionar repositório github.
# git push -u origin nomedobranch – adiciona repositório local para remoto.
# git config credential.helper store – adiciona nova credencial para o projeto para push.
# git clone endereçodoprojetogithub – clona o projeto para o novo repositório.
# git pull origin master – atualizar projeto a partir do branch principal.
# git checkout -- . – volta os arquivos ao estado original.
# gti checkout – nomedoarquivo – volta o arquivo a versão antes da modificação.l
# git add . – adiciona todos os arquivos ao staged.
# git checkout HEAD -- . – volta todos os arquivos ao estágio anterior.
# git revert id – cria novo commit removendo o que foi modificado no arquivo.
# git push -u origin master – adiciona arquivos para o branch principal.
# git reset – remove o commit.
# git reset HEAD~-numeração – numeração de quantos commits devem ser resetados.
