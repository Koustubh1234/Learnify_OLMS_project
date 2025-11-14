Learnify – Online Learning Management System (OLMS)

Learnify is a web-based Online Learning Management System (OLMS) designed to simplify the way educational content is created, managed, and accessed. The system provides a centralized platform where instructors can create courses and upload lecture materials, students can enroll in courses and study at their convenience, and administrators can review and approve courses to maintain platform quality. Built using the MERN stack (MongoDB, Express.js, React.js, and Node.js), Learnify focuses on providing a clean, user-friendly interface without unnecessary complexity. It ensures flexible learning by allowing access from any device with an internet connection. With essential features such as course creation, enrollment, lecture viewing, and admin approval, Learnify offers a simple yet effective digital learning solution suitable for educational institutions and online learning environments.

🚀 Features
👤 User Authentication & Security

Secure login/signup with JWT

Role-based access (Admin / Faculty / Student)

Encrypted password storage

📚 Course Management

Create, update, and manage courses

Upload study materials, notes, and resources

Enroll and view course content

📝 Journal & Notes Module

Write and manage personal journals

Save day-to-day learning or tasks

Cloud-stored notes accessible anytime

📅 Event Scheduling

Create and view upcoming events

Calendar-based reminders for users

⚙️ Admin Controls

Manage users, roles, and course visibility

Dashboard for overall system monitoring

☁️ Cloud & Deployment

Backend deployed on MongoDB Atlas

Environment variable-based config

Scalable and production ready

🛠️ Tech Stack
Frontend

React.js

Tailwind / CSS3

Axios

Backend

Node.js

Express.js

JWT Authentication

Mongoose

Database

MongoDB Atlas

🔧 Project Structure
Learnify/
│── client/          # React frontend
│   ├── src/
│   ├── components/
│   └── pages/
│
│── server/          # Node + Express backend
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── middleware/
│
│── .env.example     # Sample environment variables
│── package.json
│── README.md
