# Jobify

A full-stack job tracking application to help users manage job applications, track interview progress, and stay organized during the job hunt.

![image](https://github.com/user-attachments/assets/22c3f994-a308-4931-a98e-2e1f919108f8)
![image](https://github.com/user-attachments/assets/5b1154c1-a490-44a8-bed1-26952c633455)


## 🌐 Live Demo

👉 [Visit Live Site](https://jobify-fvz4.onrender.com)

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Redux Toolkit
- React Router DOM
- Axios
- Styled Components

**Backend:**
- Node.js
- Express.js
- MongoDB + Mongoose
- Bcrypt.js & JWT for authentication
- Dotenv for configuration

**Deployment:**
- Render (Backend & Frontend)
- MongoDB Atlas

---

## ✨ Features

- ✅ User Authentication (Register/Login/Logout)
- 📝 Add, Edit, Delete Job Applications
- 🔍 Filter & Search Jobs by Type, Status, and Company
- 📊 Dashboard with statistics and charts
- ⚙️ Profile Settings & Account Management
- 📱 Responsive UI

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/sujitkumar2004/jobify.git
cd jobify
PORT=8000
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
cd backend
npm install
npm run dev

cd ../frontend
npm install
npm run dev

