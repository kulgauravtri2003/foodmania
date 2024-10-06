A complete MERN stack application for food delivery, featuring Stripe integration for payment processing. The project is deployed using Render for the backend and Vercel for both the client and admin frontend.

Project Structure
backend: Contains the Express.js server code and Stripe API integration.
frontend: The client-side React application.
admin: The admin panel frontend for managing orders and users.
Features
User registration and login
Food listing and ordering
Admin panel for managing orders
Stripe payment integration
Discount coupons support
Discount Coupons
SAVE25: ₹25 off
SAVE50: ₹50 off
SAVE75: ₹75 off
Deployment
The project is deployed online with the following URLs:

Client Frontend: Tomato Food Delivery - Client
Admin Frontend and Backend: Link not attached for safety and security purposes.
Getting Started
Clone the repository:

git clone https://github.com/Tanmay-312/Tomato-Food-Delivery.git
Navigate to the project directory:

cd Tomato-Food-Delivery
Install dependencies for each folder:

Backend:

cd backend
npm install
Frontend:

cd frontend
npm install
Admin:

cd admin
npm install
Set up environment variables:

Create a .env file in the root of each directory (backend, frontend, admin) and add your environment variables. The .env file should be configured with the necessary variables for your project.

Run the development servers:

Backend:

cd backend
npm run server
Frontend:

cd frontend
npm run dev
Admin:

cd admin
npm run dev
