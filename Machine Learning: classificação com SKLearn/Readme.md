# Resumo
Nesse curso da Alura são abordados os seguintes conceitos:

- Tratamento de banco de dados utilizando o pacote pandas (renomear colunas, criar variaveis, modificar contéudos específicos);
- Conceito de atributos, treino, previsão, score e baseline no processo de classificação;
- Introdução ao algoritmos de classificação LinearSVC e SVC, da biblioteca sklearn;
- Formas de visualizar as diferentes regiões delimitadas pelos algoritmos de classificação (Usando para isso pacotes como )
- Conceito, visualização e interpretação da árvore de decisão utilizada;

# Introdução_a_Machine_Learning_Classificação_1

É feita a introdução de classificação, no caso classificamos se o objeto é um porco ou um cachorro com base em três atributos:

* tamanho do pelo
* tamanho da perna
* se ele faz o som "AuAu"

Criamos então um conjunto de dados que contenha essas informações e aplicamos um algoritmo de classificação chamado ```LinearSVC```, utilizando ele aplicamos uma previsão em outros dados, visando entender o conceito de *score*.

# Introdução_a_Machine_Learning_Classificação_2

Utilizamos nesse código um banco de dados contendo informações sobre um site que venda determinado produtos, ele apresenta quatro features (atributos):

* home
* how_it_works
* contact
* bought

O primeiro processo foi passar para o português os nomes das features, depois separamos os dados entre o treino e o teste (onde nosso y é se foi comprado ou não o produto do site), utilizando para isso uma proporção de 75% dos dados para treino e 25% para teste.
Otimizamos os passos feitos no Introdução_a_Machine_Learning_Classificação_1, utilizando funções ja presentes no sklearn para separar os diferentes tipos de dados.
Também fizemos que nosso teste e treino tivessem a mesma proporção.

# Introdução_a_Machine_Learning_Classificação_3

Essa parte do código é voltada para visualização das classificações. Através do scatter plot podemos ver como o modelo de ML separa as regiões, além disso, conseguimos utilizar um modelo mais robusto de classificador para melhorar a predição do nosso ML.

# Introdução_a_Machine_Learning_Classificação_4

Introdução ao conceito de arvore de decisão. É apresnetado como visualizar as escolhas feitas pelo classificador, bem como determinar até que camada de decisão da arvore queremos usar.
