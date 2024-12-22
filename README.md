# Node.js Server Hang Issue

This repository demonstrates a common issue in Node.js servers: hanging on long-running requests.  The `bug.js` file contains code that simulates a long-running task within a request handler. This results in the server becoming unresponsive to subsequent requests.

The `bugSolution.js` file presents a solution that uses asynchronous operations and event loops to prevent the server from blocking on long-running tasks.