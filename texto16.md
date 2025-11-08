# HTML - Entities

As **HTML Entities** (Entidades HTML) são sequências de caracteres usadas para representar
**símbolos especiais** em documentos HTML. Elas são esseciais por duas razões principais:

## Propósito das Entidades HTML

* **Exibir Caracteres Reservados:** Permitem exibir caracteres que possuem um **significado
  especial** em HTML, como o sinal de "menor que" (`<`) ou o "e comercial" (`&`), que são
  usados para definir tags e as próprias entidades, respectivamente.

* **Exibir Caracteres Não Presentes no Teclado: Possibilitam a inclusão de símbolos que não
  são facilmente digitáveis (como sinais de moeda, caracteres diacríticos complexos, ou
  símbolos matemáticos) ou que historicamente causavam problemas de codificação.

## Estrutura da Entidade

Uma Entidade HTML é uma sequência de código que começa com um **"e comercial"** (`&`) e
termina com um **"ponto e vírgula"** (`;`).

Existem duas formas principais de representá-las:

1. **Por Nome:** Mais fácil de lembrar, mas nem todos os navegadores suportam os nomes mais
   novos.

   * **Formato:** `&nome_da_entidade;`

   * Exemplo: `&lt;`

2. **Por Número (Código Numérico Decimal ou Hexadecimal):** Geralmente suportado por
   praticamente todos os navegadores.

   * **Formato:** `&#código_decimal;` ou `&#código_hexadecimal;`

   * Exemplo: `&#60;`

## Entidades Mais Comuns

Abaixo estão algumas das Entidades HTML mais frequentemente utilizadas, especialmente as
que representam caracteres reservados:

| Resultado | Descrição | Nome da Entidade | Código Numérico (Decimal) |
|-----------|-----------|------------------|---------------------------|
| **<** | Menor que (*Less Than*) | `&lt;` | `&#60;` |
| **>** | Maior que (*Greater Than*) | `&gt;` | `&#62;` |
| **&** | E Comercial (*Ampersand*) | `&amp;` | `&#38;` |
| **"** | Aspas Duplas (*Double Quote*) | `&quot;` | `&#34;` |
| **'** | Aspas Simples (*Apostrophe*) | `&apos;` | `&#39;` |
|       | Espaço Não Separável (*Non-breaking Space*) | `&nbsp;` | `&#160;` |

O **Espaço Não Separável** (`&nbsp;`) é particularmente importante, pois o HTML
normalmente ignora múltiplos espaços em branco consecutivos no código-fonte,
tratando-os como um único espaço. Usar `&nbsp;` força a exibição de espaços
adicionais.

## Outros Símbolos Úteis

Muitos outros símbolos podem ser representados por entidades:

| Resultado | Descrição | Nome da Entidade | Código Numérico (Decimal) |
|-----------|-----------|------------------|---------------------------|
| © | Copyright | `&copy;` | `&#169;` |
| ® | Marca Registrada (*Registered*) | `&reg;` | `&#174;` |
| € | Euro | `&euro;` | `&#8364;` |
| ™ | Marca Comercial (*Trademark*) | `&trade;` | `&#8482;` |
| á | Letra 'a' com acento agudo | `&aacute;` | `&#225;` |
| ñ | Letra 'n' com til | `&ntilde;` | `&#241;` |
| — | Traço Longo (*Em Dash*) | `&mdash;` | `&#8212;` |
