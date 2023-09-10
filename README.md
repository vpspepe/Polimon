# ⚡🎮 Polimon
Projeto para a matéria MAC0321 - Laboratório de Programação Orientada a Objetos utilizando os conceitos de POO em Java para o implementação de uma versão USPiana dos jogos antigos de Pokémon, como o Rubi/Safira/Esmeralda.

## 👥 Membros
Alguns membros commitaram por meio de diversas contas. Então, entre parênteses terão suas outras contas utilizadas.
1. Helena Bianchi Moyen - 13679422
2. Marcelo Takayama Russo (mtky25) - 13680164
3. Mariana Arakawa Watanabe (marimaritian) - 11797383
4. Thainara de Assis Goulart - 13874413
5. Victor Pedreira Santos Pepe (vpspepe) - 13679565

# 🎮 Controles
| Tecla | Funcionalidade |
|------|------|
|W|Movimento para cima|
|A|Movimento para esquerda|
|S|Movimento para baixo|
|D|Movimento para direita|
|I|Inventário|
|Enter| Interação com os NPCs, Pólimons e com a Batalha|
|B|Ativa bicicleta|
|P|Pause|
|double-click 1|Estilo Clássico de Jogo (Padrão)|
|double-click 2|Estilo Preto e Branco de Jogo|
|L|Durante pause, muda a dificuldade|

_OBS:_ é necessário estar muito próximo das entidades para interagir com elas.

## 💡 Ideia Inicial 
Devido ao curto período para realizar o projeto, pensamos em algo simples, mas que pudesse agregar de forma positiva no nosso jogo. Basicamente, o estudante [NOME] está chegando em seu primeiro dia de aula e irá pegar o circular para chegar até a POLI.

Dividiremos o jogo em 3 ambientes,como se fossem capítulos.
## 🚌 Terminal de ônibus Butantã
Estágio inicial do jogo.

O player nasce em frente a saída do metrô e está no terminal. Recriaremos uma parte do terminal butantã e essa será a primeira área em que se pode capiturar e evoluir polimons. Isso será necessário pois, bem no lugar em que embarcamos no circular, haverá um motorista que exige o item [BUSP] para que possamos passar por ele. 

Para pegar o *BUSP*, o player precisará derrotar um NPC (ainda indefinido), que dará o *BUSP* caso seja vencido em uma batalha. Então, o estudante terá que fortalecer seus polimons até que consiga derrotar o NPC em uma batalha. Com o BUSP, ele pode entrar no ÔNIBUS e prosseguir para a próxima área, a RAIA.

## 🚣‍♀️ Raia da USP
No caminho para a POLI, o ÔNIBUS QUEBRA. Por isso, todos devem descer na RAIA (local onde o ônibus quebrou). 
 
A Raia será a área principal do jogo. Lá o PLAYER poderá encontrar novos tipos de POLIMONS e batalhar com diversos ALUNOS (NPCs) já que todos tiveram que sair do ÔNIBUS. Como é o primeiro dia de aula, o estudante não sabe chegar até a POLI, então precisará encontrar PISTAS para chegar. 
 
Essas pistas serão dadas por NPCs após serem derrotados em batalha. Após ter todas as pistas, o estudante pode prosseguir para a POLI.

> AQUI PODEMOS COLOCAR UM ESTUDANTE DE CADA FACULDADE PARA REPRESENTAR OS ESTUDANTES. (EX: 5 estudantes FFLCH, FAL, FEA, FARMA, IME). 

# 🛸 A Poli
Estágio FINAL DO JOGO, o estudante chegou a POLI. 

Para terminar o jogo, ele deve terminar a graduação. Isso signifca derrotar 5 personagens (todos os anos de faculdade).
Cada vitória representa a evolução do estudante nos anos de Graduação, então ele receberá um "certificado" por cada ano que conclui (ou cada NPC que derrota dos "chefões" citados anteriormente). Com os 5 certificados, ele pode entrar na ADM e desafiar o grande CHEFE do jogo, o professor X. 

Caso consiga derrotar, o player conclui a faculdade e finaliza o jogo.

## 💡 Ideia De fato Implementada

Quando planejamos o jogo, não sabíamos o quão difícil seria de fato executá-lo. No final, conseguimos implementar apenas os dois primeiros mapas: o **```Butantã```** e a **```Raia```**, deixando a Poli para uma possível DLC no futuro hehe.

## MAPAS EM VERSÕES MENORES
### O Butantã

![BUTANTA](https://lh3.googleusercontent.com/pw/AIL4fc8ludfhgWEc8wdtobcmlGxg1CuzpuS3HZaZ3OL_kJ4TxcGPmVKkSnzdNMDgZrqnFAWxjt_BHFX-tc_6jkjnhxJ_prPD8rCW1feGH1r6Of57LXAfPwtIyF-naXZwUS1jysNe8RpUhfh0J50r3GsB3NN7UpdiCgCcpeYxL9jYo_IYNCb2MecSdb8czl-Qc85cKDof04Jul0AXFOPUyZCxcFFFTxpC47LFsUAEu_fXWlsur3u4TEAXVYfPgJ_xoPQeid9jraiQ1t2dmoSajhMiHGn5eYtFFD0oUhx5sRxrHdfS8JBw20vL9hDF22DaSvlw42ShNvWOiIyVBFB53O2ysDAukYI-epdZ9VuRoNr4h34ZcRbYQvF1wIs7ZYeulvUtEUdAUcXHBGRTDW7uV7BWtA4OO4RcEInZkkNJUCKLvzR9bc63sOqYZ1k12pP-7VyVGV-3PjN2PC7ckyFV17TrzVKsDoL2eGMiy-wIpNVCmQDv3oE_klSdM-Ar0FriIZRiRsmUBU7Bnz0F-vUrmXsbOgsl3nRDOAlGGVQzggBfCkK9Tc1fONvTV1Js7K6MytA526mYekvsEYFARmSLytK__MSNt2KmlwtcG3n6L-VYVGGefeX9000zkxJbwLioJ4xdqb21wJVuLY9XIFh0dHza8X8uyqpYo399OPI7mfE7b2Eo3-_vWwH0oEhd5JFHu1eAVzZEOfoz7ro4h-iKw55iN_hOs5NjZfyk3pDUEOGvcBsIkVk41oGC4BbLn2QBJzty_UmiZas8oc6WCf6AzTa_r_Z14xaF8h7iyCFFbxS8GtJGPJmB0VnGyk2jtnSfyTf-nC3NghEKlCMXLIILBZoHkV774Dc4Yf7AYi0JEloHwV-LxpiRDF9uAgyFcJvS8gQQa1CCfHIAOioag2GfRQiS1g=w798-h1019-s-no?authuser=0)
### A Raia
![RAIA](https://lh3.googleusercontent.com/pw/AIL4fc-uFZ6zBefdApXqUN8LxjAlB81emMfUaZm9bMH9j0HkhN88r_uV2gkEKyGDH5POWh2HiQYfXdOtyh4UHVNwBEUP9xtZupk3hsRPfZ6i5BKLECO5TnTuJ4pzHVGCao8i7u8g8vHcD3H5Pdu7rpL_E2v7=w603-h771-s-no?authuser=0)

## Funcionamento do Jogo e Estruturas das classes
Dentro da pasta "polimon/src", temos (por enquanto) 5 pastas diferentes:

|Pasta|Conteúdo e funcionalidades|
|------|------|
|entity|classes relacionadas ao player principal|
|main|classes com os principais atributos visuais,controles e mecanismos de jogo|       
|tiles|classes que referentes aos tijolos/pixels (tiles) do mapa e a organização dele|
|object|classe mãe de todos os objetos contidos no mapa além dos objetos propriamente ditos (BUSP, bike, etc)|
|res|arquivos relacionados à parte gráfica (PNGs de árvore, player andando, ônibus, bike, etc)|


### :map: Mapas
Para construir os mapas, usamos o software gratuito **```Tiled```**, que nos permite criar mapas sofisticados a partir de tilesets da Internet. Com os mapas criados, o software gera arquivos _.csv_, que - em cada célula - contém um valor inteiro. Esse inteiro equivale a um bloco (tile) de 16x16 pixels dentro do tileset. Então, dentro do nosso  código _tileManager_, convertemos esses arquivos  _csv_ no nosso mapa do jogo.  
### 💥 Colisões
Como o mapa possui muitos blocos diferentes, por conta dos detalhes, era impossível definir - bloco a bloco - quais deveriam ou não ter algum tipo de colisão. Por conta disso, trabalhamos com camadas dentro do **```Tiled```**, em que todos os desenhos feitos em uma determinada camada de colisão do mapa possuirão colisão com o player. Fizemos isso tanto para colisões que **impedem o movimento**, como também para colisões com a **água**, em que a velocidade diminui e a skin do personagem se modifica. 
Infelizmente, não conseguimos ajustar os detalhes gráficos dos objetos que não possuem os 256 pixels preenchidos (blocos 16x16 pixels). Por exemplo, um poste possui apenas algumas colunas de pixels preenchidas, sendo que a grande maioria deveriam ser pixels transparentes. Por algum motivo, o nosso código não conseguiu interpretar esses transparentes como vazio, apenas como um bloco branco. Apesar disso, as colisões ocorrem corretamente.

### :runner: Comandos
Os comandos do player sequem o padrão _AWSDW_, além de haver outras interações, como apertar a tecla _B_ e o play andar de bicicleta :bike:, com velocidade 
maior, porém isso só ocorre após o player encontrar e pegar a bike (no segundo mapa).

### :gift: :interrobang: Interações e Objetos
**BUSP** : Item necessário para utilizar o Circular e poder prosseguir para o mapa da Raia. Esse item está escondido em algum ambiente do Butantã. Ao possuí-lo, pode-se prosseguir para a catraca e entrar no **Circular**(Ônibus Amarelo na parte inferior do mapa).

**POKEBOLAS** : Achar os polimons não é a tarefa mais difícil, no entanto não há como batalhar com eles sem uma pokebola. Pokebolas estão espalhadas por todo o mapa e basta passar por cima delas para pegá-las.

**BIKE DO ITAÚ** : Item exclusivo do Mapa da Raia que permite aumentar a velocidade do player ao clickar no botão B.

> é possível achar o busp no canto inferior esquerdo do primeiro mapa, para assim passar pela catraca e ir para o segundo mapa. No segundo mapa, é possível interagir com a Itaú Bike ao encostar **somente** na primeira bike (inferior).

### ⚔️ Batalhas Polimon

![](https://lh3.googleusercontent.com/pw/AIL4fc8a3czfgxZE_WjMHZw2MqlkuQDn1l8ODt5Hx-xYAUV3QZzClaLl5AMMlP1gjJopY-y3XbszlsNcJiPSQBQC7Fh92-bwALThWeCzEDaDaCDQKsLhyU8mrRFg5bhnsUl2pjst6-uAkiUbtyuY5gwKIve3ETkw54tmOzW4rL8dfOfk9u_s7sE1BuIDfWlQ5qTZZ7UsCVbp9CkZQLlVO2EuQulnSfOefSOafBAj8aQJ9ZnC8e7HZerCiwTaCRafGcSw5SGQKOYqrijRiYeXrDKukhEENX7k7gfeYsFP2ZSAsZ84wptlhPyZWinzzRWvX5RhV4_EUlsALOxrdvABD-7EmGmo0BT3DpaBkNJHG7qNiGIG0eDae31C8QGlOAh5hXCT4prigTc-Qg0jmSM_vDD706_nc4QO8ekozuPjntufu_7xOtjh-nG_hFWoqZT1NGfpaWf_66hFHfaZPpg0D1rOtjprm6DZRS3cxxdg60a0Q8ZGPL7DO0WiP4hLQelpn9YwDyyYZeEOd6C3Uvu6m-lTeAAEy8O1h6ECY5Vav-xBgdiFwjS3g9S3Qz9hO30TFkMD6E278BuTyINALpL-oKnZIF6J4A6Qv1QBH4RD7DLaPIONFH_hYERLHOqgrBi-4aei742eGoXAG8PIjS3u-fjv6uVHA7ky90MfN7GqSuPAPdQxZpEs7WJgYrDiljsB9VWXIk0-JeNLfmXrW9ozLmpd4Mi6XQQFcmAgOjqPeHW-cLxwf-XztowAPzODt1EoQhpN_bCdLDQeocN8Y1FVr3qzbIz-yRWDwWjllU1vr8n5nJM2IgwH8hZCrlCuUe7u2cceqmsjtDDm8RriqOATNCgPkfpSmYYcteawaoqHzqk9eL7jZWAuHo6upeNUgJEAD8T9yUybzeOifUI3no0wJH_J0w=w760-h577-s-no?authuser=0)


Para simular a **```Batalha Polimon```**, criamos um método simples, quando comparado às grandes franquias da saga. No jogo, entra-se em uma batalha sempre que encerra o diálogo com um polimon e o player possui ao menos uma pokebola. A batalha recebe sempre um player e um polimon, ambas entidades do jogo. Há uma verificação de turnos que indica de quem é a vez de ataque. Se é a vez do polimon, o player perderá uma vida, se é vez do player, o jogo aguardará o input do player no teclado (o que simula a escolha de um ataque para ser usado).

A batalha se encerra quando as vidas do polimon acabam (em nosso jogo, o player sempre vence as batalhas). O Player recebe um coração a mais para cada batalha vencida.

### 👁️ Look-and-Feel (mudança de tema do mapa)

Para implementar os temas dos mapas, unimos os padrões criacionais **```Fábrica Abstrata```** e **```Prototype```**. Por meio das teclas _1 (Clássico)_ e _2 (Preto e Branco)_, pode-se escolher qual tema queremos para o nosso jogo. Ao escolher o tema, criaa-se um clone desse tema, que é responsavel por mudar o _path_ em que iremos pegar nossos arquivos. Dessa forma, podemos mudar o diretório constantemente em tempo de execução, dando load nos diferentes temas diversas vezes enquanto o jogo roda.

*OBS*: ao trocar de Skin, as colisões não se mantém, e acabam gerando um erro por conta dos NPCs saírem do mapa, ou seja, acessam um Index invalido do mapa "_java.lang.ArrayIndexOutOfBoundsException_" :((.

### 🤖 NPCs 

Como há muitos NPCs pelo mapa, seria muito trabalhoso implementar o comportamento deles um a um. Por conta disso, utilizamos o padrão comportamental **```Strategy```**, em que cada NPC possui uma forma diferente de se mover. Alguns se movem de forma aletória, outros apenas na vertical etc.

### 🕹️ Níveis de Dificuldade
No nosso jogo, o nível de dificuldade se reflete na velocidade em que as entidades se movimentam e na vida que os Pólimons possuem. Para manipular com isso, utilizamos o padrão comportamental **```State```**, em que cada Entidade - que não o player - possui dois estados: o *fácil* e o *difícil*. Ao clickar a tecla _L_ no menu, muda-se de estado, mudando-se, por consequência, a velocidade das entidades do mapa e a vida dos Pólimons.


