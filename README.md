# Comandos-Git
 Manual com os principais comandos do git

* git clone 

Realiza uma cópia da versão mais recente de um projeto de determinado repositório e salva-o no computador.

> git clone <https://link-com-o-nome-do-repositório>

* git config

Configura a identidade de usuário que serão empregados em cada commit.

> $ git config -global user.name "Nome do usuário"

* git commit

Adiciona as alterações realizadas no código fonte para o repositório e permite uma mensagem explicativa sobre o que foi realizado.

> git commit -m "mensagem do commit"

* git init

Inicia um repositório, transforma uma pasta com códigos no seu computador em uma pasta monitorada pelo git ou cria um repositório novo.

> git init <O nome do seu repositório>

* git add

Inclui as alterações do(s) arquivo(s) no próximo commit.

> git add<arquivo> (Para um arquivo)
> git add* (para todos os arquivos)

* git pull 

Obtem as atualizações de um repositório remoto e aplica as alterações mais recentes em seu espaço mais recentes em seu espaço de trabalho local.

> git pull <repositorio-remoto>

* git rm

Remove arquivos da sua pasta.

> rm<nome_do_arquivo>

* git checkout -b

Um branch é um caminho independente de desenvolvimento, uma alternativa.

> git branch (lista todas as ramificações)
> git chekout -b <nome_do_branch> (cria um branch com o nome especificado)
> git branch -d <nome_do_branch> (deleta o branch com o nome especificado)

* git merge

Integra as mudanças de dois branches diferentes em um único branch.

> git merge <nome_do_branch>

* git push

É usado para enviar o conteúdo do repositório local para um repositório remoto.

* git log --diff-filter=D --summary

É usado para restaurar o arquivo.

* git revert commit

Ele faz o rollback do commit informado, como um ctrl+z.

> git revert "nome do commit"

* git reset --hard commit

Retorna para um estado anterior, porém diferente do revert, ele não gera commit, ele desfaz tudo.

> git reset --hard "nome do commit"
