# Class 01 Node   

Node is a JS framework.  
Node functions on inputs, and outputs.  

## Node Modules  

Node Modules are:

* Shareable  
* installed via npm  
* or written ourselves  
* Communicates with another system.  
* include a package.json  
* import and export things (like code).

// import
let path = require('path');
//export  
module.export = 'Jacob'  

npm init to create a package.json.  
Having an index.js at the root of your module is good convention.  

 'use strict' is for strict keyword usage. Means you must define variables before you can use them.  

'use strict';
module.export = {
    name: 'Jacob'
};

use this module by:  

'use strict';  
const main = require('./jacob.js');
console.log(main);  

Always get small proofs of life througout your code.  
You can create a test file to test throughout.  

npm install jest  
describe ('Testing function x', () => {
    test('function x should produce y result', () => {
        expect(functionX(a, b)).toEqual(y)
    })
})  

describe box gives a place to describe what the tests are meant to do.  
and the test blocks describe the individual tests. 

Create folder named __tests__  
In package.json you must change test to jest --verbose --coverage  

npm install express cors dotenv  

## Express (HTTP REST Framework)  

REST = Representational State Transfer  

Requests should always have:  

* URL(Path)  
* Method of request(PUT)  

Responses should always have:  

* Data  
// test
'use strict';  

const supertest = require('supertest');  
const app = require('../server.js');
const request = supertest(app);

describe('Testing out HTTP Server, () => {
    test('Should return and object with name property'), () => {
        let response = request.get('/hello');
        expect(response.body.name).toEqual('Jacob');
        expect(response.status).toEqual(200);
    }
});  
install supertest
// supertest is like axios for testing  

// server.js  

'use strict';  
const express = require('express')  
const app = express();  

app.get('/hello', (request, response) => {
    response.json({
        name:'JACOB'
    });
});

//request parameter
app.get('/params/:name', (request, response) => {
    let name = request.params.name;
    response.json({
        name: name,
    })
})  

//query parameter  
app.get('/query', (request, response) => {
    let name =request.query.name;
    let role = request.query.rol;  
    response.json({
        name,
        role,
    })
})
module.exports = app;
