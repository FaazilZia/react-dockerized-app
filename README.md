# react-dockerized-app

A single-repository setup for a React frontend with Docker multi-stage build configuration.  
Streamlined for local and containerized development using GitHub Codespaces.

## Features

- React app (bootstrapped with Create React App)
- Production-ready NGINX web server via multi-stage Docker build
- Quick local development and deployment

## 🚀 Quick Start
Clone the repository and start the dev environment:
cd my-react-app
npm start

### Docker Build & Run
docker build -t react-dockerized-app .
docker run -p 80:80 react-dockerized-app

text
Visit the forwarded port in your browser to see the app running in Docker.

## More Info

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### CRA Documentation

- Docs: [Create React App Docs](https://facebook.github.io/create-react-app/docs/getting-started)
- React Docs: [React documentation](https://reactjs.org/)

Save the file.
In your terminal, run:

bash
git add README.md
git commit -m "Customize README for Dockerized React app"
git push
