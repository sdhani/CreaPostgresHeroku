## Create React App + Express + PostgreSQL + Knex + :rocket: Heroku

This repository is a template repo for a create-react-app express project that can be hosted on Heroku. 
It has a PostgreSQL DB with the Knex SQL query builder.

1. It renders a plain React App. Landing Page loads `App.js rendered` from the React component App.js.
2. If you navigate to `https://stormy-meadow-64978.herokuapp.com/allusers`, this renders the React component Homepage.jsx with data pulled in from the PostgreSQL database.

## Install
1. Clone this repository.
    
    HTTPS:  `git clone https://github.com/sdhani/crea-postgres-heroku.git`
    
    SSH: `git@github.com:sdhani/crea-postgres-heroku.git`
    
2. `cd crea-postgres-heroku`
3. Run `yarn install-all` in the root directory.
6. Run `yarn start-all` in the root directory. This will concurrently start the server and create react app.
7. Open `http://localhost:3000` in your browser

2019
