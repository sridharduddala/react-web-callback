eServices web callback project uses following technologies:
* [React](https://github.com/facebook/react)
* [ES6 with Babel](http://babeljs.io)
* [Webpack](http://webpack.github.io) for module dependency resolution and bundling
* [Webpack Dev Server](http://webpack.github.io/docs/webpack-dev-server.html) for local testing
* [React Hot Loader](http://gaearon.github.io/react-hot-loader/) for updating React components in real time.
* [Jasmine](https://jasmine.github.io/) for behaviour driven unit tests.
* [Karma](http://karma-runner.github.io/0.13/index.html) for running unit tests.

### Usage

#Follow the following instructions to setup the project after checking out the code
#Run following command to install all the required modules
npm install
#Run the following command to start node server
npm start
#Default server is started on port 3000
# Open http://localhost:3000

### Linting
*[ESLint] (http://eslint.org/)
ESLint with React linting options have been enabled.

#Run following command to check java script syntax
npm run lint

### Testing

Start Karma test runner.

#This will run the tests only.
npm test

#Following command will auto watch all files for changes and rerun the tests. Can be used during development.
npm run test_watch

