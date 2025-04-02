# JavaScript Webpack Boilerplate

JavaScript Webpack Boilerplate is a template repository to quickly start a new bundled Vanilla JS project.

## Getting started

`npm install` - to install all needed dependencies.

This boilerplate repository also includes Jest for code testing and babel for compiling.

### Run development environment

`npm run dev` - starts the development environment with webpack local server with auto reloading. Open [http://localhost:8080](http://localhost:8080) to view it in the browser.

### Scripts

- `build` - Creates build
- `dev` - Runs the environment
- `deploy` - Deploys changes to the gh-pages branch
- `test:watch` - Runs the Jest test suite in watch mode
- `eslint` - Runs ESLint for all JS files

### Tech Stack

#### Webpack

JavaScript Webpack Boilerplate uses [Webpack](https://webpack.js.org/) to bundle your application.

#### Jest

JavaScript Webpack Boilerplate uses [Jest](https://jestjs.io/) as the testing suite. All tests can be found with .test. postfix.

#### Babel

JavaScript Webpack Boilerplate uses [Babel](https://babeljs.io/) to transpile
our code to es5 code that old browsers can understand.
Also Babel with babel-jest package allows us to use ESM modules with Jest instead of CommonJS.

#### ESLint and Prettier

JavaScript Webpack Boilerplate uses [ESLint](https://eslint.org/) to test our code syntax and help us fix and prevent bugs. JavaScript Webpack Boilerplate uses [Prettier](https://prettier.io/) to automatically format our JS code and ensure code consistency.

#### Sass

JavaScript Webpack Boilerplate uses [Sass](https://sass-lang.com/)
with its scss syntax for compiling advanced scss files into standard CSS3.
