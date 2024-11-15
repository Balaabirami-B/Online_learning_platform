Online Learning Platform (MERN Stack)
This project is an online learning platform built using the MERN stack (MongoDB, Express.js, React, Node.js). The platform allows users to browse and enroll in courses, watch videos, and interact with instructors. Administrators can manage users and courses, while learners can track their progress and complete assessments.

Features:

  1. User Authentication: Users can register, log in, and reset their passwords using JWT-based authentication.

  2. Course Management: Admin users can create, update, and delete courses, while learners can browse and enroll in courses.
     
  3. Progress Tracking: Learners can track their progress for each course and resume learning where they left off.
     
  4. Video Streaming: Support for embedding videos in courses.
     
  5. Discussion Forums: Users can participate in course-related discussions.

Tech Stack:

Frontend: React.js, React Router, Axios

Backend: Node.js, Express.js

Database: MongoDB, Mongoose

Authentication: JSON Web Token (JWT), bcryptjs

Video Streaming: Integrated third-party APIs or custom video uploading (e.g., Cloudinary)

Deployment: Heroku or AWS for backend, Netlify or Vercel for frontend

Setup Instructions:

     Prerequisites
     Ensure you have the following installed on your local machine:

        1 Node.js 

        2 MongoDB

        3 npm or Yarn

Database Setup:

If you're running MongoDB locally, ensure it's running on the default port (27017). 

If you’re using a cloud database (e.g., MongoDB Atlas), update the MONGO_URI in the .env file.

Testing the Application:

You can now open your browser and navigate to http://localhost:3000 to test the application. Make sure both the backend and frontend servers are running.

