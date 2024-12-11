# Book Reviews

This project is part of Section 4 of the course and focuses on building a **Book Reviews** web application. The goal is to create a fully functional system where users can view, rate, and review books, leveraging Laravel's component-based architecture and advanced features.

## Features

- **Book Listing:** Displays a list of books with their titles, authors, and average ratings.
- **Star Rating System:** Allows users to see and submit star ratings for books, with visual star-based representation.
- **Reviews Management:** Submit, view, and manage user reviews.
- **Dynamic Components:** Utilized Blade components for reusable UI elements like the star rating system.
- **Caching:** Implemented caching to optimize database queries for the books list.

## Tools and Technologies

- **Laravel** Version 11.31
- **PHP:** Version 8.2.12
- **Blade Components:** Used for modular and reusable UI components.
- **Eloquent ORM:** For database interaction.
- **Tailwind CSS:** Styled the UI components for a responsive design.
- **MySQL:** Database for storing book and review information.

## Learning Objectives

1. **Blade Components:** Understand how to pass data to components and create reusable elements like the star rating display.
2. **Eloquent Relationships:** Practice one-to-many relationships for books and reviews.
3. **Caching with Laravel:** Optimize performance using caching for expensive database queries.
4. **Dynamic Data Binding:** Use Blade directives to

## **Setup Instructions**
1. Clone the repository:
   ```bash
   git clone https://github.com/ernest-salas-bauza/BookReviews.git
   ```
2. Install dependencies:
   ```bash
   composer install
   ```
3. Set up the `.env` file for database configuration and generate the application key:
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```
4. Run migrations to create database tables:
   ```bash
   php artisan migrate
   ```
5. Serve the application locally:
   ```bash
   php artisan serve
   ```
6. Access the application in your browser at `http://localhost:8000`.
