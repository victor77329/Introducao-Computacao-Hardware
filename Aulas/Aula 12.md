# Aula 12 – Internet: História, Conceitos, Protocolos e Navegadores

## Integrantes
Victor Gabriel Madeiro Brito Marques 
Nicolle Coelho da Silva

# 1. História da Internet

## ARPANET (Década de 1960 e 1970)

A Internet teve origem na ARPANET, um projeto financiado pelo Departamento de Defesa dos Estados Unidos. Seu objetivo era criar uma rede de comunicação resistente a falhas, permitindo a troca de informações entre universidades e instituições militares.

## Expansão Acadêmica e Militar

Durante os anos 1970 e 1980, a rede expandiu-se para centros de pesquisa e universidades, tornando possível a colaboração científica entre diferentes regiões.

## Comercialização nos Anos 1990

Na década de 1990, a Internet passou a ser utilizada comercialmente. Empresas e provedores começaram a oferecer acesso ao público em geral, impulsionando o crescimento da rede mundial.

## Criação da World Wide Web (WWW)

Em 1989, Tim Berners-Lee criou a World Wide Web (WWW), permitindo o acesso a documentos interligados por hiperlinks. Essa inovação facilitou a navegação e popularizou a Internet.

---

# 2. Conceitos Fundamentais

## Internet x Web

### Internet

É a infraestrutura global composta por redes de computadores interconectadas.

### Web

É um serviço que funciona sobre a Internet, permitindo o acesso a páginas e conteúdos por meio de navegadores.

**Exemplo:** Quando acessamos um site, utilizamos a Web, que funciona através da Internet.

## Arquitetura Cliente-Servidor

A comunicação na Internet ocorre geralmente através do modelo cliente-servidor:

* Cliente: computador ou dispositivo do usuário.
* Servidor: computador responsável por fornecer recursos e informações.

### Exemplo

Ao acessar um site, o navegador (cliente) envia uma solicitação ao servidor, que responde enviando a página solicitada.

## Endereço IP

O IP (Internet Protocol) identifica cada dispositivo conectado à rede.

### Exemplo

* IPv4: 192.168.1.1
* IPv6: 2001:0db8:85a3:0000:0000:8a2e:0370:7334

---

# 3. Protocolos

## TCP/IP

### Função

Conjunto de protocolos responsável pela comunicação entre dispositivos na Internet.

### Exemplo

Ao enviar uma mensagem ou acessar um site, os dados são divididos em pacotes e transmitidos usando TCP/IP.

## HTTP/HTTPS

### Função

Permitem a transferência de páginas web entre navegador e servidor.

### Diferença

* HTTP: comunicação sem criptografia.
* HTTPS: comunicação criptografada e mais segura.

### Exemplo

https://www.google.com

## DNS

### Função

Traduz nomes de domínio para endereços IP.

### Exemplo

Ao digitar [www.google.com](http://www.google.com), o DNS converte o nome para o endereço IP correspondente.

## FTP

### Função

Realiza transferência de arquivos entre computadores.

### Exemplo

Envio de arquivos de um computador para um servidor web.

---

# 4. Navegadores

Os navegadores interpretam e exibem conteúdos desenvolvidos com HTML, CSS e JavaScript.

## HTML

Define a estrutura da página.

## CSS

Define a aparência visual.

## JavaScript

Adiciona interatividade e dinamismo.

## Motores de Renderização

### Blink

Utilizado pelo Google Chrome e Microsoft Edge.

### Gecko

Utilizado pelo Mozilla Firefox.

### WebKit

Utilizado pelo Safari.

---

# 5. Exercício Prático – Análise de Protocolos

## Site Analisado

https://www.google.com

## Request (Requisição)

Método:
GET /

Host:
[www.google.com](http://www.google.com)

## Response (Resposta)

Protocolo:
HTTP/2

Conteúdo:
Página inicial do Google.

## Status Code

### 200 OK

Indica que a solicitação foi processada com sucesso.

### Outros códigos comuns

* 404 Not Found: página não encontrada.
* 403 Forbidden: acesso negado.
* 500 Internal Server Error: erro interno do servidor.

## Conclusão da Análise

Foi possível observar a comunicação entre cliente e servidor através do protocolo HTTPS, garantindo segurança na transmissão dos dados.

---

# Reflexão Individual

## Qual protocolo você considera mais essencial para o funcionamento da Internet e por quê?

Considero o protocolo TCP/IP o mais essencial para o funcionamento da Internet, pois ele é a base de toda a comunicação entre dispositivos conectados à rede. O IP é responsável pelo endereçamento dos dispositivos, enquanto o TCP garante que os dados sejam enviados e recebidos corretamente. Sem esse conjunto de protocolos, não seria possível acessar sites, enviar mensagens, realizar chamadas online ou utilizar qualquer serviço disponível na Internet. Portanto, o TCP/IP é o fundamento que permite o funcionamento de todos os demais protocolos e serviços da rede mundial.
