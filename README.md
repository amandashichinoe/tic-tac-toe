# TIC TAC TOE :x::o:

Repositório contendo o código desenvolvido no "Tutorial: Introdução ao React", disponível em: https://pt-br.reactjs.org/tutorial/tutorial.html#what-are-we-building.
A partir deste tutorial foi possível criar um jogo interativo de jogo-da-velha com React, com o objetivo de criar um entendimento sobre o React e a sua sintaxe.

Este jogo-da-velha:
- Indica quando um dos jogadores ganhou o jogo;
- Armazena um histórico do jogo à medida que ele avança;
- Permite que os jogadores revisem o histórico do jogo e vejam versões anteriores do tabuleiro.

Você pode visualizar o código-fonte acessando a pasta 'src' deste repositório.

### Ideias de melhorias
1. Mostrar a localização de cada jogada no formato (col,row), para cada jogada no histórico.
2. Estilizar com negrito o item da lista de jogadas que está selecionado no momento.
3. Reescrever o componente Board para utilizar 2 loops para fazer os quadrados, em vez de deixá-los hardcoded.
4. Adicionar um botão de toggle que lhe permita ordenar os jogadas em ordem ascendente ou descendente.
5. Quando alguém ganhar, destaque os 3 quadrados que causaram a vitória.
6. Quando ninguém ganhar, exiba uma mensagem informando que o resultado foi um empate.