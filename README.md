# Server application for CS Project

- [Server application for CS Project](#server-application-for-cs-project)
  - [Requirements ⚙️](#requirements-️)
  - [Starting the project 🛠](#starting-the-project-)
  - [Server structure 🔒](#server-structure-)
    - [ER Diagram of the database](#er-diagram-of-the-database)
  - [Deploy 🚀](#deploy-)
    - [](#)

## Requirements ⚙️

- Node v16.14.x
- Npm v8.3.x

You can install Node.js with npm [here](https://nodejs.org/download/release/v16.14.0/).

## Starting the project 🛠

In your preffered terminal do:

1. `git clone git@github.com:rokaskasperavicius/cs-project-server.git`
2. `cd cs-project-server`
3. `npm install`
4. `npm run dev`
5. Wait a few seconds for babel to transpile the code
6. Open [http://localhost:5000/](http://localhost:5000/) to see the server application

## Server structure 🔒

`index.js` is the starting file

### ER Diagram of the database

![Alt text](public/ER.png?raw=true 'Title')

## Deploy 🚀

Deployment happens automatically when the `main` branch receives new commits.

The website can be found [here](https://cs-project-server.herokuapp.com/).

###
