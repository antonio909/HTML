# HTML - Case-insensitivity

O HTML é, em geral, **não sensível a maiúsculas e minúsculas** (case-insensitive) no que diz
respeito aos nomes de tags (marcadores) e atributos.

## O que significa "Case-Insensitive" em HTML?

Significa que o *browser* (navegador) interpreta os nomes dos elementos e atributos de forma
idêntica, independentemente de estarem escritos em maiúsculas, minúsculas ou uma mistura de
ambas.

* **Exemplo para Tags:** As seguintes formas são todas válidas e o navegador as trata da
  mesma maneira:

  * `<p>`

  * `<P>`

  * `<p>`

* **Exemplo para Atributos:** O atributo `method` em um formulário, por exemplo, aceita valores
  como `GET` ou `POST` sem diferenciar a capitalização:

  * `<form method="GET">`

  * `<form method="get">`

  * `<form method="gEt">`

## Melhores Práticas e Exceções

### Recomendação Padrão

Embora o HTML seja *case-insensitive* para tags e atributos, a **convenção e a boa prática** de
codificação, especialmente ao considerar a integração com outras tecnologias como **XHTML** e
**CSS**, é escrever **todos os nomes de tags e atributos em minúsculas**.

### Exceções

A não sensibilidade a maiúsculas e minúsculas **não se aplica ao conteúdo** de todos os
atributos.

* **Valores de Atributos:** Os **valores** de alguns atributos **são sensíveis a maiúsculas e
  minúsculas** (*case-sensitive*), principalmente aqueles que se referem a:

  * **URLs/Nomes de Arquivo:** O valor do atributo `src` de uma imagem ou `href` de um *link*
    é **case-sensitive** porque o sistema operacional do servidor web que hospeda o arquivo
    geralmente diferencia maiúsculas e minúsculas nos nomes de arquivos. Exemplo:
    `minhaImagem.jpg` é diferente de `MinhaImagem.JPG`.

* **IDs e Classes:** Embora os navegadores geralmente não se importem, o padrão CSS para
  seletores de ID (#) e Classe (.) é, por defeito, **case-sensitive**. Por isso,
  `class="Menu"` é diferente de `class="menu"`. É melhor tratar esses valores como *case-
  sensitive* para manter a consistência com o CSS e JavaScript.

Em resumo, para garantir a **compatibilidade** e a **manutenção** do código, **escreva tags e
atributos em minúsculas** e preste **atenção especial** à capitalização nos **valores de atributos**
que referenciam arquivos ou IDs/Classes.

Em resumo, para garantir a compatibilidade e a manutenção do código, escreva tags e atributos em minúsculas e preste atenção especial à capitalização nos valores de atributos que referenciam arquivos ou IDs/Classes.
