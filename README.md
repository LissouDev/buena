## Description

This project displays the Buena website. It contains backend & frontend and has for goal to showcase a multi-step form.

The main technology is:

- [NestJS](https://nestjs.com/)
- [Neon Postgres Database](https://console.neon.tech/)
- [Prisma](https://www.prisma.io/)
- [NextJS](https://nextjs.org/)
- [React](https://react.dev/)
- [Typescript](https://console.neon.tech/)

## Project local setup

First make sure you have the submodules up to date.

```bash
git submodule update --init
```

Then you need to install the dependencies in both backend and frontend folders.

```bash

$ cd buena-backend

$ npm install

$ npm run build

$ cd ../buena-frontend

$ npm install

$ npm run build

```

As the backend is not hosted (yet) it will not be possible to run simultanously frontend and backend without the .env file.

To start the app, run the following command in the frontend or backend folder:

```bash
$ npm run start
```

## In the Frontend

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

The form is available at [http://localhost:3000/form/](http://localhost:3000/form/).

## In the Backend

Example of request: GET http://localhost:4000/api/users

## Unit tests for frontend and backend

To run the tests, run the following command in the frontend or backend folder:

```bash
$ npm run test
```

## Deployment

WIP - The app is deployed on AWS Amplify.

## Screenshots

![start client](./assets/start_and_test_client.png)
![start server](./assets/start_and_test_server.png)
![GET request](./assets/GET_request.png)
![UI](./assets/ui_client.png)
![UI form step 1](./assets/ui_client_form_step1.png)
![UI form error](./assets/ui_client_form_error.png)
