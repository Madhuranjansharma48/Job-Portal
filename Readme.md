# 🧑‍💼 Job Hunt – MERN Stack Job Portal

Job Hunt is a full-stack web application that connects job seekers with employers. It provides job listing, application management, and role-based dashboards using the MERN (MongoDB, Express.js, React.js, Node.js) stack.

## 🚀 Features

- 🔐 Secure JWT-based Authentication (Job Seeker & Employer)
- 📤 Job Posting, Editing, and Deletion (Employer Role)
- 📝 Job Application Tracking (Seeker Role)
- 🔍 Search & Filter by Role, Location, Type
- 📊 Personalized Dashboards
- 🌐 Fully Responsive Design

## 🛠 Tech Stack

- **Frontend:** React.js, Tailwind CSS, Axios  
- **Backend:** Node.js, Express.js, JWT, bcrypt  
- **Database:** MongoDB, Mongoose  

## 📁 Folder Structure

Job-Hunt/
├── client/ # React Frontend
│ ├── public/
│ └── src/
├── server/ # Node.js Backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── app.js
└── README.md

bash
Copy
Edit

## ⚙️ Getting Started

1. **Clone the repository**
```bash
git clone https://github.com/your-username/job-hunt.git
Install Dependencies

bash
Copy
Edit
# Backend
cd server
npm install

# Frontend
cd ../client
npm install
Configure Environment Variables
Create a .env file inside the server/ folder:

env
Copy
Edit
PORT=5000
MONGO_URI=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret_key
Run the Application

bash
Copy
Edit
# Start Backend
cd server
npm start

# Start Frontend
cd ../client
npm start
🌍 Live Demo
Frontend: 

Backend: 

👨‍💻 Author
Madhu Ranjan
GitHub • LinkedIn

📄 License
This project is licensed under the MIT License.

yaml
Copy
Edit

---

✅ You can now copy the above as your full `README.md`. Let me know if you'd like me to fill in:
- Your **actual GitHub username**
- **Live deployed links**
- Add **badges** (e.g., GitHub stars, license, hosted on Vercel/Render)
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
