Pandas
===================

análise de dados -> pandas é A biblioteca para isso. Inspirada no R.

**Dados tabulados** = 2D (o mais utilizado em Data Science)

**serie** = dados de 1 dimensão

**DataFrame** = tabela com linhas e colunas.


db.py
-------------------

biblioteca que facilita a interação com vários tipos de bancos de dados, fazendo possível a criação de DataFrames com os mesmos.

Installation = `pip install db.py`


Séries Temporais
-------------------

é um DataSet que contém certas informações sobre determinado momento do tempo (ex.:log que tem datas como começo/nome de cada linha).


Pivot Tables
-------------------

é uma forma de sumarizar as informações contidas nos dados sobre alguns critérios (=sumário).


MatPlotLib
-------------------

plotar dados.

salvar um gráfico:

```python
fig = plt.figure()
plt.plot(x, np.sin(x), 'r--')
fig.savefig('sin-01.png')
```

