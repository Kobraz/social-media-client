# social-media-client

Repo is forked from Noroff.

The following scripts are set to run:
"scripts": {
    "build": "sass src/scss:dist/css",
    "start": "sass --watch src/scss:dist/css & live-server",
    "test": "npm run test-unit",
    "test-unit": "jest",
    "format": "prettier -w src/**/*.js",
    "lint": "eslint src/**/*.js",
    "lint-fix": "eslint src/**/*.js --cache --fix",
    "prepare": "husky install"

The following devDependencies are installed:
"devDependencies": {
    "@babel/core": "^7.19.3",
    "@babel/preset-env": "^7.19.4",
    "eslint": "^8.53.0",
    "eslint-plugin-jest": "^27.6.0",
    "husky": "^8.0.3",
    "jest": "^29.7.0",
    "lint-staged": "^15.0.2",
    "live-server": "^1.1.0",
    "prettier": "^3.0.3",
    "sass": "^1.54.8"

The following dependencies are installed:
"dependencies": {
    "bootstrap-dark-5": "^1.1.3",
    "give-me-a-joke": "^0.5.1"

The following lint-stages are installed:
"lint-staged": {
    "*.js": [
      "prettier --write",
      "eslint --fix"
    ],
    "*.html": [
      "prettier --write"
    ],
    "*.scss": [
      "prettier --write"
    ]
  }
