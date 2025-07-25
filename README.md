# TV Listings Generator

## Introduction

TV Listings Generator is a simple way to generate TV schedules for a series of weeks.

TV Listings Generator has the following goals:
* **Easy to repeat:** programmes with multiple episodes can be automatically placed over multiple days or weeks with a single click.
* **Process Automation:** Minimal user intervention is required - for example: programmes are automatically classified as new.
* **Intelligent:** Programmes can be fixed to repeat at a certain time and empty slots can only be filled by programmes with the required length. This minimises errors. 

TV Listings Generator has two components. An API server which manages the schedules and can be used by the Web App or any other external tool 
and a sample web app which enables user interaction.

### API Server

The API Server is built on top of NestJS: https://nestjs.com/

The current test API server can be run via the following command: 

`cd api`

`npm run start`

The API server is then reachable at the following address:
http://localhost:3001/

The Swagger documentation can be reached at the following URL:
http://localhost:3001/api/swagger-ui

### UI Web App

The Web App is built on top of React:
https://react.dev/

The current test Web App can be run via the following command:

`cd ui`

`npm run dev`

The Web App is then reachable at the following address: 
http://localhost:3000/