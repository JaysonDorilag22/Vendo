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
   git clone https://github.com/yourusername/vendo.git  
   cd vendo  

2. Install dependencies  
   # Frontend  
   cd client  
   npm install  

   # Backend  
   cd ../server  
   npm install  

3. Create a `.env` file in the server folder with:  
   MONGO_URI=your_mongodb_uri  
   JWT_SECRET=your_jwt_secret  

4. Run the development servers  
   # Backend  
   cd server  
   npm run dev  

   # Frontend  
   cd client  
   npm run dev  

## Folder Structure
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
