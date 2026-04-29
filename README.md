# Learning-Management-System
A full-stack Learning Management System built using the MERN stack designed to streamline online education management.This platform 
enables students, lecturers, and administrators to interact through a secure and user-friendly interface.

## 🚀 Features

### Customer Features
- **User Authentication**: Register, Login, Forgot Password, JWT-based authentication
- **Course Browsing**: Browse available courses with categories, search, filters, and course recommendations
- **Course Enrollment**: Course level, Course duration, Learning category
- **Learning Dashboard**: View enrolled courses, track learning progress, upcoming deadlines
- **Assignments & Quiz Submission**: Submit assignments, attempt quizzes, and view submission history
- **Student Profile Management**: Update personal details, change password, manage profile settings
- **Learning Resources Access**: Download lecture notes, presentations, and study materials
- **Payment**: Enroll in paid courses with secure payment selection

### Admin Features
- **Dashboard**: Total students enrolled, Popular courses, Recent enrollments and activities
- **Course Management**: Add, edit, update, and delete courses with full course structure
- **Enrollment Management**: View enrolled students per course, Approve or restrict enrollments
- **User Management**: View and manage all users (students and instructors)
- **Performance Analytics & Reports**: Generate reports

## 🛠️ Tech Stack

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database (Mongoose ODM)
- **JWT** - Authentication

### Frontend
- **React 18** - UI library
- **React Router DOM** - Routing
- **Redux Toolkit** - State management
- **Tailwind CSS** - Styling
- **React Icons** - Icon library
- **Chart.js** - Analytics charts

### Installation

1. **Install Backend Dependencies**
   ```bash
   cd backend
   npm install
   ```
2. **Install Frontend Dependencies**
   ```bash
   cd frontend
   npm install
   ```
3. **Configure Environment Variables**

   Create `.env` file in backend directory:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   JWT_EXPIRE=30d
   ```
## 🔑 Demo Credentials

### Admin Account
- Email: testadmin@gmail.com
- Password: Test123

### User Account
- Email: sadeepa@example.com
- Password: Test123

## 📝 API Endpoints

### Authentication
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - Login user
- `GET /api/auth/me` - Get current user

### Product
- `GET /api/courses` - Get all courses
- `GET /api/courses/:id` - Get courses by ID
- `POST /api/courses` - Create courses (admin)
- `PUT /api/courses/:id` - Update courses (admin)
- `DELETE /api/courses/:id` - Delete courses (admin)

### Users
- `GET /api/users` - Get all users
- `GET /api/users/:id` - Get users by ID

### Orders
- `GET /api/exams` - Get all exams
- `GET /api/exams/:id` - Get exams by ID
- `POST /api/exams` - Create new exams
- `PUT /api/exams/:id/status` - Update exams status (admin)

### Reviews
- `GET /api/reviews/:productId` - Get reviews for product
- `POST /api/reviews` - Add review

## 📄 License

This project is for educational purposes.

# Screenshot of web application

## Image 1

![image alt](https://github.com/klsadeepas/Learning-Management-System/blob/0cb5ac7088b54a8c57017bcc2ce6884c376fe6c0/images/1.png)

## Image 2

![image alt](https://github.com/klsadeepas/Learning-Management-System/blob/0cb5ac7088b54a8c57017bcc2ce6884c376fe6c0/images/2.png)

## Image 3

![image alt](https://github.com/klsadeepas/Learning-Management-System/blob/0cb5ac7088b54a8c57017bcc2ce6884c376fe6c0/images/3.png)

## Image 4

![image alt](https://github.com/klsadeepas/Learning-Management-System/blob/0cb5ac7088b54a8c57017bcc2ce6884c376fe6c0/images/4.png)

## Image 5

![image alt](https://github.com/klsadeepas/Learning-Management-System/blob/0cb5ac7088b54a8c57017bcc2ce6884c376fe6c0/images/5.png)

## Image 6

![image alt](https://github.com/klsadeepas/Learning-Management-System/blob/0cb5ac7088b54a8c57017bcc2ce6884c376fe6c0/images/6.png)

## Image 7

![image alt](https://github.com/klsadeepas/Learning-Management-System/blob/0cb5ac7088b54a8c57017bcc2ce6884c376fe6c0/images/7.png)

## Image 8

![image alt](https://github.com/klsadeepas/Learning-Management-System/blob/0cb5ac7088b54a8c57017bcc2ce6884c376fe6c0/images/8.png)

## Image 9

![image alt](https://github.com/klsadeepas/Learning-Management-System/blob/0cb5ac7088b54a8c57017bcc2ce6884c376fe6c0/images/9.png)

## Image 10

![image alt](https://github.com/klsadeepas/Learning-Management-System/blob/0cb5ac7088b54a8c57017bcc2ce6884c376fe6c0/images/10.png)

## Image 11

![image alt](https://github.com/klsadeepas/Learning-Management-System/blob/0cb5ac7088b54a8c57017bcc2ce6884c376fe6c0/images/11.png)

