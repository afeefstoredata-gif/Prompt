Backend Schema Document
Database: MongoDB
Collections
Users Collection
{
  "_id": "ObjectId",
  "name": "string",
  "email": "string",
  "password": "string",
  "role": "admin",
  "createdAt": "date"
}
Products Collection
{
  "_id": "ObjectId",
  "title": "string",
  "description": "string",
  "price": "number",
  "image": "string",
  "stock": "number",
  "createdAt": "date"
}
Orders Collection
{
  "_id": "ObjectId",
  "productName": "string",
  "customerName": "string",
  "address": "string",
  "contactNumber": "string",
  "price": "number",
  "status": "Pending",
  "createdAt": "date"
}
Relationships

User → Admin Access Order → Product

API Endpoints
Authentication
POST /api/admin/login
Products
GET /api/products
POST /api/products
PUT /api/products/:id
DELETE /api/products/:id
Orders
POST /api/orders
GET /api/orders
Google Sheets Row Format

| Product Name | Customer Name | Address | Contact Number | Price |

Email Payload Format