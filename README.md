# MERN Job Portal – Created by Praveena Pantham

This is a full-stack web application built using the MERN stack (MongoDB, Express, React, Node.js). It allows students to search and apply for jobs, and recruiters to post job openings.

## 🚀 Features
- User Registration & Login (Student / Recruiter)
- Recruiters can post and manage job listings
- Students can browse and apply for jobs
- Secure authentication using JWT (JSON Web Tokens)
- File uploads for resumes and profile photos (via Cloudinary)
- Responsive UI (React + Tailwind CSS)

## 🛠️ Technologies Used
- MongoDB, Express.js, Node.js
- React + Tailwind CSS
- Redux (state management)
- JWT for authentication
- Cloudinary for file uploads

## 📦 Installation & Setup

### Backend
1. Navigate to the backend folder:  
   `cd ./Backend`

2. Install dependencies:  
   `npm install`

3. Create a `.env` file with your credentials:

PORT=5000
MONGO_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

4. Start the backend:  
`npm run dev`

You should see:
Server is running on port 5000
MongoDB Connected...


### Frontend
1. Navigate to the frontend folder:  
`cd ./Frontend`

2. Install dependencies:  
`npm install`

3. Start the frontend:  
`npm run dev`

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

## 🔧 Usage
- Register as a Student or Recruiter
- Recruiters can create and manage job posts
- Students can apply for jobs directly

## ✍️ Author
Created by Praveena Pantham  
GitHub: [https://github.com/praveenapantham](https://github.com/praveenapantham)  
