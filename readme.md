# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.


## Getting stared

### Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Running the app

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

``` docker-compose up ```

Navigate to [http://localhost:3001](http://localhost:3001) to see the front end app.
or try [localhost:3000/api/ping](localhost:3000/api/ping) to see the backend app.