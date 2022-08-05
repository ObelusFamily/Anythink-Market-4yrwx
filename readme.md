# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. You need to have docker installed and running
2. You can verify docker is up and running by typing the following in your terminal: 'docker -v' and 'docker-compose -v'
3. Then run 'docker-compose up' from the project root directory
4. If docker is working correctly, the backend should be running and able to connect to your local database
5. You can test this by pointing your broser to http://localhost:3000/api/ping
6. You can check that the frontend is connected to the backend by seeing the register user page at http://localhost:3001/register

