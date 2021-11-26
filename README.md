# APUNTES LARAVEL 
### crear proyecto
```
composer create-project --prefer-dist laravel/laravel blog
```
### ver mi pagina
```
php artisan serve
````
### para crear una entidad/modelo
```
php artisan make:model Nombredelmodelo -mcr  /*poner el nombre del modelo con la primera letra en mayuscula y la palabra en singular*/
```
### correr migraciones 
```
php artisan migrate /*Esto se utilizza para ejecutar a base de datos*/
```

### pa poner en el controller 
use Illuminate\Support\Facades\DB;
