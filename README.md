# Travel World — Backend

REST API for a full-stack travel/tours web application. Handles authentication, tour listings, bookings, and reviews.

Built as part of a MERN-stack project; this repo is the **Node/Express + MongoDB backend**. <!-- TODO: link the frontend repo here -->

## Tech stack

- **Node.js** + **Express** — REST API server
- **MongoDB** (Atlas) — data store, accessed via Mongoose models
- **JWT** — authentication & protected routes
- Structured into `controllers/`, `routes/`, `models/`, `middleware/`, `utils/`

## Features

- User registration & login with JWT-based auth
- CRUD for tours / destinations
- Booking flow
- Reviews & ratings

## Running locally

```bash
git clone https://github.com/kushalkou/travel-world-backend.git
cd travel-world-backend
npm install

# create your own .env (see below), then:
npm start
```

### Environment variables

Create a `.env` file in the project root:

```
PORT=4000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

> ⚠️ Never commit your real `.env`. Make sure `.env` is listed in `.gitignore`.

## Status

Coursework / portfolio project. <!-- adjust this line to whatever's true -->
