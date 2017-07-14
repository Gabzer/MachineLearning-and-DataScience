Machine-Learning-and-Data-Science-with-Python course
=============================

**Computational Intelligence** is a smart behavior automation.
**Artificial intelligence** an area of computational intelligence.
**Turing Test** for an AI to pass, the person with whom she speaks can not discover that she is a machine.
**Big Data** is a deluge of data.

Machine Learning 
-------------------
Is the ability of a machine to create, from an acquired experience, _a hypothesis_ capable of solving a problem.

Two things to watch:

1.Measure of performance - percentage of correctly identified data.

2.Experience - what is pointed out by the user/programmer.

Attribute Types
-------------------
meta é um dado de saída de um conjunto de dados.

_atributos quantitativos discretos_ = número finito ou infinito contável de valores.

_atributos quantitativos contínuos_ = podem assumir um número infinito de valores. Resultado de medidas. Números reais.

Attribute Scale
-------------------
define operações que podem ser realizados sobre os valores dos atributos.

podem ser de escalas:
* qualitativo       

                    - nominais     ->  valores são diferentes e carregam, a menor quantidade de informação possível.

                    - ordinais     ->  grandes, pequenos, médias; hierarquia.
* quantitativos     

                    - intervalores ->  os números variam em um intervalo.

                    - racionais    ->  carrega mais informação, tem o significado absoluto.

Types of Learning
-------------------

1. Previsão: encotrar uma função que possa ser utilizada para prever um valor para novos dados. Objetos com entrada e saída.
2. Descrição: explorar ou descrever um conjunto de dados. Objetos não possuem uma saída associada.

Learning Hierarchy
-------------------
* indutivo

    >supervisionado = preditivo -> tem um supervisor externo => conhecer a saída desejada de cada exemplo -> regressão = rótulos contínuos

                                                                                                           -> classificação = rótulos discretos
                                                                                            
    >não-supervisionado = descritivo -> algoritmos exploram regularidades dos dados -> agrupamento = de acordo com sua similaridade

                                                                                     -> sumarização = encontrar descrição compacta para dados

                                                                                     -> associação = encontrar padrões frequentes de associação entre atributos

Supervised Learning
-------------------
entrada (_atributos_) e saída (_classe/rótulo_)

o programa é "treinado" sobre um conjunto de dados pré-definido. Treinar um classificador para analise de sentimentos.

**objetivo** = a partir do passado, prever o que se segue.

**classificação** = subcategoria => consiste em atribuir um rótulo para uma nova amostra.

**regressão** = subcategoria => quando o valor tem o espectro contínuo, então podemos usá-lo.


Non-Supervised Learning
-------------------
não rotulados mas com padrões.

**objetivo** = desvendar a organização dos padrões existentes nos dados através de agrupamentos -> clusters = é possível descobrir similaridades e diferenças

agrupar objetos em classes de objetos similares -> K-Means = algoritmo de agrupamento.


Learning Techniques
-------------------

1. aprendizado semi-supervisionado = utiliza dados rotulados e não rotulados para treinamento.
2. aprendizado por reforço = o algoritmo descobre por tentativa e erro quais ações geram as maiores recompensas.
        2.1. _componentes_ = agente, ambiente e ações.
        2.2. _objetivo_ = é que o agente escolha ações que maximizem a recompensa esperada ao longo do tempo. 

