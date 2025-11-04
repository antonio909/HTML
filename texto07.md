# Como Funciona a Web: Uma Visão Geral

A World Wide Web (ou simplesmente "Web") é um sistema de documentos interligados
acessados através da **Internet**, que é a infraestrutura física de rede (cabos, roteadores, etc.). A
Web é uma das aplicações que roda sobre a Internet, permitindo o acesso a websites.

O funcionamento da Web se baseia em um modelo de **Cliente-Servidor**.

1. **O Modelo Cliente-Servidor**

   * **Cliente:** É o seu dispositivo (computador, celular, tablet) e o programa que você usa para
     acessar a web, o **navegador** (Chrome, Firefox, Safari, etc.). O cliente faz a solicitação dos
     dados.

   * **Servidor:** É um computador que armazena os sites, páginas ou aplicações web. O servidor
     recebe a solicitação, processa e envia os dados solicitados de volta.

2. **Processo Passo a Passo**

Para que você visualize uma página web, vários passos e tecnologias estão envolvidos:

| Componente | Função | Exemplo (como o seu navegador encontra o site) |
|------------|--------|------------------------------------------------|
| **URL** | O endereço que você digita na barra do navegador (ex: `google.com`). | Você digita a URL que deseja acessar. |
| **DNS (Domain Name Server)** | Funciona como uma "lista telefônica" da internet. Ele traduz o nome do domínio (`google.com`) para o endereço real do servidor, que é um **Endereço IP** (ex: `142.250.68.206)`. | O navegador consulta o DNS para obter o IP do servidor que hospeda o site. |
| **Protocolo TCP/IP** | Define como os dados são quebrados em pequenos pacotes, enviados pela internet (IP) e remontados corretamente no destino (TCP). É o mecanismo de transporte. | Os dados da sua solicitação são empacotados e roteados pela Internet até o endereço IP do servidor. |
| **Protocolo HTTP/HTTPS** | Protocolo de Transferência de Hipertexto. É o "idioma" que clientes e servidores usam para se comunicar. O cliente faz um pedido (**Requisição**), e o servidor envia uma **Resposta**. O `S` em HTTPS indica que a comunicação é criptografada. | O navegador envia uma requisição HTTP/HTTPS ao servidor solicitando a página. |
| **Servidor Web** | Recebe a requisição HTTP. Ele localiza os arquivos do site (HTML, CSS, JavaScript, imagens) e os empacota na Resposta HTTP. | O servidor processa as requisições e envia os arquivos do site de volta. |
| **Navegador (Renderização)** | O navegador recebe os arquivos do servidor e os interpreta: **HTML** para a estrutura, **CSS** para o estilo e **JavaScript** para a interatividade. O navegador então "constrói" e exibe a página na sua tela. | Você visualiza a página web! |

Em resumo, a Web funciona como um sistema global de comunicação onde seu navegador (o
cliente) solicita informações a um computador remoto (o servidor), e essa troca de informações
é gerenciada por uma série de protocolos padronizados, tudo através da infraestrutura da
Internet.
