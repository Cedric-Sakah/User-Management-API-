User Management API

A simple REST API built with Node.js, Express, TypeScript, MongoDB, and Mongoose.

Features
Create user
Get all users
Get user by ID
Update user
Delete user

Tech Stack
Node.js
Express.js
TypeScript
MongoDB
Mongoose

Installation

Bash
git clone <repo-url>
cd user-management-api
npm install

Environment Variables

Create a .env file in the root directory and add the following:

Plain Text
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/user-management

API Endpoints

Method
Endpoint
Description
POST
/api/users
Create user
GET
/api/users
Get all users
GET
/api/users/:id
Get single user
PUT
/api/users/:id
Update user
DELETE
/api/users/:id
Delete user

Example Request Body (for POST and PUT /api/users)

JSON

{
  "name": "Cedric",
  "email": "cedric@gmail.com",
  "age": 22
}

Author
Cedric Sakah

