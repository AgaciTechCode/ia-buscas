# Espa�o de Estados e formas de Buscas

Este projeto � um exemplo de implementa��o em Java dos m�todos de busca cega mais comuns da �rea de Intelig�ncia Artificial, que permitem resolver problemas diversos desde que modelados na forma de um Espa�os de Estados.

A solu��o do problema � dada atrav�s explora��o do espa�o, transitando entre diferentes estados poss�veis at� que seja alcan�ado um estado que atenda os objetivos estabelecidos para a busca (estado meta).


## Problemas modelados:

Dado o car�ter generalista que as buscas oferecem, escolhemos dois problemas diferentes e os modelamos como um espa�o de estados de maneira que seja poss�vel demonstrar essas t�cnicas em funcionamento.

- **Puzzle-8**

Um quebra-cabe�as combinat�rio e de deslizamento (do tipo _sliding tile puzzle_), composto por oito pe�as numeradas que s�o distribu�das no tabuleiro e organizadas em tr�s linhas e tr�s colunas.

Dentre as nove posi��es do arranjo h� sempre uma que encontra-se vazia. � poss�vel deslizar qualquer pe�a adjacente (tanto horizontalmente quanto verticalmente) para a posi��o livre, conferindo ao tabuleiro uma nova distribui��o.

As pe�as n�o podem ser retiradas do tabuleiro, tampouco podem ser movimentadas diagonalmente ou sobre uma outra pe�a. Vale ressaltar que nem sempre qualquer seq��ncia que o usu�rio possa imaginar seria poss�vel efetivamente, uma vez que  na realidade o processo de embaralhamento � feito usando as mesmas regras. Um referencial te�rico sobre como � poss�vel determinar se uma configura��o do tabuleiro � v�lidas ou n�o, pode ser encontradas [aqui] (http://www.cs.bham.ac.uk/~mdr/teaching/modules04/java2/TilesSolvability.html) 

- **Jogo da Velha (Tic-Tac-Toe)**

Consiste num jogo em que um quadriculado com nove posi��es, organizadas em tr�s linhas e tr�s colunas, � preenchido e no qual dois jogadores se confrontam fazendo suas jogadas alternadamente. Cada um deles faz a sua jogada marcando uma posi��o vazia com o seu s�mbolo.

Jogada ap�s jogada o tabuleiro vai sendo preenchido com os s�mbolos `X` e `O`. O ganhador da disputa ser� aquele que conseguir formar primeiro uma trinca de suas marcas numa disposi��o linear.
