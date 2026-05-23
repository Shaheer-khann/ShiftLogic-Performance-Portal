# ShiftLogic Performance Portal

A full-stack web application for managing a high-performance racing garage.
Built as a college assignment covering the complete web development stack.

## Project Contents

### Phase1-4_Vanilla_PHP.zip
Complete garage management portal built without any framework.

Technologies: HTML5, CSS3, Bootstrap 5, JavaScript, jQuery, PHP 8 OOP, MySQL, PDO

Features:
- Home page with services grid and stats
- Crew Directory with full CRUD operations
- Service Booking form with JS validation saving to MySQL database
- Performance Parts catalogue with jQuery modal effects
- Staff Login with PHP session authentication
- Protected Dashboard with session and cookie data

Test login credentials:
- Admin: admin@shiftlogic.com / admin123
- Mechanic: mechanic@shiftlogic.com / mech123

### Phase5_Laravel.zip
Complete rebuild of the same application using Laravel MVC framework.

Technologies: Laravel, Blade Templates, Eloquent ORM, Migrations, Seeders

Features:
- Crew CRUD application with department relationships
- Performance Parts catalogue
- Supercar build photo gallery with file upload
- REST API endpoint returning JSON at /api/parts
- Shared Blade layout across all pages

Setup for Laravel:
1. Extract Phase5_Laravel.zip
2. Run composer install
3. Copy .env.example to .env and set your database name to shiftlogic_laravel
4. Run php artisan key:generate
5. Run php artisan migrate --seed
6. Run php artisan storage:link
7. Run php artisan serve
8. Visit http://127.0.0.1:8000

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 + Bootstrap 5 | Styling and layout |
| JavaScript + jQuery | Validation and effects |
| PHP 8 | Server-side logic |
| MySQL | Database |
| PDO | Secure queries |
| Laravel | MVC framework |
| Eloquent ORM | Database abstraction |
| Blade | Templating engine |

## Developer
Shaheer Khan
