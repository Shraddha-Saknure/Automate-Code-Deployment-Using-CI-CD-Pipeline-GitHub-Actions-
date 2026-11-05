# DevOps Internship Task 1

## Objective
Automate code deployment using a CI/CD pipeline with GitHub Actions.

## Project Overview
This project is a simple Node.js demo application used to demonstrate a basic DevOps workflow:
- checkout code from GitHub
- set up Node.js
- install dependencies
- run tests
- build the application
- simulate Docker build
- simulate deployment

## Tech Stack
- Node.js
- GitHub
- GitHub Actions

## Project Structure

```text
ElevateLabs-DevOps-Task1/
├── app.js
├── package.json
├── README.md
└── .github/
    └── workflows/
        └── main.yml
```

## Run Locally

```bash
npm install
npm start
```

## Verify Build and Tests

```bash
npm test
npm run build
```

## CI/CD Workflow
The GitHub Actions workflow defined in `.github/workflows/main.yml` performs the following steps:
1. Checkout code
2. Set up Node.js
3. Install dependencies
4. Run tests
5. Build application
6. Simulate Docker build
7. Simulate deployment

## Author
Shraddha Saknure

