Calculator.js: a node.js Demonstration Project
==============================================
An  example node.js project, including tests with mocha, that behaves like
a pocket calculator.

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a test coverage tool.

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

To deploly to Azure: (Uses azure.yml workflow)

1. Set up your Azure SPN in secrets
2. Create a release
