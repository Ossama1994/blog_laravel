to install Laravel Project:
-Create copy of .env.example with name .env
-This is your environment file which is required by laravel project
-Open .env file and update this file with your MySQL Connection credentials
-Run  'composer install' 
-Run 'npm install' 
-Run 'npm run dev'
-After that run following command
    'php artisan key:generate'
    'php artisan config:cache'
    'composer dump-autoload'
-After that run your migration commands : php artisan migrate
-Now Run your project with following command php artisan serve --host 127.0.0.1 --port 8000
Now you are done, you can browse project on
localhost:8000 | 127.0.0.1:8000 | 0.0.0.0:8000 | YOUR_IP:8000