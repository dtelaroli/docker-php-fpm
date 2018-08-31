# Visão geral

O sistema foi desenvolvido com PHP 7.2 e Mysql 5.7.

## Configuração do ambiente

Você precisa ter instalado o [docker](https://docs.docker.com/install/) e o [docker-compose](https://docs.docker.com/compose/install/).

### Docker

O comando do compose vai criar toda a infraestrutura necessária para o projeto rodar:

`docker-compose up`

Caso você deseje recriar o ambiente você pode fazer o rebuild do projeto com o comando abaixo:

`docker-compose up --build`

É possível também apagar as imagens e volumes de disco totalmente para começar do zero o projeto:

```
docker-compose down -v
docker-compose up
```

### Banco de dados

Para ter acesso ao banco de dados instale o [mysql-workbench](https://www.mysql.com/products/workbench/).

Dados de conexão:

```
Host: localhost
Usuário: root
Senha: root
```

### Sistema

Os fontes localizados na pasta fonte estarão disponíveis para acesso. Acesse http://localhost para ter acesso ao sistema.
