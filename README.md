# LAB - 00

## Proof of Life Server

### Author: Antonella Gutierrez

### Links and Resources
* [submission PR](https://github.com/antonella-401-advanced-javascript/lab-00/pull/1)
* [travis](https://travis-ci.com/antonella-401-advanced-javascript/lab-00)
* [front-end](https://antonella-lab00.herokuapp.com/) (when applicable)

#### Documentation
* [jsdoc](https://antonella-lab00.herokuapp.com/docs/) (Server assignments)

### Modules
#### `pos.js`
##### Exported Values and Methods

###### `isAlive(dead) -> boolean`
Returns true/false to indicate how the server works

### Setup
#### `.env` requirements
* `PORT` - Port Number

**or, include an `.env.example`**

#### Running the app
* `npm start`
* Endpoint: `/`
    * Returns a boolean
* Endpoint: `/docs`
    * Returns JSDoc documentation pages
  
#### Tests
* Unit Tests: `npm test`
* Lint Tests: `npm run lint`

#### UML
![UML Diagram](uml.png)
