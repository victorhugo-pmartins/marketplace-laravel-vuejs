# marketplace-laravel-vuejs
Aplicação de Marketplace utilizando no back-end RESTful APIs em Laravel 5.3 e no front-end uma aplicação SPA VueJS.

#TODO
  - Arquitetura Multi-Tenancy;
  - Auth com JWT;
  - Iugu Pagamentos
  - Laravel Echo para menssagens Realtime;
  - SPA com VueJS

#Instalação
  - Clone o repositório;
  - No diretório criado, faça:
  - composer install
  - copie o arquivo .env.example para .env e edite-o apontando para o banco de dados
  - php artisan migrate
  - php artisan db:seed
  - php artisan key:generate
