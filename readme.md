# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. This project runs via Docker. [Install Docker](https://docs.docker.com/get-docker/).
2. After install verify installation via the following terminal commands: `docker -v` & `docker-compose -v`
3. Start the services with `docker-compose up` from the *project root directory*
4. With docker running verify the backend is running: <http://localhost:3000/api/ping>
5. Verify that the frontend is runing <http://localhost:3001/register>
6. Create an account. Success!
