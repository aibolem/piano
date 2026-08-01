# Piano Backend

This folder contains the code for the backend socket.io server.

## Developing

Run `pnpm install` to install dependencies.

Then run `pnpm dev` to start build and run in the background.

Run `pnpm build` to build the app for production. Then run `pnpm start` or `node build/index.js` to start the app in production.

# Piano

A fully featured piano with multiplayer and midi support able to be played
with a computer keyboard, mouse, midi keyboard, and touchscreen.

Live demo at https://aibolem.github.io/piano/index2.html

https://youtu.be/1f3L3tT0nS0


<img width="920" height="580" alt="image" src="https://github.com/user-attachments/assets/edb2b548-c058-469b-a436-694bccf3301b" />


## Structure

The project is seperated into two folders [frontend/](./frontend) and [backend/](./backend).

The frontend folder will contain the piano frontend website. This can just be
hosted somewhere statically able to serve files after building. The
`deploy-frontend` branch will contain the built version of the `main` branch.

The backend folder will contain the node.js backend server running socket.io. This needs
to be hosted somewhere able to run node.js (eg. Digitalocean droplet, heroku, etc.)

## Developing

To start developing, install [pnpm](https://pnpm.io/) then clone the
repo by doing `git clone https://github.com/Calbabreaker/piano --depth 1` then
read the README.md on each of the folders.

