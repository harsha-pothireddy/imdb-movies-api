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

```bash
git clone https://github.com/harsha-pothireddy/imdb-movies-api.git
cd imdb-movies-api
npm install

npm start
npx nodemon server.js
