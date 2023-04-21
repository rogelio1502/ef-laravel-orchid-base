# ef-laravel-orchid-base

Proyecto base para crear aplicación web usando Laravel Orchid complementando con paquete de componentes de indole propio.

### Instrucciones de instalación

---

* Instala paquetes composer.

  * `composer install`
* Actualiza e instala paquete de componentes.

  * `./update-ef-package.sh`

### Base de datos

---

Actualmente el proyecto esta configurado para usar sqlite como base de datos, cambia las credenciales en el archivo .env del proyecto, después dirigete a `config/database.php` y cambia la siguiente línea:

* `'default' => env('DB_CONNECTION','sqlite'),	`

por

* `'default' => env('DB_CONNECTION','mysql'),	`

### Enlaces de interés

* Laravel Orchid: `https://orchid.software/en/docs/`
* Repositorio del paquete de componentes `https://github.com/rogelio1502/ef-orchid-package `
