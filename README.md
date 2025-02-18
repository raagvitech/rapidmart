RapidMart - Quick Commerce Website
RapidMart is a full-stack quick commerce platform designed to provide a seamless online shopping experience. The website is built using modern technologies like Next.js, Shadcn component library, MongoDB, Firebase, and Stripe for handling payments.

Features
Product Browsing: Users can easily explore products categorized for quick navigation.
User Authentication: Secure login and registration.
Payment Integration: Stripe handles secure and reliable payments.
Responsive Design: Optimized for all devices, providing a smooth user experience on desktop and mobile.
Fast & Scalable: Built with Next.js for both frontend and backend, ensuring high performance and scalability.
Tech Stack
Next.js: A React framework that powers both the frontend and backend of the application, enabling server-side rendering and API routes for optimized performance.
Shadcn: A flexible and highly customizable component library built on React, used to style and build the user interface of the website.
MongoDB: NoSQL database used to store all product, user, and order-related data.
Firebase: Used as an object storage solution to store product images and other media.
Stripe: Integrated to provide a reliable and secure payment gateway for handling transactions.
Setup & Installation
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/raagvitech/rapidmart.git
2. Navigate to the Project Directory
bash
Copy
Edit
cd rapidmart
3. Install Dependencies
bash
Copy
Edit
npm install
4. Set Up Environment Variables
Create a .env.local file in the root of your project and add the necessary configurations:

env
Copy
Edit
MONGO_URI="mongodb+srv://sbhuvan455:gaiDu4VOoQtHTOID@cluster0.ihlpogh.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0"
ACCESS_TOKEN_SECRET="your-access-token-secret"
GOOGLE_MAPS_API_KEY="your-google-maps-api-key"
NEXT_PUBLIC_GOOGLE_MAPS_API_KEY="your-next-public-google-maps-api-key"
NEXT_PUBLIC_STRIPE_PUBLISHER_KEY="your-next-public-stripe-publisher-key"
STRIPE_SECRET_KEY="your-stripe-secret-key"
NEXT_PUBLIC_API_KEY="your-next-public-api-key"
NEXT_PUBLIC_APP_ID="your-next-public-app-id"
5. Run the Development Server
bash
Copy
Edit
npm run dev
6. Visit the Application
Open your browser and visit http://localhost:3000 to view the app.
