# Painel de Senhas com Flask e Docker

Este projeto é uma aplicação Flask para gerenciar senhas em uma clínica, utilizando Flask, Socket.IO e PostgreSQL.

## Pré-requisitos

Antes de começar, certifique-se de ter os seguintes softwares instalados:

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Como Rodar o Projeto

Siga os passos abaixo para iniciar o projeto em um ambiente Docker:

### 1. Clonar o Repositório

```bash
git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
cd SEU_REPOSITORIO


 ## Atualizações Futuros (Push)
 1 - Adicione os arquivos modificados: git add .
 2 - Faça um novo commit: git commit -m "Descrição das mudanças"
 3 - Envie as mudanças para o GitHub: git push


 ## Configurar Variáveis de Ambiente
 Crie um arquivo .env na raiz do projeto com as seguintes variáveis de ambiente:
 # .env
POSTGRES_DB=painel_senhas_db
POSTGRES_USER=admin
POSTGRES_PASSWORD=admin123
POSTGRES_HOST=db
POSTGRES_PORT=5432
