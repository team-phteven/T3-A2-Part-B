# T3-A2-Part-B

This Repo is the overarching README for the submission of Term 3 Assessment 2 (Part B) by Stephen Smith and Riki Fujihara.

### Link to Frontend Repo: <a href='https://github.com/team-phteven/basil-frontend'>here</a>

### Link to Backend Repo: <a href='https://github.com/team-phteven/basil-backend'>here</a>

# Libraries used

The following libraries were used to create the app.

## Node

### What is Node?

Node is a Javascript runtime built based on Chrome's V8 engine. Javascript could originally only be run in the browser, but Node allows Javascript to be run in servers.

### How is Node used in the project?

Node was used to run the backend of the application. It serves as an API, taking incoming requests and responding with appropriate data/actions.

## Express

### What is Express?

Express is a flexible framework for building web applications which is imported into the Node backend to build out RESTful APIs.

### How is Express used in the project?

Express was used to create the API that handled all incoming requests from the front end.The server instance was created using express, as well as all middleware functions that executed actions in between requests and responses.

## React

### What is React?

React is a Javascript library used for building component-based and stateful front ends.

### How was React used in the project?

React was used to build all front end components in the app including sidebars, modals, avatars, forms and so forth. Context providers were key in keeping the front end in sync with the backend.

## MongoDB

### What is MongoDB?

MongoDB is a no-sql database which stores data by grouping individual 'documents' in 'collections', instead of relational tables.

### How was MongoDB used in the project?

MongoDB was the database of choice for the app.

## Mongoose

### What is Mongoose?

Mongoose is an Object Data Modeling library that creates a connection between MongoDB and Node. Although MongoDB is schemaless, Mongoose provides the ability to create schemas and relations.

### How was Mongoose used in the project?

Mongoose was used to create schemas for the models in the app (User, Conversation, Message) and the relations between them.

## Bcrypt

### What is Bcrypt?

Bcrypt is a password hashing function.

### How was Bcrypt used in the app?

Bcrypt was used to hash passwords entered by users so that the passwords are never stored as plain-text.

## Json web token

### What is Json web token?

Json web token is a library used for generating unique json tokens that are passed between the frontend and backend for authentication.

### How was Json web token used in the project?

Json web tokens were generated for the user upon login to provide authentication for what the user can and can't access.

## Cors

### What is cors?

Cors is a library that is used to configure cross origin resource sharing options.

### How was cors used in the project?

Cors was used to provide the Netlify front end access to make requests to the Heroku backend。

## Dotenv

### What is Dotenv?

Dotenv is a library that gets variables stored in a .env file for use in the source code.

### How was Dotenv used in the app?

Dotenv was used to load environment variables and secrets that should only ever be known by the backend.

## Socket.io

### What is socket.io?

Socket.io is a library used to handle web-sockets in the Node backend.

### How was socket.io used in the project?

Socket.io was used to create the socket actions, responses and events in the Node backend, particularly for responding to incoming instant messages.

## Socket.io-client

### What is socket.io-client?

Socket.io is a library used to handle web-sockets in the front-end.

### How was socket.io-client used in the project?

Socket.io-client was used to create the socket actions, responses and events in the React front end, particularly for emitting events when sending instant messages.

## Validator

### What is Validator?

Validator is a Javascript library used to provide validation of user input.

### How was Validator used in the project?

Validator was used to conveniently validate user input for things such as email validation, which meant complex regex wasn't needed.

## Bootstrap

### What is Bootstrap?

Bootstrap is a css library that provides pre-defined css classes for use on html elements.

### How was Bootstrap used in the project?

Bootstrap was imported into the front-end which enabled the use of react-bootstrap.

## React-bootstrap

### What is React-bootstrap?

React-bootstrap is a library which gives access to React-components styled using bootstrap.

### How was React-bootstrap used in the project?

React-bootstrap was used to create many of the front-end components such as buttons, modals and forms, and was also used to lay out the structure of the front-end using bootstrap's grid system.

## Axios

### What is Axios?

Axios is a library that is used to make HTTP requests.

### How was Axios used in the project?

Axios was used to make requests from the front-end. The requests utilised configuration, headers and promise-based syntax.

## Styled-components

### What is Styled-components?

Styled-components is a library that allows the creation of React components with css styling directly in the component.

### How was Styled-components used in the project?

Styled-components was used to provide css styling directly to react components in the app. It was also used to add to and override the default bootstrap styles provided by Bootstrap and React-bootstrap.

## Jest

### What is Jest?

Jest is a testing framework for Javascript.

### How was Jest used in the project?

Jest was used to create both unit and integration tests for various functions within the app.

## Luxon

### What is Luxon?

Luxon is a javascript library for manipulating and formatting dates in Javascript.

### How was Luxon used in the project?

Luxon was used particularly for formatting times that messages were sent.

## React-icons

### What is React-icons?

React-icons is a library that provides access to a huge selection of different icons that can be used in React front ends.

### How was React-icons used in the project?

React-icons was used to enhance the user interface by providing visually appealing images instead of text for some buttons and toggles.

# User Testing (in development)

<img src="docs/whole-page-dev.png" width="800px">

# User Testing (in production)

<img src="docs/whole-page-prod.png" width="800px">

# Project Management and Task Delegation Methodology

The Agile project management methodology was utilised in this project. Work was organised into sprints and executed accordingly. Tasks were delegated based on strengths and weaknesses of team members.

## First Sprint

<img src="docs/agile/group-1/3.png" width="800px">
<img src="docs/agile/group-1/1.png" width="800px">
<img src="docs/agile/group-1/2.png" width="800px">
<img src="docs/agile/group-1/4.png" width="800px">

## Second Sprint

<img src="docs/agile/group-2/5.png" width="800px">
<img src="docs/agile/group-2/3.png" width="800px">
<img src="docs/agile/group-2/2.png" width="800px">
<img src="docs/agile/group-2/4.png" width="800px">

## Third Sprint

<img src="docs/agile/group-3/8.png" width="800px">
<img src="docs/agile/group-3/1.png" width="800px">
<img src="docs/agile/group-3/2.png" width="800px">
<img src="docs/agile/group-3/3.png" width="800px">
<img src="docs/agile/group-3/4.png" width="800px">
<img src="docs/agile/group-3/5.png" width="800px">
<img src="docs/agile/group-3/6.png" width="800px">
<img src="docs/agile/group-3/7.png" width="800px">

## Fourth Sprint

<img src="docs/agile/group-4/6.png" width="800px">
<img src="docs/agile/group-4/5.png" width="800px">
<img src="docs/agile/group-4/4.png" width="800px">
<img src="docs/agile/group-4/3.png" width="800px">
<img src="docs/agile/group-4/2.png" width="800px">
<img src="docs/agile/group-4/1.png" width="800px">

## Fifth Sprint

<img src="docs/agile/group-5/11.png" width="800px">
<img src="docs/agile/group-5/10.png" width="800px">
<img src="docs/agile/group-5/9.png" width="800px">
<img src="docs/agile/group-5/8.png" width="800px">
<img src="docs/agile/group-5/7.png" width="800px">
<img src="docs/agile/group-5/6.png" width="800px">
<img src="docs/agile/group-5/4.png" width="800px">
<img src="docs/agile/group-5/3.png" width="800px">
<img src="docs/agile/group-5/1.png" width="800px">

## Sixth Sprint

<img src="docs/agile/group-6/7.png" width="800px">
<img src="docs/agile/group-6/6.png" width="800px">
<img src="docs/agile/group-6/4.png" width="800px">
<img src="docs/agile/group-6/3.png" width="800px">
<img src="docs/agile/group-6/2.png" width="800px">

## Seventh Sprint

<img src="docs/agile/group-7/5.png" width="800px">
<img src="docs/agile/group-7/4.png" width="800px">
<img src="docs/agile/group-7/3.png" width="800px">
<img src="docs/agile/group-7/2.png" width="800px">
<img src="docs/agile/group-7/1.png" width="800px">

## Eighth Sprint

<img src="docs/agile/group-8/1.png" width="800px">
<img src="docs/agile/group-8/3.png" width="800px">
<img src="docs/agile/group-8/2.png" width="800px">
