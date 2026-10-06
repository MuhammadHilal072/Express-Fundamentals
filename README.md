# Express Fundamentals

Notes and practice projects from my journey learning Express.js.

## Topics covered

| `ExpressDir` | Express basics, routing, request handling | `index.js` |
| `EJSDIR` | Server-side templating with EJS (`views/`) | `index.js` |
| `MIDDLEWARES` | Writing middleware, custom error handling (`ExpressError.js`) | `app.js` |
| `REST_CLASS` | REST principles and a RESTful app with views and static files (`public/`) | `index.js` |

## Tech

Node.js, Express, EJS

## How to run

Each folder is a separate project with its own dependencies. For example:

    cd ExpressDir
    npm install
    node index.js

For MIDDLEWARES, use `node app.js` instead. Then open the local port printed in the terminal, or check the `app.listen(...)` line in the entry file.

## Author

Muhammad Hilal