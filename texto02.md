# Teoria - Linguagem de Marcação

A Teoria da Linguagem de Marcação explica como os símbolos e
códigos são usados para anotar texto, definindo sua estrutura,
formatação e a relação entre suas partes. A principal ideia é separar o
conteúdo (o texto em si) da sua apresentação (como ele será exibido),
permitindo que diferentes dispositivos e programas o interpretem e
exibam de maneiras distintas.

## Conceitos fundamentais

* **Conteúdo e marcação:** Um documento marcado é composto por
  duas partes: o conteúdo que será exibido e a marcação (os "sinais
  e códigos") que fornece instruções sobre a estrutura e a aparência
  do conteúdo. A marcação é invisível para o usuário final, mas é
  fundamental para o navegador ou outro software interpretar o
  documento.

* **Tags e elementos:** As tags são as instruções que "envolvem" o
  conteúdo. Por exemplo, em HTML, a tag `<h1>` indica um título
  principal. Um elemento é a combinação da tag (abertura e
  fechamento) com o conteúdo que está entre elas.

* **Declaração de documento:** Em muitas linguagens de marcação,
  existe uma declaração inicial que especifica o tipo de documento,
  permitindo que o processador saiba como interpretá-lo. 

## Tipos de linguagem de marcação

As linguagens de marcação podem ser categorizadas de acordo com
seu propósito e forma de funcionamento: 

* **Marcação de apresentação:** Incorpora marcações no texto para
  definir a formatação visual, como a exibição de texto em negrito ou
  itálico. É utilizada por processadores de texto.

* **Marcação procedimental:** Fornece instruções para o
  processamento do texto por um programa.

* **Marcação genérica (ou descritiva):** Descreve a estrutura e as
  características de um documento de forma independente do
  dispositivo, com foco na sua organização lógica. 

## Principais linguagens de marcação

* **SGML (Standard Generalized Markup Language):** O padrão
  original para a definição de linguagens de marcação. Ele
  estabeleceu as bases para a criação do HTML e do XML,
  permitindo a definição de gramáticas e regras para documentos
  complexos. Foi a partir dele que surgiu a ideia de separar a
  estrutura do conteúdo da sua apresentação.

* **HTML (HyperText Markup Language):** A linguagem de marcação
  padrão para a criação de páginas web. Define a estrutura e o
  conteúdo das páginas por meio de tags, que indicam ao navegador
  como exibir elementos como títulos, parágrafos, imagens e links.
  Atualmente, o HTML não é mais baseado em SGML, tendo suas
  próprias regras.

* **XML (eXtensible Markup Language):** Uma linguagem de
  marcação versátil e extensível, usada para armazenar e
  transportar dados de forma estruturada. Ao contrário do HTML, o
  XML não tem tags predefinidas; o usuário pode criar as suas
  próprias para descrever o conteúdo de forma específica. É uma
  metalinguagem, pois permite criar outras linguagens.

* **Markdown:** Uma linguagem de marcação leve que permite
  formatar texto de forma simples e intuitiva, usando uma sintaxe de
  fácil leitura e escrita. É frequentemente usada para documentação,
  blogs e arquivos `README`.

* **MathML (Mathematical Markup Language):** Utilizada para exibir
  equações e fórmulas matemáticas na web.

* **SVG (Scalable Vector Graphics):** Uma linguagem baseada em
  XML usada para descrever gráficos vetoriais bidimensionais, como
  ícones e ilustrações. 

## Importância

As linguagens de marcação são cruciais porque permitem que os
dados sejam estruturados de forma padronizada, o que facilita a
leitura e o processamento por diferentes programas e plataformas.
Essa padronização é a base da World Wide Web e de inúmeros
sistemas de gerenciamento de dados e documentos. 
