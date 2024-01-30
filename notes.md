# freeCodeCamp.org - Book Store Project
# Instructor: Mohammed Taheri is a full stack developer
- Learn how to use the mernstack by creating a bookstore application. The MERN stack is a powerfuol blend of mongodb, a noSQL database, expess.js, a web framework react.js (a UI building JavaScript library) and node.js (a serer-side JavaScript environment) => together they provide a cohesive framework for building efficient, responsive web applications.
- => nmp i express nodemon
=============================================================================================================================
- going to create a basic bookstore project with MERN stack (MongoDB, Express.js, React and Node.js)
=============================================================================================================================
# Prerequisites
- JS
- React.js
- Node.js =>download => nodejs.org/en
- Visual Studio Code
- Browser =>chrome
=============================================================================================================================
- create a folder => BookStore-MERN-stack => create 2 folder (backend, frontend), create .git file, readme.md
- initialize the project => make sure you are on the backends folder =>terminal: cd backend => to go to backend folder
  - terminal: npm init -y => this command will add a package.json to the project
  - package.json => 
  {
  "name": "backend",
  "version": "1.0.0",
  "description": "",
  "type": "module", <= add this line => this line will allow us to use ecmascript syntax
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}

-  "type": "module", <= add this line => this line will allow us to use ecmascript syntax which is import keyword and Export keyword.
- Add 2 more packets to the project => express.js and nodemon => npm i express nodemon => use Express as our framework also use nodemon for restarting server automatically unchanged.
- add scripts to a script section in package.json

package.json
{
  "name": "backend",
  "version": "1.0.0",
  "description": "",
  "type": "module",
  "main": "index.js",
  "scripts": {
    "start": "node index.js",
    "dev": "nodemon index.js"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}

 // A start will run the project with Node.js environment, and then we learn the project with nodemon and we use this command in development
=============================================================================================================================