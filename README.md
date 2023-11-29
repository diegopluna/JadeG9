
# Projeto Canopus - Gestão de Projetos Voluntários para Escolas Públicas
## Grupo 9 - Jade

## Visão Geral
Bem-vindo ao repositório do MVP da aplicação web de gestão de projetos para a ONG "Tribo do Bem". Esta aplicação tem como objetivo facilitar a colaboração e organização de voluntários que trabalham em projetos voltados para escolas públicas no Brasil. O sistema é construído utilizando React para o frontend, com componentes Shadcn e customizados, e Spring Boot para o backend.


## Funcionalidades Principais

### Cadastro e Gestão de Voluntários

- Os usuários podem se cadastrar como voluntários, fornecendo informações básicas.
- Usuários com níveis de acesso de moderadores (embaixadores da ONG) e administradores têm a capacidade de cadastrar e gerenciar voluntários, alocando-os em projetos e ações específicas.

### Modelagem de Entidades

- A aplicação modela entidades principais, como usuários (com diferentes níveis de acesso), escolas, projetos e ações.
- Além do básico cadastro de projetos, a aplicação coleta metadados estruturados para auxiliar na gestão eficiente. Isso inclui informações relevantes para o acompanhamento e avaliação do progresso.


### Salas de Chat Automáticas

- Para cada projeto criado, a aplicação utiliza WebSockets para automaticamente gerar uma sala de chat. Isso proporciona um espaço centralizado para discussões e repasses, eliminando a dependência de outros serviços.

## Como Contribuir

1. Faça um fork deste repositório.
2. Clone o fork para o seu ambiente de desenvolvimento.
3. Instale as dependências utilizando `npm install` para o frontend e `mvn install` para o backend.
4. Faça as alterações necessárias e teste localmente.
5. Submeta um pull request com uma descrição detalhada das alterações realizadas.

## Configuração do Ambiente de Desenvolvimento

Certifique-se de ter o Node.js, npm, e Maven instalados em sua máquina.

### Frontend (React)

```bash
cd frontend
npm install
npm start
```

### Backend (Spring Boot)
``` bash
Copy code
cd backend
mvn install
mvn spring-boot:run
```

A aplicação estará disponível em http://localhost:3000 para o frontend e http://localhost:8080 para o backend.

## Issues e Sugestões
Encontrou um bug ou tem uma ideia para melhorar a aplicação? Por favor, abra uma issue no GitHub.

Obrigado por contribuir para o Projeto Canopus! 🚀
