# movie-search-app-local

Features of the application -

1. Users would be able to search any movie name. List of movies of movies would be diaplayed as image.
2. Users can click the image to pull videos related to the movie. 
3. If API - https://www.themoviedb.org/ returns a movie id. Related youtube video would be embedded in the page.
4. Users can sign up or sign in of already resistered.
5. If an already registered user tries to sign up again. User would be asked to sign in.
6. Password and form validations are handled in HTML code.
7. Password/ Confirm password should match. Else user would be alerted.
8. Hashed password is stored in postgres DB for security. Implemented using bcrypt.

Technologies used - HTML, CSS, Javascript, node js and postgreSQL DB.

Steps to create App locally -

1. Clone repository
2. Install - Nodemon, dotenv, express, pg, ejs and knex
3. Install postgreSQL
4. Create API Key from https://www.themoviedb.org/ and add in API_KEY
5. Create .env file to pass the below parameters - 

API_KEY= ?
PORT=3000
HOST=http://localhost/

DB_HOST=localhost
DB_PORT=5432
DB_USER=
DB_PASSWORD=
DB_DBNAME=

DB_ENVIRONMENT=development

5. Run - npm run migrate to create users table. 
