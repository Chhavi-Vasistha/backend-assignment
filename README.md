# Node API

A CRUD REST API built with Node.js, Express and MongoDB (Mongoose).

## Setup

1. Install dependencies: `npm install`
2. Copy `.env.example` to `.env` and put in your MongoDB Atlas connection string.
3. Run: `npm run dev` (nodemon) or `npm start`

## Endpoints

| Method | URL | Description |
|--------|-----|-------------|
| GET | /api/products | Get all products |
| GET | /api/products/:id | Get one product |
| POST | /api/products | Create a product |
| PUT | /api/products/:id | Update a product |
| DELETE | /api/products/:id | Delete a product |

Example POST body (JSON):

```json
{ "name": "Keyboard", "quantity": 10, "price": 1499, "image": "https://example.com/kb.png" }
```
