Spike - Git e Branches

Projeto criado para praticar o uso de Git, branches e commits semânticos.

O que são branches?

Branches são ramificações do projeto que permitem desenvolver alterações separadamente sem modificar diretamente a versão principal.

A branch principal é utilizada para manter a versão estável do projeto, enquanto branches de desenvolvimento podem ser utilizadas para criar funcionalidades, corrigir erros ou realizar testes. Depois que a alteração estiver pronta, ela pode ser integrada à branch principal através de um merge.

Conceitos praticados

Criação de branches

Listagem de branches

Alternância entre branches

Alterações em uma branch separada

Commits semânticos

Merge de branches

Commits semânticos

Commits semânticos ajudam a deixar o histórico do projeto mais organizado e facilitam a identificação do tipo de alteração realizada.

feat: usado para adicionar uma nova funcionalidade

fix: usado para corrigir um erro

docs: usado para alterações na documentação

style: usado para alterações de formatação ou estilo

refactor: usado para reorganizar o código sem alterar seu funcionamento

test: usado para adicionar ou modificar testes

Comandos utilizados

git branch - lista as branches existentes.

git branch nome-da-branch - cria uma nova branch.

git checkout nome-da-branch - muda para outra branch.

git add . - adiciona as alterações para o próximo commit.

git commit -m "mensagem" - cria um commit com uma mensagem descrevendo a alteração.

git checkout master - retorna para a branch principal utilizada no projeto.

git merge nome-da-branch - integra as alterações de outra branch à branch atual.

git push - envia os commits para o repositório remoto.

Aprendizados

Com esta Spike, aprendi que branches permitem trabalhar em alterações separadamente sem modificar diretamente a versão principal do projeto. Também aprendi que commits semânticos ajudam a organizar o histórico, deixando mais claro o que foi alterado.

Em um projeto em equipe, o uso de branches permite que diferentes pessoas trabalhem em funcionalidades ou correções separadas. Depois, as alterações podem ser integradas à branch principal através de um merge.