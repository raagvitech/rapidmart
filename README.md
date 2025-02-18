# RapidMart - Quick Commerce Website

RapidMart is a full-stack quick commerce platform designed to provide a seamless online shopping experience. The website is built using modern technologies like Next.js, shadcn component library, MongoDB, Firebase, and Stripe for handling payments.

## Features
- **Product Browsing**: Users can easily explore products categorized for quick navigation.
- **User Authentication**: Secure login and registration.
- **Payment Integration**: Stripe handles secure and reliable payments.
- **Responsive Design**: Optimized for all devices, providing a smooth user experience on mobile, tablet, and desktop.
- **Fast & Scalable**: Built with Next.js for both frontend and backend, ensuring high performance and scalability.

## Tech Stack
- **Next.js**: A React framework that powers both the frontend and backend of the application, enabling server-side rendering and API routes for optimized performance.
- **shadcn**: A flexible and highly customizable component library built on React, used to style and build the user interface of the website.
- **MongoDB**: NoSQL database used to store all product, user, and order-related data.
- **Firebase**: Firebase is used as an object storage solution to store product images and other media.
- **Stripe**: Stripe is integrated to provide a reliable and secure payment gateway for handling transactions.

## Setup & Installation

### 1. Clone the repository:

```bash
git clone https://github.com/raagvitech/rapidmart.git

**### 2. Navigate to the project directory:**
bash
Copy
Edit
cd FlashMart
3. Install dependencies:
bash
Copy
Edit
npm install
4. Set up environment variables.
Create a .env.local file in the root of your project and add the necessary configurations:

bash
Copy
Edit
MONGO_URI=your_mongo_connection_string
ACCESS_TOKEN_SECRET=your_access_token_string
NEXT_PUBLIC_STRIPE_PUBLISHER_KEY=your_stripe_public_key
STRIPE_SECRET_KEY=your_stripe_secret_key
NEXT_PUBLIC_API_KEY=your_firebase_api_key
NEXT_PUBLIC_APP_ID=your_firebase_app_id
5. Run the development server:
bash
Copy
Edit
npm run dev
Visit the application at http://localhost:3000.

vbnet
Copy
Edit

