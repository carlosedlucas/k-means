# Para entender este repositório, siga as etapas abaixo:

1) Primeiro clone, bifurque ou baixe este repositório ou você pode executar k-meanspratica.ipynb no Google Colab.

2) O conjunto de dados usado são números aleatórios.

3) Agora, você pode executar o arquivo k-meanspratica.ipynb localmente ou online.

4) Usei bibliotecas Scikit Learn inbuild de agrupamento K-Means.

5) Todos, os usos e instruções são escritos no próprio arquivo de código.

Nota - Para qualquer sugestão ou recomendação, você pode me enviar uma solicitação de pull.


# O que é o K-Means?

* K-Means é um algoritmo de Machine Learning baseado em aprendizado não supervisionado.<br/>
* O objetivo é encontrar similaridades entre os dados e agrupá-los conforme o número de clusters (K).<br/>
* O algoritmo, de forma iterativa, atribui os pontos de dados ao grupo que representa a menor distância.<br/>
* O algoritmo gera K (ou menos) clusters.

# Possíveis Aplicações

* Agrupamento de clientes/usuários similares.<br/>
* Segmentação de mercado.<br/>
* Agrupamento de produtos semelhantes.<br/>
* Agrupamento de usuários em redes sociais.<br/>
* Agrupamento de notícias, documentos.<br/>
* Agrupamento de pacientes para identificar situações de risco.<br/>
* E diversas outras aplicações...

# Passo a passo

1. Inicializar os centroides aleatoriamente (precisamos saber o valor de k antes de começar);<br/>
2. Para cada ponto, calcular a distância para cada centroide e associar ao que estiver mais próximo;<br/>
3. Calcular a média de todos os pontos relacionados a um centroide e definir um novo centroide.

# Alguns detalhes importantes

* Como escolher o número de clusters?<br/>
– Within Cluster Sum of Squares (WCSS).<br/>
* Como calcular a distância entre os dados?<br/>
– Distância euclidiana, distância de Manhattan.<br/>
* Qual é a condição de parada ideal?<br/>
– Número de iterações, estabilidade dos clusters.<br/>
* Atenção à inicialização dos centroides.

