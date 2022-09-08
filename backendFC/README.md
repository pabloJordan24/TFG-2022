# REFUEL

NodeJS + Express API for our STW project. It uses MongoDB as database.

# Pre-requisites

- Install [Node.js](https://nodejs.org/en/) version 15.0.0

# Getting started

- Clone the repository

```
git clone https://github.com/STW2022/backend
```

- Install dependencies

```
cd backend
npm install
```

- Build and run the project

```
npm start
```

Navigate to `http://localhost:3003`. Problem? You will need .env file.

- API Document endpoints

/api-doc

# Getting started 2

You can fire up our API by clicking [here](https://reloop-back.herokuapp.com/api-doc)

## Project Structure

The folder structure of this app is explained below:

| Name                | Description                                                                                                |
| ------------------- | ---------------------------------------------------------------------------------------------------------- |
| **node_modules**    | Contains all npm dependencies                                                                              |
| **src**             | Contains source code that will be compiled.                                                                |
| **src/controllers** | Controllers define functions to serve various express routes.                                              |
| **src/routes**      | Contain all express routes with endpoint documentation.                                                    |
| **src/models**      | Models define schemas that will be used in storing and retrieving data from Application database (MongoDB) |
| **src/cron**        | Where periodic work is implemented                                                                         |
| app.js              | Entry point to express app                                                                                 |
| package.json        | Contains npm dependencies                                                                                  |
