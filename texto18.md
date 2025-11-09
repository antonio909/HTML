## HTML - Whitespaces

Os **"Whitespaces"** (espaços em branco) em **HTML** referem-se a qualquer sequência de **espaços**, **tabulações** ou **quebras de linha** que são ignoradas ou colapsadas pelo navegador durante a renderização de uma página.

## Comportamento Padrão do HTML

Por padrão, o HTML **colapsa** múltiplos espaços em branco (incluindo espaços, tabulações e quebras de linha no código) em um **único espaço** na exibição.

  * **Exemplo:**
    ```html
    <p> Este texto tem          muitos
    espaços e
    quebras de linha. </p>
    ```
  * **Resultado no Navegador:**
    > Este texto tem muitos espaços e quebras de linha.

## Como Inserir Espaços Adicionais ou Preservar a Formatação

Se você precisa de mais de um espaço ou quer manter a formatação exata (incluindo quebras de linha e múltiplos espaços), existem algumas técnicas principais:

| Técnica | Descrição | Uso Principal |
| :--- | :--- | :--- |
| **Entidade `&nbsp;`** | **Espaço Não Quebrável** (`Non-breaking space`). Insere um espaço adicional que **não é colapsado**. Também impede que uma quebra de linha ocorra naquele ponto. | Espaços extras entre palavras ou caracteres; preencher células vazias em tabelas. |
| **Tag `<br>`** | Força uma **quebra de linha** (igual a um `Enter`). | Inserir quebras de linha manuais em textos (não use para layout). |
| **Propriedade `white-space` (CSS)** | Controla como o navegador trata os espaços em branco dentro de um elemento. Valores como `pre`, `pre-wrap` ou `pre-line` alteram o comportamento padrão. | Preservar espaços e quebras de linha, como ao exibir códigos de programação ou poesia. |
| **Tag `<pre>`** | Exibe o texto em uma **fonte monoespaçada** e preserva **todos** os espaços em branco e quebras de linha exatamente como foram digitados (comportamento similar a `white-space: pre`). | Exibir blocos de código ou texto pré-formatado. |
| **`margin` e `padding` (CSS)** | **Margens** (espaço externo ao elemento) e **Preenchimento** (espaço interno ao elemento). | **Método recomendado** para controlar o espaçamento entre ou ao redor de elementos para fins de layout. |

-----

Para saber mais sobre como controlar o tratamento de espaços no HTML usando CSS, confira a videoaula sobre a propriedade `white-space`: [CSS: Aula \#36 - Propriedade white-space](https://www.youtube.com/watch?v=_W2-ExxUhxo).

http://googleusercontent.com/youtube_content/0
