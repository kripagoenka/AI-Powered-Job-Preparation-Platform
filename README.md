# 🚀 AI-Powered Job Preparation Platform

A production-ready, full-stack web application designed to streamline the job preparation journey using Generative AI. Built with the MERN Stack and powered by Google's Gemini AI, the platform helps users prepare for interviews, improve resumes, identify skill gaps, and create personalized learning roadmaps.

## ✨ Features

### 🤖 Generative AI Integration

* AI-generated mock interview questions tailored to specific job roles.
* Personalized resume feedback and improvement suggestions.
* Customized learning roadmaps based on career goals and skill levels.
* Intelligent career guidance powered by Google Gemini AI.

### 🔐 Secure Authentication

* User registration and login functionality.
* JWT-based authentication and authorization.
* Password encryption using Bcrypt.
* Secure session management and protected routes.

### ⚡ Scalable Architecture

* RESTful API built using Node.js and Express.js.
* Modular backend architecture for maintainability and scalability.
* Efficient handling of AI requests and user data.

### 🎨 Dynamic User Interface

* Responsive and interactive frontend developed with React.js.
* Clean and user-friendly dashboard experience.
* Fast navigation and seamless user interactions.

### 💾 Data Persistence

* MongoDB database for storing user profiles and activity.
* Secure storage of AI-generated interview sessions and recommendations.
* Structured data management using Mongoose.

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* Tailwind CSS
* Axios

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### AI & Security

* Google Gemini AI API
* JWT Authentication
* Bcrypt
* CORS
* Dotenv

---

## ⚙️ Local Development Setup

### Prerequisites

Ensure the following are installed:

* Node.js (v16 or higher)
* MongoDB (Local Installation or MongoDB Atlas)
* Google Gemini API Key

---

### Clone Repository

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

---

### Backend Setup

Navigate to the backend directory:

```bash
cd backend
npm install
```

Create a `.env` file:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_super_secret_jwt_key
GEMINI_API_KEY=your_google_gemini_api_key
```

Start the backend server:

```bash
npm run dev
```

---

### Frontend Setup

Open a new terminal and navigate to the frontend directory:

```bash
cd frontend
npm install
```

Create a `.env` file:

```env
VITE_API_BASE_URL=http://localhost:5000/api
```

Start the frontend development server:

```bash
npm run dev
```

The application will typically run on:

* Frontend: `http://localhost:5173`
* Backend: `http://localhost:5000`

---

## 📂 Folder Structure

```plaintext
📦 project-root
┣ 📂 backend
┃ ┣ 📂 controllers      # API endpoint logic
┃ ┣ 📂 models           # Mongoose schemas
┃ ┣ 📂 routes           # Express routing
┃ ┣ 📂 middleware       # JWT verification & error handling
┃ ┣ 📂 services         # Gemini AI integration logic
┃ ┗ 📜 server.js        # Backend entry point
┃
┗ 📂 frontend
  ┣ 📂 src
  ┃ ┣ 📂 components     # Reusable UI components
  ┃ ┣ 📂 pages          # Application pages
  ┃ ┣ 📂 context        # Authentication & state management
  ┃ ┗ 📜 App.jsx        # Main application routing
```

---

## 🎯 Key Functionalities

### AI Mock Interviews

Generate role-specific interview questions and answers for:

* Software Engineering
* Data Science
* Web Development
* Cloud Computing
* Product Management
* Custom Roles

### Resume Analysis

* ATS-friendly recommendations
* Resume improvement suggestions
* Skill gap identification

### Personalized Learning Roadmaps

* Career-focused learning paths
* Technology recommendations
* Skill development planning

### User Dashboard

* Access interview history
* Save AI-generated responses
* Track preparation progress

---

## 🔒 Security Features

* JWT Authentication
* Password Hashing with Bcrypt
* Protected API Routes
* Environment Variable Protection
* Secure User Session Management

---

## 🚀 Future Enhancements

* AI-powered Resume Scoring
* Voice-Based Mock Interviews
* Job Recommendation Engine
* Real-Time Interview Simulations
* Progress Analytics Dashboard
* Multi-Language Support

---

## 📈 Impact

The platform simplifies interview preparation and career planning by combining modern web technologies with Generative AI. It enables users to receive personalized guidance, improve their resumes, practice interviews effectively, and build structured learning plans—all within a single application.

---

## 👩‍💻 Author

**Kripa Goenka**

B.Tech Computer Science Engineering
MIT World Peace University (MIT-WPU), Pune

Passionate about Generative AI, Full-Stack Development, Cloud Technologies, and building impactful software solutions.
