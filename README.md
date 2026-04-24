# PlacePrep - College Placement Command Center

PlacePrep is a full-stack platform designed to streamline college placement preparation. It provides a centralized system for students to track progress, practice coding, prepare for interviews, and manage placement-related activities efficiently.

## Project Type
Academic Project (Enhanced & Maintained by Me)

## Key Features

- 📊 DSA Tracker with coding compiler
- 🧠 Aptitude mock tests with performance analysis
- 🎤 Mock interview preparation module
- 📄 Resume ATS optimization tools
- 🏢 Company-wise placement tracking

## Tech Stack

- Frontend: React + Vite
- Backend: Node.js + Express
- Database: MongoDB Atlas
- Authentication: JWT

## My Contributions

- Implemented and improved authentication using JWT
- Enhanced UI using React and Tailwind (if applied)
- Worked on API integration between frontend and backend
- Improved user flow and performance
- Debugged and optimized backend routes

## Project Structure

client/   -> React frontend  
server/   -> Express API + MongoDB models/routes  

## Local Setup

1. Install dependencies:
npm install  
cd server && npm install  
cd ../client && npm install  

2. Configure backend env in `server/.env`:
PORT=5000  
MONGO_URI=your_mongodb_atlas_uri  
JWT_SECRET=your_secret  
JWT_EXPIRES_IN=7d  
CLIENT_URL=http://localhost:5173  

3. Seed initial data:
npm run seed:all  

4. Run app:
npm run dev  

## Deployment

Deployed using Render with separate services for backend and frontend.

## Notes

- Environment variables are secured using `.env`
- Sensitive data like API keys are not committed
