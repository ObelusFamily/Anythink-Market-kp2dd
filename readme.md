# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Install Docker

In order to make things super easy to work on this code base locally we must install and use docker.

Setting up Docker is super easy, they have a GUI for windows, mac and linux. Make sure you follow the prerequisites before installing Docker for your specific operiting system.

Follow along with the Docker documentation for installation: [Install Docker](https://docs.docker.com/get-docker/)

Use `docker -v` and `docker-compose -v` in your command line to verify docker is installed and ready.

To run our application:

1. Change your directory to the project root
2. Run `docker-compose up`
3. Point your broweser to `localhost:3000`
