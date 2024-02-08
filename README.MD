# Friendshyp

This project contains both front and backend of the test application.

## Project setup

1. Download postgresql: `https://www.postgresql.org/download/`
2. Run `npm install` or `yarn` in both `friendshyp-frontend` and `friendshyp-backend` directories
3. Setup and seed db for countries list: 
   * Create `friendshyp` database locally  and place db credentials in `.env` file of `friendshyp-backend`
   * Run `npm run seed` to seed countries table in database
4. Run `npm run start:dev` in `friendshyp-backend` to start backend server in watch mode
5. Run `npm run start` in `friendshyp-frontend` to start backend server in watch mode
6. View app in `http://localhost:4200`


## Potential Improvements
1. Adding google address autocomplete to get user address and validate country
2. Manage app state and cache data to improve performance
3. Design and responsiveness