# **Projeto com arquitetura baseada em microsserviços utilizando Spring Cloud** - Guia de início rápido

### SOBRE O PROJETO

Este projeto foi feito durante o Bootcamp Santander.

O projeto original estava um pouco defasado.

https://github.com/oswaldoneto/dio-experts

Este é baseado no do colega.

https://github.com/OrnelasD-Rogers/microsservicos-usando-Spring-Cloud



### TECNOLOGIAS

- ElasticSearch 7.14
- Redis 6.2.5
- Docker
- Spring Boot 2.5.4
- Spring Cloud
- Spring Cloud Netflix
- Spring Boot Actuator

### OBJETIVO

O objetivo deste projeto foi de aprender como funciona uma arquitetura de micro serviços, fazendo a interligação de API's com Servers de configuração e criando um Gateway para controlar as requisições e o fluxo de dados de uma aplicação com este tipo de arquitetura.

### INSTALAÇÃO LOCAL

- Faça um git clone deste Repositório

- Suba os servidores no docker que estão no arquivo docker-compose.yml  através do comando:

  ```
  docker-compose up
  ```

- Importe os projetos como módulos em sua IDE de preferência e Rode primeiro os projetos: config-server e service-discovery. Após isso os outros projetos podem ser abertos.



### BIBLIOTECAS DO PROJETO

Neste projeto foram alteradas as versões das dependências para as mais atuais no momento de publicação deste projeto. Algumas códigos de configurações tiveram que ser completamente remodeladas para poder funcionar nas versões atuais.

Caso queira dar uma olhada no projeto original: https://github.com/oswaldoneto/dio-experts

### BANCO DE DADOS

Foram utilizadas duas soluções NO-SQL neste projeto, sendo elas o ElasticSearch e o Redis.






