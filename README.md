# restAPIExam
TODO application using rest API (Laravel)

Extract the ZIP file and configure the database settings using .env file.

The following are the available HTTP APIs:
.http://localhost:8000/api/todo/store    ---Create new TODO

.http://localhost:8000/api/todo/delete/{$id} ---Delete TODO

.http://localhost:8000/api/todo/get/{$id}    ----View one TODO

.http://localhost:8000/api/todo/gets         ----View all availabel TODOs

.http://localhost:8000/api/todo/update/{$id} ----Update one TODO 


Note: Run the following command in terminal before using the app:

-php artisan serve

-php artisan migrate

Thanks!
