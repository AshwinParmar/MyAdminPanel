########################################################
symfony new adminapp

http://192.168.91.11/MyAdminPanel/web/app_dev.php/book/

php bin/console generate:bundle --namespace=Custom/BookBundle
composer dump-autoload

php bin/console generate:bundle --namespace=Custom/BookBundle
php bin/console doctrine:generate:entity
php bin/console doctrine:schema:update --force
php bin/console generate:doctrine:crud

Just chmod 777 on your app/cache and app/log directory.
Better solutions are proposed on the doc here -> http://symfony.com/doc/current/setup/file_permissions.html

chmod -R 777 var/

########################################################
 After fixing these issues, re-check Symfony requirements executing this command:

   php adminapp/bin/symfony_requirements

 Then, you can:

    * Change your current directory to /var/www/html/MyAdminPanel/adminapp

    * Configure your application in app/config/parameters.yml file.

    * Run your application:
        1. Execute the php bin/console server:start command.
        2. Browse to the http://localhost:8000 URL.

    * Read the documentation at http://symfony.com/doc

Just chmod 777 on your app/cache and app/log directory.
Better solutions are proposed on the doc here -> http://symfony.com/doc/current/setup/file_permissions.html