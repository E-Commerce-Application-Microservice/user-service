# User Service
Handles user registration, login, and profile management.

## Endpoints
- `POST /register` — Register new user
- `POST /login` — Login
- `GET /profile/:id` — Get user profile
- `PUT /profile/:id` — Update profile
- `GET /users` — List all users (admin)
- `GET /health` — Health check

## Environment Variables
- `PORT` — Service port (default: 3001)
- `MONGO_URI` — MongoDB connection string
