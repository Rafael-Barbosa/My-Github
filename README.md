### git config -- global user.name"SeuNome" --: colocar seu nome no Git

### git config -- global user.email"SeuEmail" --> colocar seu email no Git

### git init --> Cria dentro da pasta atual uma nova pasta .git

### git status --> verificar o status do commit

### git log --> acessa o historico dos commit, verificar quantos commits você tem, mostra a lista de todos os commits feitos

### git cat NomeDoArquivo --> pega um arquivo e mostra o que tem dentro dele, sem precisar abri-lo

### git clone LinkDoRepositório --> clonar repositório diretamente do GitHub

### git add . -- > adicionar o arquivo para a staging area, adicionar o commit

### git commit -m "NomeDoCommit" --> salvar no repositório local

### git reset --> remove o commit da área de staging (volta o commit)

### git diff CodigoDoCommitX CodigoDoCommitY --> diferenciar dois commits

### git push --> adicionar no git hub, empurrar os arquivos para o GitHub

### git pull --> sincronizar os repositórios e realizar o download das alterações no repositório local

### git stash--> manda um commit/arquivo para o stash (stash é como se fosse uma gaveta onde voce esconde um arquivo)

### git stash apply stash{0} --> serve para levar do stash para o local, o 0 é o numero do commit, o stash é uma pilha ou seja o 0 é a posição na pilha, o stash funciona como uma pilha, ou seja o primeiro a ir para o stash é o numero 0

### git stash list --> vai fazer uma lista dos commits do stasb que voce tem

### git fetch --> repositorio remoto para repositorio local

### git merge --> repositorio local para local

### git restore --staged --> stage para local

### git -a v1.0 -m "Versão 1.0" --> Cria uma tag para marcar o proximo commit

### git checkout -b nome_Da_branch --> para criar uma branch (branch é como se fosse uma ramifiação, para que mais de 1 pessoa possa mexer no mesmo projeto ao mesmo tempo, sem que tenha conflitos, por isto voce cria uma branch da main.)

### git checkout nome_da_branch --> mudar de branch
