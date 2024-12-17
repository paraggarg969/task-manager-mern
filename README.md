# Task Manager

A task management application built with **React** for the frontend and **Node.js/Express** for the backend. The application allows users to create, edit, delete, and toggle task completion status. It utilizes **MongoDB** for data storage.

## Features

- **Add Task**: Users can create tasks by entering a title and description.
- **Edit Task**: Users can modify the title, description, and completion status of existing tasks.
- **Delete Task**: Users can remove tasks from the list.
- **Toggle Task Completion**: Users can mark tasks as completed or pending.
- **Task List**: Displays tasks with their details and action buttons (Edit, Delete, Complete).

## Tech Stack

- **Frontend**: React, Axios, CSS
- **Backend**: Node.js, Express, MongoDB (with Mongoose)
- **Database**: MongoDB (locally hosted or via a cloud service)
- **API**: REST API for handling task operations (CRUD)

## Installation

Follow these steps to set up the Task Manager application locally:

### 1. Clone the Repository

```bash
git clone https://github.com/paraggarg969/task-manager-mern.git
```

### 2. Install Backend Dependencies
- Navigate to the backend directory and install the required packages:

```bash
cd backend
npm install
```

### 3. Set Up MongoDB
- Ensure you have MongoDB installed and running on your local machine. Alternatively, you can set up a cloud MongoDB instance

### 4. Start the Backend Server
- Start the backend server: This will start the server at http://localhost:8000

```bash
npm start
```

### 5. Install Frontend Dependencies
- Navigate to the frontend directory and install the required packages:

```bash
cd frontend
npm install
```

### 6. Start the Frontend Server
- Start the React development server: This will open the application at http://localhost:3000

```bash
npm start
```

### 7. API Endpoints
The backend provides the following API endpoints:

- GET /tasks – Fetch all tasks
- POST /tasks – Create a new task
- PUT /tasks/:id – Update an existing task (mark as completed or edit details)
- DELETE /tasks/:id – Delete a task

### 8. .env (Optional)
- If you are using a cloud database or want to use custom environment variables, create a .env file in the backend directory and add the following:

```bash
MONGODB_URI=your_mongodb_connection_string
```

## Screenshot
![Screenshot 2024-12-17 131911](https://github.com/user-attachments/assets/2c14e553-3b81-455a-881d-344e7225e092)
![Screenshot 2024-12-17 132926](https://github.com/user-attachments/assets/14ac6700-8dc7-48d0-8179-cab54826bc04)
![Screenshot 2024-12-17 132811](https://github.com/user-attachments/assets/7fe19eef-9ae0-4675-935a-1cfedcfb1f74)
![Screenshot 2024-12-17 132352](https://github.com/user-attachments/assets/64bd7e57-775a-4565-a055-61abc1c806f2)
![Screenshot 2024-12-17 132235](https://github.com/user-attachments/assets/28c89161-4335-4e73-9f44-2dba151de811)


