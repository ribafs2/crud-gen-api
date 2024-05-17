# Gerador de CRUDs para API Laravel
## Com suporte para as versões 8, 9 e 10 do Laravel

## Escolha uma das versões:
```bash
composer create-project laravel/laravel:8.* api
composer create-project laravel/laravel:9.* api
composer create-project laravel/laravel:10.* api

cd api
```
wget https://ribamar.net.br/down/laravel/commands/crud-gen-api.zip
```bash
unzip crud-gen-api.zip
```
Exemplo de CRUD
```bash
php artisan crud:api products name,price
```
Ajustar .env para banco
```bash
php artisan migrate

php artisan serve

http://127.0.0.1:8000/api/products
```
