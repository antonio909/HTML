# HTML - Tags e Atributos

O HTML (HyperText Markup Language) é a espinha dorsal de qualquer página web. Ele é
baseado em dois conceitos principais para estruturar o conteúdo: **Tags** e **Atributos**.

## Tags HTML (Marcações)

* **O que são:** As tags são as palavras-chave que definem o tipo de conteúdo na página
  (parágrafos, títulos, links, imagens, etc.). Elas são a base para a criação dos **Elementos**
  HTML.

* **Sintaxe:** Uma tag de abertura começa com `<` e termina com `>`. Se houver conteúdo, ela é
  seguida por uma tag de fechamento, que adiciona uma barra `/` antes do nome da tag.

  * **Com Fechamento:** `<p>Este é um parágrafo.</p>`

  * **Sem Fechamento (Self-closing):** Tags que não contém conteúdo, como `<br>` (quebra
    de linha) e `<img>` (imagem).

* **Exemplos Comuns:**

  * **Estrutura:** `<html>`, `<heady>`, `<body>`

  * **Conteúdo:** `<h1>` a `<h6>` (Títulos), `<p>` (Parágrafo), `<a>` (Link), `<img>` (Imagem),
    ´<ul>´ e `<ol>` (Listas)

  * **Divisão:** `<div>`, `<span>` (Usadas para agrupar e estilizar)

## Atributos HTML

* **O que são:** Os atributos fornecem **informações adicionais** ou **instruções** sobre um
  elemento HTML. Eles modificam o comportamento, a aparência ou a funcionalidade padrão
  da tag.

* **Sintaxe:** Um atributo é sempre definido na **tag de abertura** e possui a estrutura:
  `nome="valor"`.

  * **Exemplo:** `<a href="https://www.google.com" target="_blank">Google</a>`

    * `href` e `target` são os **nomes** dos atributos.

    * `"https://www.google.com"` e `"_blank"` são os **valores** dos atributos.

  * **Tipos de Atributos:**

    * **Globais:** Podem ser usados em *qualquer* tag HTML. Os mais importantes são:

      * `class`: Usado para agrupar elementos e aplicar estilos com CSS ou manipular com
        JavaScript.

      * `id`: Usado para **identificar de forma única** um elemento na página (útil para links
        internos ou JavaScript).

      * `style`: Permite aplicar estilos CSS diretamente no elemento.

      * `lang`: Específica o idioma do conteúdo do elemento.

    * **Específicos:** Funcionam apenas em tags específicas.

      * `src`: Usado em `<img>`, `<script>` ou `<video>` para indicar a origem do arquivo.

      * `href`: Usado na tag `<a>` para indicar o URL de destino do link.

      * `alt`: Usado em `<img>` para fornecer um texto alternativo caso a imagem não
        carregue (importante para acessibilidade e SEO).

      * `type`: Usado em `<input>` para definir o tipo do campo (texto, senha, botão, etc.).

## Exemplo Prático de Tags e Atributos:

```
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <title>Minha Página HTML</title>
</head>
<body>
  <h1 id="titulo-principal">Título da Página</h1>

  <p class="introducao">
    Este é um parágrafo com um <a href="pagina2.html" target="_self">link para outra página</a>.
  </p>

  <img src="imagem.jpg" alt="Descrição da Imagem" width="300">
</body>
</html>
```

| Componente | Tipo | Explicação |
|------------|------|------------|
| `<h1>` | Tag | Define um título de nível 1. |
| `id` | Atributo Global | Identificador único para o `<h1>`. |
| `lang` | Atributo Global | Define o idioma do documento (`<html>`). |
| `<p>` | Tag | Define um parágrafo de texto. |
| `class` | Atributo Global | Usado para aplicar estilo CSS ao parágrafo. |
| `href` | Atributo Específico | Define o destino do link (`<a>`). |
| `src` | Atributo Específico | Define a origem (URL) da imagem (`<img>`). |
| `alt` | Atributo Específico | Texto alternativo para a imagem (`<img>`). |
