# Vendo 🛒
Vendo is an e-commerce web application built with the MERN stack. It provides a smooth online shopping experience where users can browse products, add them to their cart, and place orders. Admins can manage products, users, and orders through a simple dashboard.

## Features
- User authentication and authorization (JWT)
- User profile management
- Product CRUD (Create, Read, Update, Delete)
- Image uploads for products
- Shopping cart and checkout flow
- Order management (User and Admin)
- Search and filter products
- Admin dashboard with analytics

## Tech Stack
- Frontend: React (Vite), Tailwind CSS
- Backend: Node.js, Express.js
- Database: MongoDB (Atlas)
- Authentication: JWT + bcrypt
- Deployment: Vercel (frontend), Render/Heroku (backend)

## Installation
1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/vendo.git
   cd vendo
Install dependencies

bash
Copy code
# Frontend
cd client
npm install

# Backend
cd ../server
npm install
Create a .env file in the server folder with:

env
Copy code
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
Run the development servers

bash
Copy code
# Backend
cd server
npm run dev

# Frontend
cd client
npm run dev
Folder Structure
csharp
Copy code
vendo/
│
├── client/          # React (Vite) + Tailwind frontend
│   ├── public/
│   └── src/
│
├── server/          # Express backend
│   ├── models/      # Mongoose schemas
│   ├── routes/      # API routes
│   └── controllers/ # Business logic
│
└── README.md
