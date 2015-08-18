# bas-web-ser

Basic Web service is a simple web service implementation providing a collection of basic backend and frontend implementation and set of tools & technologies.  

It is mainly aimed for starting point for developing (and learning) something about web services.

Basic Web Service implementation is based on following Frameworks, Libs & Tools

* [NodeJs](https://nodejs.org/)
* [ExpressJs](http://expressjs.com/)
* [Polymer 1.0](https://www.polymer-project.org/1.0/)
* [Typescript](http://www.typescriptlang.org/)
* [Jade](http://jade-lang.com/)
* [Gulp](http://gulpjs.com/)
* [Bower](http://gulpjs.com/)
* [npm](https://www.npmjs.com/)


## Status
Initial version without any really important stuff like testing, tslint, uglify, database example. They will follow...
Also, not much CSS stuff, I will someday take a look of LESS and use it in somewhere


## Project Structure
This repository contains necessary files for fetching backend, frontend and typedefinitions from their own sub-repositories.

Might feel little bit overkill for now, but if and when the simple components starts to grow and starts to live their own life...

## How to get started
* install nodejs, bower...
* $ git clone https://github.com/arikekalainen/bas-web-ser.git
* $ cd bas-web-ser
* $ git submodule update --init
* $ cd bas-web-ser-example-app
* $ npm install
* $ gulp
* $ cd release
* $ nodejs backend/main.js
* Open web browser and surf to http://localhost:3000

Enjoy! I will.
