# photos-app
Paginated viewing gallery of publicly available images.

## Getting started
The client and server projects are broken into separate folders `client` and `server`.
- Inside of `client` you'll find a basic react app created through create-react-app.
- Inside of `server` you'll find a basic express/node server.

## Installing dependencies
First, in order to run locally you'll need to install depencies in both the root directory and `client`
- `yarn install` (root)
- `yarn install` (/client)

## Project build instructions
If you'd like to to run the full project (client + server) from the root directory, you can run:

### `yarn build`
- Compiles typescript server code inside /dist output folder

### `yarn server`
- Concurrently compiles typescript server code in watch mode and starts express server
- Open [http://localhost:3001](http://localhost:3001) to hit it from the browser.
- The server will reload when you make changes.\
- You may also see any lint or loading errors in the console.

### `yarn client`
- Runs client react app (same as running `yarn start` from inside /client folder).
- See "Client build instructions" below for more info.

### `yarn dev`
- Concurrently runs `yarn server` and `yarn client` above.
- The server code will compile and start up followed by [http://localhost:3001](http://localhost:3001) being opened up automatically in your browser.


## Client build instructions
If you'd like to run the client separately without the server code you can run the following:

### `yarn start`
- Runs the app in the development mode.\
- [http://localhost:3000](http://localhost:3000) will be opened up automatically to view in your browser.
- The page will reload when you make changes.\
- You may also see any lint errors in the console.

### `yarn test`
- Launches the test runner in the interactive watch mode.\

### `yarn build`
- Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.
- The build is minified and the filenames include the hashes.\
- Your app is ready to be deployed!
