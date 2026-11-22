# Node.js E-Commerce Back-End API

The server side of an online store. It stores users and products, handles secure login, and controls who can access what.

Built in June - October 2022 in Yangon, Myanmar, as a self-taught project during internet shutdowns and power cuts after the military coup. Uploaded to GitHub in 2026.

## Features
- REST API with routes for users, categories, sub-categories, products, roles, and permissions
- Full create, read, update, and delete for store categories
- User registration that blocks duplicate emails and phone numbers
- Secure login: bcrypt password hashing, JWT tokens, and Redis session caching
- Protected routes that check the token and Redis session before allowing access
- Role and permission models for role-based access control
- Image upload for product photos

## Tech Stack
- Runtime: Node.js, Express
- Database: MongoDB (Mongoose)
- Cache: Redis
- Security: bcrypt, JSON Web Token (JWT), Joi validation

## Project Structure
- controllers/: request handling logic
- models/: MongoDB data schemas
- routes/: API endpoints
- utils/: authentication, Redis, and validation helpers
- app.js: server setup
