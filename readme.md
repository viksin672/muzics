# :musics

https://muzics.herokuapp.com

A music app made with React + Redux + Nodejs



## Features
* login to create and listen to your playlists
* download song when you are logged in
* paginated fetching
* player play/stop/forward/backward track
* search tracks by name and artist

## Installation
### To run the app with Node.js and MongoDB
> This app will fetch tracks from an external api, so there is no need for a database to store tracks, but we still need one for creating user's playlists

Install and start MongoDB (https://docs.mongodb.org/manual/installation).

Install Node.js (http://nodejs.org). Any version above 6.0 works fine


1. Run `npm install`.

2. Run `npm run dev:client` to start the frontend server

Wait for the build process to complete


3. Run `npm run dev:server` to start the api server

Navigate to http://localhost:8000 in your browser to explore the app

## Build the app
* Build manually
```
 $ npm start
```


After building the app, frontend and backend servers will be merged into a single server and be available at http://localhost:5000
