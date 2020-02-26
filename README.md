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
filtrar os mesmo generos que o usuario ja assistiu, sem saber a nota em si.

#4º Usuarios similares - User Based
tanto que gostaram quanto nao gostaram de filmes, calcular a distancia Euclidiana

#5º KNN identifica o vizinho mais próximo e faz uma busca de valores parecidos que estejam próximos.

---

tipos de recomendacao:
Collaborative filtering - filtragem colaborativa, usando informaçoes de todos os usuarios do sistema

Content base filtering - filtragem por conteudo, por genero e preferencia do usuario, criando perfil do usuario


tipos de abordagem:
um regresao probabilidade
classificação
hanking


caracteristicar para medir o sistema recomendado, beyond Accuracy
divercidade

lista de recomendacoes:
Populares, mais vistos
Melhores Notas
Pq vc viu tal
Pq vc deu uma nota pra tal
filmes que vc ja viu, assita novamente
continue assistindo
