# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1.  Make sure you have Docker desktop up and running. If you don't have Docker setup, <a href="https://docs.docker.com/get-docker/ ">install it</a>.
2.  Run `docker-compose up` from the root directory of the project.
3.  Head to `localhost:3000/api/ping` and check to see if the backend is up and running.
4.  Go to `localhost:3001/register` and create a new user to verify everything is working properly.
