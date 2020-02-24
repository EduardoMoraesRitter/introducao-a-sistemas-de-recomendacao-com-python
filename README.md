# introducao-a-sistemas-de-recomendacao-com-python
introdução a sistemas de recomendação utilizando Machine Learning.

usar o colab
https://colab.research.google.com/notebooks/welcome.ipynb

baixar o conjunto de dados no site do grouplens, na versão mais atualizada:
Escolha a versão ml-latest-small para trabalhar com um conjunto de dados reduzido ou ml-latest para o conjunto maior.
https://grouplens.org/datasets/movielens/latest/


Heurística de recomendação e entendendo o que é colaboração


#1º tipo de recomendação - medida de popularidade por item
quando nao tenho informação sobre o usuario novo eu recomendo os itens mais populares.
risco popular em quantidade de visulizacao mas nao nota.

o que é popular?


#2º tipo de recomendação - media da nota por item
quando nao tenho informação sobre o usuario novo, posso recomendar filmes com notas medias mais altas.

cuidado com item com pouco votos e que tem nota alta.

qual numero minimo de votos necessarios?


#3º Recomendação baseada em similaridade de genero