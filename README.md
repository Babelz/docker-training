# Docker entrypoint and server exercises

## Exercise 1

1. Create a folder **cmd**, that contains two files: **Dockerfile** and **index.js**.
2. To **index.js**, add printing the first command-line parameter in format "Hello ${param}!".
3. Write a Dockerfile that runs that file (as an entrypoint).
4. Add a command-line parameter to the **docker** command execution and make sure it prints "Hello ${param}!", e.g. "Hello world!".

## Exercise 2

1. Create a folder **cmd**, that contains three files: **Dockerfile**, **package.json** and **server.js**.
2. Add [express](http://expressjs.com/) or [koa](http://koajs.com/) to **package.json**.
3. Install [npm](https://www.npmjs.com/) dependencies
4. Make **server.js** answer to endpoint **/** and return "Hello world".
5. Add [node](https://nodejs.org/), **package.json** and **server.js** to **Dockerfile**
6. Run server using **docker**.

## Exercise 3

Add **docker-compose.yml** to exercise 2 and run the server through that.
