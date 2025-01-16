# ANTES DE CORRER EL PROYECTO
## COMANDOS
1. Instalar dependencias: composer install
2. Copiar el .env.example - linux cp .env.example .env - windows copy .env.example .env
3. Generar app_key - php artisan key:generate
4. Correr migraciones y seeders - php artisan migrate --seed
5. para que el middleware funcione tenemos que generar un token con el comando - php artisan jwt:secret