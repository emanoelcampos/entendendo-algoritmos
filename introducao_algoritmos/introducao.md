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

### A notaçao Big O estabelece o tempo de execução para a pior hipótese

- A notação Big O leva em conta a pior das hióteses
- É importante analisar o tempo de execução para o "caso médio"

### Alguns exemplos comuns de tempo de execução Big O

- Cinco tempos de execução, ordenados do mais rápido para o mais lento:
1. O(log n) - tempo logarítmico &rarr; pesquisa binária
2. O(n) - tempo linear &rarr; pesquisa simples
3. O(n <sup>*</sup> log n) - algoritmo rápido de ordenação &rarr; quicksort
4. O(n <sup>2</sup>) - algoritmo lento de ordenação &rarr; ordenação por seleção
5. O(n!) - algoritmo bastante lento &rarr; caixeiro-viajante

- A rapidez de um algoritmo não é medida em segundos, mas pelo crescimento do número de operações
- Em vez disso, discutimos sobre o quão rapidamente o tempo de execução de um algoritmo aumenta conforme o número de elementos aumenta.
- O tempo de execução em algoritmos é expresso na notação Big O.
- O(log n) é mais rápido do que O(n), e O(log n) ca ainda mais rápido
conforme a lista aumenta.
