
# ⭐StudyNotion

StudyNotion is a fully functional ed-tech platform designed to provide an immersive learning experience to students and a robust platform for instructors to showcase their expertise. Built using the MERN stack (MongoDB, Express.js, React.js, and Node.js), StudyNotion enables users to create, consume, and rate educational content seamlessly.


## Project Description

StudyNotion is an ed-tech platform aimed at making education more accessible and engaging by providing a seamless and interactive learning experience. The platform supports:
- A wide range of educational content
- A rating system for courses
- A platform for instructors to connect with learners globally

## System Architecture

StudyNotion follows a client-server architecture, consisting of:
- **Front-end:** Built using ReactJS for dynamic and responsive user interfaces.
- **Back-end:** Powered by Node.js and Express.js, handling APIs for functionalities like user authentication, course creation, and content consumption.
- **Database:** Utilizes MongoDB, a NoSQL database for storing unstructured and semi-structured data like videos, images, and user details.

## Features

- User Authentication (with OTP verification)
- Course Creation and Management
- Course Consumption and Rating
- Payment Integration via Razorpay
- Cloud-based Media Management via Cloudinary

## Tech Stack

- **Front-end:** ReactJS, Redux, Tailwind CSS
- **Back-end:** Node.js, Express.js, MongoDB, JWT for authentication, Bcrypt for password hashing
- **Database:** MongoDB
- **Hosting:** Vercel (Front-end), Render (Back-end), MongoDB Atlas (Database)


## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Suyash33/Study-Notion.git
   ```
2. **Install dependencies for both frontend and backend:**
   ```bash
   cd src
   npm install
   cd ../server
   npm install
   ```
3. **Set up environment variables:**
   Create a `.env` file in the root of your backend directory and add the required environment variables.

4. **Run the application:**
   ```bash
   cd src
   npm start
   cd ../server
   npm run dev
   ```


---


Feel free to modify any sections as per your specific needs!
