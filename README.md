# <p align="center">Sequelized Burger</p>

## Overview

This is a single page style web application that allows the user to "devour" preloaded burgers from a database then make them again if desired. It also allows a user to make a custom order(burger), add it to the page by using the input form then hit submit.

## How To Use

To run a local instance of this application clone the repo. Once cloned navigate the the folder in the terminal run `npm i` or `npm install` to load all the dependencies needed. In `mySQL workbench` copy and run `schema.sql` to create the database needed to run. After the database is created and the dependencies are installed, create a `.env` file with variables on `config/config.js` needed for the `SQL` server to run locally. When that is saved run the command `node server` to start the server then navigate to `localhost:8888/` and the page will be displayed.

To use as a web app [click this link](https://murmuring-wave-75224.herokuapp.com/ "Heroku Deployed Page") to the deployed page.

- On the app there are a few options.
  - Add a custom burger.
  - Devour a preloaded burger.
  - Make Again

## Technology Used

1. Node.js
2. Express.js
3. Sequelize
4. Handlebars
5. mySQL
6. jQuery

### Contributers

**Niles Bingham** - Full-Stack Developer
