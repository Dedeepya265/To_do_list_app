# Multi-User Todo List Application

A full-stack task management application that enables multiple users to securely register, log in, and organize their personal to-do lists. The project is developed using the MERN stack (MongoDB, Express.js, React, and Node.js) along with modern frontend technologies.

---

## 🚀 Features

### User Features

* 🔐 Secure user registration and login using JWT authentication.
* 👤 Individual task management for every registered user.
* 📝 Create, edit, update, and delete tasks.
* ✅ Mark tasks as completed or pending.
* 🔎 Search tasks and filter them by status or priority.
* 📅 Assign due dates to tasks for better planning.
* 🎯 Organize tasks using Low, Medium, and High priority levels.
* 📱 Responsive interface compatible with desktops, tablets, and mobile devices.

### Technical Features

* 🛡️ Client-side and server-side input validation.
* 🔒 Protected routes with authenticated access.
* 🎨 Clean and responsive UI built with Tailwind CSS.
* 🔄 Global state management using React Context API.
* 📦 Developed with TypeScript for improved type safety.
* 🔔 Interactive toast notifications for user actions.
* ⚡ Fast development workflow powered by Vite.

---

## 🛠️ Technology Stack

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* bcryptjs
* express-validator
* CORS

### Frontend

* React 18
* TypeScript
* Vite
* Tailwind CSS
* React Router DOM
* React Hook Form
* Zod
* Axios
* React Context API
* React Hot Toast
* Lucide React Icons

---

## 📂 Project Structure

```text
todo-app/
│
├── backend/
│   ├── config/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   ├── package.json
│   └── env.example
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── hooks/
│   │   ├── pages/
│   │   ├── types/
│   │   ├── utils/
│   │   ├── App.tsx
│   │   ├── main.tsx
│   │   └── index.css
│   ├── package.json
│   └── README.md
│
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

Before running the application, install:

* Node.js (v16 or later)
* MongoDB
* npm or Yarn

---

### Backend Setup

1. Move to the backend folder.

```bash
cd backend
```

2. Install dependencies.

```bash
npm install
```

3. Create a `.env` file using the example provided.

```bash
cp env.example .env
```

4. Configure the environment variables.

```env
PORT=5000
NODE_ENV=development
MONGODB_URI=mongodb://localhost:27017/todo-app
JWT_SECRET=your-secret-key
CORS_ORIGIN=http://localhost:3000
```

5. Start the backend server.

```bash
npm run dev
```

The backend will run at:

```
http://localhost:5000
```

---

### Frontend Setup

1. Navigate to the frontend folder.

```bash
cd frontend
```

2. Install the required packages.

```bash
npm install
```

3. Create the environment file.

```env
VITE_API_URL=http://localhost:5000/api
```

4. Start the React application.

```bash
npm run dev
```

The frontend will be available at:

```
http://localhost:3000
```

---

## 📖 API Endpoints

### Authentication

* Register a new user
* Login
* Retrieve the current user's profile

### Tasks

* Fetch all tasks
* Create a new task
* Retrieve a task by ID
* Update a task
* Delete a task
* Toggle task completion status

### User

* View user profile
* Update profile information
* Delete user account

---

## 🎯 Learning Outcomes

This project demonstrates:

* Full-stack web application development using the MERN stack.
* JWT-based authentication and authorization.
* RESTful API development with Express.js.
* MongoDB schema design using Mongoose.
* Modern React development with Context API.
* Form validation using React Hook Form and Zod.
* Responsive UI design with Tailwind CSS.
* Secure password handling and API validation.
* Error handling and protected routes.

---

## 🌐 Deployment

### Backend (Render)

1. Connect the GitHub repository.
2. Create a new Web Service.
3. Install dependencies using:

```bash
npm install
```

4. Start the application with:

```bash
npm start
```

5. Configure the required environment variables.

---

### Frontend (Vercel)

1. Import the GitHub repository.
2. Build the project using:

```bash
npm run build
```

3. Set the output directory to:

```
dist
```

4. Add the frontend environment variables.

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new feature branch.
3. Implement your changes.
4. Test the application.
5. Submit a Pull Request.

---

## 📄 License

This project is licensed under the ISC License.

---

## 🙌 Acknowledgements

Special thanks to the communities behind React, Express.js, MongoDB, Node.js, Tailwind CSS, and Vite for providing the tools and frameworks that made this project possible.
