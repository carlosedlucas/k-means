# O que é o K-Means?

 K-Means é um algoritmo de Machine Learning baseado em aprendizado não supervisionado.
 O objetivo é encontrar similaridades entre os dados e agrupá-los conforme o número de clusters (K).
 O algoritmo, de forma iterativa, atribui os pontos de dados ao grupo que representa a menor distância.
 O algoritmo gera K (ou menos) clusters.

# Possíveis Aplicações

 Agrupamento de clientes/usuários similares.
 Segmentação de mercado.
 Agrupamento de produtos semelhantes.
 Agrupamento de usuários em redes sociais.
 Agrupamento de notícias, documentos.
 Agrupamento de pacientes para identificar situações de risco.
 E diversas outras aplicações...

# Passo a passo

1. Inicializar os centroides aleatoriamente (precisamos saber o valor de k antes de começar);
2. Para cada ponto, calcular a distância para cada centroide e associar ao que estiver mais próximo;
3. Calcular a média de todos os pontos relacionados a um centroide e definir um novo centroide.

# Alguns detalhes importantes

 Como escolher o número de clusters?
– Within Cluster Sum of Squares (WCSS).
 Como calcular a distância entre os dados?
– Distância euclidiana, distância de Manhattan.
 Qual é a condição de parada ideal?
– Número de iterações, estabilidade dos clusters.
 Atenção à inicialização dos centroides.
