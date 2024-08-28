# Comandos Github
# Comandos git

##### git add . -> adicionar na stage
##### git commit -m "Alteracoes" -> Salva no repositório local
##### git push -> sobe para o github
##### git status -> verifica o status
##### git pull -> atualiza o repositório local
##### git pull (significado) -> significa basicamente dois comandos git fetch e git merge.
##### git log -> acessa o históricos dos commits
##### git -a v1.0 -m "Versão 1.0" -> cria uma tag para marcar o próximo commit
![](nada.gif)

##### git merge Nova-Branch 

##### No pull request é uma solicitação de atualização...
##### git add
###### adiciona as modificações na camada de stash

##### git pull
###### puxa as informações de alguma branch para a branch atual

#### git push <repositorio> <branch>
##### envia as alterações do repositório local para o repositório remoto

###### git checkout >branch<
###### acessa uma branch

##### Como deletar uma branch?
###### git branch -d >nome-da-branch<

##### git cherry-pick
###### usado para colocar apenas um commit de uma branch em outra branch utilizando o hash do commit

##### Para resolver o conflito do código, por que é preferível utilizar o rebase em vez do merge?
###### porque mantém o histórico limpo e linear, evitando commits de merges desnecessários

##### Como inserir apenas um commit de uma branch para a main?
###### acessando a main e fazendo um cherry-pick com o hash do commit desejado

##### Como fazer um Pull-Request?
###### no repositório remoto, acesse a aba pull request, clique em new pull request, selecione a branch que será feito o merge e a branch que será usada para fazer o merge, então crie o pull request

##### Como adicionar Reviewers em seu repositório?
###### no pull request, aperte no campo reviewers e adicione um revisor