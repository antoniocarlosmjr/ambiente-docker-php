# Ambiente Docker PHP Laravel

Um ambiente de desenvolvimento Docker para ser utilizado em Laravel.

- PHP
- Nginx
- MySQL

### Estrutura de diretórios

- ambiente-docker-php
    - .docker
    - db
    - src
    - docker-compose.yml 
    
      
- *.docker*: este diretório contém todos os containers relacionados a configuração do PHP, Nginx, Mysql e o Dockerfile;
- *db*: diretório mapeado com o container do MySQL;
- *src*: diretório que contem o projeto laravel;
- *docker-compose.yml*: arquivo que contém todas as configurações do containers;
