# task01-grupo10
Tarefa em grupo para o programa Vem Ser, Git, dia 01.

# Comandos:

## git rebase
### funcionamento
Este comando serve para alterar a base da ramificação do commit para outra, fazendo parecer como se você criou a ramificação a partir de um commit diferente.
### sintaxe
git rebase master/main
### aplicação


## git cherry pick
### funcionamento
### sintaxe
### aplicação

## git revert
### funcionamento
### sintaxe
### aplicação

## git squash
### funcionamento

É usado para combinar várias confirmações (commits) em uma única confirmação. Você pode fazer isso a qualquer momento (usando o recurso "Interactive Rebase" do Git), embora seja mais frequentemente feito ao mesclar ramificações.

Fonte: https://www.git-tower.com/learn/git/faq/git-squash/

### sintaxe

A sintaxe básica do comando "git squash" envolve o uso do comando "git rebase -i <\commit>"

Fonte: https://imasters.com.br/desenvolvimento/como-fazer-squash-de-commits-no-git/

### aplicação
Podemos fazer isso iniciando uma sessão de Rebase Interativa:

$ git rebase -i HEAD~3

Uma janela do editor será aberta onde você poderá escolher como deseja manipular a parte selecionada do seu histórico de confirmação. Tenha em mente que o Rebase Interativo permite executar muitas ações diferentes em seu histórico de confirmação; Para o nosso caso de exemplo aqui, no entanto, estamos interessados na palavra-chave de ação "squash". Se você marcar uma ou mais linhas como "squash", elas serão combinadas com a acima:
1°. "Combine 3 into 1"
2° Irá aparecer 3 "pick". O segundo e terceiro "pick" troca por "squash"

Fonte: https://www.git-tower.com/learn/git/faq/git-squash/

