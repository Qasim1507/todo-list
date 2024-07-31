# Todo List Application

## Overview
This Todo List application is built using React. It allows users to create, update, mark as done, and search tasks. The tasks are displayed in an expandable list format.

## Features
- **Create Task:** Add new tasks with a title and description.
- **Update Task:** Edit existing tasks.
- **Mark as Done:** Mark tasks as completed.

## System Design
The application is structured with the following components:
- `TodoForm`: Handles task creation.
- `TodoWrapper`: Displays the list of tasks.
- `EditTodoForm`: Handles task updates.
- `Todo`: Handles task done or not.

The data is stored in a dummy JSON file located in the `public` directory.

## Implementation
- **React Router:** Used for routing and handling URL parameters.
- **Component-Based Architecture:** Ensures modular and reusable code.

## Setup and Run
1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd todo-list-app
