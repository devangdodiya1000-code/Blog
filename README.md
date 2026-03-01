📝 Laravel 10 Blog Project
📌 About The Project

This is a personal blog application built using Laravel 10.
The main purpose of this project is to practice backend development, improve logic-building skills, and experiment with Laravel features.

It includes basic blog functionalities such as post creation, editing, deletion, and listing.

🚀 Features

Create, Edit, Delete Blog Posts

Form Validation

MVC Architecture

Clean and Structured Code

Authentication (if implemented)

RESTful Routing

Blade Templating

🛠️ Built With

Laravel 10

PHP

MySQL

Blade Template Engine

Bootstrap / Tailwind (if used)

⚙️ Installation Guide

Follow these steps to run the project locally:

1️⃣ Clone the Repository
https://github.com/devangdodiya1000-code/Blog.git

2️⃣ Navigate to Project Folder
cd Blog

3️⃣ Install Dependencies
composer install

4️⃣ Copy Environment File
cp .env.example .env

5️⃣ Generate Application Key
php artisan key:generate

6️⃣ Configure Database

Open the .env file and update:

DB_DATABASE=your_database_name
DB_USERNAME=your_database_username
DB_PASSWORD=your_database_password
7️⃣ Run Migrations
php artisan migrate

(If you have seeders)

php artisan db:seed
8️⃣ Start Development Server
php artisan serve

Now open:

http://127.0.0.1:8000
📂 Project Structure

app/ – Application logic (Controllers, Models)

routes/ – Web and API routes

resources/views/ – Blade templates

database/migrations/ – Database structure

public/ – Public assets

🎯 Purpose of This Project

This project was created for:

Practicing Laravel 10

Improving backend development skills

Strengthening logic-building ability

Testing new features and concepts

👨‍💻 Author

Devang Dodiya
Backend Developer | Laravel & CodeIgniter
2.5+ Years of Experience
