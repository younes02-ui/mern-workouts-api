MERN Workouts App

MERN Workouts App is a fullstack MERN application for managing workouts, built with MongoDB, Express, React, and Node.js.

It allows users to:

- Create new workouts
- View all workouts or a single workout
- Update existing workouts
- Delete workouts

The backend provides a RESTful API with:

- Routes → REST endpoints for CRUD operations
- Controllers → business logic and database operations
- Models → Mongoose schemas for validation
- Middleware → request logger and JSON parser

The frontend is built with React, providing:

- Dynamic list of workouts
- Forms to create, update, and delete workouts
- Real-time feedback and validation

💡 Bonus: automatic timestamps (createdAt / updatedAt) and field validation to ensure data consistency.

🛠️ Technologies Used

Node.js & Express → backend API server
MongoDB & Mongoose → database and ORM
React → frontend UI
dotenv → environment variable management

🚀 Features :

Backend (API) :

GET /api/workouts → Retrieve all workouts
GET /api/workouts/:id → Retrieve a single workout
POST /api/workouts → Create a new workout
PATCH /api/workouts/:id → Update a workout
DELETE /api/workouts/:id → Delete a workout

Frontend (React) :

Displays all workouts dynamically
Add, update, and delete workouts using forms
Shows validation errors and feedback
