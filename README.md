# Professional-Blog-API
This is a professional blog restful API for blog post.
A full-featured RESTful Blog API built with Node.js, Express, and MongoDB.  
It supports user authentication and CRUD operations for blog posts.

---
## Features
- User Registration & Login (JWT Authentication)
- Create, Read, Update, Delete (CRUD) Blog Posts
- Protected Routes with Middleware
- MongoDB Database Integration
- Clean MVC Architecture

---
## Tech Stack
- Node.js
- Express.js
- MongoDB
- Mongoose
- JSON Web Token (JWT)
- dotenv

---
## Project Structure
Professionnal-blog-api
│
├── controllers
│   ├── authController.js
│   └── postController.js
│
├── models
│   ├── User.js
│   └── Post.js
│
├── routes
│   ├── authRoutes.js
│   └── postRoutes.js
│
├── middleware
│   ├── auth.js
│   ├── errorHandler.js
│   └── rateLimiter.js
│
├── validators
│   ├── authValidator.js
│   └── postValidator.js
│
├── config
│   └── db.js
│
├── server.js
│
├── node_modules
│
├── package-lock-json
│
├── packae.json
│
├── strt.txt
│
├── readme.md
│
└── .env

### 1. Clone the repository
git clone: https://github.com/chidinma/blog-api.git (https://github.com/Chidinma-Git/Professional-Blog-API)
cd blog-api
