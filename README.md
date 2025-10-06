# Movies API

This is a Node.js + Express microservice that provides movie data from a SQLite database.  
It supports pagination, filtering by year and genre, fetching movie details by IMDb ID, and includes Swagger documentation.

---

## Prerequisites
- Node.js (v18 or later recommended)
- npm
- SQLite installed locally
- `movies.db` and `ratings.db` should be placed in the `db/` folder

---

## Installation
Clone the repository and install dependencies:

## Run the Project
npm start
npx nodemon server.js
http://localhost:3000
http://localhost:3000/api-docs

## Running Unit Tests

npm test

## Project Structure

movie-api/
│
├── db/                 # SQLite database files (movies.db, ratings.db)
├── routes/             # Express route definitions (v1/moviesRoutes.js)
├── services/           # Database access and business logic
├── tests/              # Jest + Supertest test cases
├── server.js           # Entry point of the application
├── swagger.js          # Swagger configuration
└── README.md           # Project documentation

```bash
git clone https://github.com/harsha-pothireddy/imdb-movies-api.git
cd imdb-movies-api
npm install


