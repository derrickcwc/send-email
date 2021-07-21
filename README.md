# send-email
## Run Locally (First Time Setup)

- Clone this repo
- Run MySQL database server using XAMPP or other
- Create a database named todo

1. ```cd send-email``` -> todo
2. ```composer install``` (run composer install inside todo folder)
3. ```npm install && npm run dev```
4. ```copy .env.example .env```
5. ```php artisan key:generate```
6. ```php artisan optimize:clear```
7. ```php artisan migrate``` (to create database tables)
8. ```php artisan serve```(inside todo folder)
