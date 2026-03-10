# **MERN Stack Setup**

A clean and simple starter template for building **full-stack web applications using the MERN stack**.

This repository provides a basic project structure with separated **frontend and backend environments**, allowing developers to quickly start building scalable full-stack applications.

The MERN stack consists of **MongoDB, Express, React, and Node.js**, a popular JavaScript-based technology stack used to build modern web applications where JavaScript is used on both the client and server.

---

# **Tech Stack**
**Backend**
- Node.js
- Express.js
- MongoDB
- Mongoose

**Frontend**
- React
- Vite
- Tailwind CSS

---

# **Project Structure**
```
mern-stack-setup
│
├── backend
│   ├── server.js
│   ├── routes
│   ├── controllers
│   └── models
│
├── frontend
│   ├── src
│   ├── components
│   └── pages
│
└── README.md
```

This structure separates the **API server from the frontend client**, making the project easier to scale and maintain.

---

# **How the MERN Stack Works**

In a MERN application:

1. **React** handles the user interface.
2. **Express + Node.js** run the backend server and API.
3. **MongoDB** stores the application data.

Typically, the frontend sends requests to the backend API, which processes logic and interacts with the database before returning responses to update the UI.

---

# **Getting Started**

1. Clone the repository

```
git clone https://github.com/BotPlayerAI/mern-stack-setup.git
cd mern-stack-setup
```

2. Install dependencies

Backend:
```
cd backend
npm install
```
Frontend:
```
cd frontend
npm install
```

3. Run the development servers

Backend:
```
npm run dev
```
Frontend:
```
npm run dev
```
