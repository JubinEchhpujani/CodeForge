
# CodeForge 🚀

A LeetCode-style online coding platform that allows users to explore coding problems, write and submit code in multiple programming languages, and evaluate solutions against predefined test cases. The platform also features an AI-powered chatbot and video integration to enhance the coding and learning experience.

## ✨ Features

- **User Authentication:** Secure user registration and login using JWT-based authentication.
- **Role-Based Access Control:** Separate admin access for managing coding problems.
- **Problem Management:** Browse coding problems and practice programming.
- **Online Code Execution:** Compile and execute code in multiple programming languages using Judge0.
- **Automated Test Cases:** Evaluate submitted solutions against predefined test cases.
- **AI-Powered Chatbot:** Get interactive assistance and guidance while solving coding problems.
- **Video Integration:** Access video-based learning resources to improve understanding of coding concepts.
- **Redis Integration:** Manage token handling and maintain a token blocklist for logout functionality.
- **Database Management:** Store user information and coding problems using MongoDB.
- **REST APIs:** Backend APIs built with Node.js and Express.js.

## 🛠️ Tech Stack

### Frontend
- HTML
- CSS
- JavaScript
- React.js

### Backend
- Node.js
- Express.js

### Database & Tools
- MongoDB
- Redis
- Judge0 API
- JWT Authentication
- Git & GitHub

## 🏗️ Project Architecture

The application follows a client-server architecture:

1. **Frontend:** React.js provides the user interface for browsing problems and submitting code.
2. **Backend:** Node.js and Express.js handle authentication, problem management, and API requests.
3. **Database:** MongoDB stores user data and coding problems.
4. **Redis:** Handles token blocklisting for authentication and logout.
5. **Judge0:** Executes submitted code and returns execution results.
6. **AI Chatbot & Video Integration:** Provide interactive assistance and supplementary learning resources.

## ⚙️ Installation and Setup

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm
- MongoDB
- Redis

### 1. Clone the Repository

```bash
git clone <YOUR_REPOSITORY_URL>
cd <YOUR_PROJECT_FOLDER>
```

### 2. Install Dependencies

Install the dependencies for the backend:

```bash
cd backend
npm install
```

If your frontend is in a separate folder:

```bash
cd ../frontend
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the backend directory and add the required configuration:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
REDIS_URL=your_redis_connection_url
JUDGE0_API_KEY=your_judge0_api_key
```

Add any additional environment variables required for the AI chatbot and other integrations.

**Note:** Replace the placeholder values with your actual credentials. Never commit your `.env` file to GitHub.

### 4. Run the Application

Start the backend:

```bash
cd backend
npm run dev
```

Start the frontend in a separate terminal:

```bash
cd frontend
npm run dev
```

The frontend and backend will run on the local URLs displayed in your terminal.

## 🔄 Application Workflow

1. Users register or log in to the platform.
2. Users browse coding problems and write solutions.
3. Submitted code is sent to the backend through REST APIs.
4. The backend forwards the code to Judge0 for compilation and execution.
5. Execution results are returned to the frontend.
6. Users can access the AI chatbot and video resources for additional learning support.

## 🔮 Future Enhancements

- Add user profiles and coding progress tracking.
- Implement leaderboards and coding contests.
- Add problem difficulty filters and search functionality.
- Improve AI-powered coding assistance.
- Add submission history and performance analytics.

## 👨‍💻 Author

**Jubin Echhpujani**

B.Tech | Electronics and Communication Engineering  
NIT Patna

## 📄 License

This project is intended for educational and learning purposes.
