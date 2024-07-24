# Ordenação por seleção

## Arrays e listas encadeadas

|            | arrays | listas |
|:----------:|:------:|:------:|
|  leitura   |  O(1)  |  O(n)  |
|  inserção  |  O(n)  |  O(1)  |
| eliminação |  O(n)  |  O(1)  |

### Arrays

- Pode encontrar qualquer elemento instantaneamente

### Listas encadeadas

- Itens podem estar em qualquer lugar da memória
- Cada item armazena o endereço do próximo item da lista

## Inserindo algo no meio da lista

- Array &rarr; mover todos os itens que estão abaixo do endereço de inserção
- Listas &rarr; mudar o endereço para o qual o elemento anterior está apontando
- Listas encadeadas são melhores para inserção

## Deleções

- Array &rarr; tudo precisa ser movido quando um elemento é eliminado
- Listas &rarr; mudar o endereço para o qual o elemento anterior está apontando
- Listas encadeadas são melhores para deleções