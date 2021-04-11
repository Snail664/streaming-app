## About

Live Streaming operation built with React and Redux.
Managing CRUD operations with redux and redux-form.

Lightweight backend with NPM [json-server](https://www.npmjs.com/package/json-server) and [node-media-server](https://www.npmjs.com/package/node-media-server).

# Getting Started

- Clone this repository into local machine.

- Run `npm i` in all 3 sub directories to install dependencies.

- Create a `.env` file in the client directory.

- Create env variable `REACT_APP_GOOGLE_CLIENT` and provide your own api key for Google OAuth.

# Run Application

- Run `npm start` in all 3 sub directories.

# Streaming

Use a streaming application such as OBS

Steam on `rtmp://localhost/live`

Using the stream ID of your stream as the `stream key`.

Stream keys are stored in `/api/db.json` after stream has been created.
