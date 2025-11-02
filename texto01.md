# Introdução ao HTML

O **HTML (HyperText Markup Language - Linguagem de Marcação de Hipertexto)** é a
espinha dorsal da web. Ele é usado para **estruturar** o conteúdo de uma página da internet.

## O que é HTML?

* **Linguagem de Marcação:** O HTML não é uma Linguagem de Programação. Em vez disso, ele
  usa um conjunto de **"etiquetas"** ou **"tags"** para envolver o conteúdo e dar-lhe um
  significado (por exemplo, "isto é um parágrafo", "isto é um título", "isto é uma imagem").

* **Estrutura:** Ele diz ao navegador como deve exibir o conteúdo no ecrã, organizando-o em
  seções lógicas.

* **Arquivos:** Os documentos HTML são arquivos de texto simples que terminam com a
  extensão `.html` ou `.htm`.

## Conceitos Fundamentais

1. **Elementos e Tags**

A maior parte do HTML é composta por **elementos**. Um elemento geralmente consiste em:

* **Tag de abertura:** `<p>`

* **Conteúdo:** `Este é um parágrafo.` 

* **Tag de fechamento:** `</p>`

Juntos, eles formam o **elemento:** `<p>Este é um parágrafo.</p>`

* **Exceção:** Alguns elementos são "vazios" (não contêm conteúdo) e não precisam de uma tag
  de fechamento, como o elemento de quebra de linha `<br>`.

2. **Atributos**

Os atributos são usados para fornecer informações adicionais sobre um elemento e são sempre
colocados na **tag de abertura**.

**Exemplo:**

`<img src="imagem.jpg" alt="Descrição da imagem">`

* `src` e `alt` são **atributos** do elemento `<img>`.

* Eles fornecem informações extras (a fonte da imagem e um texto alternativo,
  respetivamente).

3. **Estrutura Básica de um Documento HTML**

Todo documento HTML deve ter uma estrutura fundamental:

```
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Título da Página</title>
</head>
<body>
  <h1>Meu Primeiro Título</h1>
  <p>Este é um parágrafo de exemplo.</p>
</body>
</html>
```

* `<!DOCTYPE html>`: Declara o tipo de documento, informando ao navegador que se trata de
  HTML5.

* `<html>`: O elemento raiz que envolve todo o conteúdo da página.

* `<head>`: Contém informações (metadados) sobre o documento, como o conjunto de
  caracteres e o título que aparece na aba do navegador.

* `<body>`: Contém todo o conteúdo que o utilizador vê.

## HTML, CSS e JavaScript

O HTML é apenas uma das três tecnologias principais que formam a maior parte dos sites:

| Tecnologia | Função Principal | Analogia |
|------------|------------------|----------|
| **HTML**   | **Estrutura** o conteúdo (esqueleto). | O esqueleto e os órgãos. |
| **CSS**    | **Estiliza** o conteúdo (aparência, cores e layout). | A roupa, maquiagem e design. |
| **JavaScript** | Adiciona **interatividade** e funcionalidade dinâmica. | O movimento e a inteligência. |
