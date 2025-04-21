# Eary - Hearing Test Application

Eary is a web application designed to provide hearing tests and assessments. The application allows users to take hearing exams while administrators can manage tests, users, and exam questions.

## Features

- **User Authentication**: Registration, login, and profile management
- **Hearing Tests**: Take interactive hearing exams with audio questions
- **Test History**: View past test results and progress
- **Admin Dashboard**: Manage users, tests, and exam questions
- **Responsive Design**: Works on various screen sizes and devices

## Technology Stack

### Frontend
- React.js
- React Router for navigation
- Bootstrap & React-Bootstrap for UI
- Axios for API requests
- FontAwesome for icons

### Backend
- Node.js with Express
- MySQL database
- JWT for authentication
- Bcrypt for password hashing
- Multer for file uploads
- Nodemailer for email notifications

## Project Structure

- `/src` - Frontend React application
  - `/components` - React components
  - `/middleware` - Auth middleware
  - `/helper` - Helper functions
- `/Server` - Backend Node.js application
  - `/Controllers` - API controllers
  - `/Models` - Data models
  - `/Routes` - API routes
  - `/Middleware` - Server middleware
  - `/DataBase` - Database configuration
  - `/Audios` - Stored audio files for hearing tests

## Getting Started

### Prerequisites
- Node.js (v12+)
- MySQL database

### Installation

1. Clone the repository
```
git clone https://github.com/yourusername/eary.git
cd eary
```

2. Install frontend dependencies
```
npm install
```

3. Install backend dependencies
```
cd Server
npm install
```

4. Configure environment variables
   - Create a `.env` file in the Server directory based on the existing template
   - Configure your database connection and other settings

5. Start the backend server
```
npm run dev
```

6. Start the frontend application (in a new terminal window)
```
# From the root directory
npm start
```

7. The application should now be running at http://localhost:3000

## Database Structure

The application uses the following database structure:
- Users - Stores user information and authentication details
- Exams - Stores exam configurations
- Questions - Stores exam questions and correct answers
- History - Tracks user exam history and results

## Usage

### For Users
1. Register a new account or login
2. Take hearing tests from the available exams
3. View your test history and results
4. Update your profile information

### For Administrators
1. Manage users (add, update, delete)
2. Create and manage exams
3. Add and edit test questions
4. Review user test results

## License

This project is licensed under the ISC License.
