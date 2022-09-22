# React (Framework for JavaScript):

In order to learn react I will follow [this tutorial](https://reactjs.org/tutorial/tutorial.html) from the oficial website of React.

## How to install Node js: 

update ``apt`` - apt is a command-line utility for installing, updating, removing, and otherwise managing deb packages on Ubuntu, Debian, and related Linux distributions.
```
sudo apt update
```
Install Node js:
```
sudo apt install nodejs
```
Check that the install was successful by querying node for its version number:
```
node -v
```

If the package in the repositories suits your needs, this is all you need to do to get set up with Node.js. In most cases, you’ll also want to also install npm, the Node.js package manager. You can do this by installing the npm package with apt:
```
sudo apt install npm
```
Info: https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04

## Create a React App:

[Create React App](https://github.com/facebook/create-react-app) is a comfortable environment for learning React, and is the best way to start building a new single-page application in React.

It sets up your development environment so that you can use the latest JavaScript features, provides a nice developer experience, and optimizes your app for production. **You’ll need to have Node >= 14.0.0 and npm >= 5.6** on your machine. 
To create a project, run:

```
npx create-react-app my-app
cd my-app
npm start
```
> **Note:** ``npx`` on the first line is not a typo — it’s a **package runner tool** that comes with npm 5.2+.

Create React App **doesn’t handle backend logic or databases**; it just creates a ``frontend`` build pipeline, so you can use it with **any backend you want**. Under the hood, it uses [Babel](https://babeljs.io/) and [webpack](https://webpack.js.org/), but you don’t need to know anything about them.

When you’re ready to deploy to production, running npm run build will create an optimized build of your app in the build folder. You can learn more about Create React App [from its README](https://github.com/facebook/create-react-app#create-react-app--) and the [User Guide](https://create-react-app.dev/).

## What Is React?

React is a declarative, efficient, and flexible ``JavaScript library`` for building user **interfaces**. It lets you compose complex UIs from small and isolated pieces of code called **“components”**.

React es una biblioteca Javascript de código abierto diseñada para crear interfaces de usuario con el objetivo de facilitar el desarrollo de aplicaciones en una sola página. Es mantenido por Facebook y la comunidad de software libre. En el proyecto hay más de mil desarrolladores libres.
--> [Wikipedia info](https://es.wikipedia.org/wiki/React)

More info: [W3schools](https://www.w3schools.com/whatis/whatis_react.asp)
