# AI Image Generator
A web application that transforms text prompts into stunning AI-generated images.

## ✨ Features
* Text-to-Image Generation: Convert text descriptions into visual art
* User Authentication: Secure login and registration system
* Credit System: Purchase credits to generate images
* Responsive Design: Works on all device sizes
* Modern UI: Clean, intuitive interface with animations

## 🛠 Technologies Used
### Frontend
* React.js
* Tailwind CSS
* Framer Motion (for animations)
* React Router
* React Toastify (for notifications)
* Axios (for API calls)

### Backend
* Node.js
* Express.js
* MongoDB
* JWT Authentication
* Razorpay Payment Gateway
* Clipdrop API (for image generation)

## 🚀 Setup Instructions
#### 1. Clone the repository:
    git clone https://github.com/your-username/ai-image-generator.git
    cd ai-image-generator

### 2. Install dependencies for both frontend and backend:
####  Frontend
    cd frontend
    npm install

####  Backend
    cd ../backend
    npm install

#### 3. Create a .env file in the backend directory with the required environment variables.

#### 4. Run the development servers:
    # In backend directory
    npm start server

    # In frontend directory
    npm run dev

# 📱 Usage
### 1. Register or log in to your account
### 2. Purchase credits through the payment gateway
### 3. Enter your text prompt to generate unique AI images
### 4. Download or share your creations

# 📁 Project Structure

    ai-image-generator/
    ├── frontend/           # Contains all React components and pages
    ├── backend/            # Node.js server with API routes and controllers
    │   ├── models/         # MongoDB schema definitions
    │   ├── routes/         # Express route definitions
    │   └── controllers/    # Business logic for API endpoints

# 📄 License
### MIT License – Free for personal and commercial use
