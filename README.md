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

#### git config --global user.name"SeuNome" - configurar seu nome no Git;
#### git config --global user.email"SeuEmail" - configurar seu email no Git;
#### git init - criar dentro da pasta atual uma nova pasta com a extensão .git;
#### git status - verificar o status do commit;
#### git log - acessar o histórico dos commits (verificar quantos commits você tem, mostra a lista de todos os commits feitos);
#### git cat NomeDoArquivo - pegar um arquivo e mostrar o que tem dentro dele, sem precisar abrir ele;
#### git clone LinkDoRepositório - clonar um repositório diretamente do GitHub;
#### git add . - adicionar os arquivos para a stage area;
#### git commit -m "NomeDoCommit" - salvar os arquivos no repositório local;
#### git restore . - remover o commit da stage area (voltar o commit);
#### git diff CodigoDoCommitX CodigoDoCommitY - diferenciar dois commits (verificar o que há de diferente);
#### git push - enviar os arquivos para o GitHub (salvar os arquivos no repositório remoto);
#### git pull - realizar o download das alterações no repositório local (significa basicamente dois comandos, git fetch e git merge);
#### git pull --rebase -- deixar o histórico limpo;
#### git fetch - enviar os arquivos do repositório remoto, para o repositório local;
#### git merge - enviar os arquivos do repositório local, para o local;
#### git merge NomeDaBranch - juntar duas branchs;
#### git stash - enviar os arquivos do local, para o stash;
#### git stash apply stash{0} - enviar os arquivos da stash, para o local;
#### git stash list - listar os arquivos que estão na stash;
#### git tag -a v1.0 -m "Mensagem" - adicionar uma tag para marcar o próximo commit;
#### git checkout -b NomeDaBranch - criar uma nova branch;
#### git checkout NomeDaBranch - alterar de branch;
#### git branch -d NomeDaBranch - deletar uma branch;
#### Para fazer um pull request - git checkout -b minha-nova-featureFaça as alterações necessárias no código Adicione as mudanças ao stage: git add . Faça um commit das suas mudanças: git commit -m "Descrição das mudanças" Envie as alterações para o seu repositório remoto: git push origin minha-nova-feature Crie um Pull Request no GitHub: Vá até o seu repositório no GitHub. Clique em "Compare & pull request". Preencha os detalhes e crie o Pull Request.
#### fazer uma reviews - Abra o Pull Request que você criou. No lado direito da página, procure a seção "Reviewers".Clique em "Reviewers" e selecione os membros que você quer adicionar como revisores. Os revisores receberão uma notificação para revisar seu Pull Request.


