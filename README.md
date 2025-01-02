<p align="center">
<img src="https://github.com/user-attachments/assets/0a420e8b-16ab-41f4-adf5-14081b518c39"/>
</p>
<p align="center">
<img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=ABERTO%20PARA%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

### Tópicos 

- [Descrição do projeto](#descrição-do-projeto)

- [Funcionalidades](#funcionalidades)

- [Ferramentas utilizadas](#ferramentas-utilizadas)

- [Técnicas e Tecnologias Utilizadas](#tecnicas-e-ferramentas-utilizadas)
  
- [Acesso ao projeto](#acesso-ao-projeto)

- [Abrir e rodar o projeto](#abrir-e-rodar-o-projeto)

## Descrição do projeto 

<p align="justify">
 Este projeto simula um backend de uma loja com três entidades (usuários, produtos e pedidos). Ao se autenticar, um usuário pode realizar o CRUD nas outras duas entidades.
</p>

## Funcionalidades

:heavy_check_mark: `Funcionalidade 1:` CRUD na API;

:heavy_check_mark: `Funcionalidade 2:` Cria uma sessão de usuário por meio do token de acesso;

:heavy_check_mark: `Funcionalidade 3:` Armazena os dados no Postgres por meio do TypeORM;

## Ferramentas utilizadas
[![My Skills](https://skillicons.dev/icons?i=nodejs,nestjs,ts,redis,postgres,docker)](https://skillicons.dev)


###

## ✔️ Técnicas e Tecnologias Utilizadas

As principais técnicas e tecnologias abordadas são:

- `NodeJS`: Permite executar código JavaScript no lado do servidor;
- `NestJS`: Framework de código aberto para desenvolvimento de aplicações do lado do servidor;
- `TypeScript`: Superconjunto do JavaScript. Adiciona recursos ao JavaScript, como tipagem estática, interfaces, classes e orientação a objetos;
- `Redis`: Banco de dados de código aberto que armazena dados na memória, em vez de em disco ou em unidades de estado sólido;
- `JWT`: Usado na autenticação e na autorização em aplicativos da web e móveis;

## Acesso ao projeto
 <p align="left"> 
  A versão do NodeJS deste projeto é a 18.18.0
 </p>
 
  - ``git clone https://github.com/BrenonSAraujo/compree.git``: Clone o projeto do GitHub para a sua máquina
  
  - ``npm i``: Instale as dependências do projeto
  
  - ``npm run typeorm migration:generate src/db/migrations/cria-tabelas``: Gere as migrações com as tabelas do banco de dados
  
  - ``npm run typeorm migration:run``: Rode as migrações
  
  - ``docker compose up -d``: Suba a aplicação com o Docker
  
  - ``npm run start``: inicie o servidor da aplicação
    
 
## Abrir e rodar o projeto
 <p align="left"> Caso queira verificar o banco de dados, é preciso primerio logar na página do pgAdmin4 com os dados de email e senha no arquivo docker-compose.yaml. Após isso, insira as informações de nome, senha e porta de acordo com as variáveis de ambiente no arquivo .env </p>

  Você pode interagir com este projeto por meio de uma ferramenta de desenvolvimento e teste de API, como o Postman. Segue o [arquivo JSON](https://cdn3.gnarususercontent.com.br/3248-nest-js-cache-escalabilidade-auth/compree-postman-aula-5.json) com as rotas disponíveis pela API.
  

