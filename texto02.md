# Conceitos de Linguagens de Marcação

Uma **Linguagem de Marcação** (*Markup Language*) é um sistema para anotar um documento de
forma a descrever sua **estrutura** e, em alguns casos, sua **apresentação**. Ela utiliza códigos,
geralmente chamados de **tags** ou **marcas**, que são inseridas no texto ou dados para fornecer
informações adicionais

1. **O que são Tags(Marcas)?**

As tags são os componentes essencias de uma linguagem de marcação. Elas servem para:

* **Delimitar** partes do documento (elementos).

* **Fornecer metainformações** (dados sobre os dados).

* **Definir formatação** e/ou **estilo** (dependendo do tipo de marcação).

**Exemplo Básico (em HTML):**

`<p>Este é um parágrafo.</p>`

* `**<p>**`: Tag de abertura, indica o início de um parágrafo.

* `**</p>**`: Tag de fechamento, indica o fim do parágrafo.

* `**Este é um parágrafo.**`: O conteúdo do elemento.

2. **Classificações da Marcação**

As linguagens de marcação podem ser categorizadas com base no propósito da marcação:

| Tipo de Marcação | Objetivo Principal | Exemplos |
|------------------|--------------------|----------|
| **Descritiva** | Descrever a **estrutura** lógica e o significado das partes do documento, separando a estrutura do processamento. Foco no **"o que é"** (um título, um parágrafo, um produto, etc.). | **XML**, **SGML**, **HTML** (foco na estrutura) |
| **Apresentação** | Incorporar marcas no texto para ditar sua **aparência** visual (negrito, itálico, tamanho da fonte). | Algumas tags descontinuadas do HTML. |
| **Procedimental** | Fornecer **instruções** para que um programa processe o texto (como formatar, onde quebrar a página, etc.). | **Tex**, **troff**, **PostScript** |

3. **Diferença Crucial: Marcação vs. Programação**

É importante notar a diferença fundamental:

| Linguagem de Marcação | Linguagem de Programação |
|-----------------------|--------------------------|
| Usada para **estruturar e formatar** dados/texto. | Usada para controlar o **comportamento** de máquinas e expressar **algoritmos**. |
| **Não contém lógica** de programação (não faz cálculos, nem toma decisões. | Contém **lógica** (condicionais, laços, funções). |
| **Exemplos:** HTML, XML, Markdown. | **Exemplos:** Python, Java, C++, JavaScript. |

4. **Principais Linguagens de Marcação**

| Linguagem | Nome Completo | Uso Principal | Característica Chave |
|-----------|---------------|---------------|----------------------|
| **SGML** | *Standard Generalized Markup Language* | Padrão precursor; serviu de base para HTML e XML. | Define um conjunto de regras para criar outras linguagens de marcação (metalinguagem). |
| **HTML** | *HyperText Markup Language* | Criação de documentos e páginas web. | Possui um conjunto **predefinido** de tags. Define a estrutura e elementos em navegadores. |
| **XML** | *eXtensible Markup Language* | Armazenamento e intercâmbio de dados. | É **extensível**; não tem tags predefinidas. O usuário define suas próprias tags. Foco na descrição dos dados. |
| **XHTML** | *eXtensible HyperText Markup Language* | Combinação de HTML e XML (segue regras sintáticas mais rigorosas do XML). | Maior rigor sintático que o HTML 4 (atualmente menos utilizada que o HTML5). |
| **Markdown** | (Sem nome completo) | Formatação de texto simples (readme, blogs, documentação). | É uma linguagem de **marcação leve**, mais fácil de ler e escrever. |
