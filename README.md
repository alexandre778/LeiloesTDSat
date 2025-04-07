# Leilões

Este projeto é uma aplicação web para gerenciar leilões de produtos e serviços. O sistema permite que os usuários criem leilões, participem de lances e acompanhem o andamento dos leilões em tempo real. O objetivo é fornecer uma plataforma segura e eficiente para a realização de leilões online.

## Funcionalidades

- Criação de leilões com descrição, preço inicial e data de encerramento.
- Participação em leilões com lances em tempo real.
- Notificação para os participantes quando um leilão é finalizado.
- Visualização do histórico de lances.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação utilizada para a lógica de backend do sistema.
- **Spring Boot**: Framework utilizado para criar a aplicação backend de forma rápida e eficiente.
- **MySQL**: Banco de dados relacional utilizado para armazenar informações sobre os leilões e usuários.
- **HTML, CSS e JavaScript**: Tecnologias utilizadas para desenvolver o frontend da aplicação.
- **Thymeleaf**: Template engine para renderização de páginas HTML dinâmicas.
- **Bootstrap**: Framework CSS para design responsivo e moderno.

## Como Rodar o Projeto

1. Clone o repositório:

    ```bash
    git clone https://github.com/usuario/leiloes.git
    ```

2. Acesse o diretório do projeto:

    ```bash
    cd leiloes
    ```

3. Configure o banco de dados MySQL com as credenciais necessárias e crie as tabelas.
4. Compile e execute a aplicação:

    ```bash
    mvn spring-boot:run
    ```

5. Acesse a aplicação pelo navegador em `http://localhost:8080`.

## Como Contribuir

1. Faça um fork deste repositório.
2. Crie uma branch para sua nova funcionalidade (`git checkout -b feature/nova-feature`).
3. Faça as alterações necessárias e commit suas mudanças (`git commit -am 'Adicionando nova feature'`).
4. Envie as mudanças para o repositório remoto (`git push origin feature/nova-feature`).
5. Abra um Pull Request para revisão.

## Licença

Este projeto está licenciado sob a licença MIT.
