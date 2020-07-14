# Unit2-Unit3-Web-TakeHome

## Running this project

The front end is set up with [Parcel Bundler](https://parceljs.org/), a library that compiles our assets and comes with an integrated development server with auto-reload. This server runs on port `1234` by default, but will use another if `1234` is being used by another application.

The "quotes" API runs on port `3333` which needs to be free, or this server won't be able to start.

- Clone the repo.
- Navigate into the project folder.
- Run `npm install` to download the project's dependencies.
- Run `npm run api` to start the "quotes" API locally on `http://localhost:3333/api/quotes`.
- Run `npm run react` to build the React project and serve it on `http://localhost:1234`.
- Run `npm test` to run tests using Cypress (optional).

## Task A

### Task A Summary

Complete eight callbacks so the React app is able to work like in [this video](https://youtu.be/IGB39rc4SZA).

### Task A Instructions

- Read `server.js` to understand how each endpoint works. Testing the API with [Postman](https://www.postman.com/downloads/) before starting to write code is highly recommended. The project has no database, so restarting the `api` script returns the quotes to their original state.

- There is a total of **eight callbacks** (tasks 1 through 8) that need to be completed. They are found inside the `Container.js` and `Form.js` components. Each callback includes a log statement with specific instructions. You can tackle the tasks in any order you wish. You do _not_ need to touch any code outside of these callbacks.

## Task B (optional)

### Task B Summary

Use **Redux** to manage application state.

### Task B Instructions

- Add `redux` and `react-redux` to the project, and use them to centralize application state inside a Redux store.
- Connect the `Container.js` component so it receives state and action creators **through props**.
