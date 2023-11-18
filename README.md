# Cardapio

Este repositório contém o código-fonte do backend de um sistema de cardápio desenvolvido em Java com o framework Spring e utiliza um banco de dados PostgreSQL. Além disso, foram utilizadas ferramentas como o testador de rotas Insomnia para facilitar o desenvolvimento e teste das APIs.

## Tecnologias Utilizadas

- Java
- Spring Framework (Spring Boot, Spring MVC, Spring Data JPA)
- PostgreSQL
- Insomnia

## Configuração do Ambiente

Para executar localmente, certifique-se de ter as seguintes ferramentas instaladas:

- Java Development Kit (JDK)
- PostgreSQL
- Insomnia (para testes de rotas)

### Passos para Configuração

1. **Clonar o Repositório:**

   ```bash
   git clone https://github.com/seu-usuario/backend-cardapio.git
   ```

2. **Configurar Banco de Dados:**

   - Instale o PostgreSQL e crie um banco de dados para o projeto.
   - Configure as credenciais do banco no arquivo `application.properties`.

3. **Executar o Backend:**

   - Utilize sua IDE preferida ou execute o projeto via linha de comando:

   ```bash
   ./mvnw spring-boot:run
   ```

4. **Testar as Rotas:**

   - Importe o arquivo de workspace do Insomnia que se encontra na pasta `insomnia/` para ter acesso às rotas e seus testes pré-configurados.

## Estrutura do Projeto

A estrutura do projeto está organizada da seguinte maneira:

```
|-- src/
|   |-- main/
|   |   |-- java/
|   |   |   |-- com/
|   |   |   |   |-- example/
|   |   |   |   |   |-- backendcardapio/
|   |   |   |   |   |   |-- controller/
|   |   |   |   |   |   |-- food/
|   |   |   |   |   |   |-- BackendCardapioApplication.java
|   |-- resources/
|   |   |-- application.properties
|-- insomnia/
|   |-- backend_cardapio_insomnia.json
|-- .gitignore
|-- README.md
|-- pom.xml
```

## Contribuição

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões para melhorias, sinta-se à vontade para abrir uma **issue** ou enviar um **pull request**.

## Licença

Este projeto está licenciado sob a licença [MIT](https://opensource.org/licenses/MIT) - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
