laravel new ApiExample

create database

modify .env file

php artisan make:model Task --migration

Edit migration file

php artisan migrate

Edite routes/api.php

Test with postman:

Create a task

Post $domain/api/tasks insert name field in body.

Show all tasks

Get $domain/api/tasks

Delete a task

Delete $domain/api/tasks/{id}

Update a task

Put $domain/api/tasks/{id} insert name field in body and select x-www-form-urlencoded.
