README.md


Make sure you have the following installed on your machine:

    Composer
    Node.js
    NPM (comes with Node.js installation)
    PHP
    MySQL or any other database system of your choice

Steps

 Clone the repository:

 bash

    (https://github.com/Amy9594/qa-engineer-exam.git)

Navigate to the project directory:

bash 

    cd your-project

Install Composer dependencies:

 bash
 
     composer install

 Install NPM dependencies:

 bash    
            
	npm install

Copy the environment file:

bash

    cp .env.example .env

Generate an application key:

bash

    php artisan key:generate

Configure the database:

Update the .env file with your database credentials:
           
    dotenv


 Modify Database
     DB_CONNECTION=mysql
     DB_HOST=127.0.0.1
     DB_PORT=3306
     DB_DATABASE=your_database_name
     DB_USERNAME=your_database_username
     DB_PASSWORD=your_database_password

Run database migrations and seeders:

bash

    php artisan migrate --seed

Run the tests:

bash

    php artisan test
