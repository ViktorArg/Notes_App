# Notes_App


This is a second project using typescript with React and Redux. It's a simple app where you can write and list of notes.

There will be future features in this app.


## Available Scripts

To run the project go to react-redux-typescript directory and write the commands. 

### `npm install` 

      then

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\



## Server

To get database notes from the console, write the commant:

curl http://localhost:4000/notes/new

To post notes into database from the console, write the commant:

curl --header "Content-Type: application/json" --request POST --data '{"text": "Hello express js with lowdb"}'  http://localhost:4000/notes/new
