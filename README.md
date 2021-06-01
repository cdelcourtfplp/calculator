Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.
![Build Status](https://dev.azure.com/christophedelcourt/Agile%20Planning/_apis/build/status/cdelcourtfplp.calculator?branchName=master)]
![example workflow](https://github.com/github/docs/actions/workflows/main.yml/badge.svg)
The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

