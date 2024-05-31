# TaskManager

## Description
This project is a full-stack web application built using Node.js for the backend and React for the frontend. The application allows users to manage a list of tasks, including creating, reading, updating, and deleting tasks.

## Table of Contents
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Configuration](#configuration)
- [Assignment Requirements](#assignment-requirements)
- [Authors](#authors)
- [References](#references)
- [License](#license)

## Setup and Installation

### Prerequisites
- Node.js
- npm (Node Package Manager)

### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo/backend
   ```

2. Install backend dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the `backend` directory and add the following:
     ```makefile
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     ```

4. Start the backend server:
   ```bash
   npm start
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```

2. Install frontend dependencies:
   ```bash
   npm install
   ```

3. Start the frontend development server:
   ```bash
   npm start
   ```

## Usage
Once both the backend and frontend servers are running, you can access the application at `http://localhost:3000`.

### Example Usage
1. Open the application in your web browser.
2. Add a new task using the input form.
3. View the list of tasks.
4. Edit or delete tasks as needed.

## Screenshots
![Homepage](screenshots/homepage.png)
![Task List](screenshots/tasklist.png)


## Configuration
- **Backend:**
  - `PORT`: The port number for the backend server.
  - `MONGO_URI`: The connection string for MongoDB.

- **Frontend:**
  - Configuration is managed in `src/config.js` (if applicable).

## System Design
The system design of TaskManager includes the following components:

### Frontend Components:
   React Components: UI components built using React.js, including forms, task list, task item, etc.
   Material-UI: UI library for designing consistent and visually appealing components.

### Backend Components:
   Node.js Server: Backend server built with Node.js and Express.js.
   RESTful API: Provides endpoints for managing tasks, including CRUD operations.
   MongoDB Database: NoSQL database used for storing tasks persistently.


## Authors
- **Your Name** - *Project Author* - [Your Profile](https://github.com/yourusername)

## References
- [Node.js Documentation](https://nodejs.org/en/docs/)
- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [MongoDB Documentation](https://docs.mongodb.com/)

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
