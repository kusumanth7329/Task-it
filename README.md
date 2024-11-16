# To-Do List Management App

## Overview
The **To-Do List Management App** is a feature-rich application designed to help users manage their daily tasks efficiently. It combines a modern, professional UI with a robust back-end architecture, offering functionalities like secure user authentication, task creation, editing, deletion, and real-time updates. The application is built with industry best practices and technologies to deliver a responsive and seamless user experience.

---

## Features

### User Authentication
- Secure login and registration functionality using **JWT (JSON Web Tokens)**.
- Passwords are securely hashed for added security.

### Task Management
- **Create Tasks**: Users can add new tasks with attributes such as title, description, status, priority, and due date.
- **Edit Tasks**: Modify task details in real time with an intuitive form-based interface.
- **Delete Tasks**: Remove tasks permanently.

### Empty State Handling
- A visually engaging empty state is displayed when there are no tasks, including a relaxing animation and a friendly message: *"You're all caught up!"*.

### Task List Display
- Tasks are displayed in a clean grid format with hover animations and visually distinct action buttons.
- Task cards include details like title, description, status, priority, and due date.

### Professional and Responsive Design
- The application uses a **consistent color scheme** across all pages, creating a cohesive and polished look.
- Fully responsive layout that adapts to various screen sizes, ensuring usability on desktops, tablets, and mobile devices.

---

## Best Practices Followed

### Front-End
- **React.js with Modular Components**: Code is split into reusable and testable components.
- **CSS Optimization**: Consistent styling with SCSS and Bootstrap to ensure scalability and maintainability.
- **State Management**: Tasks and user authentication are managed efficiently using React hooks and context.

### Back-End
- **Separation of Concerns**: API endpoints for authentication and task management are logically organized.
- **Error Handling**: Comprehensive error responses to guide the user when operations fail.
- **Secure Communication**: Usage of HTTP-only cookies for session management and environment variables for sensitive data.

### UI/UX
- **Interactive Design**: Hover effects and animations for buttons and cards to enhance interactivity.
- **Accessibility**: Components and forms are designed to be user-friendly and accessible.

---

## Technologies Used

### Front-End
- **React.js**: For building the user interface.
- **Bootstrap**: For responsive and modern UI components.
- **SCSS**: For customized and scalable styling.

### Back-End
- **Node.js with Express**: For building API endpoints.
- **SQLite**: Lightweight and efficient database management.
- **JWT**: For secure authentication.

### Additional Tools
- **Axios**: For making API requests.
- **Regex**: For input validation in the front-end and back-end.
- **Nodemon**: For back-end live reloading during development.



---

## Project Structure

```
project-root/
│
├── backend/
│   ├── controllers/
│   ├── db/
│   ├── middleware/
│   ├── routes/
│   ├── server.js
│   ├── .env
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── styles/
│   │   └── App.js
│   ├── public/
│   └── package.json
│
├── README.md
└── .gitignore
```

## Getting Started

### Prerequisites
Ensure you have the following installed:
- **Node.js** (v16+ recommended)
- **npm** or **yarn**
- **SQLite** (configured as part of the backend)

### Installation

1. Clone the repository:
```
git clone https://github.com/your-repository-url.git
```

2. Navigate to the project folder:
```
cd taskit
```

3. Install dependencies for both the front-end and back-end:
```
# Back-end
cd backend
npm install

# Front-end
cd ../frontend
npm install
```

## Running the Application

1. start the back-end server:
cd backend
npm start

2. In a separate terminal, start the front-end application:
cd frontend
npm start


## Development

### Front-End
- **Location:** /frontend
- **Entry Point:** src/index.js
- **Important Scripts:**
  - npm start: Runs the app in the development mode.
  - npm test: Launches the test runner.
  - npm run build: Builds the app for production to the build folder.

### Back-End
- **Location:** /backend
- **Entry Point:** server.js
- **Important Scripts:**
  - npm start: Starts the Node server.
  - npm run dev: Starts the server with nodemon for live reloading.

## Key Pages
### Login Page
- Features an off-white background with a gradient and a professional card-based form.
- Includes a footer with links to the designer's email and LinkedIn profile.
### Register Page
- Similar design to the Login Page with fields for user registration.
### Tasks Page
- Split layout: Task creation form on the left and task list on the right.
- Responsive grid layout for tasks with hover effects.
- Empty state with a relaxing animation when no tasks are present.


