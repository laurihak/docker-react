# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:
### `npm install`

Install the projects dependencies.

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

## Set up for docker

You need node to install and run the project, for example node:alpine from dockerhub. \
If you are running on node alone you need to first copy/fork the project to your host machine. \
Then you can use Dockerfile to copy the project straight to the image.

If you are running image on linux you can install git and copy the project in the image. \
You will still need to install node to your image so the dependencies can be installed and the app can be ran.


