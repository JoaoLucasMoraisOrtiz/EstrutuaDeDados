# Introdução
Horowitz e Sahni trazem como uma interessante definição de Ciências de Computação: ciência da computação é o estudo dos algoritmos.
Para eles, esse estudo compreende 4 áreas distintas:

* Máquinas para processar algorítmos.
* Linguágens para descrever os algoritmos.
* Fundamentos dos algoritmos.
* Análize dos algoritmos

Portanto, devemos também definir o que vem a ser um algoritmo. A definição feita pelos altores é:

**algoritmo** é um conjunto determinado de instruções que quando seguidas desempenham uma tarefa particular.

Entretanto, os autores melhoram a definição acima, descrevendo a ciência da computação como o estudo sobre os dados:
* Máquinas para manejar dados.
* Linguágens para descrever a manipulação dos dados.
* Fundamentos para dizer quais dados refinados podem ser obtidos de dados crus.
* Estrutura para representação dos dados.

Esta mudança de visão se deve pois como argumentam os autores, os algoritmos apresentam um meio para um fim: a transformação de dados.

Os algoritmos estão intimamente ligados com a forma como os dados com os quais vamos trabalhar estão estruturados.

Um exemplo para percebemos isto é o seguinte: dado uma lista de nomes e telefones:

```
lista = [[nome1, tel1], [nome2, tel2], ..., [nomeN, telN]]
```

temos a seguinte missão: ***dado um nome X, encontrar seu telefone.***

Podemos percorrer toda a lista e procurar pelo nome X. Isto pode funcionar para uma cidade pequena, mas e se for uma cidade grande?

Podemos entretanto pensar em uma solução melhor caso saibamos que os dados da lista estão em ordem alfabética, assim só vamos procurar os nomes iniciados com as letras do nome que estamos a procurar.