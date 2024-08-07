# Book Review Laravel App

This project is a book review application developed using PHP with the Laravel framework and containerized using Docker. The goal is to provide a platform where users can review books, see the most popular and highest-rated books, and interact with the features of a book review system.

## Documentation

**Project Setup and Creation**:

-   Initial setup of the project using Laravel and Docker.

## Features

-   Listing Popular and Highest Rated Books: Displaying the highest-rated and popular books.
-   Recent Reviews: Fetching books with recent reviews.
-   Filter Books by Title: Implementing a form and logic to filter books by title.
-   Displaying Popular and Highest Rated Books: - Developing views and logic for popular and highest-rated books.
-   Single Book Page: Creating a dedicated page for each book.
-   Review Count and Average Rating: Displaying review count and average rating on all pages.
-   Blade Components: Creating a star rating component using Blade.
-   Adding Reviews: Implementing a scoped resource controller to add reviews.


/books

![image](https://github.com/user-attachments/assets/a8a740be-508e-4c1e-b581-45af4f50b250)

/books/id
![image](https://github.com/user-attachments/assets/76b0ddba-6c65-476b-b41d-fb835be3ceee)

/books/id/reviews/create
![image](https://github.com/user-attachments/assets/947ae22a-8a55-4c55-ad32-ff1161b5c86c)

review added to book of id 16 with current date (july 15, 2024)
![image](https://github.com/user-attachments/assets/2fefb3fd-292c-4d36-bbbb-f9762afbe062)

filter/search bar

/?title=aliquam&filter=
![image](https://github.com/user-attachments/assets/8f65e8f4-a2ee-4362-bc12-6558179d782e)

**Model Relationships**:

-   Definition of one-to-many relationships between models.
-   Querying and associating related models.
-   Utilizing local scopes for specific queries.

**Controllers and Resource Controllers**:

-   Setting up controllers to manage CRUD operations.

**Test Data Generation**:

-   Use of Factory and Seeder to generate mock data.

**Caching and Invalidating Cache**:

-   Implementing caching to improve query performance.
-   Managing cache invalidation when data is updated.

**Rate Limiting**:

-   Applying rate limits for adding reviews.


<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

-   [Simple, fast routing engine](https://laravel.com/docs/routing).
-   [Powerful dependency injection container](https://laravel.com/docs/container).
-   Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
-   Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
-   Database agnostic [schema migrations](https://laravel.com/docs/migrations).
-   [Robust background job processing](https://laravel.com/docs/queues).
-   [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

### Premium Partners

-   **[Vehikl](https://vehikl.com/)**
-   **[Tighten Co.](https://tighten.co)**
-   **[WebReinvent](https://webreinvent.com/)**
-   **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
-   **[64 Robots](https://64robots.com)**
-   **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
-   **[Cyber-Duck](https://cyber-duck.co.uk)**
-   **[DevSquad](https://devsquad.com/hire-laravel-developers)**
-   **[Jump24](https://jump24.co.uk)**
-   **[Redberry](https://redberry.international/laravel/)**
-   **[Active Logic](https://activelogic.com)**
-   **[byte5](https://byte5.de)**
-   **[OP.GG](https://op.gg)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
