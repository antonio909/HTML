# DNS

O DNS, ou **Sistema de Nomes de Domínio**, é essencialmente a **"lista telefônica" da internet**.

* **O que ele faz?** Ele traduz nomes de domínio legíveis por humanos (como `www.exemplo.com`)
  em **endereços IP** legíveis por máquina (como `192.0.2.44`). Os computadores e servidores
  na internet usam endereços IP para se localizar e se comunicar, mas para as pessoas, é
  muito mais fácil memorizar nomes.

* **Por que é necessário?** Se não fosse pelo DNS, você teria que digitar o endereço IP de um
  site toda vez que quisesse visitá-lo. O DNS automatiza esse processo de conversão.

## Como o DNS Funciona (o Processo de Resolução)

Quando você digita um nome de domínio no seu navegador, ocorre uma série de consultas:

1. **Consulta Inicial:** Seu computador envia uma solicitação (consulta) para um **Resolvedor
   Recursivo de DNS** (geralmente fornecido pelo seu Provedor de Serviços de Internet - ISP,
   ou um serviço público como o DNS do Google 8.8.8.8).

2. **Servidor Raiz:** Se o resolvedor não tiver a resposta em cache, ele consulta um **Servidor
   Raiz** (o topo da hierarquia do DNS). O Servidor Raiz direciona o resolvedor para o servidor
   de **Domínio de Nível Superior (TLD)** apropriado (por exemplo, o servidor responsável por
   todos os endereços `.com`).

3. **Servidor TLD:** O servidor TLD direciona o resolvedor para o **Servidor de Nomes
   Autoritativo** para aquele domínio específico (por exemplo, `exemplo.com`).

4. **Servidor Autoritativo:** O Servidor Autoritativo contém o **registro DNS real** (como o registro
   'A') para o domínio e retorna o **endereço IP** do servidor web para o resolvedor recursivo.

5. **Resposta:** O resolvedor recursivo envia o endereço IP de volta para o seu computador.

6. **Conexão:** Seu navegador agora usa o endereço IP para se conectar ao servidor web e
   carregar a página.

## Tipos de Servidores DNS

O Sistema DNS é distribuído e hierárquico, utilizando vários tipos de servidores para gerenciar e
responder às consultas:

| Tipo de Servidor | Função Principal |
|------------------|------------------|
| **Resolvedor Recursivo** | Recebe a consulta do usuário e faz as solicitações necessárias para encontrar o endereço IP, funcionando como um intermediário. |
| **Servidor Raiz** | O topo da hierarquia, direciona as consultas para o Servidor TLD correto. |
| **Servidor TLD** | Gerencia informações para domínios de nível superior (´.com´, ´.org´, ´.br´, etc.), direcionando para o Servidor Autoritativo. |
| **Servidor Autoritativo** | Contém a informação definitiva (os registros) para um domínio específico, fornecendo o endereço IP final. |
