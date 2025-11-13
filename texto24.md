# HTML - Elemento META

O elemento `<meta>` em HTML é usado para fornecer **metadados** (metainformações) sobre o
documento HTML. Ele é sempre colocado dentro do elemento `<head>` e **não tem uma tag de
fechamento** (é um elemento vazio).

Esses metadados não são exibidos diretamente na página, mas são cruciais para navegadores,
mecanismos de busca e outros serviços da web entenderem e processarem a página
corretamente.

-----

## Atributos e Funções Principais

O elemento `<meta>` utiliza principalmente os atributos `name`, `content`, `charset` ou `http-
equiv` para definir o tipo de metadado.

1. `charset` **(Conjunto de Caracteres)**

Define a codificação de caracteres do documento. **É fundamental** que seja a primeira tag
`<meta>` dentro do `<head>`.

```HTML

<meta charset="UTF-8">

```

* **Função:** Garante que todos os caracteres (incluindo acentos e símbolos) sejam exibidos
  corretamente. `UTF-8` é a codificação universalmente recomendada.

2. `name` e `content` **(Metadados Gerais)**

Usados para fornecer informações de nome/valor. O atributo `name` especifica o tipo de
metadado, e `content` fornece o valor.

| Exemplo de Código | `name` | Função |
|-----|-----|-----|
| `<meta name="description" content="Uma breve descrição sobre a página">` | `description` | Resumo do conteúdo da página, usado por motores de busca nos resultados da pesquisa (SERP). |
| `<meta name="keywords" content="html,css,javascript">` | `keywords` | Lista de palavras-chave relacionadas ao conteúdo (menos relevante para CEO hoje em dia, mas ainda usado). |
| `<meta name="viewport" content="width=device-width, initial-scale=1.0">` | `viewport` | Essencial para **design responsivo**, controla a dimensão da área de visualização do navegador no dispositivo (largura igual à do dispositivo, zoom inical de 100%). |
