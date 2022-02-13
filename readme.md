# Welcome to the Anythink Market repo

Setup:
1. install all the dependencies: yarn install
2. change the default port of the frontend so it doesn't collide with port 3000 of the backend. Add the following in frontend/.env: PORT=3001
3. set the URI of your local MongoDB in backend/.env: MONGODB_URI="mongodb://localhost"
4. There's a bug in the current version of Node that breaks the mongoose. The workaround is the use Node 14 until there's a fix in 17.5. Make sure Node 14 is the first in your PATH 

To start the app use: `./start.sh`, it'll start both the backend and the frontend.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.
