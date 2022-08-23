
## Api
"Application Programming Interface"

API ou Interface de Programação de Aplicação é um conjunto de padrões estabelecidos por um software que permite uma comunicação entre plataformas. Um exemplo seria - um app para Android de edição de fotos, ele poderá ter acesso à câmera e à galeria de fotos através da API do sistema operacional, sem precisar criar uma interface de câmera do zero.

A proposta geral da API é de simplificar o desenvolvimento de programas e aplicações, a partir da abstrações das partes que envolvem um software, ou seja, o desenvolvedor precisa entender como utilizar os serviços disponibilizados pelas Apis's.

## Api REST

REQUEST(ROTA) - RESPONSE(JSON/XML)
usa protocolo HTTP
ele tem 4 principais agentes, são eles: POST, GET, PUT, DELETE.

ROTAS  = ENDPOINTS
***EXEMPLO**
https://api.github.com/users/AnaCandida

REST não é um protocolo ou padrão, mas sim um conjunto de restrições de arquitetura. Os desenvolvedores de API podem implementar a arquitetura REST de maneiras variadas.

Quando um cliente faz uma solicitação usando uma API RESTful, essa API transfere uma representação do estado do recurso ao solicitante ou endpoint. Essa informação (ou representação) é entregue via HTTP utilizando um dos vários formatos possíveis: Javascript Object Notation (JSON), HTML, XLT, Python, PHP ou texto sem formatação. O formato JSON é a linguagem de programação mais usada porque, apesar de seu nome, é independente de qualquer outra linguagem e pode ser lido por máquinas e humanos.

Lembre-se também de que cabeçalhos e parâmetros são importantes nos métodos HTTP de uma solicitação HTTP de API RESTful porque contêm informações relevantes sobre o identificador, bem como metadados, autorização, Uniform Resource Identifier (URI), cache, cookies e outras informações da solicitação. Há os cabeçalhos da solicitação e os cabeçalhos da resposta, cada um contendo as informações de suas respectivas conexões HTTP e códigos de status.

Para que uma API seja considerada do tipo RESTful, ela precisa está em conformidade com os seguintes critérios:

-   Ter uma arquitetura cliente/servidor formada por clientes, servidores e recursos, com solicitações gerenciadas por HTTP.
-   Estabelecer uma comunicação  [stateless](https://www.redhat.com/pt-br/topics/cloud-native-apps/stateful-vs-stateless)  entre cliente e servidor. Isso significa que nenhuma informação do cliente é armazenada entre solicitações GET e toda as solicitações são separadas e desconectadas.
-   Armazenar dados em cache para otimizar as interações entre cliente e servidor.
-   Ter uma interface uniforme entre os componentes para que as informações sejam transferidas em um formato padronizado. Para tanto, é necessário que:
    -   os recursos solicitados sejam identificáveis e estejam separados das representações enviadas ao cliente;
    -   os recursos possam ser manipulados pelo cliente por meio da representação recebida com informações suficientes para tais ações;
    -   as mensagens autodescritivas retornadas ao cliente contenham informações suficientes para descrever como processá-las;
    -   hipertexto e hipermídia estão disponíveis. Isso significa que após acessar um recurso, o cliente pode usar hiperlinks para encontrar as demais ações disponíveis para ele no momento.
-   Ter um sistema em camadas que organiza os tipos de servidores (responsáveis pela segurança, pelo carregamento de carga e assim por diante) envolvidos na recuperação das informações solicitadas em hierarquias que o cliente não pode ver.
-   Possibilitar código sob demanda (opcional): a capacidade de enviar um código executável do servidor para o cliente quando solicitado para ampliar a funcionalidade disponível ao cliente.

Embora uma API REST precise estar em conformidade com os critérios acima, ela é considerada mais fácil de usar do que um protocolo prescrito, como o Protocolo Simples de Acesso a Objetos (SOAP). Esse tipo de protocolo tem requisitos específicos, como o sistema de mensageria XML, além de precisar cumprir com exigências de segurança incorporada e transações, o que o torna mais lento e pesado.

Em comparação, a arquitetura REST é composta de um conjunto de diretrizes que podem ser implementadas conforme necessário. Isso faz com que as APIs REST sejam mais rápidas, leves e escaláveis




https://www.redhat.com/pt-br/topics/api/what-is-a-rest-api


https://programathor.com.br/blog/o-que-e-api/

https://lucas-eschechola.medium.com/construindo-uma-simples-api-restful-com-asp-net-4-6-x-ac17604add8c

