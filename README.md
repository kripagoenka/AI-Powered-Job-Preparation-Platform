🚀 AI-Powered Job Preparation Platform
A production-ready, full-stack web application designed to streamline the job preparation process. Built with the MERN stack and seamlessly integrated with Google's Gemini AI, this platform empowers users with personalized, generative AI-driven insights to help them excel in interviews and career planning.

✨ Features
Generative AI Integration: Leverages the Google Gemini API to generate customized mock interview questions, resume feedback, and tailored learning roadmaps.

Secure Authentication: Robust user authentication, authorization, and session management implemented using JSON Web Tokens (JWT) and Bcrypt password hashing.

Scalable Architecture: A fully decoupled RESTful backend built with Node.js and Express to handle complex AI service requests efficiently.

Dynamic User Interface: A highly responsive and interactive frontend developed with React.js, designed for an intuitive user experience.

Data Persistence: Secure and structured storage of user profiles, session histories, and AI-generated insights using MongoDB.

🛠️ Tech Stack
Client: React.js, Vite (or Create React App), Tailwind CSS (if applicable)

Server: Node.js, Express.js

Database: MongoDB, Mongoose

Integrations & Security: Google Gemini AI API, JWT, CORS, Dotenv

⚙️ Local Development Setup
Follow these steps to set up the project locally on your machine.

Prerequisites
Make sure you have the following installed and set up:

Node.js (v16 or higher)

MongoDB (Local installation or MongoDB Atlas URI)

A Google Gemini API Key

1. Clone the repository
Bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
2. Backend Setup
Navigate to the backend directory, install dependencies, and configure environment variables.

Bash
cd backend
npm install
Create a .env file in the backend root and add the following:

Code snippet
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_super_secret_jwt_key
GEMINI_API_KEY=your_google_gemini_api_key
3. Frontend Setup
Open a new terminal window, navigate to the frontend directory, and install dependencies.

Bash
cd frontend
npm install
Create a .env file in the frontend root (if you are using Vite, prefix with VITE_):

Code snippet
VITE_API_BASE_URL=http://localhost:5000/api
4. Running the Application
Start the backend server:

Bash
# In the backend directory
npm run dev
Start the frontend development server:

Bash
# In the frontend directory
npm run dev
The application should now be running. The frontend is typically accessible at http://localhost:5173 (Vite) or http://localhost:3000 (CRA), and the backend is listening on http://localhost:5000.  

📂 Folder Structure
Plaintext
📦 project-root
 ┣ 📂 backend
 ┃ ┣ 📂 controllers    # API endpoint logic
 ┃ ┣ 📂 models         # Mongoose schemas
 ┃ ┣ 📂 routes         # Express routing
 ┃ ┣ 📂 middleware     # JWT verification, error handling
 ┃ ┣ 📂 services       # Gemini API integration logic
 ┃ ┗ 📜 server.js      # Entry point for backend
 ┗ 📂 frontend
 ┃ ┣ 📂 src
 ┃ ┃ ┣ 📂 components   # Reusable UI components
 ┃ ┃ ┣ 📂 pages        # Application views (Home, Dashboard, etc.)
 ┃ ┃ ┣ 📂 context      # React context for state management (Auth)
 ┃ ┃ ┗ 📜 App.jsx      # Main application routing
