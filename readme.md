# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Set up code environment first. Clone repo. Download dependencies.

Run docker-compose up in your codespace's terminal to load Anythink's backend and frontend.

Once docker-compose finishes loading up, the backend should be running and able to connect to the database.

After the server is up, make sure you test it by pointing your browser to https://Git-username-vigilant-space-6qpq79wgxvj345g6-3000.preview.app.github.dev/api/ping

Easy Peasy! The backend is up and running.

Now, it’s time to check the frontend and make sure it’s connected to the backend.

If everything is working properly, you’ll be able to create a new user on https://samardis-01-maxx-vigilant-space-6qpq79wgxvj345g6-3001.preview.app.github.dev/register

Create one (choose a cool nickname and everything) and you’ll be able to move to the next task.

Just make sure that you run all scripts in the next quests on one of the containers created by docker-compose up.  Also, you can use docker exec to run commands on a running container.

It looks like your environment is ready! 😀

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
