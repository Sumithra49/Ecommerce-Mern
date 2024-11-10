# Ecommerce-Mern

![image](https://github.com/user-attachments/assets/5e4f2e52-ae7c-4c9e-a147-661ac54651af)

## Register Page
![image](https://github.com/user-attachments/assets/18b7e6b3-8946-439b-a780-467703678a9b)

## Login page
![image](https://github.com/user-attachments/assets/98360f99-a743-4753-921b-fd93963a1b5d)

## Cart
![image](https://github.com/user-attachments/assets/ea0a0b7d-1edc-4ede-831b-f963f14a78d0)

## Payment Method
![image](https://github.com/user-attachments/assets/613c0b42-0bda-4b96-906b-6883a4270831)

![image](https://github.com/user-attachments/assets/b4344c7e-4902-4560-b9e0-a4aafc0b9e8f)

![image](https://github.com/user-attachments/assets/08580512-5bcf-4255-bf93-dae2d6d50602)
![image](https://github.com/user-attachments/assets/cf2484be-816b-4fd1-9641-5a886098fdbc)

 ## User Details
 ![image](https://github.com/user-attachments/assets/5a3ff198-6063-4dda-952b-b7b48856391c)


## Features

- **User Authentication**: Secure registration, login, and logout functionality.
- **Product Browsing**: Users can view products by category or search by keywords.
- **Product Details**: Detailed view for each product with an option to add items to the cart.
- **Shopping Cart**: Allows users to add products to the cart and view cart items.
- **User Dashboard**: Users can view their profile, update information, and view past orders.
- **Admin Dashboard**: Allows admins to add, edit, or delete products and categories.
- **Responsive Design**: The app is fully responsive and optimized for various screen sizes.

## Environment Variables
Create a .env file in the root directory and set the following variables:
PORT=8000
MONGO_URI=your_mongodb_connection_string
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
PORT: The port on which the server runs.
MONGO_URI: MongoDB connection string.
RAZORPAY_KEY_ID: Razorpay API key ID for payment processing.
RAZORPAY_KEY_SECRET: Razorpay API key secret for payment processing.

# API Endpoints
## Auth Routes
POST /api/v1/auth/register - Register a new user.
POST /api/v1/auth/login - User login.
POST /api/v1/auth/logout - User logout.
## Category Routes
GET /api/v1/category - Get all categories.
POST /api/v1/category - Create a new category (Admin only).
PUT /api/v1/category/:id - Update an existing category (Admin only).
DELETE /api/v1/category/:id - Delete a category (Admin only).
## Product Routes
GET /api/v1/product - Get all products.
GET /api/v1/product/:productSlug - Get details of a specific product.
POST /api/v1/product - Create a new product (Admin only).
PUT /api/v1/product/:id - Update a product (Admin only).
DELETE /api/v1/product/:id - Delete a product (Admin only).
## Payment Routes
POST /api/v1/payment/order - Create a Razorpay order.
POST /api/v1/payment/verify - Verify payment signature from Razorpay.
## Tech Stack
React<br>
Html<br>
CSS<br>
Node.js<br>
Express.js<br>
Mongodb


