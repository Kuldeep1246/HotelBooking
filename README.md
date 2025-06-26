# 🏨 Hotel Booking Website

A modern full-stack hotel booking web application that allows users to browse, search, and book hotels with ease. The platform is designed with a sleek UI, secure authentication, and integrated payment functionality.

---

## 🔧 Tech Stack

### Frontend:
- **React** – for building dynamic UI components
- **Tailwind CSS** – for utility-first styling
- **DaisyUI** – for pre-built responsive UI components

### Backend:
- **Node.js & Express** – for building robust REST APIs
- **MongoDB** – for database management (NoSQL)

### Integrations:
- **Stripe** – for secure and smooth payment processing
- **Clerk** – for authentication, user management, and session handling
- **Cloudinary** – for optimized image uploading and hosting

---

## 🚀 Features

- 🏨 **Hotel Listing:** Browse and view detailed information about hotels.
- 🔍 **Search & Filter:** Easily find hotels by location, price, or amenities.
- 🧾 **Booking System:** Book hotels with live availability tracking.
- 🔐 **Secure Authentication:** Sign up / Sign in via Clerk (supports email, password, social logins).
- 🖼️ **Cloudinary Integration:** Upload hotel images securely and efficiently.
- 💳 **Stripe Payments:** Seamless and secure checkout for hotel bookings.
- 📱 **Fully Responsive:** Mobile-first design with TailwindCSS and DaisyUI.

---

## 📂 Folder Structure (Basic Overview)

hotel-booking-app/
├── client/ # React Frontend
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── App.jsx
│ │ └── main.jsx
│ └── tailwind.config.js
│
├── server/ # Node.js Backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── config/
│ ├── index.js
│ └── .env
│
├── README.md
└── package.json

---

## 🛠️ Getting Started

### Prerequisites
- Node.js & npm
- MongoDB (local or Atlas)
- Stripe account
- Clerk account
- Cloudinary account

### Installation

# Clone the repository
git clone https://github.com/yourusername/hotel-booking-app.git
cd hotel-booking-app

# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install
Environment Variables
Create a .env file in the server/ directory and add the following:

## env
MONGO_URI=your_mongodb_uri
STRIPE_SECRET_KEY=your_stripe_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
CLERK_SECRET_KEY=your_clerk_secret_key


🚀 Running the App
Start Backend Server:
cd server
npm run dev

Start Frontend App:
cd client
npm run dev
