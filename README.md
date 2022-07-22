# Finance Test Task

## Main features

- application is connected to the locally running service
- application renders price changes for some tickers in real time
- application compares previous and actual 'change percent' value and highlights positive or negative trends in the prices on the UI in realtime
- data loading foresees 3 states: loading, success and error
- reducer and components were tested with React Testing Library
- application has responsive web-design

Used technologies:

- React (with hooks)
- Redux (with Redux-Thunk)
- Socket.io
- CSS Modules
- React Testing Library

## Running the local service

1. Open a new bash shell
2. `cd server`
3. `npm install` or `yarn install`
4. `npm run start` or `yarn start`
5. You can visit [http://localhost:4000](http://localhost:4000) to check that the service is working correctly and inspect the data it produces.

## Run application

1. Open a new bash shell
2. `cd client`
3. `npm install` or `yarn install`
4. `npm run start` or `yarn start`

## Run the tests

1. Open a new bash shell
2. `cd client`
3. `npm run test` or `yarn test`
