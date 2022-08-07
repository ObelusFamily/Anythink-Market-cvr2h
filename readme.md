# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
Step 1: clone the repo from https://github.com/ObelusFamily/Anythink-Market-cvr2h
Step 2: Install docker from https://docs.docker.com/get-docker/
Step 3: navagate to the root of your Anything directory and run the command 'docker-compose up' without the quotes
Step 4: Docker is working correctly, the backend should be running and able to connect to your local database. Test this by pointing your browser to http://localhost:3000/api/ping
Step 5: If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register
