#ProductManagementAPI

GET /products

Purpose: Retrieve all products.

Example response:

[
  {
    "id": 1,
    "name": "Laptop",
    "price": 999.99
  }
]


POST /products

Purpose: Create a new product.

Example request body:

{
  "name": "Keyboard",
  "price": 49.99
}