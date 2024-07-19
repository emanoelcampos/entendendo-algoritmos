# Introdução a algoritmos

## Pesquisa Binária

- Entrada é uma lista ordenada de elementos
- Se o elemento que buscamos estiver na lista, sua localização é retornada
- Caso não exista, retorna `None`
- Precisa de log<sub>2</sub>n pra retorna o valor

### Tempo de execução

- Pesquisa simples = tempo linear &rarr; `O(n)`
- Pesquisa binária = tempo logarítmico &rarr; `O(log)n`

## Notação Big O

- Notação especial que diz o quão rápido é um algoritmo

### Tempo de execução dos algoritmos cresce a taxas diferentes

- Não basta saber quanto tempo um algoritmo leva para ser executado
- Precisa saber se o tempo de execução aumenta conforme a lista aumenta


| elementos  | pesquisa simples | pesquisa binária |
|:----------:|:----------------:|:----------------:|
|    100     |      100ms       |       7ms        |
|   10000    |       10s        |       14ms       |
| 1000000000 |     11 dias      |       32ms       |

- Uma lista de tamanho *n* &rarr; tempo de execução é `O(n)` - **sem os segundos**
- A notação Big O:
  - não fornece o tempo em segundos
  - permite que você compare o número de operações
  - informa o quão rapidamente um algoritmo cresce