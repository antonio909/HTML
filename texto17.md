# HTML - Cometários

Os comentários em HTML são usados para **adicionar anotações ou explicações** dentro do seu
código, mas **não são exibidos** na janela do navegador para o usuário final. Eles são
extremamente úteis para documentar seu código, facilitar a leitura por outros desenvolvedores
(ou por você mesmo no futuro) e desativar temporariamente partes do código.

-----

## Sintaxe do Comentário

A sintaxe para iniciar e encerrar um comentário em HTML é a seguinte:

$$\text{}$$

  * **Início:** O comentário **começa** com \`\`

**Exemplo Prático:**

```html
<!DOCTYPE html>
<html>
<head>
    <title>Exemplo de Comentário</title>
</head>
<body>

    <h1>Título Principal</h1>

    <p>Este é o conteúdo principal da página.</p>

    <div>Outra seção.</div>

</body>
</html>
```

-----

## Usos Comuns dos Comentários

1.  **Explicações e Documentação:**

      * Descrever a função de uma seção complexa do código.
      * Indicar quem escreveu ou quando o código foi modificado.

2.  **Desativar Conteúdo (Comentar o Código):**

      * Você pode envolver qualquer código HTML, CSS ou JavaScript com comentários para
        que ele não seja renderizado pelo navegador temporariamente. Isso é ótimo para testes
        ou para "guardar" código que você pode precisar mais tarde.

    > **Exemplo de desativação:**

    > ````html
    > > ```
    > ````

3.  **Lembretes:**

      * Colocar notas para si mesmo sobre o que precisa ser feito em seguida.

-----

## ⚠️ Observações Importantes

  * **Não São Visíveis:** Lembre-se que o **conteúdo dentro dos comentários não aparece na
    página**, mas ele **pode ser visto** por qualquer pessoa que inspecione o código-fonte da
    página (clicando com o botão direito $\rightarrow$ "Ver Código Fonte da Página" ou usando as
    Ferramentas do Desenvolvedor).
  * **Aninhamento:** Comentários HTML **não podem ser aninhados** (colocar um comentário
    dentro de outro). O primeiro `-->` que o navegador encontrar encerrará o comentário.
