
Sistema para venta en casino con Laravel, angular, Maaterial, web token y json


sistema en laravel 5, angular y jwt. tiene dos roles de usarios cajeros y administradores los cuales pueden hacer solo canjeos o administrastrar jugadores, usuarios, fichas y registrar movimientos

todo esto editado y con ayuda externa 




crear los modelos
php artisan migrate

Correr seed para llenar modelos con datos de pruebas
#database/seeds/{nombre}Seeder.php
php artisan db:seed --class=DatabaseSeeder
php artisan db:seed --class=JugadorTableSeeder
php artisan db:seed --class=FichaTableSeeder
php artisan db:seed --class=CanjeoTableSeeder
php artisan db:seed --class=RegistroTableSeeder


