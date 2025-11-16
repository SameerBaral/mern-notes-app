# MERN NOTES APP

**Project Overview :-**

A simple CRUD notes application built with the MERN stack (MongoDB, Express, React, Node). Provides user authentication, persistent notes per user, and a responsive UI to create, read, update, and delete notes. Using tailwind CSS for styling.


**Key Features :-**
- User Authentication: Sign up, log in, and secure note access.
- CRUD Operations: Create, read, update, and delete notes.  
- Responsive Design: Works well on both desktop and mobile devices.
- RESTful API: Backend built with Express and Node.js.  
- MongoDB Integration: Notes and user data stored in a MongoDB database.
- Tailwind CSS: For modern and responsive UI design.
- JWT Authentication: Secure user sessions with JSON Web Tokens.
- Password Hashing: User passwords are hashed using bcrypt for security.
- Error Handling: Proper error messages and status codes for API responses.


**Technologies Used :-**

- Frontend: React, Tailwind CSS, Axios
- Backend: Node.js, Express.js, Mongoose
- Database: MongoDB
- Authentication: JWT, bcrypt

**Installation and Setup :-**

1. Clone the repository: git clone https://github.com/SameerBaral/mern-notes-app.git

2. Navigate to the project directory: cd `mern-notes-app`

3. Install backend dependencies:
   ```
   cd backend
   npm install
   ```
4. Install frontend dependencies:
   ```
   cd frontend
   npm install
   ```
5. Set up environment variables:
   - Create a `.env` file in the `mern-notes-app` directory.

    - Add the following variables:
      ```
      MONGO_URI=your_mongodb_connection_string
      JWT_SECRET=your_jwt_secret_key
      PORT=5000
      NODE_ENV=production
      ```
6. Start the backend server:
   ```
    cd backend
    npm start
    ```
7. Start the frontend development server:
    ```
     cd frontend
     npm start
    ```
    **Note: In the browser, use**
    ctrl+click on links to open in new tabs.


8. Open your browser and navigate to `http://localhost:5173` to access the application.

9. Make sure your MongoDB server is running and accessible.

10. 

**Usage :-**
- Sign up for a new account or log in with existing credentials.

- Create, view, edit, and delete notes through the user-friendly interface.

- Notes are saved to your account and can be accessed anytime you log in.

- This project is very useful for managing personal notes and tasks efficiently.



**Contributing :-**
- Contributions are welcome! Please fork the repository and create a pull request with your changes.
