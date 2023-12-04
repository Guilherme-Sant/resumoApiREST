# resumoApiREST

# Resumo sobre API rest <h1>

## O que é uma API rest? <h2>

Uma API REST ou API RESTful é uma interface de programação que faz o uso dos princípios de design do REST,
assim, possibilitando a interação com serviços WEB. Todavia, há ligeiras diferenças entre REST e RESTful, sendo REST um conjunto de princípios e RESTful a aplicação prática desses princípios em sistemas ou serviços específicos.

## REST, e o design REST <h2>

REST é um agrupamento de restrições de arquitetura, sendo assim, tais restrições dão forma ao que chamamos de Arquitetura REST. Dado essas regras ou limitações pode-se implementá-las comforme o necessário, fazendo das API's REST
mais rápidas, menos pesadas e escaláveis.

## Príncipais critérios para a API REST <h2>

### Arquitetura Cliente-Servidor: <h3>

Separação clara entre cliente e servidor.

### Stateless (Sem Estado): <h3>

Nenhuma informação do cliente é armazenada entre solicitações GET.
Todas as solicitações são separadas e desconectadas.

### Armazenamento em Cache: <h3>

Uso de cache para otimizar interações cliente-servidor.

### Interface Uniforme: <h3>

Recursos identificáveis e separados das representações enviadas.
Manipulação de recursos pelo cliente através da representação recebida.
Mensagens autodescritivas contêm informações suficientes para processamento.
Disponibilidade de hipertexto e hipermídia, permitindo navegação via hiperlinks.

### Sistema em Camadas: <h3>

Organização hierárquica de servidores, invisível ao cliente.
Tipos de servidores (segurança, carga, etc.) em camadas.

### Código Sob Demanda (Opcional): <h3>

Capacidade opcional de enviar código executável do servidor para o cliente.
Ampliação da funcionalidade disponível ao cliente mediante solicitação.

## Funcionamento da API REST <h2>

Ela opera por meio das solicitações HTTP para realizar operações CRUD em recursos. Operações essas que podem transmitir informações em diversos formatos, sendo o mais utilizado o JSON, devido a legibilidade humana e máquina, além de ser independente da linguagem utilizada.

# O protocólo HTTP <h1>

## O que é o protocólo HTTP <h2>

O protocolo define um conjunto de métodos de requisição, frequentemente referidos como "Verbos HTTP", que têm a responsabilidade de indicar a ação a ser executada em um recurso específico. Descritos como métodos substantivos, esses verbos HTTP delineiam as operações a serem realizadas nos recursos. Cada um deles sendo diferentes, mas alguns recursos são compartilhados por um grupo deles.
 
## HTTP STATUS <h2>

O HTTP status faz a indica quando uma solicitação foi concluida com sucesso, o HTTP status é dividido em 5 grupos sendo eles:

 Informativo;
 Sucesso;
 Redirecionamento;
 Erro do Cliente;
 Erro do Servidor.

Autor do resumo: José William Guilherme Santos - 01553544
