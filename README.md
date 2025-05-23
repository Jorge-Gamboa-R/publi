# publi
trabajo final bases de datos 2

paso 1
intalar xampp
intalar mysql  - workbench
instalacion de PHP

paso 2
instalacion de composer
Composer es una herramienta de gestión para dependencias en PHP
https://getcomposer.org/

paso 3
instalar Node

paso 4
crear un nuevo proyecto Laravel mediante el comando
create-project de Composer

paso 5
configura base de datos, en este caso se utilizo mysql - workbench
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=publi
DB_USERNAME=root
DB_PASSWORD=*****

paso 6
Creación de migraciones o crear tablas
utilizar el siguiente comando:
php artisan make:migration create_nombre_de_la_tabla_table
se generará un archivo de migración en el directorio database/migrations.

paso 7
creacion de modelos
crea un modelo junto con su migración, puedes utilizar el siguiente comando:
php artisan make:model NombreDelModelo -m
se generará un archivo de modelo en app/Models

paso 8
creacion del controlador
php artisan make:controller nombredelcontrolador
Los controladores son responsables de manejar las solicitudes HTTP

paso 9
Al utilizar el comando php artisan make:controller con la opción --resource,
Laravel genera un controlador con los métodos básicos necesarios para realizar operaciones CRUD

paso 10
Define las rutas de tu aplicación en routes/web.php para las vistas de las páginas web y
en routes/api.php para las rutas de la API.

paso 11
Defina las vistas en resources - views 
crea carpetas para cada tabla, para visualizar en web las cuales se descargaran en bootstrap
igual descarga el admi

paso 12
Defina en resources - views - plantilla
una segunta plantilla he integra en en codigo
