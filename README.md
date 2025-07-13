# Zabbix Server com Docker

Este projeto tem como objetivo criar um servidor Zabbix utilizando Docker e Docker Compose.

## Pré-requisitos

- Docker
- Docker Compose

## Estrutura do Projeto

Certifique-se de criar uma pasta chamada `zbx_env` no mesmo diretório onde está localizado o arquivo `docker-compose.yml`.

## Como executar

Após criar a pasta `zbx_env` e posicionar os arquivos necessários dentro dela, execute o seguinte comando para iniciar os containers em segundo plano:

```bash
docker compose up -d
