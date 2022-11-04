# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

After stepping away from the quest for a few days, I had trouble finding the correct URL to use for the backend ping. Look at the console output in the codespace for the latest URL, e.g. here was mine

=============================================
LABEL     PORT   VISIBILITY  BROWSE URL
Backend   3000   public      https://smoothlandon-turbo-tribble-xj5px9v792p4x9-3000.githubpreview.dev

Run docker-compose up
Copy/paste the URL above into your browser and append with /api/ping
https://smoothlandon-turbo-tribble-xj5px9v792p4x9-3000.githubpreview.dev

and you will get the response from the backend
{"msg":"Pong! Seems like Everythink is working, great job!"}
