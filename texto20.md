# HTML - Declaração !DOCTYPE

O `<!DOCTYPE html>` é a **declaração de tipo de documento** para HTML5 e é a **primeira coisa
que deve aparecer em documento HTML.

-----

## Finalidade Principal

A principal finalidade do `<!DOCTYPE html>` é informar ao navegador qual é a versão do HTML
usada no documento. Especificamente:

* **Renderização Padrão:** Garante que o navegador tente renderizar a página no **modo
  padrão** ("standards mode") em vez do "quirks mode" (modo de compatibilidade com
  navegadores antigos e práticas não-padrão). O modo padrão garante que o CSS e o
  JavaScript se comportem de maneira previsível e consistente, seguindo as especificações
  modernas.

* **Declaração Simples:** Para o **HTML5**, a declaração é incrivelmente simples: `<!DOCTYPE
  html>`. Nas versões anteriores do HTML (como o HTML 4.01), era uma declaração muito
  longa e complexa.

-----

## Regras Essenciais

* **Posição:** Deve ser o **primeiro** código no arquivo HTML, antes da tag `<html>`.

* **Obrigatoriedade:** Embora tecnicamente não seja uma *tag* HTML, é uma **instrução
  obrigatória** em todos os documentos HTML5.

* **Case Insensitive:** A declaração **não diferencia maiúsculas de minúsculas** (*é case-
  insensitive*), então `<!DOCTYPE html>`, `<!doctype html>`, e `<!DoCtYpE hTmL>` são todos
  válidos, mas a convenção e a prática comum é usar `<!DOCTYPE html>`.

-----

## Exemplo de Estrutura

Aqui está a estrutura básica de um documento HTML5 válido:

```HTML

<!DOCTYPE html>
<html>
<head>
  <title>Minha Página</title>
</head>
<body>
  <h1>Olá Mundo</h1>
  <p>Este é um parágrafo.</p>
</body>
</html>

```

-----

O uso correto do `<!DOCTYPE html>` é um passo fundamental para garantir que sua página web
seja exibida de forma consistente em diferentes navegadores modernos.
