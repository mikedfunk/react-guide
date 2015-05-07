Using [this guide](http://facebook.github.io/react/docs/tutorial.html) to create a [React](http://facebook.github.io/react/) app.

This uses [json-server](https://github.com/typicode/json-server) to serve a quick,
fake API and the example html page. The app is divided into several nested
react classes. It polls the json API every 2 seconds to refresh the DOM. It
also posts to the API when you fill out the form and updates the DOM.

## Setup

1. `npm install`
2. `bower install`
3. `json-server comments.json`
4. browser to [http://localhost:3000/example.html](http://localhost:3000/example.html)
