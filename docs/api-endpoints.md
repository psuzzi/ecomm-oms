# API Endpoints

## Product Catalog Service

- GET /products - List all products
- GET /products/{id} - Get a specific product
- POST /products - Create a new product
- PUT /products/{id} - Update a product
- DELETE /products/{id} - Delete a product
- GET /products/search - Search products by name or category
- PUT /products/{id}/inventory - Update product inventory

## Order Service

- POST /orders - Create a new order
- GET /orders/{id} - Get a specific order
- GET /orders/user/{userId} - Get orders for a specific user
- PUT /orders/{id}/status - Update order status
- GET /orders/{id}/items - Get items for a specific order

## User Service

- POST /users - Create a new user
- GET /users/{id} - Get a specific user
- PUT /users/{id} - Update user information
- DELETE /users/{id} - Delete a user
- POST /auth/login - User login
- POST /auth/logout - User logout