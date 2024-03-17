# student-task
Sure, here's a README.md tailored for GitHub:

```markdown
# Student Task Manager

Student Task Manager is a web application built with Express.js, MongoDB, HTML, CSS, and JavaScript. It helps students manage their tasks for different courses efficiently.



## Features

- **Course Management**: Create, retrieve, update, and delete courses.
- **Task Management**: Create, retrieve, update, and delete tasks for each course.
- **Task Completion**: Mark tasks as completed.
- **Deadline Management**: Set deadlines for tasks.

## Prerequisites

Before running the application, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

## Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd student-task-manager
```

2. Install dependencies:

```bash
npm install
```

3. Set up MongoDB:

   - Ensure MongoDB is running on your machine.
   - Create a new database named `studentTaskManager`.

4. Start the server:

```bash
npm start
```

The server will run on http://localhost:3000 by default.

## Usage

### API Endpoints

#### Courses

- **GET /courses**: Get all courses.
- **GET /courses/:id**: Get a specific course by ID.
- **POST /courses**: Create a new course.
- **PUT /courses/:id**: Update a course.
- **DELETE /courses/:id**: Delete a course.

#### Tasks

- **GET /tasks**: Get all tasks.
- **GET /tasks/:id**: Get a specific task by ID.
- **POST /tasks**: Create a new task.
- **PUT /tasks/:id**: Update a task.
- **DELETE /tasks/:id**: Delete a task.

