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
### git branch -d NomeDaBranch - deletar uma branch

###  git cherry-pick HashCommit - pegar o commit identificado pelo hash e aplicá-lo na branch atual onde você está
### git tag -a v1.0 -m "Mensagem - adicionar uma tag para marcar o próximo commit

### Para criar um pull request no GitHub,

### Faça um fork do repositório: Vá até o repositório que você deseja contribuir e cli que no botão “Fork” no canto superior direito. Isso criará uma cópia do repositório na sua conta.
### Clone o repositório forkado: No seu repositório forkado, clique no botão “Code” e copie o link. No seu terminal, execute:
### git clone [URL_DO_REPOSITORIO]
### Substitua [URL_DO_REPOSITORIO] pelo link copiado.
### Crie uma nova branch: Navegue até o diretório do repositório clonado e crie uma nova branch para suas alterações:
### git checkout -b minha-nova-branch

### Faça as alterações necessárias: Edite os arquivos conforme necessário.
### Commit suas alterações: Adicione e commit suas alterações:
### git add .
### git commit -m "Descrição das minhas alterações"

### Envie a branch para o GitHub: Envie sua branch para o repositório forkado:
### git push origin minha-nova-branch

### Acesse o repositório: Vá para a página principal do seu repositório no GitHub.
### Abra as configurações: Clique na aba “Settings” (Configurações) abaixo do nome do repositório.
### Gerencie o acesso: Na barra lateral, clique em “Collaborators & teams” (Colaboradores e equipes).
### Adicione pessoas: Clique em “Add people” (Adicionar pessoas). Digite o nome de usuário ou o e-mail da pessoa que você deseja adicionar como revisor.
### Envie o convite: Clique em “Add NOME ao REPOSITÓRIO” para enviar o convite. A pessoa receberá um e-mail com o convite para se tornar colaborador do repositório
