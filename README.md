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

## Criar um Repositório no GitHub ##
# git init

## copiar o  repositório no meu computador e repetir tbm com o do professor ##
# git clone <repositório>

### Copiar o conteúdo de head-spinning-GSAP para o meu repositório ##
# cp -r head-spinning-GSAP/* MeuRepositorio/
# cd MeuRepositorio/
# git add .
# git commit -m "Adicionando conteúdo do head-spinning-GSAP"

## Incluir e subir a imagem que foi modificada ##
# git add .
# git commit -m "Alteração da imagem no index.html"
# git push origin main

## Criar/salvar uma chave SSH ##
# ssh-keygen -t rsa -b 4096 -C <"meuemaildogithub@gmail.com">
# git config --global credential.helper cache

## Atualizar o repositório local com as mudanças feitas no GitHub ##
# git pull --  atualizar o repositório local com as alterações mais recentes do repositório remoto

## Ver meu histórico ##
# git log

## criar uma tag do projeto##
# git tag -a v1.0 -m "Versão 1.0 do projeto"
# git push origin v1.0

## Dar um titulo para o index.html e criar uma branch com esse nome ##
# git checkout -b feature/<titulo>

## Acessar/trocar a branch ##
# git checkout <branch>

## deletar a branch ##
# git branch -d <branch>

## Entrar na main branch e fazer um merge da branch##
# git checkout main
# git merge feature/<titulo>

## Resetar o meu código até um momento específico utilizando o hash do commit##
# git reset --hard commit-hash

## Crie um arquivo .txt e guarde-o em sua stash ##
# git stash push -m "arquivo txt"

## no repositório no GitHub devo selecionar a minha branch e clicar em "Compare & pull request"
## Depois clicar em "Create pull request"

## Para adicionar Reviewers tem que abrir o Pull Request, clicar em "Reviewers" e selecionar os colaboradores desejados