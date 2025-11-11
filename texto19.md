# Tags Estruturais Essenciais

Estas tags definem a estrutura fundamental de todo documento HTML:

* `<!DOCTYPE html>`: Esta não é tecnicamente uma tag, mas uma **declaração** que define o
  tipo de documento. Ela deve ser a primeira coisa no seu código e informa ao navegador que
  o documento é HTML5.

* `<html>`: A **tag raiz** que engloba todo o conteúdo da página HTML.

* `<head>`: Contém **metadados** sobre o documento, como o título, links para folhas de estilo
  (CSS) e informações de caracteres (charset). Seu conteúdo não é vísivel diretamente na
  página.

* `<title>`: Define o **título** que aparece na aba do navegador. Fica dentro da tag `<head>`.

* `<body>`: Contém **todo o conteúdo visível** da página, como textos, imagens, links e vídeos.

-----

## Tags de Texto e Conteúdo

Essas tags são usadas para formatar e estruturar o texto dentro do `<body>`:

* `<h1>` **a** `<h6>`: Tags de **cabeçalho** (ou títulos), onde ´<h1>´ é o mais importante e `<h6>` o
  menos importante.

* `<p>`: Define um **parágrafo** de texto.

* `<a>`: Define um **hiperlink** (âncora). O destino do link é especificado no atributo `href`.

  * Exemplo: `<a href="https://www.google.com">Ir para o Google</a>`

* `<img>`: Usada para **incorporar uma imagem**. É uma tag **vazia** (não requer tag de
  fechamento). Os atributos essenciais são `src` (caminho da imagem) e `alt` (texto
  alternativo).

  * Exemplo: `<img src="caminho/imagem.jpg" alt="Descrição da Imagem">`

* `<ul>`: Define uma **lista não ordenada** (com marcadores).

* `<ol>`: Define uma **lista ordenada** (com números ou letras).

* `<li>`: Define um **item de lista**, usado dentro de `<ul>` ou `<ol>`.

* `<b>` ou `<strong>`: Usadas para deixar o texto em **negrito**. `<strong>` é preferivel por
  indicar `importância` (semântica).

* `<i>` ou `<em>`: Usadas para deixar o texto em **itálico**. `<em>` é preferível por indicar **ênfase**
  (semântica).

* `<br>`: Insere uma **quebra de linha** (line break). É uma tag vazia.

* `<hr>`: Insere uma **linha horizontal** temática (horizontal rule). É uma tag vazia.

-----

## Tags de Conteúdo Semântico (Bloco)

Essas tags são usada para dividir e organizar o conteúdo em seções lógicas, dando **significado**
(semântica) ao seu código.

* `<div>`: O elemento de **divisão** genérico. É muito usado para agrupar e estilizar blocos de
  conteúdo com CSS.

* `<header>`: Representa o **conteúdo introdutório** ou de navegação do topo.

* `<nav>`: Contém **links de navegação**.

* `<main>`: Define o **conteúdo principal** e exclusivo do documento.

* `<section>`: Agrupa **conteúdo relacionado** (por exemplo, um capítulo).

* `<article>`: Define **conteúdo independente** e autocontido (como um post de blog).

* `<aside>`: Representa o conteúdo que está **relacionado tangencialmente** ao conteúdo ao
  seu redor (como uma barra lateral).

* `<footer>`: Representa o **rodapé** de um documento ou seção.
