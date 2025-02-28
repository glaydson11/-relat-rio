# -relatório
O Git é um controle de versão distribuído, que permite controlar as mudanças no código ao longo do tempo. As funções e os principais comandos aqui estão:

Controles do git:

Acomoda o registro das mudanças no código-fonte e a preservação de um histórico integral das alterações realizadas.

Comando: git commit -m "mensagem"

Branching e Merging:

Facilita o criar branches para se trabalhar em funcionalidades de maneira isolada e, em seguida, mesclar as alterações no branch principal.

Comandos:
Cadastrar branch: git branch nome-do-branch
Trocar branch: git checkout nome-do-branch ou git switch nome-do-branch
Mesclar (merge): git merge nome-do-branch

Staging Area (Área de Preparação):

De antemão, antes do commit, os arquivos que foram modificados podem ser colocado na área de preparação para verificar quais as mudanças vão ser salvos no commit seguinte.
Comandos:
Colocar arquivo no staging: git add nome-do-arquivo
Colocar todos os arquivos no staging: git add.
Commit:

O commit salva suas modificações no repositório local, deixando um ponto de salvamento.
Comando: git commit -m "mensagem"
Clonar repositório:

Usado para realizar cópia local do repositório remoto.
Comando: git clone url-do-repositorio
Push e Pull:

Push envia as alterações locais para o repositório remoto.
Pull busca as alterações do repositório remoto para a local.
Comandos:
Enviar alterações para o remoto: git push origin nome-do-branch
Obter alterações do remoto: git pull origin nome-do-branch
