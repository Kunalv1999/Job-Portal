# 🧑‍💼 Job Portal Web Application

Welcome to the **Job Portal** – a full-stack MERN (MongoDB, Express.js, React.js, Node.js) based web application developed as part of my industrial training during my B.Tech in CSE at **RBSSIET, Rewari, Haryana (Graduating 2025)**.

This platform is designed to streamline the job application and recruitment process, enabling job seekers to explore and apply for jobs and recruiters to post and manage openings efficiently.

---

## 📌 Features

### 👨‍💻 For Job Seekers:
- User Registration & Login
- Create and manage profile/resume
- Search and filter job listings
- Apply for jobs
- Track applications

### 🏢 For Recruiters:
- Register & Login
- Post job openings
- Edit or delete job listings
- View and manage applicant data

### 🔐 Security:
- JWT Authentication
- Role-based access (Jobseeker / Recruiter)
- Form validation and secure routes

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | React.js, Tailwind CSS / Bootstrap |
| **State Management** | Redux Toolkit |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB + Mongoose |
| **Authentication** | JWT, bcrypt.js |
| **Other Tools** | Postman (API testing), Git, GitHub |

---

## 🏗️ Folder Structure

```
job-portal/
│
├── client/                 # React frontend
│   ├── src/
│   └── public/
│
├── server/                 # Express backend
│   ├── models/             # Mongoose schemas
│   ├── routes/             # Route handlers
│   ├── controllers/        # Business logic
│   ├── middleware/         # Auth & error middleware
│   └── config/             # DB connection
│
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/kunalverma/job-portal.git
cd job-portal
```

### 2. Backend Setup

```bash
cd server
npm install
npm run dev
```

> Create a `.env` file in `server/`:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

### 3. Frontend Setup

```bash
cd client
npm install
npm start
```

> Make sure the backend is running before launching the frontend.

---

## 👨‍🎓 About Me

Hi, I'm **Kunal Verma**, a MERN stack developer and Computer Science student (B.Tech CSE, 2025) passionate about building impactful full-stack applications. This project is a part of my **industrial training** and a step toward mastering backend, frontend, and deploying production-ready solutions.

- 📧 Email: kv87323@gmail.com  
- 📍 Location: Mandi, Himachal Pradesh, India  
- 🎓 College: RBSSIET, Rewari, Haryana  
- 💡 Interests: Web Dev, EdTech, YouTube content creation, Freelancing  

---

## 📈 Planned Features

- Admin Dashboard
- Resume Builder Integration
- Email Notifications
- Interview Scheduling
- Advanced Search Filters
- Job Recommendation System using AI (future idea)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

⭐ **Star this repo** to support the project and follow for more future development!
