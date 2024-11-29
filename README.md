<h1>Jogo da Memoria</h1>

Um jogo da memória 4x4 de dois jogadores feito no Logisim com circuitos lógicos.

Trabalho de Circuitos Digitais - Ciência da Computação - Universidade Federal do Cariri

Alunos: <br>
João Gabriel de Alencar Fonseca <br>
Fabricio Elizio Lima dos Santos

Professor: <br>
Ramon Santos Nepomuceno


<h2>O Projeto</h2>
<p>Este projeto consiste na criação de um jogo da memória utilizando o Logisim. O jogo apresenta um tabuleiro com design 4x4, contendo 8 pares de números (de 1 a 8) que devem ser encontrados pelos jogadores. O controle do jogo é feito por meio de botões direcionais para selecionar as casas, além de um botão de confirmação e outro de reset, que permite reiniciar a partida. O circuito também inclui um placar que exibe a pontuação dos jogadores, indicando vitórias do jogador A, do jogador B ou um possível empate. Confira o game:</p>

![Imagem do Jogo](./imagens/01.png)

<h3>Como Jogar</h3>

<p>O jogador, em sua vez(indicada pelo LED acima da pontuação), deve selecionar duas casas utilizando os controles direcionais e o botão de confirmação. Após escolher as duas casas e confirmar novamente, o jogo verificará se ambas contêm o mesmo número. Caso isso ocorra, o jogador ganha um ponto e a vez passa para o próximo jogador. O jogo termina quando todas as combinações forem encontradas, e vence o jogador com a maior pontuação. Se ambos obtiverem 4 pontos, o jogo terminará em empate.</p>

<h2>O Circuito</h2>

<h3>Estados</h3>

<p>O jogo possui três estados, que são guardados em um contador de 2 bits limitado de 0-2, funcionando como uma Máquina de Estados Finitos</p>
