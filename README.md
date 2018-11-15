# Simple API Demo
[![CircleCI](https://circleci.com/gh/adidas-group/demo-simple-api.svg?style=svg)](https://circleci.com/gh/adidas-group/demo-simple-api)

Demo of a Simple API including CI/CD tests and Apiary integration.

## API Documentation
See the documentation at [Apiary.io](http://docs.demosimpleapi.apiary.io/#)

## Tests
The API Description contract (swagger.yaml) is used to test the implementation (sever.js) with the [Dredd](https://github.com/apiaryio/dredd) CLI testing tool.

The tests can be run locally by typing `dredd` in the project directory (requires a Node.js and Dredd installation).

The test are run in a CI system [CircleCI](https://circleci.com/). You can see the full listing ot test runs at <https://circleci.com/gh/adidas-group/demo-simple-api>.
