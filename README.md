## Livewire app for Youtube Course in My channel

## To install the application

1. clone the repo : git clone https://github.com/alzaabi98/livewire-course.git
2. copy .env-example as .env file 
3. Create database and modify .env file with db name and db account details
4. install venodr packages : composer install
5. npm install
6. npm run dev
7. Database Migrate  : php artisan migrate
8. Run : php artisan key:generate
9. Open the project in browser and register one user to be able to run seeder in the next step
10. Database Seed: php artisan db:seed
11. Visit /tasks to see all tasks for this user ( or click tasks from dropdown under username menu)
