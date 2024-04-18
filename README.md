Para iniciar o projeto:

git clone: link

cd: nome do projeto

docker compose up -d

docker compose exec laravel_api cp .env.example .env

docker compose exec laravel_api composer install

docker compose exec laravel_api /var/www/html/artisan migrate:fresh


docker compose exec laravel_api /var/www/html/artisan db:seed

docker compose down


Acessar api
http://localhost:9090

Laravel Nuxt

https://www.youtube.com/watch?v=NY9yoqoN72w&t=1004s

https://www.youtube.com/watch?v=HLPoKz9j9KY&t=325s

 Docker

https://www.youtube.com/watch?v=ScmgXebitlQ&list=PLN_FLtIvNW0mo63rPdFBgL_UP5wF5eWLT


Para atualizar

git pull

cd laravel-nuxt

# Subir containers e atualizar as imagens
docker compose up -d --build
