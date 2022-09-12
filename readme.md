# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Install [Docker](https://docs.docker.com/get-docker/)
- You can verify docker is ready by running the following commands in your terminal: `docker -v` and `docker-compose -v`
- Make sure everything is updated: `docker-compose run anythink-backend-rails bash -c "cd backend && bin/update"`
- Check if you can access the api http://localhost:3000/api/ping
- Check the frontend and make sure it’s connected to the backend: try to register a user http://localhost:3001/register
