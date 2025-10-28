# O que é DNS?

DNS, ou **Sistema de Nomes de Domínio**, funciona como a "lista
telefônica" da internet, traduzindo nomes de domínio legíveis por
humanos, como `www.google.com`, para endereços IP numéricos que os
computadores podem entender, como `192.0.2.44`. Esse processo é
fundamental para que os navegadores carreguem sites e outros
recursos na internet.

## Como o DNS funciona

* **Consulta do navegador:** Quando você digita um endereço web
  em um navegador, ele inicia uma solicitação para um servidor DNS
  recursivo.

* **Consulta ao servidor raiz:** Se o servidor recursivo não tiver a
  resposta em seu cache, ele começa uma busca, consultando
  servidores raiz.

* **Consulta ao servidor de TLD:** Os servidores raiz direcionam o
  pedido para o servidor de nível superior (TLD - Top-Level Domain)
  correto (por exemplo, `.com` ou ´.br´).

* **Consulta ao servidor autoritativo:** O servidor de TLD, por sua
  vez, encaminha a consulta para o servidor DNS autoritativo do
  domínio específico, que contém o endereço IP exato.

* **Resposta:** Por fim, o servidor autoritativo responde com o
  endereço IP, que é enviado de volta ao navegador do usúario para
  que a página possa ser carregada.

## Por que o DNS é importante

* **Facilita o uso da internet:** Torna a navegação mais fácil,
  permitindo que os usuários usem nomes fáceis de lembrar em vez
  de sequências numéricas complexas.

* **Melhora o desempenho:** O armazenamento em cache
  (armazenamento temporário de informações) nos servidores DNS
  acelera as consultas futuras, pois o endereço IP não precisa ser
  pesquisado do zero a cada vez.

* **Permite a existência de uma infraestrutura global:** O sistema
  distribuído de servidores DNS é essencial para que a internet
  funcione, sem a necessidade de ter um único e centralizado
  "catálogo" para toda a rede.
