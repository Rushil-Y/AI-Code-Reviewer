# AI Code Reviewer

An AI-powered full-stack application that analyzes source code and provides intelligent feedback to help developers improve code quality, readability, security, and performance.

This project was built using React, Node.js, Express, MySQL, Prisma ORM, and AI integration to create an automated code review assistant.

## 🚀 Features

- AI-powered code review and feedback
- Analyze source code quality and readability
- Identify potential bugs and improvement areas
- Suggest performance optimizations
- Provide security recommendations
- Full-stack architecture with React frontend and Node.js backend
- Store code review results using MySQL and Prisma ORM

## 🛠️ Tech Stack

### Frontend

- React.js
- Vite
- JavaScript
- Tailwind CSS
- Axios

### Backend

- Node.js
- Express.js
- Prisma ORM
- MySQL

### AI Integration

- Google Gemini API

## 📂 Project Structure

```
AI-Code-Reviewer
│
├── frontend        # React frontend application
│
├── backend         # Express backend API
│
└── interface       # UI assets
```

## 📌 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Rushil-Y/AI-Code-Reviewer.git
cd AI-Code-Reviewer
```

## 2. Backend Setup

Navigate to the backend folder:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file inside the backend directory:

```env
DATABASE_URL="mysql://root:password@localhost:3306/code-reviewer"
JWT_SECRET="your_secret_key"
GEMINI_API_KEY="your_api_key"
```

Run Prisma migrations:

```bash
npx prisma migrate dev
```

Start the backend server:

```bash
node server.js
```

Backend will run on:

```
http://localhost:3000
```

## 3. Frontend Setup

Open another terminal and navigate to the frontend folder:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the frontend development server:

```bash
npm run dev
```

Frontend will run on:

```
http://localhost:5173
```

## 📡 API Endpoint

### AI Code Review

| Method | Route            | Description                                   |
| ------ | ---------------- | --------------------------------------------- |
| POST   | `/ai/get-review` | Submit code and receive AI-generated feedback |

## 🔮 Future Improvements

- Add user authentication
- Save review history for users
- Support multiple programming languages
- Add code quality scoring
- Improve AI review customization

## 📷 Screenshots

Add application screenshots here.

## 👨‍💻 Author

**Rushil Reddy**

GitHub:  
https://github.com/Rushil-Y
