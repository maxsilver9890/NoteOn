# NoteOn

NoteOn is a dynamic web application designed for personal and collaborative note-taking. It features a visually appealing and user-friendly interface, supporting seamless note management with advanced functionalities.

## Live Demo

Check out the live demo of NoteOn [here](https://NoteOn-eight.vercel.app/).

## Features

- **Responsive Design:** Fully responsive design with switchable dark and light themes.
- **User Authentication:** Secure login and signup with JSON Web Tokens (JWT).
- **Rich Text Editor:** Create and edit notes with a rich text editor.
- **Advanced Search:** Efficiently search notes with advanced functionality.
- **Tag Management:** Organize and manage notes with tags.
- **Pinned Notes:** Pin important notes for quick access.
- **Email Validation:** Ensure valid email addresses during registration.

## Technologies Used

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT
- **Deployment:** Vercel
- **APIs:** RESTful APIs
- **Other:** CSS, JavaScript, Postman



## Getting Started

To get started with NoteOn locally, follow these steps:

1. **Clone the repository:**
   ```bash
   
   ```
2. **Navigate from the project's root directory and install dependencies for both frontend and backend:**
- For frontend
    ```bash
   cd frontend/NoteOn
   npm install
   ```

- For backend
    ```bash
   cd backend
   npm install
   ```

3. **Set up environment variables:**
- Create a .env file in the backend directory and add your environment variables such as MongoDB URI and JWT secret.
    ```bash
    ACCESS_TOKEN_SECRET=your_jwt_secret
    MONGODB_CONNECTION_STRING=your_mongodb_uri
    ```

- In the frontend add your backend's base url in constants.js
    ```bash
    cd frontend/NoteOn/src/utils/constants.js
    ```

    ```bash
    export const BASE_URL = "http://localhost:8000"
    ```


4. **Run the application:**
- Start the backend server:
    ```bash
    cd backend
    npm start
    ```

- Start the frontend server:
    ```bash
    cd frontend/NoteOn
    npm run dev
    ```

5. **Access the application:**
- Open your browser and go to http://localhost:5173 to see the application in action.

## Contribution

**Contributions are welcome! If you'd like to contribute to NoteOn, please follow these steps:**

- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Make your changes.
- Commit your changes (git commit -m 'Add some feature').
- Push to the branch (git push origin feature-branch).
- Open a pull request.

## Future Scope

Currently working on creating an extension for **NoteOn** which would allow users to add note from any webpage directly to to their NoteOn account.

## Contact
If you have any questions or suggestions, feel free to reach out:


