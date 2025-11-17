# HTML - Tag `<p>`

A tag HTML `<p>` (do inglês **paragraph**) é usada para definir um **parágrafo** de texto. É um dos
elementos de bloco mais fundamentais e amplamente utilizados no HTML para estruturar o conteúdo.

## Características Principais

* **Propósito:** Ela agrupa frases e textos relacionados em um único bloco de parágrafo.

* **Elemento de Bloco:** Por padrão, o `<p>` é um elemento de bloco (*block-level element*), o
  que significa que ele ocupa toda a largura disponível de seu contêiner e sempre começa em
  uma nova linha.

* **Conteúdo Permitido:** Ele só pode conter conteúdo de *phrasing* (*phrasing content*), ou seja,
  elementos que fazem parte da frase ou fluxo de texto, como texto simples, *links* (`<a>`),
  ênfase (`<em>` ou `<strong>`), imagens (`<img>`), etc. **Não** deve conter outros elementos de
  bloco como `<div>`, `<h1>`, `<ul>`, ou outro `<p>`.

* **Margem:** Os navegadores geralmente adicionam um espaço (margem) antes e depois de
  um parágrafo para separá-lo visualmente de outros elementos.

* **Fechamento de Tag:** A tag de fechamento `</p>` é tecnicamente **opcional** em algumas
  situações no HTML5, se o parágrafo for imediatamente seguido por outra tag de bloco
  (como outro `<p>`, `<h1>`, `<ul>`, etc.). No entanto, é **altamente recomendável** sempre
  incluir a tag de fechamento para garantir a compatibilidade e a legibilidade do código.

-----

## Exemplo de Uso

Um exemplo simples de como a tag `<p>` é usada:

```HTML

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8">
  <title>Exemplo de Tag P</title>
</head>
<body>

  <h1>Título Principal</h1>

  <p>Este é o primeiro parágrafo de texto. Ele será exibido em uma linha separada no navegador, com algum espaço acima e abaixo dele.</p>

  <p>Este é o segundo parágrafo. Ele está aqui para demonstrar a separação automática que o navegador aplica entre os elementos de parágrafo.</p>

</body>
</html>

```

-----

## Observação Importante

Não utilize a tag `<p>` apenas para criar espaços em branco ou quebras de linha entre o texto.
Para uma quebra de linha simples (sem iniciar um novo parágrafo), use a tag `<br>`. Para
controlar o espaçamento entre elementos, é melhor usar **CSS** (Cascading Style Sheets).
