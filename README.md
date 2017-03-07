# angular2-webpack-library-seed
Angular2 library seed - based on Webpack

## Getting started
```bash
$ git clone https://github.com/bargoldi/ng2-package-starter
$ cd project_directory
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

## Publishing
```bash
$ npm run bundle
$ npm publish
```

## Bundle Structure
```
├───bundles
│       bundle.umd.js
│       bundle.umd.js.map
│
├───src
│       source files
│
│  .npmignore
│  LICENSE.txt
│  package.json
│  README.md

```

## Notes:
* You may and should change your umd file name in webpack.aot.js configuration (Don't forget to change the name in your `main` configuration in package.json)
* `ngc` doesn't support template and styles inlining therefore if you would like to publish the package to both ``SystemJS`` and ``Webpack``, you might need to inline the templates yourself

## Directory Structure
```
├───config
│       karma-test-shim.js
│       karma.conf.js
│       root-helper.js
│       webpack.aot.js
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
│   │   │   app.component.html
│   │   │   app.component.ts
│   │   │   app.module.ts
│   │   │   main.ts
│   │   │
│   │   └───shared
│   │           shared.module.ts
│   │
│   ├───assets
│   │       data.json
│   │
│   └───css
│           main.css
│
├───src
│       main.ts
│   .gitignore
│   .npmignore
│   karma.conf.js
│   LICENSE.txt
│   package.json
│   README.md
│   tsconfig.aot.json
│   tsconfig.json
│   webpack.aot.config.js
│   webpack.config.js
```
## Coming Soon
- Webpack bundling ability