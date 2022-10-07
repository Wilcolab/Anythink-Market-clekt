# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

For first setup of the environment of your machine, make sure to first download docker. After docker is downloaded, open the codebase in the root dir. From here, open a terminal (still in the root dir) and run docker -v to confirm docker installed. 

Next, run docker-compose up
This will build the container, and then you can check if it built successfully by going to http://localhost:3000/api/ping 

Then you can go to http://localhost:3001/register and register an account. 
