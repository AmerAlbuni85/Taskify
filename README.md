# Taskify
Remote-Task-Manager
A simple task manager that allows you to create, read, update, and delete tasks. It uses a RESTful API built with Node.js and Express for the backend, and a React frontend to interact with the API.
## Features
- Create, read, update, and delete tasks
- Mark tasks as completed
- Filter tasks by status (all, completed, pending)
- Responsive design for mobile and desktop
## Technologies Used
- Backend: Node.js, Express, MongoDB
- Frontend: React, Axios, Tailwind CSS
## Prerequisites
- Node.js and npm installed
- MongoDB installed and running locally or a MongoDB Atlas account
## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/taskify.git
    cd taskify
    ``` 
2. Install backend dependencies:
    ```bash
    cd backend
    npm install
    ```
3. Install frontend dependencies:
    ```bash
    cd ../frontend
    npm install
    ```
4. Create a `.env` file in the `backend` directory and add your MongoDB connection string:
    ```
    MONGODB_URI=your_mongodb_connection_string
    PORT=5000
    ```
## Running the Application
1. Start the backend server:

    ```bash
    cd backend
    npm start
    ```
2. Start the frontend development server:
    ```bash
    cd ../frontend
    npm start
    ```
3. Open your browser and navigate to `http://localhost:3000` to use the
application.
## API Endpoints
- `GET /api/tasks`: Get all tasks
- `POST /api/tasks`: Create a new task
- `GET /api/tasks/:id`: Get a task by ID
- `PUT /api/tasks/:id`: Update a task by ID
- `DELETE /api/tasks/:id`: Delete a task by ID
## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.
## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
## Acknowledgements
- [Express](https://expressjs.com/)
- [React](https://reactjs.org/)
- [MongoDB](https://www.mongodb.com/)   
- [Tailwind CSS](https://tailwindcss.com/)  
- [Axios](https://axios-http.com/)
- [Node.js](https://nodejs.org/)
- [GitHub](https://github.com/) 
- [npm](https://www.npmjs.com/) 
- [Visual Studio Code](https://code.visualstudio.com/)
- [Postman](https://www.postman.com/)
- [Heroku](https://www.heroku.com/)
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- [Font Awesome](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)
- [Figma](https://www.figma.com/)
- [Unsplash](https://unsplash.com/)
- [FreeCodeCamp](https://www.freecodecamp.org/)
- [MDN Web Docs](https://developer.mozilla.org/)
- [W3Schools](https://www.w3schools.com/)
- [Stack Overflow](https://stackoverflow.com/)
- [Git](https://git-scm.com/)
