# Jogo da Velha
Projeto criado usando HTML, CSS e JavaScript Puro. [Acessar aplicação](https://werlen-dev.web.app/projeto-jogo-da-velha/)

[![galeria](https://firebasestorage.googleapis.com/v0/b/werlen-dev.appspot.com/o/projects%2Fimages%2Fjogovelha.png?alt=media&token=da55ddda-1755-4e60-9f86-5961a6461816)](https://werlen-dev.web.app/jogo-da-velha/)

Nesse projeto foram vistos e praticados conceitos com eventos de mouse, seleção de elementos por querySelector, atribuição e remoção de attributos HTML, estilização da aparência do HTML manipulando o CSS via JavaScript.

Foi criado sistema de condição de vitória para verificar qual player venceu mostrando a 
mensagem de vitória.

Sistema de condição para checar se o player1 ou o player 2 que fará a proxima
jogada;

Sistema de checagem de vitória
 - Vai ser declarado vencedor se os simbolos da horizontal que foi toda preenchida
 - Forem iguais. A msm lógica é aplicada a cada coluna e as diagonais.
 - Se nehuma das linhas fecharem com simbolos iguais dará a mensagem de "Velha".

Quando o jogador vence, é aplicada a lógica de aumentar a contagem de placar
visivel no HTML

Utilizou a biblioteca Math do javaScript para fazer o computador marcar uma posição
aleatoria no jogo da velha para que fosse possivel jogar contra a máquina

Após o fim da jogada, utilizamos os métodos de manipulação de elementos através do javascript
para remover os simbolos que forma preenchidos durante a ultima partida.
