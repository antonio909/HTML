# O que é HTML?

HTML, ou HiperText Markup Language, é a
linguagem de marcação padrão para a criação de
páginas web. Ela fornece a estrutura e o conteúdo
de um site, definindo elementos como títulos,
parágrafos, imagens e links. Os navegadores
interpretam o código HTML para exibir as páginas
web visuais e interativas que vemos todos os dias.

## Compreendendo os blocos de construção

O HTML utiliza um sistema de elementos,
frequentemente chamados de tags, para marcar o
conteúdo. Esses elementos informam ao navegador
como exibir o texto, as imagens e outras mídias. A
maioria dos elementos HTML consiste em uma tag
inicial, uma tag de conteúdo e uma tag final.

### Elementos e Tags

* **Marcador de início:** marca o início de um
  elemento (por exemplo: `<p>`).
* **Tag final:** marca o fim de um elemento e é
  semelhante à tag inicial, mas inclui uma barra
  (por exemplo, `</p>`).
* **Conteúdo:** As informações reais contidas no
  elemento (por exemplo, "Este é um parágrafo").
* **Elementos vazios:** Alguns elementos, como
  `<br>`(quebra de linha) e `<img>`(imagem), não
  requerem tags de fechamento. Eles são
  chamados de elementos de fechamento
  automático ou vazios. Em HTML5, você pode
  (mas geralmente não precisa) fechá-los com
  `/>`(por exemplo, `<br />`).

Exemplo:

`<p>Este é um parágrafo de texto.</p>`

Neste exemplo, `<p>` é a tag inicial, `</p>` é a tag final
e `Este é um parágrafo de texto.` é o conteúdo.

### Atributos

Os elementos HTML também podem ter atributos,
que fornecem informações adicionais sobre o
elemento. Os atributos são especificados na tag
inicial e consistem em um nome e um valor,
separados por um sinal de igual (=). O valor
geralmente é colocado entre aspas duplas.

Exemplo:

```
<a href="https://www.example.com">Visit Example.com</a>
<img src="image.jpg" alt="An example image">
```

* No primeiro exemplo, `href` é um atributo do
  elemento `<a>` (anchor) que especifica a URL do
  link.
* No segundo exemplo, `src` é um atributo do
  elemento `<img>` que especifica a origem da
  imagem e `alt` fornece texto alternativo caso a
  imagem não possa ser exibida.

## A estrutura básica do HTML

Todo documento HTML possui uma estrutura
básica que inclui diversos elementos essenciais. Eles
fornecem a base sobre a qual o restante da página
web é construido.

```
<!DOCTYPE html>
<html>
<head>
  <title>Page Title</title>
</head>
<body>

  <h1>This is a Heading</h1>
  <p>This is a paragraph.</p>

</body>
</html>
```

Vamos analisar cada parte:

* `<!DOCTYPE html>`: Esta declaração define o tipo
  de documento como HTML5. É importante
  incluí-la para que os navegadores renderizem a
  página corretamente. Esta *não* é uma tag
  HTML em si.
* `<html>`: O elemento raiz da página HTML.
  Todos os outros elementos estão contidos
  nesta tag.
* `<head>`: Contém metainformações sobre o
  documento HTML, como título, conjunto de
  caracteres, links para folhas de estilos e scripts.
  Essas informações geralmente não são exibidas
  na página em si.
