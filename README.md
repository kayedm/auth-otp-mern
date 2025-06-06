# auth-otp-mern

A login, signup, and password reset system using OTP verification.  
Built with MongoDB, Express.js, React, and Node.js.

## Features

- User registration & login
- Email OTP verification
- Password reset with OTP
- JWT-based auth with cookies
- Sends welcome email on signup

![Untitled-1](https://github.com/user-attachments/assets/330422fb-ff15-4fa4-99a3-ab47dd7363a1)

## 🛠️ Setup Instructions

### Server Setup

1. Create a `.env` file in `/server` with the following:

   ```env
   MONGODB_URI=""
   JWT_SECRET=""
   NODE_ENV=development
   SMTP_HOST=""
   SMTP_PORT=""
   SMTP_USERNAME=""
   SMTP_PASSWORD=""
   SENDER_EMAIL=""
   ```

2. Install dependencies:

   ```bash
   cd server
   npm install
   ```

3. Run the backend server:

   ```bash
   npm run server
   ```

---

### Client Setup

1. Create a `.env` file in `/client` with:

   ```env
   VITE_BACKEND_URL=http://localhost:YOURPORTNUMBER
   ```

2. Install dependencies:

   ```bash
   cd client
   npm install
   ```

3. Start the frontend development server:

   ```bash
   npm run dev
   ```

---
