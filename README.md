# task01-grupo10
Tarefa em grupo para o programa Vem Ser, Git, dia 01.

# Comandos:

## git rebase
### funcionamento
Este comando serve para alterar a base da ramificação do commit para outra, fazendo parecer como se você criou a ramificação a partir de um commit diferente.
### sintaxe
git rebase master/main
### aplicação
TESTE


## git cherry pick
O cherry-pick é um comando poderoso e conveniente que é muito útil em alguns cenários. O git cherry-pick é um comando que permite que commits de Git arbitrários sejam coletados como referência e anexados ao HEAD de trabalho atual. Ele não deve ser utilizado no lugar do git merge ou do git rebase. O comando git log é necessário para ajudar a encontrar commits para fazer o cherry-pick.

### funcionamento
"Cherry picking" é o ato de selecionar um commit da ramificação e fazer a aplicação a outra. O git cherry-pick pode ser útil para desfazer alterações. Por exemplo, digamos que o commit seja feito sem querer na ramificação errada. É possível alterar para a ramificação correta e fazer o cherry-pick do commit para onde ele deveria pertencer.

### sintaxe

git cherry-pick X

Onde X é uma referência de um commit

O git cherry pick pode também receber algumas opções de execução -edit --no-commit --signoff
O cherry-pick do git também aceita a entrada opcional de resolução de conflito de mesclagem, que inclui as opções: --abort --continue e --quit
### aplicação
O git cherry pick é um que permite ao usuário selecionar commits específicos para trazer ao branch desejado.
Quando trabalhamos em equipes em um projeto, é comum haver momentos em que mais de um desenvolvedor trabalha no mesmo código.
Por exemplo, quando o desenvolvedor back-end cria uma estrutura de dados que o front-end também vai utilizar. O desenvolvedor front-end pode usar o git cherry pick para continuar trabalhando no commit que tem o banco de dados, mas da sua maneira.

fonte<https://www.atlassian.com/br/git/tutorials/cherry-pick>

## git revert

### Funcionalidade: Dado um ou mais commits existentes, reverte as alterações introduzidas pelos patches relacionados e registra alguns novos commits que os registrem. Isso requer que sua árvore de trabalho esteja limpa (sem modificações do commit HEAD).

### sintaxe: git revert [--[no-]edit] [-n] [-m <número-pai>] [-s] [-S[<keyid>]] <commit>… git revert (--continue | - -pular | --abortar | --quit)

### aplicação:  O git revert é usado para registrar alguns novos commits e reverter o efeito de alguns commits anteriores (geralmente apenas um com falha).Fonte:<https://git-scm.com/docs/git-revert>

## git squash
### funcionamento
### sintaxe
### aplicação


