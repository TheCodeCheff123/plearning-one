# plearning-one

Practicing my git hub skills and learning more about javascript

while using the es 6 module of import and export
i encountered an issue of a node js warning. Here is how to solve the issue
got to the package.json file and input this
{
  "type": "module"
}

Node doesn't know i am using es modules. the above code tells node that.
this is what the code looks like now

{
  "name": "plearning-one",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "type": "module",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}
i noticed when importing funtions you can add 2 or more functions together like this 
import {generateRandomNumbers, subtract} from './utils.js'

Note: Math.floor() rounds up the number to a whole number
Math.random() gives you random numbers from 1 to 9
