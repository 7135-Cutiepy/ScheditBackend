# ScheditBackend

Backend server written in Node.js for 

## Install Dependencies

To install dependecies (required to run the server), run `npm install`. This is assuming you already have NPM installed on your machine.

## Running the Server

To start up the server, run `npm start`. This will bring the server up at [localhost:3200](). Changes will be reloaded any time a file changes, thanks to Nodemon. All you have to do is refresh your browser. No need to restart the server manually on the command line.

## Routes

### /

Returns an index page...todo: get rid of this b.s.

### /schedule

Currently returns a string that says "fuck, dude". This route will be the basis for queing schedule creation, checking the status of a job, and returning schedules after they're created.