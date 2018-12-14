Real-time Chat Application
=========================================

Both server and client side are written using `TypeScript`, `Node.js`, `Angular Framework`, `Angular Material`, `Socket.io`.

# Running Server and Client locally
## Requirements

Ensure you have the following installed:

1. Node.js - Download and Install latest version of Node: [NodeJS](https://nodejs.org)
2. Angular CLI - Install Command Line Interface for Angular [Angular CLI](https://cli.angular.io/)

## Clone repository

To start the project use:

```bash
$ git clone https://github.com/StasKuzichev/chat-app
$ cd chat-app
```

## Run Server

To run server locally:

```bash
$ cd server
$ npm install -g gulp-cli
$ npm install
$ gulp build
$ npm start
```

Server defaults to run on port `8080`

## Run Angular Client

Open other terminal and run following:

```bash
$ cd client
$ npm install
$ ng serve
```

Now open your browser in following URL: [http://localhost:4200](http://localhost:4200/)
