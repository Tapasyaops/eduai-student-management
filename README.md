# 🎓 EduAI — AI-Powered Student Management System

An AI-powered student management platform designed to simplify academic tracking, improve student productivity, and provide personalized learning assistance.

## 📌 About the Project

EduAI is a full-stack web application that brings student management and AI-powered academic support together in one place. It enables students to track attendance, view marks, monitor academic performance, and organize their studies, while administrators can manage student records and academic information.

The project aims to make academic management more accessible, organized, and intelligent through a clean user interface and AI-assisted learning tools.

> **Project Status:** 🚧 In Development

## ✨ Features

### 👨‍🎓 Student Portal

- 📊 Personalized academic dashboard
- 📅 Attendance tracking and percentage calculation
- 📝 Marks and academic performance analysis
- 🗓️ Timetable management
- 👤 Student profile management
- 🤖 AI-powered academic assistant
- 📚 Personalized study-plan generation
- 📢 Notices and announcements

### 👨‍💼 Admin Portal

- 👥 Student record management
- 📋 Attendance management
- 📝 Marks and grades management
- 📚 Subject management
- 📢 Notices and announcements
- 📈 Academic data overview

### 🤖 AI Academic Assistant

- Academic question answering
- Personalized study plans
- Exam preparation assistance
- Attendance insights
- Academic performance summaries

*Features will be implemented progressively throughout development.*

## 🛠️ Tech Stack

| Technology   | Purpose                        |
| ------------ | ------------------------------ |
| React        | Frontend user interface        |
| TypeScript   | Type safety                    |
| Tailwind CSS | Styling and responsive design  |
| Node.js      | Backend runtime                |
| Express.js   | REST API                       |
| MongoDB      | Database                       |
| Mongoose     | Database modeling              |
| JWT          | Authentication                 |
| OpenAI API   | AI-powered academic assistance |
| Recharts     | Data visualization             |
| Git & GitHub | Version control                |

## 🏗️ System Architecture

```text
                 ┌─────────────────────┐
                 │    React Frontend   │
                 │   TypeScript + UI   │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │   Express Backend   │
                 │ REST API + Security │
                 └──────────┬──────────┘
                            │
                  ┌─────────┴─────────┐
                  ▼                   ▼
          ┌──────────────┐    ┌──────────────┐
          │   MongoDB    │    │  OpenAI API  │
          │ Academic Data│    │ AI Assistant │
          └──────────────┘    └──────────────┘
```

## 📁 Project Structure

```text
eduai/
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── types/
│   │   ├── App.tsx
│   │   └── main.tsx
│   └── package.json
├── backend/
│   ├── src/
│   │   ├── config/
│   │   ├── models/
│   │   ├── controllers/
│   │   ├── routes/
│   │   ├── middleware/
│   │   ├── services/
│   │   └── server.ts
│   ├── .env.example
│   └── package.json
├── .gitignore
└── README.md
```

*The folder structure may evolve as development progresses.*

## 🚀 Getting Started

### Prerequisites

Install the following before running the project:

- [Node.js](https://nodejs.org/) — LTS version recommended
- npm — included with Node.js
- [Git](https://git-scm.com/)
- [MongoDB Atlas](https://www.mongodb.com/atlas) account for the cloud database when backend integration is implemented
- OpenAI API access for AI features when integration is implemented

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/eduai-student-management.git
cd eduai-student-management
```

Replace `YOUR-USERNAME` with your GitHub username and adjust the repository name if necessary.

### 2. Set Up the Frontend

```bash
cd frontend
npm install
npm run dev
```

Open the local URL displayed in your terminal.

### 3. Set Up the Backend

Once the backend has been created:

```bash
cd backend
npm install
```

Create a `.env` file using `.env.example` as a reference and configure the required environment variables.

Start the backend using the development script defined in `backend/package.json`.

### 4. Configure Environment Variables

Example backend configuration:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secure_random_secret
OPENAI_API_KEY=your_openai_api_key
CLIENT_URL=http://localhost:5173
```

These are example variable names. Configure them to match your implementation.

**Important:** Never commit your actual `.env` file, database credentials, JWT secrets, or OpenAI API key to GitHub. Keep the OpenAI API key exclusively on the backend.

## 🗺️ Development Roadmap

- Initialize project structure
- Build responsive frontend UI
- Create student dashboard
- Implement student and subject management
- Develop backend REST APIs
- Integrate MongoDB
- Implement authentication and role-based access
- Add attendance and marks management
- Build academic analytics and charts
- Integrate the AI academic assistant
- Develop the admin dashboard
- Test application functionality and security
- Deploy the application

## 🔐 Security Considerations

- Secure authentication and role-based authorization
- Password hashing and input validation
- Protected API endpoints
- Environment-based secret management
- Restricted database access
- Rate limiting for API and AI requests
- Synthetic student data for public demonstrations

## 🌱 Future Enhancements

- Faculty portal
- Parent portal
- Assignment management
- AI-generated quizzes
- Career guidance
- Notifications and reminders
- Mobile application

## 🎯 Project Goals

- Simplify academic information management
- Help students monitor their academic progress
- Provide accessible AI-assisted learning support
- Create a responsive and user-friendly experience
- Explore the integration of full-stack development and AI

## 👩‍💻 Author

**Tapasya**
**Rashi Sharma**

Computer Science Engineering Student

GitHub: https://github.com/Tapasyaops

## 📄 License

This project is developed for educational and portfolio purposes. A formal open-source license can be added as the project evolves.
