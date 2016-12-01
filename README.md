# Programming Practice

[![Build Status](https://travis-ci.org/amrtgaber/programming-practice.svg?branch=master)](https://travis-ci.org/amrtgaber/programming-practice) [ ![Codeship Status for amrtgaber/programming-practice](https://app.codeship.com/projects/2d04db70-c14f-0133-84a7-7a084011ffad/status?branch=master)](https://app.codeship.com/projects/137470)

Practice and test programming problems.

It's recommended to come up with the algorithm and write the code out by hand before implementing the solution.

## Instructions

1. Install [node](https://nodejs.org)
2. `npm install`
3. `npm test`

## Scripts

```bash
npm run lint
npm test
npm run cover
```

There is also a test watch script.

```bash
npm run test:watch
```

## Adding new problems

Test script runs every .spec.js file in the project. Add new problems by creating a .spec.js along with any file or folder structure that clearly encapsulates the problem.
