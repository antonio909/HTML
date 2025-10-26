# HTTP/3 agora é um padrão: por que usá-lo e como começar

O HTTP/3 se tornou um padrão em 2021, trazendo uma evolução
significativa na forma como a internet funciona. Ele é baseado em um
protocolo de transporte mais moderno, o QUIC, para oferecer melhor
desempenho, segurança e menor latência.

## Por que usar o HTTP/3?

1. **Desempenho e velocidade**

   * **Baseado em QUIC:** Diferentemente das versões anteriores
     (baseadas em TCP), o HTTP/3 utiliza o protocolo QUIC, que usa o
     UDP como base. Isso permite um estabelecimento de conexão mais
     rápido e uma experiência de navegação mais fluida.

   * **Correção de erros sem atrasos:** Com o QUIC, a perda de pacotes
     (dados) não bloqueia a entrega dos pacotes seguintes. Isso elimina
     o problema de "head-of-line blocking" que afeta o HTTP/2,
     resultando em carregamentos mais rápidos, especialmente em
     conexões instáveis.

   * **Conexões persistentes:** Ao alternar entre redes (como Wi-Fi e
     dados móveis), o HTTP/3 mantém a conexão ativa, evitando o atraso
     de reconexão. Isso é ideal para usuários em movimento.

2. **Segurança aprimorada**

   * **Criptografia por padrão:** O HTTP/3 oferece criptografia obrigatória
     e automática no nível de transporte. Isso significa que todo o tráfego
     é criptografado por padrão, melhorando a segurança de dados
     sensíveis para todos os usuários.

3. **Latência reduzida**

   * **Handshake mais rápido:** O QUIC realiza o handshake de
     segurança (a etapa de negociação inicial) de forma mais eficiente, o
     que reduz a latência e o tempo de carregamento da página.

## Como começar a usar o HTTP/3?

### Para desenvolvedores e proprietários de sites

* **Verifique o suporte do seu servidor:** Muitos servidores web
  modernos, como o NGINX e o Apache, já oferecem suporte ao
  HTTP/3. Verifique a documentação do seu servidor para ver se o
  recurso está disponível e como ativá-lo.

* **Use uma CDN:** Se você utiliza um Rede de Entrega de Conteúdo
  (CDN) como a Cloudflare, Akamai ou Fastly, a ativação do HTTP/3
  pode ser tão simples quanto marcar uma caixa nas configurações do
  serviço.

* **Mantenha seu software atualizado:** Para aproveitar os benefícios
  do HTTP/3, certifique-se de que seu software de servidor e
  bibliotecas estejam atualizados.

* **Implemente no código:** Para desenvolvedores, bibliotecas como a
  `HttpClient` no .NET Core já suportam HTTP/3.

### Para usuários finais

* **Atualize seu navegador:** A maioria dos navegadores modernos já
  suportam o HTTP/3 por padrão. Manter o seu navegador (Chrome,
  Firefox, Edge, etc.) atualizado garante que você esteja utilizando o
  protocolo mais recente.

* **Navegue na web:** Ao usar um navegador atualizado, você já está
  aproveitando os benefícios do HTTP/3, pois os servidores mais
  modernos já o utilizam.

O HTTP/3 é um passo importante para uma internet mais rápida e
segura, e a sua adoção crescente por grandes empresas como Google e
Meta demonstra sua eficácia.
