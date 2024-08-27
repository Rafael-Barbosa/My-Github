# Comandos Github

##### git add . -> adicionar na stage
##### git commit -m "Alteracoes" -> Salva no repositório local
##### git push -> sobe para o github
##### git status -> verifica o status
##### git pull -> atualiza o repositório local
##### git pull (significado) -> significa basicamente dois comandos git fetch e git merge.
##### git log -> acessa o históricos dos commits
##### git -a v1.0 -m "Versão 1.0" -> cria uma tag para marcar o próximo commit

##### git merge Nova-Branch 

##### No pull request é uma solicitação de atualização...

# Comandos Gustavo Siega 

# Comandos GitHub
#### git add . -> adicionar na stage
#### gti commit -m "alteracoes..." -> Salva no repositório local
#### git push -> sobe para o github
#### git status -> verifica o status
#### git pull -> Para atualizar a branch local com as alterações de uma branch remota (do rep. remoto direto para o local)
#### git pull (significado) -> significa basicamente dois comandos git fetch (volta do rep. remoto para rep. local) e git merge (rep. local para local).
#### git log -> acessa o histórico dos commits
#### git checkout nome-da-branch -> acessar uma branch 

#### git switch nome-da-branch -> trocar de branch
#### git branch -d nome-da-branch -> deletar uma branch
### Para resolver o conflito do código, por que é preferível utilizar o rebase em vez do merge?
#### - História mais limpa;
#### - Evita commits de merge desnecessários;
#### - Resolução de conflitos mais clara;

### Como inserir apenas um commit de uma branch para a main?
#### - Para inserir um commit específico de uma branch para a branch main, pode ser usado o comando git cherry-pick que permite aplicar as alterações de um commit específico em outra branch.

# Como fazer um Pull-Request?
## - Faça checkout em uma nova branch e faça suas alterações
####	git checkout -b minha-branch
## - Faça suas alterações no código
####	git add .
####	git commit -m "Descrição das alterações"

## -  Empurre a branch para o repositório remoto
####	git push origin minha-branch

#### - Acesse o repositório no GitHub e inicie um pull request
#### - Na interface web do GitHub, você verá uma notificação para comparar e criar um pull request logo após o push.

#### - Configure o pull request:
#### - Base Branch: Selecione a branch base (geralmente `main` ou `master`).
#### - Compare Branch: Selecione a branch com suas alterações (`minha-branch`).
#### - Adicione um título e uma descrição para o pull request.

#### - Crie o pull request clicando no botão "Create pull request"


