# MERN E-Commerce Project
---

This is a full-stack e-commerce application built using the MERN stack (MongoDB, Express.js, React, Node.js). It allows users to browse products, add them to a cart, process payments via Stripe, and includes features like user authentication and image uploads via Cloudinary.

---

**Prerequisites**
To run this project, you need basic knowledge of:

- Node.js: Server-side JavaScript runtime
- React: Frontend library for building user interfaces
- Express.js: Web framework for Node.js
- MongoDB: NoSQL database

---

**Installation**
1. Clone the Repository
git clone https://github.com/yash936936/MERN_ECOMMERCEE.git
cd MERN_ECOMMERCEE

2. Install Dependencies
Install dependencies for both the backend and frontend:
- Install backend dependencies
npm install

- Navigate to the client folder and install frontend dependencies
cd client
npm install

3. Environment Variables
Create a .env file in the root directory and add the following environment variables:

- MongoDB connection URI
MONGO_URI=your_mongodb_connection_string

- JWT secret for authentication
JWT_SECRET=your_jwt_secret

- Stripe secret key for payments
STRIPE_SECRET_KEY=your_stripe_secret_key

- Cloudinary credentials for image uploads
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

4. Run the Application
Start the backend and frontend servers:
- Start the backend server (from the root directory)
npm run server

- Start the frontend server (from the client directory)
cd client
npm start

The backend server will run on http://localhost:5000 and the frontend on http://localhost:3000.

---

**Features**

- Product Browsing: View a list of products with details such as price, description, and images.
- Shopping Cart: Add, remove, and update items in the cart.
- User Authentication: Register, login, and manage user profiles using JWT.
- Payment Processing: Secure payments via Stripe.
- Image Uploads: Upload product images using Cloudinary.
- Responsive Design: Mobile-friendly user interface.

---

**Technologies Used**

- MongoDB: Database for storing user and product data.
- Express.js: Backend framework for API development.
- React: Frontend library for building the user interface.
- Node.js: JavaScript runtime for the backend.
- Stripe: Payment processing.
- Cloudinary: Image upload and management.
- JWT: User authentication.

---

**Contributing**
Contributions are welcome! Please follow these steps:

- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Make your changes and commit (git commit -m "Add feature").
- Push to the branch (git push origin feature-branch).
- Open a pull request.
