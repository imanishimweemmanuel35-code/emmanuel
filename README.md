# E-Shopping Website

A complete e-commerce platform with user authentication, product management, and order processing.

## Features

### User Types
1. **Admin**
   - Manage all users and products
   - View statistics
   - Delete users and products

2. **Seller**
   - Upload product photos
   - Set product location
   - Manage their products

3. **Customer**
   - Browse products
   - Download product information
   - Place orders
   - Comment on products

## Website Pages (10+ pages)

1. index.html - Home page
2. login.html - Login page
3. register.html - Registration page
4. products.html - All products listing
5. product-detail.html - Product details with comments
6. about.html - About page
7. contact.html - Contact form
8. seller-dashboard.html - Seller dashboard
9. admin-dashboard.html - Admin dashboard
10. customer-dashboard.html - Customer orders

## Technologies Used

- HTML5
- CSS3
- JavaScript
- PHP
- MySQL

## Database Setup

1. Import the database.sql file into your MySQL server
2. Update database credentials in php/config.php if needed
3. Default admin credentials:
   - Email: admin@eshopping.com
   - Password: admin123

## Installation

1. Place all files in your web server directory (e.g., htdocs for XAMPP)
2. Import database.sql into MySQL
3. Create an 'uploads' folder in the root directory for product images
4. Access the website through your localhost

## User-Friendly Features

- Responsive design
- Clean navigation
- Form validation
- Easy product browsing
- Download product information
- Comment system
- Order tracking

## Database Tables

- users (Admin, Seller, Customer data)
- products (Data entered by Sellers)
- orders (Data entered by Customers)
- comments (Customer comments)
- contacts (Contact form submissions)
