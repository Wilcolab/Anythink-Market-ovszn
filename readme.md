# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Install Docker usign from [here](https://docs.docker.com/get-docker/).

Once done you can verify that Docker is ready usign following commands in your terminal:
`docker -v` and `docker-compose -v`.

If everything is working go to the project directory and run the following command: `docker-compose up`.

If Docker is working correctly, the backend should be running and able to connect to your local database.

Let's test this by pointing your browser to http://localhost:3000/api/ping

Now, check the frontend and make sure it’s connected to the backend.

If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register
