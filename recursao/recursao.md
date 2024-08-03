# Recursão

- é usada para tornar a reposta mais clara.
- não há nenhum benefício quanto ao desempenho.

## Caso-base e caso recursivo

- quando escrever uma função recursiva, informar quando a recursão deve parar.
- toda função recursiva tem duas partes:

1. caso-base: quando a função não chama a si mesma
2. caso recursivo: quando a função chama a si mesma

```python
def regressiva(i):
    print(i)
    if i <= 1: # caso-base
        return None
    else: # caso recursivo
        regressiva(i-1)
```