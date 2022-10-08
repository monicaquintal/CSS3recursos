## Curso Desenvolvimento Web Completo 2022 (Seção 6: HTML5 e CSS3 Recursos especiais).

<strong>1. Aula 01: Apresentação.<br><br></strong>

<strong>2. Aula 02: Normalize CSS. <br><br></strong>

- Corrige diferenças de exibições entre browsers e corrige bugs comuns em CSS, em razão dessas diferenças.<br>
- <a href="https://necolas.github.io/normalize.css/" target="_blank">Link para documentação e download.</a> <br><br>

<strong>3. Aula 03: Box Sizing e Cantos arredondados. <br><br></strong>

- Algumas versões mais antigas de browsers não suportam a propriedade border radius; utilizar prefixos para que o browser compreenda a funcionalidade (chrome, mozila, safari).<br>
- Exemplo:<br>
  -webkit-border-radius: 10px 50px 80px 100px; CHROME<br>
  -moz-border-radius: 10px 50px 80px 100px; MOZILA<br>
- <em>BOX SIZING:</em> independente do padding, o tamanho da caixa será o mesmo sempre; também utilizar prefixos.<br><br>

<strong>4. Aula 04: Degradê e transparências. <br><br></strong>

- linear-gradient, radial-gradient, rgba. <br><br>

<strong>5. Aula 05: Sombras. <br><br></strong>

- <em>text-shadow:</em> primeiro parâmetro movimenta a sombra na horizontal, e o segundo, na vertical. Podem ser utilizados valores negativos;<br>
- A sombra funciona como um background, não empurra os textos;<br>
- Inserir a cor da sombra na sequência (nome, hexadecimal, rgba);<br>
- A sombra pode ser aplicada diretamente na div (caixa), utilizando <em>box-shadow</em>;<br>
- É possível aplicar um blur incluindo um terceiro valor; <br>
- Há tambpem o parâmetro spread, quarto valor, que é o espalhamento da sombra. <br><br>

<strong>6. Aula 06: Animações. <br><br></strong>

- Em CSS, são possibilidades de ir de uma formatação para outra.<br>
- <em>"keyframes"</em> identifica que estamos fazendo uma animação, e deve-se dar um nome a ela na sequência. <br>
- Cria a animação separadamente, depois utiliza dentro do identificador da caixa, como uma propriedade CSS.<br>
- Aplicar os prefixos para que as animações funcionem corretamente. <br>
- É possivel definir todos os parâmetros em uma única linha. <br><br>

<strong>7. Aula 07: Transições. <br><br></strong>

- Para transições, utilizar ":hover";<br>
- A propriedade "Transition" também requer o uso dos prefixos corretos;<br>
- Permite incluir parâmetros, como tempo para a transição ocorrer. Conferir o <a href="https://www.w3schools.com/css/css3_transitions.asp" target="_blank">link</a>. <br><br>

<strong>8. Aula 08: Novas tags HTML5 - Header, Nave e Footer. <br><br></strong>

- A tag &lt;header&gt; é uma tag de cabeçalho, evitando o id "cabeçalho" e facilitando a aplicação de formatações, de localização e para leitores.<br>
- A tag &lt;nav&gt;, por sua vez, define uma navegação. Utilizada em listas de links, principalmente.<br>
- A tag &lt;footer&gt; substitiu a id de rodapé.<br><br>

<strong>9. Aula 09: Novas tags HTML5 - Article, Section, Aside e time. <br><br></strong>

- A tag &lt;article&gt;: estrutura o site; pode incluir as postagens dentro dessa tag, por exemplo. É possível criar seções (tag &lt;section&gt;) dentro dele para separar os conteúdos.<br>
- A tag &lt;time&gt; é utilizada para inserir e formatar datas em geral.<br>
- A tag &lt;aside&gt; é utilizada para definir conteúdos laterais.<br><br>

<strong>10. Compatibilidade HTML5. <br><br></strong>
