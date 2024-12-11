# Kitchen Online

## Overview
Kitchen Online is an e-commerce platform built with Laravel designed to offer a wide range of kitchenware products. This platform provides an online store interface for users to browse and purchase kitchenware products easily.

## Features
- Browse products by category
- Search for products
- Product details page
- Shopping cart functionality
- User authentication (login and registration)
- Admin dashboard for managing products and categories
- Responsive design for mobile and desktop

## Installation
To set up this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone github.com/engr-ibraheem/kitchen-online.git
   ```

2. Navigate into the project directory:
   ```bash
   cd kitchen-online
   ```

3. Install the project dependencies:
   ```bash
   composer install
   npm install
   ```

4. Set up the environment file:
   ```bash
   cp .env.example .env
   ```
   Update the `.env` file with your database credentials and other necessary configurations.

5. Generate the application key:
   ```bash
   php artisan key:generate
   ```

6. Run the migrations and seeders to set up the database:
   ```bash
   php artisan migrate --seed
   ```

7. Serve the application:
   ```bash
   php artisan serve
   ```
   The application will be available at `http://localhost:8000`.

## Usage
Once the application is running, you can visit the homepage to browse kitchenware products, add items to your cart, and complete purchases. Admin users can log in to access the dashboard to manage products and categories.

## Technologies Used
- Laravel (PHP framework)
- MySQL (Database)
- Vue.js (Frontend)
- Tailwind CSS (Styling)
- Composer (PHP dependency management)
- NPM (JavaScript dependency management)

## Contributing
If you'd like to contribute to the project, feel free to submit a pull request. Please ensure that your code follows the existing coding standards and include relevant tests where applicable.

## License
This project is licensed under the MIT License.
