[![Board Status](https://dev.azure.com/srinivaspeela/544b45c1-0270-490f-a30c-622414873f6e/cef68a1c-ef6e-4bdd-b91b-23b61048c470/_apis/work/boardbadge/089196d8-a856-4389-ab58-4be20d722b31)](https://dev.azure.com/srinivaspeela/544b45c1-0270-490f-a30c-622414873f6e/_boards/board/t/cef68a1c-ef6e-4bdd-b91b-23b61048c470/Microsoft.RequirementCategory)
Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

