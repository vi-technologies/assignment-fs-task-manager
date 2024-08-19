
# Vi Assignment - Task Management Application

A Task Management Application built with Vite.js for the frontend and Node.js with Express for the backend. The project uses Recoil for global state management and either Material-UI (MUI v5) or SCSS Modules for styling.

![Screenshot 2024-08-19 at 14 53 43 (1) (1)](https://github.com/user-attachments/assets/535ee090-8335-4b47-a8a0-e62200a3d1f8)

## Features

### Frontend
- **Task List:** Displays a list of tasks managed by the global state, with options for filtering and sorting.
- **Task Creation Form:** A form with local state management for adding new tasks, including fields for task title, description, and due date.
- **Task Editing Modal:** A modal containing a form for editing existing tasks. This modal should be triggered when a user selects a task to edit.
- **Search Bar:** A search bar that allows users to search through tasks by title or description, with results dynamically updating the task list.
- **Global State Management:** Recoil is used to manage the global state of tasks, including adding, updating, and deleting tasks.

### Backend
- **RESTful API:** Provides CRUD operations for managing tasks.
- **Endpoints:**
  - `GET /tasks`: Retrieve the list of tasks.
  - `GET /tasks/:id`: Retrieve a specific task by ID.
  - `POST /tasks`: Create a new task.
  - `PUT /tasks/:id`: Update an existing task.
  - `DELETE /tasks/:id`: Delete a task by ID.
- **MVC Structure:** Organized using the Model-View-Controller pattern for maintainability.
- **Mock Database:** A `tasks.json` file is provided in the `server/_mockDB/` directory, containing a sample set of tasks to work with. As your application grows, you may want to consider how to efficiently manage and retrieve data, especially when working with a larger dataset. 

## Getting Started

### Prerequisites
- **Yarn** is mandatory as the package manager for this project. Please do not use npm.
- Ensure you have Node.js installed.

### Installation

1. **Fork the repository** and then clone your fork:
   ```bash
   git clone https://github.com/vi-technologies/assignment-fs-task-manager.git
   cd task-management-app
   ```

2. **When your assignment is ready, dependencies should be installed as follows:**
   ```bash
   yarn install
   cd client
   yarn install
   cd ../server
   yarn install
   ```

### Running the Application

1. **Start the frontend:**
   ```bash
   cd client
   yarn start
   ```

2. **Start the backend:**
   ```bash
   cd server
   yarn start
   ```

3. **Run both client and server concurrently:**
   ```bash
   yarn run-all
   ```

## Folder Structure

The repository contains a suggested folder structure, but you are free to modify it as needed. Refer to the existing codebase for the current organization.
