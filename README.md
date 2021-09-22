![Jtech Logo](http://www.jtech.com.br/wp-content/uploads/2015/06/logo.png)

# Curso da Jtech sobre Command Query Responsibility Segregation (CQRS) e Event Sourcing

Este curso será dividido em 7 (sete) passos para podermos entender como funciona o mundo do event sourcing e também do cqrs nos microsserviços.

Neste curso iremos abordar uma forma linear de entender como funciona de maneira avançada, os microsserviços orientados a enventos e também, entender qual a diferença entre o evento como conhecemos para um event sourcing.

Analisaremos vários aspectos da abordagem sobre camadas e sobre responsabilidades entre os objetos e classes que iremos desenvolver e também, entenderemos como essa forma de arquitetura ganha espaço e é utilizada pelas maiores empresas de tecnologia do mundo.

## Conteudo do Curso

1. **Seção 1**: **_Introdução ao curso_**

    * O que iremos fazer?
    * O que são microsserviços na verdade?
    * CQRS e Event Sourcing.
    * A plataforma Axon.
    * Teste de conhecimento.

2. **Seção 2**: **_Setup e Estrutura do Projeto_**

    * Conhecendo o Spring Initializr.
    * Fazendo o setup básico do projeto.
    * Criando _docker-compose.yml_ para o projeto.
    * A estrutura CQRS do projeto.
    * A Configuração do Axon.

3. **Seção 3**: **_O Microserviço de Usuário_**

    * Entendendo o que vamos fazer.
    * Criando os dominios do usuário.
    * Criando os comandos do usuário.
    * Criando os eventos do usuário.
    * Entendendo o agregador e criando um para o usuário.
    * Criando um event handler para o usuário.
    * Criando um repositorio para o usuário.
    * Criando o controller para registrar o usuário.
    * Registrando nosso primeiro usuário.
    * Criando o controller para atualizar o usuário.
    * Criando o controller para remover o usuário.
    * Criando as queries de usuário.
    * Criando um query handler para o usuário.
    * Criando um controller para fazer lookup no usuário.
    * Teste de conhecimento.

4. **Seção 4**: **_Segurança no nosso Microserviço_**

    * Introdução ao Spring Security e OAuth2.
    * Gerando o projeto OAuth2 com Spring Initializr.
    * Configurando o projeto.
    * Criando o repositorio de usuário.
    * Criando o serviço de usuário da Spring.
    * Criando um Authorization Server e arrumando as configurações.
    * Colocando a segurança nos comandos do usuário e nas queries.
    * Teste de conhecimento.

5. **Seção 5**: **_API Gateway_**

    * Introdução ao API Gateway e Spring Cloud Gateway
    * Criando um API Gateway com o Spring Cloud Gateway
    * Testando as rotas do API Gateway

6. **Seção 6**: **_O Microserviço de Conta Bancária_**

    * Entendendo o que vamos fazer.
    * Configurando o Postman
    * Criando os dominios da conta.
    * Criando os comandos da conta.
    * Criando os eventos da conta.
    * Criando um agregador para a conta.
    * Criando um event handler para a conta.
    * Criando um repositorio para a conta.
    * Criando o controller para abrir uma conta.
    * Abrindo nossa primeira conta.
    * Criando o controller para realizar um deposito na conta.
    * Criando o controller para realizar um saque da conta.
    * Criando o controller para fechar uma conta.
    * Criando as queries da conta.
    * Criando um query handler para a conta.
    * Criando um controller para fazer lookup na conta.
    * Teste de conhecimento.

7. **Seção 7**: **_Dockerizando nossos Microsserviços_**

    * Introdução aos containers e a Docker.
    * Containerzando nosso primeiro microserviço.
    * Containerzando nossos outros microsserviços.
    * Criando nosso _docker-compose.yml_
    * Teste de conhecimento.

### Proximos cursos

#### > Criando microsserviços com Spring Boot e Netflix OSS (_Básico_)

#### > Criando microsserviços orientado a eventos com RabbitMQ (_Básico_)

#### > Desenvolvendo microsserviços em cloud-native (_Intermediário_)

#### > Microsserviços com Orquestração (_Avançado_)

#### > Microsserviços com Coreografia (_Avançado_)

#### > Microsserviços com SAGA e Kafka (_Avançado_)

#### > Decompondo um monolito (_Intermediário_)