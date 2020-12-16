# Escacs: el joc de les 64 caselles


## Origens
> Els escacs són un joc de tauler de naturalesa recreativa i competitiva per a dos jugadors. Segons els historiadors dels escacs, el joc original fou el xaturanga, que es practicava a l'Índia al segle VI dC,  i que es va transmetre des d'allà cap a Pèrsia i l'orient d'una banda, i cap al món àrab de l'altra.<br><br> La forma actual del joc, anomenada més específicament escacs occidentals (o escacs internacionals), per diferenciar-lo dels seus predecessors i d'altres variacions actuals, sorgí al sud-oest d'Europa durant la segona meitat del segle xv,  a partir del xatranj. Els escacs occidentals pertanyen a la mateixa família dels actuals xiangqi (escacs xinesos) i shogi (escacs japonesos). 



## Peces i tauler
> Cada jugador disposa inicialment de setze peces: **vuit peons, dos cavalls, dos alfils, dues torres (o rocs), un rei i una dama o reina**. Cada tipus de peça té un moviment únic i característic. En el món dels escacs, hom coneix com a peces majors la reina i les torres, i com a peces menors els alfils i els cavalls. 

>| -----------*   |      Peces      |* ----------- |
|----------|:-------------:|------:|
| ♔| Rei | ♚|
|♕ |   Reina   |   ♛ |
|♖ | Torre |    ♜ |
|♗ | Alfil |    ♝ |
|♘ | Cavall |    ♞ |
|♙ | Peó  |♟ |
<br>

![inici](https://user-images.githubusercontent.com/75562243/102388362-efdec180-3fd1-11eb-9914-a9bafa9d07d7.png)<br><br>

>El tauler d'escacs és un quadrat subdividit en 64 caselles iguals (8 × 8), també quadrades, alternativament de color clar i de color fosc. Un jugador se situa de cara al contrincant, de tal manera que cada jugador tingui una casella blanca en el seu cantó dret.

>Els elements bàsics del tauler són: 
<ul>
    <li>Fila. És cadascuna de les vuit línies de vuit caselles que es formen alineant aquestes horitzontalment respecte dels jugadors. Es numeren de l'1 al 8, començant des de la primera fila pel que fa al bàndol de les peces blanques.</li><br>
  
![fila](https://user-images.githubusercontent.com/75562243/102393906-469bc980-3fd9-11eb-9eb2-f07b7464886a.png)<br><br>

</ul>
<ul>
    <li>Columna. És cadascuna de les vuit línies de vuit caselles que es formen alineant aquestes verticalment respecte dels jugadors. S'anomenen amb lletres         minúscules de la (a) a la (h), començant des de la primera columna esquerra pel que fa al bàndol de les peces blanques.</li><br>


![columna](https://user-images.githubusercontent.com/75562243/102394307-d80b3b80-3fd9-11eb-8c17-c794cf1d2278.png) <br><br>
</ul>
<ul>
    <li>Diagonal. És cadascuna de les 16 línies que es formen agrupant les caselles diagonalment. Les dues grans diagonals tenen vuit caselles.</li>
    
![diagonal](https://user-images.githubusercontent.com/75562243/102394440-0d178e00-3fda-11eb-9695-452b01599bd1.png) <br><br>
</ul>
<ul>
    > <li>Centre. El centre del tauler són les quatre caselles centrals.</li>

![centre](https://user-images.githubusercontent.com/75562243/102394551-30dad400-3fda-11eb-928d-edd4f86b8837.png) <br><br>
</ul>
<ul>
    <li>Cantonades. Cadascuna de les quatre caselles situades a les cantonades del tauler.</li>
</ul>
<ul>
    <li>Vores. Les dues columnes (a i h) i dues files (1 i 8) situades als extrems del tauler.</li> 
</ul>


## Installation

## Captures i Escacs
### Com moure les peces

> Durant una partida d'escacs, cada escaquista controla setze peces que poden ser de color clar o obscur (normalment blanques i negres). Les blanques han de fer sempre el primer moviment.
<ul>
<li>Peó: El peó és la peça amb menys valor  del tauler (tècnicament). Només es pot moure endavant una casella i només pot capturar en diagonal una casella. Si es el primer cop que es mou el peó es pot moure dos caselles endavant i si tens sort i aquest peó arriba a la ultima casella de la columna, el podràs transformar en qualsevol peça que vulguis, el que se li diu coronar.</li>  

![peó](https://user-images.githubusercontent.com/75562243/102401822-2de4e100-3fe4-11eb-8f1d-51a796773f88.gif)  <br><br>
  
<li>Cavall: El cavall és l'única peça del tauler que pot saltar sobre altres peces. El cavall es mou dues caselles en direcció horitzontal o vertical i després una casella més en angle recte. El moviment de l'cavall té la forma d'una "L".</li>    

 ![cavall](https://user-images.githubusercontent.com/75562243/102401980-671d5100-3fe4-11eb-954e-0e02b0bfe732.gif) <br><br>
 
<li>Alfil: Es mou en diagonal, no pot saltar peces intervinents.</li>    

 ![alfil](https://user-images.githubusercontent.com/75562243/102402088-903de180-3fe4-11eb-8ed5-350660200c89.gif) <br><br>
 
<li>Torre: La torre es mou en una línia recta horitzontal o vertical al llarg de qualsevol nombre de caselles desocupades.</li>    

 ![torre](https://user-images.githubusercontent.com/75562243/102402098-9469ff00-3fe4-11eb-8a71-8f1764b6703f.gif) <br><br>
 
<li>Reina: Es pot moure qualsevol nombre de caselles en línia recta, tant de manera horitzontal com vertical o diagonal. La reina es mou com la torre i l'alfil junts.</li>    

 ![reina](https://user-images.githubusercontent.com/75562243/102402123-9cc23a00-3fe4-11eb-9eb4-66de5ec92c67.gif) <br><br>
 
<li>Rei: El rei és la peça més important dels escacs, la seva captura és l'únic objectiu del joc. El seu moviment consisteix en el desplaçament d'una casella o escac en horitzontal, vertical o diagonal. </li>    

 ![rei](https://user-images.githubusercontent.com/75562243/102402139-a055c100-3fe4-11eb-8ccf-3960b98e464f.gif) <br><br>
 
<li>Enroc: En cas que el jugador no hagi mogut el rei durant el joc, se li permet realitzar un moviment especial anomenat enroc amb una de les torres, complint alguns requisits. Aquest moviment normalment s'utilitza per posicionar el rei en una posició segura</li>  

![enroc](https://user-images.githubusercontent.com/75562243/102405224-1b20db00-3fe9-11eb-97a5-f90c6b9a5989.gif)

</ul>

## Com es guanya
### Regles Bàsiques

> Durant el transcurs de la partida, quan el rei d'un jugador és directament atacat per una peça enemiga, es diu que el rei està en **escac**. En aquesta posició el jugador ha de moure el rei per a posar-lo fora de perill, capturar la peça adversària que està efectuant l'escac o bloquejar l'atac amb una de les seves pròpies peces. Aquesta última opció no és possible si la peça atacant és un cavall, ja que aquesta peça pot saltar sobre les peces adversàries. L'objectiu del joc és fer **escac i mat ** a l'adversari, la qual cosa té lloc quan el rei oponent es troba en escac i no es pot realitzar cap moviment de fugida, defensa o atac per a anul·lar l'escac. En aquest cas, o la peça és menjada per l'adversari o el jugador perdedor tomba el rei, com a senyal de rendiment. Hi ha l'obligatorietat que els jugadors diguen, en el cas d'escac, escac, i en el cas d'escac i mat, escac i mat, excepte si l'adversari tomba la peça.

> Els jugadors també disposen dels tres moviments especials: l'enroc, que fortifica el rei, protegint-lo d'atacs enemics, tot i que no pot dur-se a terme si el rei està en escac; la captura al pas, quan un peó que arriba a la cinquena filera avança fins a la sisena i pren un altre peó oponent que, en les dues columnes adjacents, ha avançat dues caselles en el seu moviment inicial; i la promoció, permesa als peons que, quan arriben a la vuitena fila, poden ser promoguts a qualsevol altra peça, amb l'excepció del rei. 

## Exemple d'escac i mat (mat del pastor)
> ![pastor](https://user-images.githubusercontent.com/75562243/102406090-5d96e780-3fea-11eb-926f-e2acd6379b07.gif)
