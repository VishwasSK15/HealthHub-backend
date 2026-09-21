# HealthHub Backend API

The backend service for **HealthHub**, a full-stack doctor appointment booking platform. Built with Node.js, Express.js, and MongoDB, it provides secure APIs for user and doctor management, appointment scheduling, administration, media uploads, and payment workflows.

## ✨ Features

- User and doctor authentication
- Doctor profile and speciality management
- Appointment booking and management
- Doctor availability handling
- Admin operations and platform management
- RESTful API endpoints
- Cloudinary integration for media uploads
- Payment workflow integration
- MongoDB database integration
- CORS and environment-based configuration

## 🛠️ Tech Stack

- **Runtime:** Node.js
- **Framework:** Express.js
- **Database:** MongoDB with Mongoose
- **Authentication:** Token-based authentication
- **Media Storage:** Cloudinary
- **Payments:** Payment gateway integration
- **Deployment:** Render

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/VishwasSK15/HealthHub-backend.git
cd HealthHub-backend
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file and configure the required values for your database, authentication, Cloudinary, payment services, and server port.

Example structure:

```env
PORT=4000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret
```

Use the exact variable names expected by the application configuration.

### 4. Run the server

```bash
npm start
```

For development, use the development script configured in `package.json`, if available.

## 🔗 Frontend Integration

The backend is designed to work with the HealthHub React frontend and admin dashboard through REST API requests.

## 🔐 Security Note

Never commit `.env` files, database credentials, JWT secrets, API keys, or payment credentials to GitHub. Configure sensitive values through local environment variables or your deployment platform's protected settings.

## 👨‍💻 Author

**Vishwas S K**

GitHub: [VishwasSK15](https://github.com/VishwasSK15)
