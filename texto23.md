# HTML - Elemento HEAD

O elemento `<head>` em HTML é um **container** para **metadados** (dados sobre o documento
HTML) e está posicionado entre a tag `<html>` e a tag `<body>`. Ele **não** exibe conteúdo
diretamente na página da web para o usuário.

-----

## Função Principal

O `<head>` contém informações essenciais sobre a página que são usadas pelo **navegador** (para
renderização e funcionalidade) e por **mecanismos de busca** (para indexação e apresentação de
resultados).

-----

## Elementos Comuns Dentro de `<head>`

Alguns dos elementos mais frequentemente encontrados dentro do `<head>` incluem:

* `<title>`: **Obrigatório**. Define o título que aparece na **aba do navegador** ou na janela. É
  crucial para SEO (Search Engine Optimization).

* `<meta>`: Usado para especificar a **codificação de caracteres** (ex: `<meta charset="UTF-
  8">`), a **viewport** para responsividade, a **descrição** da página, **palavras-chave**, e o **autor**.

* `<link>`: Usado para **vincular folhas de estilo externas** (CSS). Ex: `<link
  rel="stylesheet" href="styles.css">`.

* `<style>`: Usado para escrever **estilos CSS externos** diretamente no documento HTML.

* `<script>`: Pode ser usado para incluir **código JavaScript**, embora geralmente seja
  recomendado colocar scripts no final do `<body>` para melhorar o desempenho de
  carregamento.

* `<base>`: Especifica a URL base e/ou o destino padrão para todos os URLs relativos em um
  documento.

-----

## Exemplo Básico

Aqui está como o elemento `<head>` se encaixa na estrutura básica de um documento HTML:

```HTML

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página Web</title>
    <link rel="stylesheet" href="estilos.css">
</head>
<body>
    <h1>Olá Mundo!</h1>
</body>
</html>

```
