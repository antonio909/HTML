# Preenchendo a página: Como funcionam os navegadores

Quando você digita um endereço em um navegador, um processo
complexo de renderização é acionado para exibir a página na sua tela.
Esse processo, que envolve a comunicação com servidores e a
construção visual dos elementos, acontece em várias etapas
rápidas.

## O fluxo de preenchimento da página

1. **Requisição e DNS:** Tudo começa quando você digita a URL ou clica
   em um link. O navegador envia uma requisição para o servidor DNS
   (Domain Name System) a fim de encontrar o endereço de IP
   correspondente ao nome do domínio (por exemplo,
   `www.google.com`).
   
2. **Conexão e requisição HTTP:** Após encontrar o IP, o navegador
   estabelece uma conexão com o servidor e envia uma requisição
   HTTP para solicitar os arquivos da página, como HTML, CSS,
   JavaScript, imagens e outros recursos.

3. **Análise e criação das árvores:** Ao receber os arquivos, o motor de
   renderização do navegador inicia a análise dos dados.

   1. **Árvore DOM:** O HTML é convertido em uma estrutura de árvore
      chamada Document Object Model (DOM), que representa a
      estrutura e as relações entre os elementos.

   2. **Árvore CSSOM:** O CSS é analisado para criar o CSS Object
      Model (CSSOM), que mapeia todas as regras de estilo.

4. **Criação da árvore de renderização:** A árvore DOM e a CSSOM são
   combinadas para formar a árvore de renderização. Essa árvore
   contém apenas os elementos visíveis da página e seus respectivos
   estilos.

5. **Layout:** Nessa etapa, o navegador calcula a posição e o tamanho
   exatos de cada elemento visível na tela. Isso é feito considerando o
   conteúdo e os estilos de todos os elementos.

6. **Pintura (ou Painting):** O navegador preenche os pixels na tela com
   o conteúdo e os estilos calculados na etapa de layout,
   renderizando a página visualmente.

7. **Composição:** Os elementos pintados são combinados em camadas
   para criar a visualização final, permitindo efeitos como
   sobreposição e transparência.

8. **Interação com JavaScript:** Se houver JavaScript na página, o
   navegador pode pausar o processo de renderização, executar o
   script e, dependendo do código, modificar a árvore DOM. Isso pode
   acionar um novo ciclo de layout e pintura para refletir as
   mudanças. 

## Motores de renderização

Diferentes navegadores usam diferentes motores de renderização para
interpretar e exibir o conteúdo da web: 

* **WebKit:** Utilizado pelo Safari.

* **Gecko:** Usado pelo Firefox.

* **Blink:** Desenvolvido a partir do WebKit, é usado pelo Google
  Chrome, Opera e Microsoft Edge.
