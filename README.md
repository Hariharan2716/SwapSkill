# 🔁 SkillSwap — Learn. Teach. Grow. 🌱

> A full-stack skill exchange platform where users can connect, chat, and schedule learning sessions by swapping skills.

## 🚀 Overview

**SwapSkill** is a web-based application that connects people who want to learn a skill with those willing to teach it.  Think of it as the "language exchange" concept, but for any skill - from coding to cooking, UI/UX to Yoga.

Designed with **real-world scalability**, **clean architecture**, and **a user-first mindset**, this capstone demonstration of my ability to take a product from idea to development using the latest full-stack development tools and practices.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Why This Project?

- Solve a real-world need: accessible peer-to-peer learning.
- ShowCase end-to-end development skills (forntend, backend, database, authentication, scheduling, chat).
- Emphasize problem-solving, design thinking, and user experience.

> This project isn't just code-it's about understanding product design usability, and scalable system architecture.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Tech Stack

---------------------------------------------------------------------------------------
|  Area                |            Tools and Frameworks                               |
|----------------------|---------------------------------------------------------------|
|  **Frontend**        |  React, Tailwind CSS, Figma (prototypes)                      |
|  **Backend**         |  Node.js, Express.js                                          |
|  **Database**        |  MongoDb  (Mongoose ODM)                                      |
|  **Authentication**  |  JWT (JSON Web Tokens)                                        |
|  **Real-time Chat**  |  Socket.IO (WebSockets)                                       |
|  **Scheduling**      |  Custom scheduler with Calendar support                       |
|  **Dev Tools**       |  Git, GitHub, Postman, ESLint, Prettier                       |
|  **Deployment**      |  Render / Vercel (Frontend), Render / Railway (Backend)       |
----------------------------------------------------------------------------------------



## Features

### Authentication
- Secure user signup/login with JWT-based sessions
- Password hashing with bcrypt

### Dashboard
- Personalized dashboard showing skills and suggested matchces

### Skill Matching
- Search + suggestion engine based on interests and skill needs
- Smart filters to find ideal partners

### Chat Interface 
- Real-time chat with connected users
- Message history persisted in DB

### Session Scheduling
- Pick date and time with matched user
- Schedule stored in DB with validations
- Future calendar integration (Google Calendar, Outlook)

### Responsive UI
- Minimalist design based on low-fidelity Figma prototype
- Built mobile-first and scales to desktop
- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Application Flow

1. **Landing Page**: Learn about SwapSkill, Click "Get Started"
2. **Autn**: Login/Signup to access the dashboard
3. **Dashboard**: See your skills and suggested matches
4. **Match**: Search and connect with compatible users
5. **Chat**:  Coordinate and connect in real-time
6. **Schedule**: Book a session and track upcoming ones

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## UI Mockups  (Low-Fidelity)

[link to the figma wireframe] (#) *(Link to your public Figma file or screenshots)*

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Installation

```bash
# Clone the repository
git clone https://githum.com/Hariharan2716/SwapSkill.git
cd SwapSkill

# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install

# Run both servers
# Frontend: http://localhost:5173
# Backend: http://localhost:5000

# Start frontend (Vite)
npm run dev

# Start backend
npm run dev
