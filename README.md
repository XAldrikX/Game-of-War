# Game-of-War

Esse projeto faz um Request para a API "Deck of cards", criei um jogo simples de War onde você irá jogar contra o computador, o objetivo é tirar a carta com o maior valor.<br>
O primeiro passo foi fazer um GET request para a API e receber a promise de um "Deck_id", tendo o Deck_id pude utilizar o endpoint="draw/?count=2" e ir comprando duas cartas por vez, sendo que uma foi atribuída ao computador e a outra ao jogador.<br>
Para a lógica de comparar o valor das cartas usei um array com os possíveis valores das cartas e utilizando uma propriedade que a API fornece, eu pude chegar o valor da carta que recebi com o index do array que eu havia criado utilizando indexOf(), assim a carta que recebi da API dá um match com os valores do array e a que tiver o maior index ganha.<br>
<br>
<br>
Link do deployment -->
