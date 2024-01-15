Funcionalidades Principais:

UserController: Controla operações RESTful para manipulação de usuários. Disponibiliza endpoints para listar todos os usuários, recuperar um usuário por ID e inserir novos usuários.

Entidades:

Department: Representa os departamentos da organização, armazenando informações como o ID e o nome.
User: Reflete os usuários do sistema, contendo detalhes como ID, nome, e-mail e seu relacionamento com um departamento específico.
Repository:

UserRepository: Utiliza o Spring Data JPA para facilitar operações no banco de dados, como busca e persistência de usuários.
Configurações e Banco de Dados:

Application.properties: Configurações do banco de dados H2, incluindo informações de conexão e habilitação do console web para visualização. Além disso, define a exibição de consultas SQL no console.
import.sql: Popula o banco de dados H2 com dados iniciais, criando departamentos e usuários de exemplo.
Tecnologias Utilizadas:

Spring Boot: Framework que simplifica o desenvolvimento Java, permitindo maior foco na lógica de negócios e menos configurações iniciais.
H2 Database: Banco de dados em memória ideal para ambientes de teste e desenvolvimento.
Maven: Ferramenta de automação de construção e gerenciamento de projetos.
Postman: Utilizado para testar e documentar APIs, facilitando a integração e verificação de endpoints.
Execução:

A aplicação é inicializada pela classe UserdeptApplication, configurada para usar o banco de dados H2.
Instruções Adicionais:

O código-fonte completo e detalhes de implementação estão disponíveis nos arquivos fornecidos.
Este projeto oferece uma base sólida para o desenvolvimento de sistemas similares, destacando as boas práticas e eficiência proporcionadas pelo uso do Spring Boot.
