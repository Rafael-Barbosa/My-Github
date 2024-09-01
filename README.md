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

# O Git Bash é um aplicativo que oferece funcionalidades de linha de comando para Git, além de emular o shell bash. Com alguns comandos simples, você pode criar novos repositórios, atualizar os existentes e muito mais. A seguir, apresento alguns dos comandos mais comuns que podem ser úteis no dia a dia:

# Configuração Inicial

# bash
# opiar código
# git config --global user.name "Seu Nome"
# git config --global user.email "seuemail@exemplo.com"
# Esses comandos permitem configurar as suas informações de usuário no Git.

# Iniciando um Repositório

# bash
# Copiar código
# git init
# Este comando é utilizado para iniciar um novo repositório Git.

# Clonando um Repositório

# bash
# Copiar código
# git clone /caminho/para/o/repositório
# Esse comando serve para obter uma cópia de um repositório Git existente.

# Adicionando e Confirmando Alterações

# bash
# Copiar código
# git add
# git commit -m "Mensagem do commit"
# O git add adiciona um arquivo ao índice, enquanto o git commit é usado para registrar as alterações no repositório.

# Enviando Alterações

# bash
# Copiar código
# git push origin master
# Esse comando envia as alterações feitas localmente para o repositório remoto.

# Atualizando o Repositório Local

# bash
# Copiar código
# git pull
# Usado para buscar e mesclar mudanças do repositório remoto para o local.

# Verificando o Status do Repositório

# bash
# Copiar código
# git status
# este comando mostra o estado atual do repositório.

# riando uma nova Branch

# bash
# Copiar código
# git checkout -b "Nova-Branch"
# git merge Nova-Branch
# Utilizado para criar uma nova branch e fazer o merge dela
