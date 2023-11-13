
Install

0: Git clone
=> cd src:
1: composer install

2: npm install

####
--- composer require tymon/jwt-auth
--- php artisan jwt:secret
####
3: .env.example  to .env  => config database

4: php artisan key:generate

5: php artisan migrate

6: php artisan storage:link

7: npm run dev


8: goto website
php artisan serve