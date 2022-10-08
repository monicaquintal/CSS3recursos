## Curso Desenvolvimento Web Completo 2022 (Seção 6: HTML5 e CSS3 Recursos especiais).

- Aula 01: Apresentação.

- Aula 02: Normalize CSS. <br>

  Corrige diferenças de exibições entre browsers e corrige bugs comuns em CSS, em razão dessas diferenças.<br>
  <a href="https://necolas.github.io/normalize.css/" target="_blank">Link para documentação e download.</a>

- Aula 03: Box Sizing e Cantos arredondados. <br>

  Algumas versões mais antigas de browsers não suportam a propriedade border radius; utilizar prefixos para que o browser compreenda a funcionalidade (chrome, mozila, safari).<br>
  Exemplo:<br>
  -webkit-border-radius: 10px 50px 80px 100px; CHROME<br>
  -moz-border-radius: 10px 50px 80px 100px; MOZILA<br>
  <em>BOX SIZING:</em> independente do padding, o tamanho da caixa será o mesmo sempre; também utilizar prefixos.<br>

- Aula 04: Degradê e transparências. <br>

  linear-gradient, radial-gradient, rgba. <br>

- Aula 05: Sombras. <br>

  <em>text-shadow:</em> primeiro parâmetro movimenta a sombra na horizontal, e o segundo, na vertical. Podem ser utilizados valores negativos;<br>
  A sombra funciona como um background, não empurra os textos;<br>
  Inserir a cor da sombra na sequência (nome, hexadecimal, rgba);<br>
  A sombra pode ser aplicada diretamente na div (caixa), utilizando <em>box-shadow</em>;<br>
  É possível aplicar um blur incluindo um terceiro valor; <br>
  Há tambpem o parâmetro spread, quarto valor, que é o espalhamento da sombra. <br>

- Aula 06: Animações. <br>

  Em CSS, são possibilidades de ir de uma formatação para outra.<br>
  <em>"keyframes"</em> identifica que estamos fazendo uma animação, e deve-se dar um nome a ela na sequência. <br>
  Cria a animação separadamente, depois utiliza dentro do identificador da caixa, como uma propriedade CSS.<br>
  Aplicar os prefixos para que as animações funcionem corretamente. <br>
  É possivel definir todos os parâmetros em uma única linha. <br>

- Aula 07: Transições. <br>
