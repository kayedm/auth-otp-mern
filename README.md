# auth-otp-mern

A login, signup, and password reset system using OTP verification.  
Built with MongoDB, Express.js, React, and Node.js.


## ✨ Features

- User registration & login  
- Email OTP verification  
- Password reset with OTP  
- JWT-based auth with cookies  

![App Screenshot](https://github.com/user-attachments/assets/750cad9d-8a99-4507-b4cf-0d6f49bf0983)


## 🛠️ Setup Instructions

###  Backend Setup

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

2. Install backend dependencies:

    ```bash
    cd server
    npm install
    ```

3. Run the backend server:

    ```bash
    npm run server
    ```

---

### Frontend Setup

1. Create a `.env` file in `/client` with:

    ```env
    VITE_BACKEND_URL=http://localhost:YOURPORTNUMBER
    ```

2. Install frontend dependencies:

    ```bash
    cd client
    npm install
    ```

3. Start the frontend development server:

    ```bash
    npm run dev
    ```

Make sure the backend server is already running and reachable at the URL you configured above.

---
