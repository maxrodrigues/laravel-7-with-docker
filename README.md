Esse é um projeto padrão Laravel na versão 7.28, o ambiente foi contruído em Docker, usando o PHP 7.2, NGINX e MySQL.

Após clonar o repositório, dento dele os comandos para executar são:

- docker run --rm -v $(pwd):/app composer install
- cp .env_example .env
- docker-compose up -d
- docker-compose exec app php artisan key:generate

O ambiente estará disponível em localhost:8000

