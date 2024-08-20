
# Vi Assignment - Task Management Application

## Background Story
In the fast-paced world of project management, effective task handling is critical to success. Vi Technologies has been growing rapidly, and with growth comes the need for a robust system to manage the increasing workload. Imagine you're part of a newly formed team tasked with building an internal Task Management Application. This tool will be the backbone for project tracking, ensuring that all tasks, from minor bug fixes to major feature developments, are monitored and completed on time.

Your job as a developer is to contribute to this application by creating a scalable, user-friendly system that allows team members to manage tasks efficiently. This project will simulate a real-world development environment, allowing you to demonstrate your skills in both frontend and backend development.

![Screenshot 2024-08-19 at 14 53 43 (1) (1)](https://github.com/user-attachments/assets/535ee090-8335-4b47-a8a0-e62200a3d1f8)
(a very basic sketch of the task management application)

## Task Definition

### Objective
Your objective is to develop a full-stack Task Management Application that provides the following capabilities:

- **Task Creation:** Users can create new tasks with relevant details like title, description, due date, priority, and task owner.
- **Task Management:** The application should allow users to view, update, delete, and filter tasks based on various criteria like status, priority, and due date.
- **Task Details View:** Users can click on a task to see more detailed information.

### Frontend Requirements
- **Task Creation Form:** Implement a form with local state management for adding new tasks. The form should include fields for task title, description, due date, priority, and task owner.
- **Global State Management:** Use Recoil to manage the global state of tasks, enabling operations like adding, updating, and deleting tasks.
- **Task List:** Display tasks in a list format with options to filter and sort them based on different attributes (e.g., due date, status).
- **Task Details View:** Allow users to click on a task to view its detailed information.

### Backend Requirements
- **RESTful API:** Develop a RESTful API that provides CRUD (Create, Read, Update, Delete) operations for managing tasks.
  - **GET /tasks:** Retrieve the list of tasks.
  - **GET /tasks/:id:** Retrieve a specific task by its ID.
  - **POST /tasks:** Create a new task.
  - **PUT /tasks/:id:** Update an existing task.
  - **DELETE /tasks/:id:** Delete a task by ID.
- **MVC Structure:** Organize your code using the Model-View-Controller pattern to ensure maintainability and scalability.

### Initial Setup
The project includes a mock database file containing 1,000 tasks (`tasks.json`). Your initial setup should recognize and utilize these tasks as the application's starting dataset. This will allow you to focus on implementing and testing the application's core features right from the start.

- **File:** `server/_mockDB/tasks.json`

The mock data file contains various tasks, each with attributes such as title, description, due date, priority, and task owner. These tasks will provide a realistic dataset for your development and testing efforts.

## Assignment Goals

### What You Will Be Tested On
- **Code Quality:** We’ll evaluate the clarity, efficiency, and organization of your code. Clean, readable, and well-documented code is highly valued.
- **Frontend Skills:** Your ability to build a responsive and user-friendly interface will be tested. We’ll look at how effectively you use Vite.js, Recoil, and either Material-UI (MUI v5) or SCSS Modules for styling.
- **Backend Skills:** We’ll assess your ability to design and implement a robust RESTful API using Node.js with Express. Your understanding of the MVC pattern will be crucial here.
- **State Management:** How well you manage and manipulate the global state with Recoil will be a key factor in your evaluation.
- **Problem-Solving:** Your approach to implementing features like task filtering, sorting, and handling complex data structures will be examined.
- **Testing and Debugging:** We’ll also look at how you test and debug your code, ensuring it meets the required functionality.

### Bonus Points
- Implementing unit and integration tests.
- Handling edge cases and potential errors gracefully.
- Providing additional features like user authentication or advanced filtering options.

## Conclusion
This assignment is your opportunity to demonstrate your full-stack development skills in a realistic and meaningful way. By completing this project, you’ll showcase your ability to build a complete web application from scratch, covering both frontend and backend aspects. We’re excited to see your approach and creativity in solving this task.

Good luck, and happy coding!
