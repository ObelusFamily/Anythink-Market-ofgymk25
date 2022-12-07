# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Following steps will help you setup the backend and frontend environment on your local system

1. Install Docker  
2. From the root directory run the command `docker-compose up`
3. Test whether backend is running by going to your browser: [http://localhost:3000/api/ping](http://localhost:3000/api/ping)
4. If the above step works fine, check whether front end is working. Go to [http://localhost:3001/register](http://localhost:3001/register) and create a new user. If everything goes well you'll be logged in using the newly created user.

This completes the setup and your app is running on local!
