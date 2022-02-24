# Otimizacao_de_hiperparametros_em_Machine_Learning
Contem algoritmos de otimização como GridSearch, RandomSearch dentre outros.


O que é  o GridSearch (pesquisa de grade)?
A pesquisa em grade é uma técnica de ajuste que tenta calcular os valores ótimos dos hiperparâmetros. 
É uma busca exaustiva que é realizada nos valores de parâmetros específicos de um modelo. 
O modelo também é conhecido como estimador.

1. Instale a biblioteca sklearn
2.Importar biblioteca sklearn
3. Importe seu modelo
4.Crie uma lista de dicionário de hiperparâmetros
Este é o passo chave.
Vamos considerar que queremos encontrar os valores ótimos de hiperparâmetros para:
kernal: Queremos que o modelo treine a si mesmo nos seguintes kernels e nos dê o melhor valor entre os valores lineares, poli, rbf, sigmoid e pré-computados
C: queremos que o modelo tente os seguintes valores de C: [1,2,3,300,500]
max_iter: queremos que o modelo use os seguintes valores de max_iter: [1000,100000] e nos dê o melhor valor.
Podemos criar o dicionário necessário:
5. Instantiate GridSearchCV and pass in the parameters
6. Finally, print out the best parameters:
