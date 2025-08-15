# Bazario: Full-Stack E-commerce Application

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="React">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/MUI-007FFF?style=for-the-badge&logo=mui&logoColor=white" alt="MUI">
</p>

Welcome to **Bazario**, a full-stack e-commerce platform designed to provide a seamless and secure online shopping experience. This project is built using a modern technology stack, offering a robust back-end and a dynamic, user-friendly front-end.


---

### Key Features

- **User Authentication**: Secure user registration and login with password hashing (`bcrypt`) and token-based authentication (`jsonwebtoken`).
- **Product Management**: An intuitive system for managing product listings, including details like name, category, and seller.
- **Shopping Cart**: A functional shopping cart system that allows users to add, view, and manage items before making a purchase.
- **Order Processing**: A streamlined process for creating and tracking user orders.
- **Enhanced Security**: Integrates `reCAPTCHA` on the login route to prevent bot access.
- **Responsive Design**: A user interface built with **MUI (Material-UI)** to ensure a consistent and appealing experience across various devices.
- **Generative AI Integration**: Potential for using Google's Generative AI to enhance specific features.

---

### Technologies Used

This project leverages a modern MERN-like stack and other key technologies.

#### Front-end
- **React**: A powerful JavaScript library for building the user interface.
- **Vite**: A fast, next-generation front-end tooling for rapid development.
- **MUI (Material-UI)**: A comprehensive UI component library for professional styling.
- **React Router DOM**: Manages the application's routing and navigation.
- **Axios**: A promise-based HTTP client for making API requests.

#### Back-end
- **Node.js**: The JavaScript runtime environment.
- **Express.js**: A minimalist web framework for building the API and server.
- **MongoDB**: A flexible, NoSQL document database.
- **Mongoose**: An elegant object data modeling (ODM) library for MongoDB.

#### Security & Utilities
- **bcrypt**: A library for hashing passwords securely.
- **jsonwebtoken**: Used for creating and verifying JSON Web Tokens for authentication.
- **cors**: Enables Cross-Origin Resource Sharing.
- **multer**: Middleware for handling `multipart/form-data`, primarily for file uploads.
- **@google/generative-ai**: A dependency for integrating Google's AI services.

---

### Getting Started

#### Prerequisites

- Node.js (LTS version recommended)
- MongoDB instance (local or hosted, e.g., MongoDB Atlas)

#### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Snehajindl24/Buy---Sell-](https://github.com/Snehajindl24/Buy---Sell-)
    cd Buy---Sell-
    ```

2.  **Install dependencies for both front-end and back-end:**
    ```bash
    # Install back-end dependencies
    npm install

    # Navigate to the client directory (if applicable) and install front-end dependencies
    cd client  # Or similar front-end directory
    npm install
    ```

#### Configuration

1.  Create a `.env` file in the root directory and add your environment variables:
    ```
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    RECAPTCHA_SECRET=your_recaptcha_secret_key
    ```
2.  Update the CORS origins in `server.js` if you are running the front-end on a different port.

#### Running the Project

1.  **Start the back-end server:**
    ```bash
    npm start
    ```
2.  **Start the front-end development server:**
    ```bash
    cd client  # Or similar front-end directory
    npm run dev
    ```

The application should now be running, with the front-end accessible on `http://localhost:5173` (as suggested by the `vite.config.js`) and the back-end API on `http://localhost:3000`.
