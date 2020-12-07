# wellingtonollv.github.io
*Responsive Site*

Para alterar cores, consulte o arquivo style.scss.
$nav-color - > altera a cor do menu.
$main-color - > altera a cor principal do site
$font: -> altera a fonte.
---------------------------------------------------------------------
Para alterar margens entre containers, consulte o arquivo style.css
$margin-retangle-nav: 56px;
$margin-nav-flex: 71px;
$margin-flex-text: 82px;
$margin-text-footer: 48px;
----------------------------------------------------------------------

<----Breve explicação----->

Optei por utilizar o framework Bootstrap 4, pois já havia utilizado antes, e sua facilidade para um design responsivo é notável.

O site consiste de uma forma cortada superiormente, seguido de um menu para filtragem, denominado nav. Em seguida possuimos uma flexbox com a combinação de elementos como imagem, texto e botão, em seguida uma imagem com texto disposto a direita e por fim uma forma em formato retangular no footer. 

<--Alguns detalhes-->

A parte da nav, o botão sobrepondo o input text tem algumas falhas em telas de 540x720px.

Tive dificuldade em alternar para o modo horizontal o conjunto de imagem e dados central, quando o display é menor que 500px. A solução encontrada foi a  utilização de flexbox, porém este tipo de elemento não é tão suscetível à alinhamentos e espaçamentos no modo geral, como pode ver no layout.

Testei o método com linhas e colunas, porém não obtive sucesso na alternância de vertical para horizontal.Fora isso, o site é composto de containers simples e do tipo fluido, a diferença entre eles é que o fluid tem um width de 100%, enquanto o simples se mantém no centro.
