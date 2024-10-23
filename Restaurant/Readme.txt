# Food Mania Restaurant 

## Overview

Welcome to the Trendy Restaurant E-Commerce Platform! This web application allows users to browse and order a variety of trendy restaurant items online. From Pizza to Avocado Toast, and from Coffee to Smoothies, we've got your cravings covered.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Frontend:**
  - Visually appealing homepage showcasing featured items.
  - Responsive design for optimal user experience on various devices.
  - Dynamic elements using JavaScript, such as interactive menus and image sliders.

- **Product Catalog:**
  - Enticing visuals and detailed descriptions for each item.
  - Sorting by popularity, filtering by category, and dynamic updates using JavaScript.
  - Product details page with customization options and an "Add to Cart" button.

- **Shopping Cart:**
  - Sleek page for viewing and customizing selected items.
  - Dynamic updates with JavaScript for adding, removing, and customizing items.
  - Easy quantity adjustments and a review section before checkout.

- **Backend (PHP and MySQL):**
  - Management of product data in a MySQL database.
  - Secure server-side logic for user shopping carts and order history.
  - Login and registration system with secure password hashing.

- **Checkout Process:**
  - Streamlined checkout process with multiple steps.
  - JavaScript enhancements for a guided user experience.
  - Connection to the backend to record and confirm orders.

- **User Authentication and Authorization:**
  - User authentication for tracking shopping carts and order history.
  - Authorization checks to ensure only authenticated users can proceed to checkout.

- **Online Ordering and Delivery:**
  - System for choosing delivery options and entering delivery details.
  - Connection to external services or APIs for online ordering and delivery.

- **Security Measures:**
  - Password hashing for user authentication.
  - Input sanitization and prepared statements to prevent SQL injection attacks.
  - Secure transmission of sensitive data, especially during checkout.

## Requirements

Please refer to the project requirements in the [Requirements.md](Requirements.md) file.

## Setup Instructions

Follow these instructions to set up and run the project locally. Make sure you have [PHP](https://www.php.net/) and [MySQL](https://www.mysql.com/) installed.

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/trendy-restaurant-ecommerce.git
   cd trendy-restaurant-ecommerce

(1)Database setup:

Create a MySQL database.
Import the provided SQL dump file (database.sql) into your database.

(2)Configuration:

Rename config-sample.php to config.php.
Open config.php and update the database connection details.

Usage
Visit the homepage and explore the featured items.
Navigate through the product catalog, customize items, and add them to your cart.
Go to the shopping cart, review your selections, and proceed to checkout.
Complete the checkout process, including address entry and payment details.

Technologies Used
HTML
CSS
JavaScript
PHP
MySQL
