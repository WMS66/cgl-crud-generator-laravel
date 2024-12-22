# 🚧 cgl-crud-generator-laravel

Criar o projeto:

- Atualizar versao do Laravel

```PHP
composer global require laravel/installer
```

usar o instalador do Laravel

```PHP
laravel new
```

Escolher as opcoes para instalação.

Criar o Migrate

Criar a Model

```PHP
php artisan make:model Post -m
```

Criar Migração

```PHP
php artisan migrate
```

Instalar Pakage Crud Generator

```bash
composer require ibex/crud-generator --dev
```

publicar a configuração do Pakage

```PHP
php artisan vendor:publish --tag=crud
```

Gerar o CRUD
Todas as configurações serão geradas aqui.

```PHP
php artisan make:crud posts
```

Personalização:

- Dashboard
- views/layouts/app.blade.php
- Aplicar o modo Dark

    ''data-bs-theme="dark''
    ''remover a marcação light em cada view na div principal.''

```bash
npm install
npm run dev
```

Rodar o projeto

```PHP
php artisan serve
```

[Clone do Projeto](https://github.com/WMS66/cgl-crud-generator-laravel.git)
