# shzware-framework
[![NPM](https://nodei.co/npm/@shzware-framework/main.png?stars&downloads)](https://nodei.co/npm/@shzware-framework/main/)  
Simple framework for JavaScript.

## Installation
For node.js, you can use this command to install:

    npm install @shzware-framework/main

## Usage
You could use like this:
```JavaScript
const framework = require("@shzware-framework/api");
```
## Example
```JavaScript
const api = require('@shzware-framework/api');

// getFrameworkVersion
console.log(api.frameworkVersion);

// getFrameworkAPIVersion
console.log(api.frameworkAPIVersion);

// Better logging system
api.log('Hello world!');

// Check if an npm module is installed
api.isInstalled('your module name here'); // return true if installed or return false if isn't installed

// Create a ASCII Table
const table = api.createAscii('your table name', 'heading name 1', 'heading name 2');

// Print ASCII Table
// With console.log()
console.log(table.toString());
// With api.log()
api.log(table.toString(), 'none'); // I added 'none' as second args to remove the date time at beginning to avoid the ascii table looking weird

// This Framework is currently under development stage
```

## License
The project is released under the [MIT license](http://www.opensource.org/licenses/MIT).
