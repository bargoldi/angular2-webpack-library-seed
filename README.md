# angular2-webpack-library-seed
Angular2 library seed - based on Webpack

## Getting started
```bash
$ git clone https://github.com/bargoldi/ng2-package-starter
```
```bash
$ cd project_directory
```
```bash
$ npm install
```
## Usage
In order to run a webpack dev-server, use the command:
```bash
$ npm start
```
## Running tests
```bash
$ npm test
```

## Directory Structure
```
├───config
│       karma.conf.js
│       root-helper.js
│       webpack.common.js
│       webpack.dev.js
│       webpack.test.js
│
├───demo
│   │   index.html
│   │   polyfills.ts
│   │   tsconfig.json
│   │   vendor.ts
│   │
│   ├───app
│   │   │   app.component.css
│   │   │   app.component.html
│   │   │   app.component.ts
│   │   │   app.module.ts
│   │   │   main.ts
│   │   │
│   │   └───shared
│   │           shared.module.ts
│   │
│   ├───assets
│   │   │   data.json
│   │   │
│   │   └───svg
│   │           more.svg
│   │
│   └───css
│           main.css
│
└───src
│       main.ts
│   .gitignore
│   .npmignore
│   gulpfile.js
│   karma.conf.js
│   package.json
│   README.md
│   tsconfig.aot.json
│   tsconfig.json
│   webpack.config.js
```
## Configuration