# Aprendendo sobre HTML E JS E CSS
<img src="html5-logo-7.png" alt="Imagem de exemplo">

# HTML (Hypertext Markup Language):
HTML é a linguagem de marcação usada para criar a estrutura básica de uma página da web. Ele é composto por elementos chamados "tags" que são usados para definir a estrutura do conteúdo, como títulos, parágrafos, imagens, links e muito mais.
Exemplo de código HTML simples:

```html

<!DOCTYPE html> <!---Essa declaração define o tipo de documento como um documento HTML5. Ela informa ao navegador que o conteúdo a seguir será escrito em conformidade com a especificação do HTML5.--->
<html> <!---Esta é a tag principal que envolve todo o conteúdo da sua página. Ela indica o início do documento HTML.--->
<head> <!--- Esta tag contém informações sobre o documento, como meta informações, título da página, links para arquivos CSS e muito mais. O conteúdo dentro da tag <head> não é exibido na página, mas fornece informações importantes para o navegador.-->
    <title>Minha Primeira Página</title>
</head>
<body>
    <h1>Olá, mundo!</h1>
    <p>Esse é um inicio de aprendizagem em HTML.</p>

</body>
</html>

```
CSS (Cascading Style Sheets):
CSS é usado para estilizar o conteúdo HTML. Ele controla a aparência visual dos elementos, como cores, fontes, espaçamento, layout e muito mais. A separação entre HTML e CSS permite que você mantenha a estrutura e o estilo separados.
Exemplo de código CSS simples (usando um seletor de tag):


```CSS
/* Estilizando todos os parágrafos */
p {
    color: blue;
    font-size: 16px;
    margin-bottom: 20px;
}

```

JavaScript:
JavaScript é uma linguagem de programação que permite adicionar interatividade e comportamento dinâmico às páginas da web. Com JS, você pode responder a eventos (cliques de botão, movimentos do mouse, etc.), manipular o conteúdo da página e interagir com APIs externas.
Exemplo de código JavaScript simples (exibindo uma mensagem ao clicar em um botão):


```JS

// Obtendo uma referência ao botão por seu ID
var meuBotao = document.getElementById("meuBotao");

// Adicionando um ouvinte de evento de clique ao botão
meuBotao.addEventListener("click", function() {
    alert("Botão clicado!");
});

```

Algumas Tags importantes e uma melhor do que cada uma faz:

```<!DOCTYPE html>``` : Essa declaração define o tipo de documento como um documento HTML5. Ela informa ao navegador que o conteúdo a seguir será escrito em conformidade com a especificação do HTML5.

```<html>```: Esta é a tag principal que envolve todo o conteúdo da sua página. Ela indica o início do documento HTML.

```<head>```: Esta tag contém informações sobre o documento, como meta informações, título da página, links para arquivos CSS e muito mais. O conteúdo dentro da tag <head> não é exibido na página, mas fornece informações importantes para o navegador.

```<title>```: Esta tag define o título da página que aparecerá na guia do navegador ou na barra de título da janela. É uma informação importante para os motores de busca e para os usuários que têm várias abas abertas.

```<body>```: O conteúdo visível da página é colocado dentro desta tag. Ela contém os elementos que serão exibidos na janela do navegador, como texto, imagens, links, etc.

```<h1>, <h2>, <h3>, ... <h6>```: Essas tags são usadas para criar cabeçalhos com diferentes níveis de importância. ```<h1>``` é o cabeçalho mais importante, usado para títulos principais, enquanto ```<h6>``` é o menos importante.

```<p>```: Essa tag é usada para criar parágrafos de texto.

```<img>```: Usada para incorporar imagens na página. O atributo src define o caminho da imagem, e o atributo alt fornece um texto alternativo para acessibilidade ou caso a imagem não possa ser exibida.

```<a>```: Essa tag é usada para criar links. O atributo href especifica o URL de destino do link.

```<ul>```: Tag para criar uma lista não ordenada (lista com marcadores).

```<ol>```: Tag para criar uma lista ordenada (lista numerada).

```<li>```: Tag para criar um item de lista em uma lista ```<ul>``` ou ```<ol>```.

```<div>```: Uma tag de divisão usada para agrupar e organizar elementos, muitas vezes com o propósito de aplicar estilos ou manipular com JavaScript.

```<span>```: Semelhante ao ```<div>```, mas é uma tag em linha (não causa quebra de linha) usada para aplicar estilos ou manipular partes específicas do texto.









