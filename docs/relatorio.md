# Relatório Final - Página Colaborativa de Receitas

## Integrantes do Grupo
- Nome do projeto: Trabalho-git
- Integrantes: Duarte Valerio 2024354
- Repositório: [https://github.com/Duartevalerio/Trabalho-git.git]

## Branches Criadas
Foram criadas branches específicas para cada funcionalidade para manter a organização e evitar mexer diretamente no código principal (main).

feature/Bolo-Chocolate: Criada para adicionar a receita de bolo de chocolate.

feature/Pudim: Criada para adicionar a receita de pudim.

feature/Gelado: Criada para adicionar a receita de gelado.

main: Branch principal onde o código final é unificado.

Processo de Merge: Os merges foram realizados através de Pull Requests no GitHub, garantindo que o código pudesse ser revisto pelos colegas antes de ser integrado.

## Histórico de Commits
Procurámos utilizar mensagens claras e objetivas seguindo as boas práticas. Exemplos utilizados no projeto:

"Adiciona receita de bolo de cenoura"

"Adiciona receita de Pudim"

"Adiciona receita de Gelado"

## Issues Criadas
Utilizámos as Issues para gerir o trabalho pendente e atribuir tarefas. As principais issues criadas foram:

Criar receita de Bolo de Chocolate (Responsável: Duarte)

Criar receita de Pudim (Responsável: Duarte)

Criar receita de Gelado (Responsável: Duarte)

Completar relatório em docs/relatorio.md (Tarefa de documentação)

Revisar e aprovar Pull Requests (Tarefa de gestão)

## Pull Requests
Para cada receita finalizada numa branch, foi aberto um Pull Request (PR):

O código foi enviado para o GitHub (git push).

O PR foi criado com título e descrição das alterações.

Foi solicitado um Reviewer (colega de grupo) para aprovar.

Após a aprovação, o código foi fundido (merge) na branch main.

## Conflitos e Resoluções
Se não tiveste erros de conflito (quando duas pessoas mexem na mesma linha), podes escrever:

Não houve conflitos graves de código, pois cada membro trabalhou em ficheiros separados (receitas diferentes).

Tivemos apenas um erro inicial ao tentar fazer push de uma branch que não existia localmente, resolvido criando a branch corretamente com git checkout -b.

## Dificuldades Enfrentadas
Nomes das Branches: Inicialmente houve uma tentativa de fazer push para uma branch (feature/Bolo-Chocolate) antes de ela ser criada localmente, o que gerou o erro cannot be resolved to branch.

Fluxo do Git: Entender a sequência correta de comandos (add -> commit -> push) exigiu prática no início.

## Principais Comandos Git Utilizados
git clone [url]: Para baixar o repositório para o computador local.

git checkout -b [nome-branch]: Para criar e mudar para uma nova branch de trabalho.

git status: Para verificar em que branch estávamos e o estado dos ficheiros.

git add .: Para preparar todos os ficheiros modificados.

git commit -m "mensagem": Para guardar as alterações no histórico.

git push origin [nome-branch]: Para enviar a branch e o código para o GitHub.

## Conclusão
Com este projeto, aprendemos a importância de trabalhar com branches para não afetar o código principal. Entendemos também que o GitHub é essencial para a colaboração, usando Pull Requests e Issues para organizar quem faz o quê, simulando um ambiente real de desenvolvimento de software.
