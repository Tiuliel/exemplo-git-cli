# Exemplos de operações básicas para git via CLI

## Comandos de uso geral da CLI

- Criar pasta: mkdir nomepasta
- Listar conteúdo: dir
- Limpar tela: cls
- Entar na pasta: cd nomepasta

## Comandos principais do git


`git config user.name "Seu nome como quiser"` e 
`git config user.email "Seu email"`
Mudar usuário e e-mail de forma global.

**Obs:** normalmente estes dados estão relacionados ao usuário/conta do site GitHub

`git init`

inicializar um repositório (executado dentro da pasta)

`git branch nome-branch-atual novo-nome-para-branch`

renomear branches.

Para alterar a branch de **master** para **main** (novo padrão), usaríamos: `git branch master main`

`git status`

verificar o status do repósitorio.

`git add nomearquivo` ou `git add .`

adicionar (tornar arquivo rastreável) ao monitoramento do git.

`git commit -m "Texto da mensagem sobre esta alteração"`

fazer commit das alterações (salvar no histórico).

`git remote add origin endereço-do-repositório.git`

adicionar/conectar o repositório remoto ao local.

`git push origin main`

Enviar as mudanças para GitHub (PUSH)

`git pull origin main`

Pegar/Obter as mudanças do repositório online GitHub (PULL).

`git clone endereço-do-repositório.git`

copiando/baixando um repositório para a máquina remota.

