# api-produtos-Springboot

## Estrutura principal

 - **controller**: classes que recebem as requisições HTTP.
 - **service**: regras de negócio e lógica da aplicação.
 - **repository**: interfaces que fazem a persistência de dados 
 (Geralmente com Spring Data JPA)
 - **model** ou **domain**: clases de domínio
 - **config**: classes de configuração (ex.: CORS, segurança...)
 - **dto**: objeto simples (POJO) criado para transportar dados.

 ## Comandos Importantes


 ### Executar a Aplicação
 ```bash
 ./mvnw spring-boot:run

 ```

 ### Testar a Aplicação
 ```bash

 ./mvnw test

 ```
