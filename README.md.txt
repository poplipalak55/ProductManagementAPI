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


DELETE /products/{id}

Purpose: Delete a product using its ID.

Example: DELETE /products/1

Expected success response: 204 No Content