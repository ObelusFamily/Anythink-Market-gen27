# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Check if Docker is installed

Run the commands 'docker -v' and 'docker-compose -v' to check if you have Docker installed. Otherwise, you may install it from here: https://docs.docker.com/get-docker/

## Run the backend and the frontend applications

Run the command 'docker-compose up' from the project root directory. If everything is OK, the backend is pointing to http://localhost:3000/api/ping, and the frontend to http://localhost:3001/register
