# HTML - Tag de Títulos

No HTML, as tags de títulos (ou *headings*) são usadas para definir **títulos e subtítulos** em uma
página web. Elas são cruciais para a estrutura e a **hierarquia semântica** do conteúdo, além de
serem muito importantes para a **acessibilidade** e a **otimização para motores de busca (SEO)**.

-----

## Tags e Hierarquia

O HTML oferece **seis** níveis de títulos, do mais importante ao menos importante:

| Tag | Nível de Importância | Uso Tipico |
|-----|-----|-----|
| `<h1>` | O mais alto | Título principal da página (deve haver **apenas um** `<h1>` por página). |
| `<h2>` | Alto | Títulos de seções principais dentro da página. |
| `<h3>` | Médio-Alto | Subtítulos das seções definidas por `<h2>`. |
| `<h4>` | Médio | Subtítulos de níveis mais profundos. |
| `<h5>` | Médio-Baixo | Títulos raramente usados, para estrutura muito detalhada. |
| `<h6>` | O mais baixo | O menor e menos importante título. |

-----

## Exemplo de Código

Aqui está como você as usaria no código HTML:

```HTML

<!DOCTYPE html>
<html>
<head>
  <title>Exemplo de Títulos</head>
</head>
<body>

  <h1>Título Principal da Matéria</h1>

  <h2>Introdução</h2>
  <p>Texto de introdução...</p>

  <h2>Desenvolvimento do Tema</h2>

  <h3>O Primeiro Ponto de Vista</h3>
  <p>Texto sobre o primeiro ponto...</p>

  <h3>O Segundo Ponto de Vista</h3>
  <p>Texto sobre o segundo ponto...</p>

  <h2>Conclusão</h2>
  <p>Texto de conclusão...</p>

</body>
</html>

```
-----

## Regras Essenciais

1. **Ordem Lógica:** Use as tags de títulos **na ordem hierárquica correta**. Nunca pule níveis
   (por exemplo, ir de um `<h2>` direto para um `<h4>`). A estrutura deve ser lógica, como um
   índice de livro.

2. **Um** `<h1>` **por Página:** Cada página HTML deve ter **apenas um** `<h1>`, que representa o
   assunto principal daquela página.

3. **Não para Estilo:** O tamanho da fonte padrão dessas tags pode ser alterado via **CSS**. Você
   deve usá-las pela **semântica** (a estrutura lógica do conteúdo), e não apenas para fazer o
   texto parecer maior ou em negrito.
