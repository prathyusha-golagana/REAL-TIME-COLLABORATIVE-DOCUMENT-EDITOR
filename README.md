# REAL-TIME-COLLABORATIVE-DOCUMENT-EDITOR

COMPANY : CODTECH IT SOLUTIONS

NAME : Prathyusha Golagana

INTERN ID : CT04DF2741

DOMAIN : Full Stack Development

DURATION : 4 Weeks

MENTOR : NEELA SANTHOSH KUMAR

##DESCRIPTION :

The Real-Time Document Editor is a full-stack, collaborative platform that enables multiple users to create, edit, and manage documents simultaneously in real-time. Built with the powerful MERN stack—MongoDB, Express, React, and Node.js—this application offers seamless, secure, and user-friendly document editing capabilities, making it ideal for teams, students, and professionals.

It uses Socket.IO to provide real-time communication between users, ensuring that changes made by one user are instantly reflected for others editing the same document. With robust authentication, role-based access control, and a clean, responsive UI, the Real-Time Document Editor provides a complete experience for live collaboration.

🚀 Features

🔐 User Authentication

Secure login and registration system using JWT (JSON Web Tokens), ensuring each user has a personalized and protected workspace.

📄 Document Management

Users can create, update, delete, and manage their own documents in a structured environment. Each document is stored in MongoDB, making retrieval and updates seamless.

🤝 Real-Time Collaboration

Multiple users can collaborate on a single document with real-time editing, cursor tracking, and automatic syncing, powered by Socket.IO.

👥 Collaborator Management

Users can add or remove collaborators to any document, giving them edit access while maintaining ownership control.

🌐 Responsive UI

The frontend, built with React and styled using Bootstrap, is designed to be intuitive and responsive across devices, ensuring a smooth experience on both desktop and mobile.

🛡️ Role-Based Access Control

Only authorized users (owners or collaborators) can view or edit a document, maintaining strict control over content and user permissions.

##Project Structure

Realtime_DocumentEditor/

├── src/

│   ├── client/           # React frontend (Vite)

│   │   ├── src/

│   │   ├── public/

│   │   ├── index.html

│   │   └── package.json

│   ├── controllers/      # Express route controllers

│   ├── middlewares/      # JWT and authentication middleware

│   ├── models/           # Mongoose schemas/models

│   ├── routes/           # API route definitions

│   ├── utils/            # Utility functions (e.g., DB config, email)

│   ├── server.js         # Entry point for backend server

│   └── package.json      # Backend dependencies

└── README.md


##Technologies Used

Frontend: React, Vite, React Router, Quill.js, Bootstrap

Backend: Node.js, Express.js, Socket.IO, JWT, Nodemailer

Database: MongoDB with Mongoose

##Installation Steps

1.Clone the repository:

git clone <repository-url>

cd Realtime_DocumentEditor/src

2. Install backend dependencies:

npm install

3. Install frontend dependencies:

cd client

npm install

4.Configure Environment Variables:

Create a .env file in /src with the following:

MONGODB_URI=your_mongodb_uri

JWT_SECRET=your_secret

EMAIL_USER=your_email

EMAIL_PASS=your_password

5.Start Backend Server:

npm run dev

6.Start Frontend Server:

cd client

npm run dev

7.Open in Browser:

http://localhost:5173

##OUTPUT:

![Image](https://github.com/user-attachments/assets/a49746fe-4525-43c3-b48a-241f647f2559)


