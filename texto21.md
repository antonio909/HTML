# HTML - Elemento <html>

O elemento `<html>` é o **elemento raiz** de um documento HTML. Ele é o contêiner de todos os
outros elementos HTML (exceto a declaração `<!DOCTYPE>`) e sinaliza ao navegador onde o
documento HTML começa e termina.

-----

## Estrutura e Função

* **Raiz do Documento:** Tudo que pertence ao documento HTML (o cabeçalho e o corpo)
  deve estar aninhado dentro deste elemento.

* **Contêiner:** Ele atua como o principal contêiner para o elemento `<head>` (que contém
  metadados) e o elemento `<body>` (que contém o conteúdo visível da página).

* **Obrigatório (Tecnicamente Opcional):** Embora a especificação HTML5 permita que a *tag*
  de abertura (`<html>`) seja omitida, é uma **prática recomendada** incluí-la para garantir a
  compatibilidade e a clareza. A *tag* de fechamento (`</html>`) também é frequentemente
  opcional em HTML5, mas incluí-la torna o código mais robusto.

  -----

  ## Atributo Principal: `lang`

  O atributo mais importante a ser usado no elemento `<html>` é o `lang`.

  * **Sintaxe:** `<html lang="código_do_idioma">`

  * **Função:** Define o **idioma principal** do conteúdo do documento. Isso é crucial para:

    * **Acessibilidade:** Leitores de tela podem pronunciar o conteúdo corretamente.

    * **SEO (Otimização para Mecanismos de Busca):** Ajuda os mecanismos de busca a
      categorizar o conteúdo por idioma.

    * **Navegadores:** Ajuda os navegadores a oferecer traduções.

  * **Exemplo:** Para português do Brasil, você usaria: `<html lang="pt-BR">`

  -----

  ## Exemplo Básico de Código

  Veja como o elemento `<html>` se encaixa na estrutura básica de um documento:

  ```HTML

  <!DOCTYPE html>
  <html lang="pt-BR">
  <head>
    <meta charset="UTF-8">
    <title>Minha Primeira Página</title>
  </head>
  <body>
    <h1>Olá Mundo!</h1>
    <p>Este é o conteúdo principal da página.</p>
  </body>
  </html>

  ```

  O elemento `<html lang="pt-BR">` engloba todo o conteúdo da página, definindo-o como um
  documento HTML cujo idioma primário é o português do Brasil.
