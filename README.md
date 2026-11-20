# Student Registry

A small web application for managing a student registry, created as a practical exercise during the SoftUni QA training program.

The project uses Node.js and Express, renders pages with Pug, and separates request handling from the student data model.

## Technology

- Node.js
- Express.js
- Pug
- Mocha
- JavaScript

## Application

The application includes pages and routes for:

- Viewing the home page and student registry
- Viewing an About page
- Opening the Add Student form
- Adding a student using name and email
- Validating required fields before accepting a submission

Student data is loaded from the JSON file in the models directory.

## Project Structure

```text
.
├── controllers/
│   └── students-controller.js
├── models/
│   ├── students-model.js
│   └── students.json
├── views/
├── tests/
├── index.js
└── package.json
```

The controller configures the application routes and renders Pug views. The model loads the initial student data from JSON.

## Getting Started

### Prerequisites

- Node.js
- npm

### Install dependencies

```bash
npm install
```

### Run the application

```bash
npm start
```

The application defaults to port `8080`. A port can also be supplied as a command-line argument or through the `PORT` environment variable.

Open http://localhost:8080 in your browser.

## Tests

Run the test suite:

```bash
npm test
```

The test command is configured to run the JavaScript tests in the `tests/` directory with Mocha.

## Learning Objectives

This exercise demonstrates:

- Basic Node.js and Express application structure
- MVC-style separation between controllers, models, and views
- Server-side rendering with Pug
- Handling HTTP GET and POST requests
- Form input validation
- Running automated tests with Mocha

## Context

This repository is a training exercise completed as part of the SoftUni QA program. It is intended to demonstrate learning and practice rather than represent a production-ready application.
