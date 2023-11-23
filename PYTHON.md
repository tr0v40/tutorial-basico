# Python Com Pressa


## Instalação:

### Linux
https://python.org.br/instalacao-linux/

### Windows
Baixar no site do proprio python
Avançar até finalizar ( for dummies )

## Inicio

## Virtualenv

No terminal na pasta que você irá fazer o projeto
`python -m venv venv`

Caso receba a mensagem
> Comando 'python' não encontrado, você quis dizer:

tente 
`python3 -m venv venv`


## Como começar


Direto no terminal para não perder tempo com detalhes:

Digite `python` ou `python3` e isso abrirá o shell. Os exemplos que irei detalhar a partir de agora podem ser colados direto no terminal

## Declara variaveis

| Tipo | Codigo de Exemplo | 
|------|--------|
| Int | `numero = 10 ` |
| String| `texto = eu` |
| Boolean| `verdadeiro= True` ou `falso=False`|
| float ou decimal | `moeda = 10.05` | 

Para mais: https://www.w3schools.com/python/python_variables.asp

## Listas, tuplas e Dicionarios
Por mais que minha intenção seja fazer um tutorial rápido, essa parte se faz necessário um estudo melhor.
Tuplas, Listas e dicionários são muito presentes no dia-a-dia, possuem metódos proprios e sua propria forma de serem trabalhados. Recomendo muito que procurem leiam mais sobre na W3Schools e busquem por mais explicações.
Tentando ser prático

### Tuple
São sequências imutáveis, que não podem ser alteradas após serem declaradas
`tupla = ('a', 3, 'john')`
Veja mais: https://www.w3schools.com/python/python_tuples.asp

### List
Listas são coleções de dados em uma unica variavél
`lista = ['Pera', 'Uva', 'Salda Mista 123']`

Veja mais: https://www.w3schools.com/python/python_lists.asp

### Dicts
Dicionários são coleções, similar a lista, mas com o detalhe de ser chave-valor.
dicionario = {
    "nome": "Ricardo",
    "sobrenome": "Fernandes",
    "idade": 39,
    "saldo_bancario": 0.0005,
}

Veja mais: https://www.w3schools.com/python/python_dictionaries.asp
## Operadores

| Operador | Codigo de Exemplo | Resultado no Terminal |
|----------|-------------------|-----------------------|
| == | `1 == 1` | `True`|
| != | `1 != 2` | `True` |
| > | `2 > 1` | `True`| 
| < | `1 < 2` | `True`| 

Lista completa: https://www.w3schools.com/python/python_operators.asp

## Estrutura de Seleção If

```
a = 1
b = '1'

if a == b:
    print('a é igual a b')
else:
    print('a não é igual a b')
```
Resultado:
> a não é igual a b

##### Motivo:
a é um inteiro enquanto b é um texto. No python sempre se atente á diferença de tipos

Mais sobre If e else: https://www.w3schools.com/python/python_conditions.asp


## Loop For

```
lista = ['eu', 'voce', 'ele']

for l in lista:
    print(l)

```
Resultado:
> eu
voce
ele

Mais sobre for: https://www.w3schools.com/python/python_for_loops.asp

### Observação:
Existem outras formas de loop's em python, vale a pena dar uma olhada mas no geral o for é o mais usado

Veja o While: https://www.w3schools.com/python/python_while_loops.asp