# Mesclar Duas Listas Ligadas Ordenadas

## Descrição

Este projeto apresenta uma solução para **mesclar duas listas ligadas ordenadas** em uma única lista ligada também ordenada.  

A atividade é baseada no problema clássico **Merge Two Sorted Lists** do LeetCode.  

O objetivo é receber duas listas ligadas ordenadas e juntá-las em uma única lista, mantendo a ordem dos elementos.  
A lista resultante reutiliza os próprios nós das listas originais, apenas reorganizando seus encadeamentos.

---

## Complexidade da Solução

###  Complexidade de Tempo
- **O(n + m)**, onde:
  - `n` = tamanho da primeira lista
  - `m` = tamanho da segunda lista  
- Cada nó das duas listas é visitado **uma única vez** durante a mesclagem.

###  Complexidade de Espaço
- **O(1)**, pois:
  - A solução é **iterativa**.
  - Reutiliza os próprios nós das listas originais.
  - Apenas um nó *dummy* é utilizado, ocupando espaço constante.

