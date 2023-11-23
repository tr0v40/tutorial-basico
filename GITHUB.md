# Github


## Clonar um repositorio do git

`git clone https://github.com/tr0v40/tutorial-basico`

## Criar Branch
`git checkout -b NOME-DA-BRANCH`

## Trocar de branch

`git checkout BRANCH-EXISTENTE`

## Atualizar Branch/Puxar atualizações do repositorio

`git pull origin BRANCH`

## Enviar arquivos para a branch ( Commit )

##### Adicionar arquivos para commitar
`git add NOME DO ARQUIVO`
> utilize `git add . ` para adicionar todos os arquivos

##### Escrever o commit
`git commit -m "Descritivo do que fiz"`

##### Enviar para o server

`git push origin BRANC-DE-ORIGEM`
> a branch de origem é a que voce está trabalhando em seu computador

## Tricks
Quando se trabalha em equipe, existe a possibilidade de outras pessoas trabalharem no mesmo projeto. Nesse caso, mantenha sempre o seu local atualizado com o git pull antes de fazer o push para diminuir conflitos.

### Links Úteis
https://www.freecodecamp.org/news/git-cheat-sheet/

https://docs.github.com/pt/get-started/quickstart/hello-world

https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners

https://www.w3schools.com/git/ (Meu predileto, sempre procure na W3schools antes de perder tempo em outros lugares)