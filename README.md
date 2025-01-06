# Express.js req.body undefined Issue

This repository demonstrates a common issue encountered when working with Express.js and JSON request bodies.  The problem lies in the improper placement or configuration of the `express.json()` middleware, leading to `req.body` remaining undefined even after a POST request with a JSON payload.

The `bug.js` file shows the flawed implementation, while `bugSolution.js` provides the correct solution.

## Setup

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install express`
4. Run the server using node (bug.js or bugSolution.js)