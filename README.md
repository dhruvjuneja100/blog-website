# Blog Website

## Description
This blog website is a full-featured platform built with Node.js, Express, and MongoDB, providing users with an intuitive and engaging way to share and explore content. The site includes user authentication, an admin dashboard, and CRUD (Create, Read, Update, Delete) operations for managing blog posts.

![image](https://github.com/user-attachments/assets/1a14172f-2cd5-41bf-b1d5-a04f790c512e)



## Features
- **User Registration and Authentication:** Secure user sign-up and login using bcrypt for password hashing and JWT for session management.
![image](https://github.com/user-attachments/assets/f817bf30-d2f6-48b7-bc1d-e7b1171fd7f4)

- **Admin Dashboard:** A dedicated space for administrators to manage posts, including creating, editing, and deleting content.
![image](https://github.com/user-attachments/assets/a5e04561-2c69-452f-a7f1-286cb5d24dd0)

- **Responsive Design:** Built with responsive principles, ensuring a seamless experience across all devices.
- **Pagination:** Allows users to navigate through posts easily.
- **Error Handling:** Robust error handling and informative messages for smooth user experience.
- **Middleware:** Custom middleware for authentication and authorization checks.

## Technologies Used
- **Node.js:** JavaScript runtime for server-side programming.
- **Express:** Web framework for Node.js.
- **MongoDB:** NoSQL database for storing user and post data.
- **EJS:** Template engine for rendering HTML with embedded JavaScript.
- **bcrypt:** Library for hashing passwords.
- **jsonwebtoken (JWT):** For creating and verifying authentication tokens.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/blog-website.git
   ```

2. Navigate to the project directory:
   ```bash
   cd blog-website
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up environment variables in a `.env` file:
   ```
   MONGODB_URI=your-mongodb-connection-string
   JWT_SECRET=your-jwt-secret
   ```

5. Start the server:
   ```bash
   npm start
   ```

## Usage
- Visit `http://localhost:3000` to view the homepage.
- Register a new user account or log in with existing credentials.
- Access the admin dashboard at `http://localhost:3000/admin` to manage posts.
- Create, edit, and delete blog posts as an authenticated user.
