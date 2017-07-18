NumPy
===================

É pacote para a computação científica para python. Possibilidade de construção de objetos arrays n dimensional. Baseado em C = desempenho superior. Tem várias funções eficientes para a manipulação de objetos, que são matemáticas.

Comparative example of the efficiency of NumPy:

```python
soma = 0
for i in range(1, 100000001):
        soma += i
```

e

```python
import numpy as np
np.arange(1, 100000001).sun()
```

matPlotLib -> plota dados em 2D

saber dimensões de uma matriz: matriz.ndim

axes de uma matriz: axis = 0 ou 1