# KMeans
Prática Padrão das petalas e sepálas.

## O que é ?
KMeans é um **aprendizado não supervisionado** que é utilizado para:
- segmentação do mercado;
- agrupamento de clientes em potencial
- agrupamento de caracteristicas de clientes 
- produtos mais similares
- agrupar perfis de clientes

## Versões:
Kmeans - versão com comentários sobre as bibliotecas e métodos usados. Aconselhado para estudantes.<br>
KMeans_ClearVersion - versão só com a aplicação.

## Nesta prática utilizamos:

Parametros:<br>
**n_clusters**
**random_state** :determina um numero de randomico para gerar o centroide

Atributos:<br>
**cluster_centers_** : coordenadas do centro do cluster<br>
**inertia_**: a soma do quadrado das distancias das amostras mais pertas dos centroides do cluster

Metodos:<br>
**.fit()**: calcula os clusters<br>
**.fit_prediction()**: calcula os centróides

## Processo
1. Importação das bibliotecas Pandas, Numpy, Plotly Express e Graph Objects, Sklearn Preprocessing (StandardScaler) e Sklearn Cluster (KMeans)
2. Informar a base de dados
3. Conhecendo a base de dados (head, shape, describe, unique)
4. Separando a prática em duas fase: petalas e sepalas
5. Realizar agrupamento pelas petalas
6. Normalizando os dados usando StandardScaler e ajustá-los e transformá-los (.fit_transform)
7. Calculando o numero de clusters
8. Criando gráfico do cotovelo 
9. Gráfico de agrupamento
10. Passos 5 a 9 repetidos, agora para as sepalas.

## Documentação
https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html <br>
https://scikit-learn.org/dev/modules/clustering.html#k-means

## Final
Agradecimento ao Prof Leandro Lessa pelo aprendizado.
Repositório original: https://github.com/ProfLeandroLessa/FDA-material-video-aulas

Aulas ofertadas pela IGTI (atual XP Educação) em parceria com o Banco Pan

Alterações e acrescimos: Lidiane Aureliano
https://github.com/laurelianox
