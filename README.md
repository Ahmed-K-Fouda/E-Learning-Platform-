# E-Learning Platform Project

This project is a comprehensive **E-Learning Platform** that includes features for user management, authentication, course management, job listings, and more. It is built using **React**, **Redux Toolkit**, **Bootstrap**, and several other modern web technologies. This platform serves as a one-stop hub for students, instructors, and administrators, offering various features tailored for online learning and professional development.

---

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Scripts](#scripts)
- [Components](#components)
- [Redux Slices](#redux-slices)
- [Contact](#contact)

---

## Features

- **User Authentication**: Login, logout, and registration with role-based access for students, instructors, and admins.
- **Admin and Instructor Portals**: Separate admin and instructor portals with access control for managing content and monitoring progress.
- **Dynamic Course Management**: A complete course listing with details and enrollment options.
- **Job Listings and Search**: Browse job openings with the ability to filter results.
- **CV Creation Tool**: Allows users to create and download their CVs.
- **Exam Management**: Schedule and conduct exams with automated results display.
- **News Sections**: Displays the latest business, technology, sports, and medical news.
- **Responsive Design**: Designed with Bootstrap to be fully responsive and adaptable to various screen sizes.

---

## Technologies Used

- **React**: Front-end library for building user interfaces.
- **Redux Toolkit**: Manages the application's state for user, course, job, and exam data.
- **React Router**: Handles navigation and routing within the app.
- **Bootstrap**: Provides a responsive, mobile-first design framework.
- **Axios**: For making HTTP requests to fetch or send data.
- **Fortawesome Icons**: For icons used across the UI.
- **Vercel Speed Insights**: Monitors and optimizes application speed and performance.
- **HTML2Canvas** and **jsPDF**: For rendering HTML as images and generating PDFs for the CV creation tool.

---

## Project Structure

```plaintext
src
├── components
│   ├── Header.jsx
│   ├── Footer.jsx
│   ├── ProtectedRoute.jsx
│   └── auth
│       ├── Login.jsx
│       └── Signup.jsx
├── pages
│   ├── Home.jsx
│   ├── AdminPortal.jsx
│   ├── InstructorPortal.jsx
│   ├── StudentPortal.jsx
│   ├── JobsPage.jsx
│   ├── CoursesPage.jsx
│   ├── ExamPage.jsx
│   ├── CreateCv.jsx
│   ├── Profile.jsx
│   └── News
│       ├── BusinessNewsPage.jsx
│       ├── SportsNews.jsx
│       ├── MedicalNews.jsx
│       └── TechNews.jsx
├── Redux
│   ├── AuthSlice.js
│   ├── ArticlesSlice.js
│   ├── JobsSlice.js
│   ├── CoursesSlice.js
│   ├── ExamSlice.js
│   └── AdminJobsSlice.js
└── App.js
└── index.css

## Usage

Admin Portal: Provides access to manage jobs, courses, and users.
Instructor Portal: Allows instructors to manage and create course content and exams.
Student Portal: Allows students to view enrolled courses, access exams, and view results.
Jobs Section: Browse and search for jobs with category filters.
News Section: Displays the latest news updates in various categories.
CV Creation Tool: Enables users to create and download their CVs as PDFs.

## Components

Header: Provides the navigation links and user options.
Footer: Displays essential links and site information.
ProtectedRoute: Protects routes based on user roles.
Login / Signup: Manages user authentication.
Profile: Allows users to view and edit their profiles.
News Pages: Displays categorized news items from different sources.

## Redux Slices
- AuthSlice.js
 Manages user authentication:

-loginUser: Handles user login through async Thunks.
-registerUser: Handles user registration and saves the new user data.
-logoutUser: Logs out the current user.
-toggleAuthModel: Toggles the visibility of the login/signup modal.
-clearError: Clears any authentication errors.

# JobsSlice.js
Manages job data:

-getJobs: Fetches job listings.
-setSearchQuery: Sets the search query for filtering jobs.
-resetSearchQuery: Clears the search filter.

# ArticlesSlice.js
Manages news articles:

-getArticles: Fetches the latest articles.
-clearError: Clears any errors related to article fetching.

# CoursesSlice.js
Manages course data:

-setCourses: Sets the list of available courses.
-setCourseDetails: Updates detailed course info.

# ExamSlice.js
Handles exam functionality:

-scheduleExam: Schedules a new exam.
-submitExam: Submits exam answers.
-fetchResults: Retrieves exam results for a student.

## Contact
For questions or feedback, please contact:

Name: Ahmed Khaled Fouda
Email: ahmedfoudahany@example.com
```
