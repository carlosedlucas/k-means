# O que é o K-Means?

 K-Means é um algoritmo de Machine Learning baseado em aprendizado não supervisionado.<br/>
 O objetivo é encontrar similaridades entre os dados e agrupá-los conforme o número de clusters (K).<br/>
 O algoritmo, de forma iterativa, atribui os pontos de dados ao grupo que representa a menor distância.<br/>
 O algoritmo gera K (ou menos) clusters.

# Possíveis Aplicações

 Agrupamento de clientes/usuários similares.<br/>
 Segmentação de mercado.<br/>
 Agrupamento de produtos semelhantes.<br/>
 Agrupamento de usuários em redes sociais.<br/>
 Agrupamento de notícias, documentos.<br/>
 Agrupamento de pacientes para identificar situações de risco.<br/>
 E diversas outras aplicações...

# Passo a passo

1. Inicializar os centroides aleatoriamente (precisamos saber o valor de k antes de começar);<br/>
2. Para cada ponto, calcular a distância para cada centroide e associar ao que estiver mais próximo;<br/>
3. Calcular a média de todos os pontos relacionados a um centroide e definir um novo centroide.

# Alguns detalhes importantes

 Como escolher o número de clusters?<br/>
  – Within Cluster Sum of Squares (WCSS).<br/>
 Como calcular a distância entre os dados?<br/>
  – Distância euclidiana, distância de Manhattan.<br/>
 Qual é a condição de parada ideal?<br/>
  – Número de iterações, estabilidade dos clusters.<br/>
 Atenção à inicialização dos centroides.
