# Desenvolvimento Frontend - HTML

O **HTML** (HyperText Markup Language - Linguagem de Marcação de Hipertexto) é o **bloco de
construção mais fundamental da Web**.

Ele é essencial no Desenvolvimento Frontend, pois:

* **Define a Estrutura:** O HTML é responsável por dar **significado e estrutura** ao conteúdo de
  uma página web. É como "esqueleto" do site.

* **Utiliza Marcações (Tags):** A estrutura é criada através de **tags** (como `<h1>` para um título
  principal, `<p>` para um parágrafo, `<img>` para uma imagem), que orientam o navegador
  sobre como exibir as informações.

* **Base para Outras Tecnologias:**

  * Sozinho, o HTML cria páginas estáticas.

  * Ele trabalha em conjunto com o **CSS** (Cascading Style Sheets) para definir a
    **aparência/estilo** (cores, layout, fontes).

  * E com o **JavaScript** para adicionar **funcionalidade/interatividade** (comportamento
    dinâmico).

## Estrutura Básica de um Documento HTML

Um documento HTML básico geralmente segue esta estrutura:

```
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Título da Minha Página</title>
</head>
<body>
  <h1>Meu Título Principal</h1>
  <p>Este é um parágrafo de exemplo.</p>
  <a href="outra_pagina.html">Link para Outra Página</a>
</body>
</html>
```

## Principais Conceitos

* **Tags e Elementos:** Tags definem o início e fim de um elemento (`<p>` e `</p>`). O elemento é
  todo o conteúdo entre as tags, incluindo as tags em si.

* **Atributos:** Fornecem informações adicionais sobre o elemento. Por exemplo, o atributo
  `href` na tag `<a>` especifica o destino do link.

* **HTML5:** É a versão mais recente e amplamente utilizada. Ela introduziu novas tags
  **semânticas** (como `<header>`, `<nav>`, `<article>`, `<footer>`) que dão mais significado ao
  conteúdo, além de suporte nativo a multimídia (vídeo e áudio).
