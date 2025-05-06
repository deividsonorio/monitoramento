# Monitoramento
v0.1.1


## Sobre

Projeto de ferramente de monitoramento auto-hospedada.

## Iniciando

Para a execução em ambiente de desenvolvimento, você deve instalar previamente o docker e o docker-compose.

- [Get Docker](https://docs.docker.com/get-docker/)
- [Install Docker Compose](https://docs.docker.com/compose/install/)

### Rodando o projeto

Na pasta do projeto rodar:

```
docker compose up -d
```

## Acessando

O sistema deve estar disponível no endereço:

http://localhost:3001/

### Configurando

No primeiro acesso será pedido o idioma, banco de dados que se deseja utilizar e a criação de um usuário.

Para o banco de dados são 3 opções:

- Embedded MariaDB (imagem docker incorporada e configurada do MariaDB)
- MariaDB/MySQL (conectar a um banco de dados existente)
- SQLite (Um arquivo de banco de dados simples)
- 
### Usuário administrador

Forneça o nome, senha e confirmação de senha do usuário administrador. 

### Utilização do sistema 

Informações de como utilizar o sistema podem ser encontradas aqui:

https://github.com/louislam/uptime-kuma/wiki
