# SVG - Criando imagens direto no HTML

<p>
Todos os dias desenvolvedores web lidam com imagens, isso é fato, desde a mais simples até a mais complexas,
elas estarão lá nos fazendo companhia. O que será abordado é a criação de imagens vetoriais diretamente no HTML usando
a tag <<span>svg</span>>, uma maneira poderosa de trabalhar com imagens.
</p>

## Para principio de conversa - O que é SVG???

<p>
"SVG é a abreviatura de <b>Scalable Vector Graphics</b> que pode ser traduzido do inglês como 
<b>gráficos vetoriais escaláveis</b>. Trata-se de uma linguagem XML para descrever de forma vetorial desenhos e
gráficos bidimensionais, quer de forma estática, quer dinâmica ou animada. Umas das principais características dos 
gráficos vetoriais, é que eles não perdem qualidade ao serem ampliados, isso já é um ganho consideravel quando se pensa 
em responsividade". - <a href="https://pt.wikipedia.org/wiki/SVG">Wikipedia</a>
</p>

### Mas como funciona???

<p>
Antes de mais nada preciso falar de duas coisas primordiais para trabalhar com SVG que são a <b>viewport</b> e <b>viewBox</b>.
Vamos ver então a definição de cada e seu uso:

<p>
<b>Viewport</b> - nada mais é do que a área visível da imagem SVG, onde os atributos <b>width</b> e <b>height</b> definem 
o tamanho que a mesma ocupará. 

<pre>
<<span>svg width="300" height="200" style="background:#A9F5A9;"</span>>
    <i>"width e height definem o tamanho de nossa viewport"</i>
<<span>/svg</span>>
</pre>

![rect-liso](https://user-images.githubusercontent.com/19720603/27777259-871d16e8-5f87-11e7-9415-a4cafd8368e8.png "viewport: 300x200")

</p>

<p>
<b>viewBox</b> - especifica a área em que os elementos contidos no svg ocuparão dentro dele. A viewBox recebe quatro argumentos onde os dois primeiros servirão como coordenadas do elemento e os dois últimos definirão o tamanho do elemento, então são eles: <b>min-x</b>, <b>min-y</b>, <b>width</b> e <b>height</b>.
</p>

<p>
Lembra do <b>plano cartesiano</b> que você aprendeu na escola? Pois é, ele é essencial para se trabalhar com SVG!
</p>

![image](https://user-images.githubusercontent.com/19720603/27767045-03511d6a-5ebe-11e7-816a-8d208c4ec8be.png "Coordenadas de gráficos SVG")

### SVG - Rect

<p>
React é a representação de um retângulo. 
</p>

![react](https://user-images.githubusercontent.com/19720603/27766808-47ff4e6e-5eb4-11e7-9dcc-7c0c5a92b6d3.png "Um simples desenho utilizando react")
