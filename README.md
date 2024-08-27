# Comandos Github

##### git add . > adicionar na stage area

##### git commit -m "msg" > salva no repositório local

##### git push  sobe para o git

##### git status > verifica o status

##### git pull > atualiza o repositorio local

##### git pull (significado) > significa basicamnete dois git fetch e git merge

##### git fetch > coamndo primario usado para baixar conteudo de um repositorio remoto

##### git merge > permite que você pegue as linhas de desenvolvimento independentes criadas pelo git branch e as integre em uma ramificação única

##### git log > acessa o historico de commits

##### stash aply > Este comando pega o stash mais alto na pilha e o aplica ao repositório stash@{0}

##### 

## Perguntas

##### 11- Acesse o histórico da sua branch atual (main): > git log

##### 12- Crie uma tag do seu projeto: > git tag <nome>

##### 13- Inclua um título no index.html (ou outra modificação), crie uma branch com o nome feature inclusão-do-título. 

##### 14- Como acessar uma branch? > git checkout "nome da branch"

##### 15- Como trocar de branch? > git checkout "nome"

##### 15- Como deletar uma branch? > git branch -d "nome"

##### 16- Entre na main branch e faça um merge da branch desejada para integrar ao main. > git merge "nome"

##### 17- Para resolver o conflito do código, por que é preferível utilizar o rebase em vez do merge? > O rebase é preferível porque mantém um histórico de commits mais limpo e linear, evitando "merge commits" que podem poluir o histórico e dificultar a leitura.

##### 18- Como inserir apenas um commit de uma branch para a main? > git cherry-pick "hashdocommit"

##### 19- Resete seu código até algum momento utilizando como parâmetro o hash da commit: > it reset --hard "hashdocommit"

##### 20- Crie um arquivo tipo txt e guarde em sua stash: > git add "arquivo.txt" e depois git stash

##### 21- Como fazer um Pull-Request? > vc vai na branch, ai va no pull request ai clica em new pull request, escolhe a versão., coloca uma descrição e o membros do projeto e comfima 

##### 22- Como adicionar Reviewers em seu repositório:> em open Pull request va em reviewers e aperte a emgrenagem, logo após insira o nome de,es que deseja adicionar


