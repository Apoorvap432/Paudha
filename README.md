# Mini Plant Store

A full-stack web application for browsing and managing plant inventory.

## Features
- Browse plant catalog with search and filtering
- Responsive design for mobile and desktop
- Admin functionality to add new plants
- Real-time stock availability
- Category-based filtering
- RESTful API backend

## Tech Stack
- **Frontend**: React.js, Tailwind CSS, Lucide React
- **Backend**: Node.js, Express.js, MongoDB
- **Database**: MongoDB with Mongoose ODM

## Setup Instructions

1. Clone the repository
2. Install backend dependencies: `cd backend && npm install`
3. Install frontend dependencies: `cd frontend && npm install`
4. Set up environment variables (see .env.example files)
5. Start MongoDB service
6. Seed the database: `cd backend && npm run seed`
7. Start backend: `cd backend && npm run dev`
8. Start frontend: `cd frontend && npm start`

## API Endpoints
- GET /api/plants - Get all plants with optional search/filter
- POST /api/plants - Add new plant
- GET /api/plants/:id - Get single plant

## License
MIT
