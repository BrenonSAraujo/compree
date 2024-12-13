<p align="center">
<img src="https://github.com/user-attachments/assets/0a420e8b-16ab-41f4-adf5-14081b518c39"/>
</p>
<p align="center">
<img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=ABERTO%20PARA%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

### Tópicos 

- [Descrição do projeto](#descrição-do-projeto)

- [Funcionalidades](#funcionalidades)

- [Aplicação](#aplicação)

- [Ferramentas utilizadas](#ferramentas-utilizadas)

- [Acesso ao projeto](#acesso-ao-projeto)

- [Abrir e rodar o projeto](#abrir-e-rodar-o-projeto)

## Descrição do projeto 

<p align="justify">
 Este projeto simula um backend de uma loja com três entidades (usuários, produtos e pedidos). Ao se autenticar, um usuário pode realizar o CRUD nas outras duas entidades.
</p>

## Funcionalidades

:heavy_check_mark: `Funcionalidade 1:` Cria uma sessão de usuário por meio do token de acesso;

:heavy_check_mark: `Funcionalidade 2:` Armazena os dados no Postgres por meio do TypeORM;

:heavy_check_mark: `Funcionalidade 3:` 

## Ferramentas utilizadas
[![My Skills](https://skillicons.dev/icons?i=nestjs,ts,postgres,docker)](https://skillicons.dev)


###

## Acesso ao projeto
  - ``git clone https://github.com/BrenonSAraujo/compree.git``: Clone o projeto do GitHub para a sua máquina
  
  - ``npm i``: Instale as dependências do projeto
  
  - ``npm run typeorm migration:generate src/db/migrations/cria-tabelas``: Gere as migrações com as tabelas do banco de dados
  
  - ``npm run typeorm migration:run``: Rode as migrações
  
  - ``docker compose up -d``: Suba a aplicação com o Docker
  
  - ``npm run start``: inicie o servidor da aplicação
 
## Abrir e rodar o projeto

  Você pode interagir com este projeto por meio de uma ferramenta de desenvolvimento e teste de API, como o Postman. Após isso, você pode se cadastrar na rota de 'http://localhost:3000/autenticacao/login' colocando seu nome, email e senha e. Com isso será gerado um token de acesso, o qual deve ser colocado no body toda vez em que você quiser fazer uma requisição de cadastro.

