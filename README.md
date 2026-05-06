# API Testing Project (Postman)

## Overview

This project demonstrates API testing using Postman for a sample REST API.

The collection covers core API testing concepts including CRUD operations, authentication, filtering, sorting, and validation.


## Features Covered

* Authentication (Login API, token handling)
* CRUD operations (GET, POST, PUT, DELETE)
* Environment variables (accessToken, userId, productId)
* Response validation (status codes, schema, business logic)
* Filtering validation (e.g., category = smartphones)
* Sorting validation (price, title)
* Data integrity checks (unique IDs, field types)


## Test Scenarios

* Successful login
* Get products list
* Get filtered products (by category)
* Get sorted results (price ascending/descending)
* Update user data
* Delete resource

## Example Validations

* Status code verification
* Response time checks
* Token structure validation (JWT)
* Business rules (price > 0, rating between 0–5)
* Sorting correctness (API returns properly sorted data)


## How to Run

1. Import the collection into Postman
2. Set up environment variable
3. Run requests individually or use Collection Runner


## Structure
* Ecom API Project
  * Auth
  * POST login
  * GET user Profile

* Products
  * GET all products
  * GET single product
  * GET search product
  * GET sort product
  * GET all product categories
  * GET prodduts category list
  * GET products by category

* Cart
  * POST add product
  * PUT update product
  * DELETE product
  * GET all carts
  * GET single cart
  * POST add cart
  * DELETE cart


<img width="1005" height="675" alt="Screenshot 2026-05-06 at 1 10 57 PM" src="https://github.com/user-attachments/assets/4f73a38f-3366-4cb6-ba34-c5fbc5186051" />



