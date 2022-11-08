# Anythink Frontend

The Anythink Frontend is an SPA written with [React](https://reactjs.org/) and [Redux](https://redux.js.org/)

## Getting started

Make sure your server is up and running to serve requests.
Go ahead and create your own codespace , I'll wait.

(No need to change anything in the default options, just click on the Create codespace button and wait for it to boot)

Great! Looks like your codespace is up and running. You can now run docker-compose up in your codespace's terminal to load Anythink's backend and frontend.

Once docker-compose finishes loading up, the backend should be running and able to connect to the database.

After the server is up, make sure you test it by pointing your browser to https://Git-username-vigilant-space-6qpq79wgxvj345g6-3000.preview.app.github.dev/api/ping

Easy Peasy! The backend is up and running.

Now, it’s time to check the frontend and make sure it’s connected to the backend.

If everything is working properly, you’ll be able to create a new user on https://samardis-01-maxx-vigilant-space-6qpq79wgxvj345g6-3001.preview.app.github.dev/register

Create one (choose a cool nickname and everything) and you’ll be able to move to the next task.

Just make sure that you run all scripts in the next quests on one of the containers created by docker-compose up.  Also, you can use docker exec to run commands on a running container.

It looks like your environment is ready! 😀

## Pages overview

- Home page (URL: /#/ )
  - List of tags
  - List of items pulled from either Feed, Global, or by Tag
  - Pagination for list of items
- Sign in/Sign up pages (URL: /#/login, /#/register )
  - Use JWT (store the token in localStorage)
- Settings page (URL: /#/settings )
- Editor page to create/edit articles (URL: /#/editor, /#/editor/slug )
- Item page (URL: /#/item/slug )
  - Delete item button (only shown to item's author)
  - Render markdown from server client side
  - Comments section at bottom of page
  - Delete comment button (only shown to comment's author)
- Profile page (URL: /#/@username, /#/@username/favorites )
  - Show basic user info
  - List of items populated from seller's items or user favorite items
