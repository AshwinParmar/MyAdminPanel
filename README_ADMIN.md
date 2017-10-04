symfony new adminapp

Just chmod 777 on your app/cache and app/log directory.
Better solutions are proposed on the doc here -> http://symfony.com/doc/current/setup/file_permissions.html

 Downloading Symfony...

    5.8 MiB/5.8 MiB ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓  100%

 Preparing project...

 ✕  Symfony 3.3.9 was successfully installed but your system doesn't meet its
     technical requirements! Fix the following issues before executing
     your Symfony application:

 * date.timezone setting must be set
   > Set the "date.timezone" setting in php.ini* (like Europe/Paris).

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