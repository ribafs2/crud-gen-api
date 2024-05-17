# Gerador de CRUDs para API Laravel
## Com suporte para as versões 8, 9 e 10 do Laravel

## Escolha uma das versões:
```bash
composer create-project laravel/laravel:8.* api
composer create-project laravel/laravel:9.* api
composer create-project laravel/laravel:10.* api

cd api

wget https://ribamar.net.br/down/laravel/commands/crud-gen-api.zip

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
## Tutorial para API no Laravel 11
Como este gerador não suporta a versão 11 do Laravel
Segue um tutorial para essa versão

https://www.binaryboxtuts.com/php-tutorials/laravel-tutorials/how-to-make-laravel-11-rest-api/ 
