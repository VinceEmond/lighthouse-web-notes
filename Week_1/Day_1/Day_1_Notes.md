# Day 1 Notes


## Command Line Args
### Passing Command Line Arguments in Node.js
#### Using process.argv:
* The first element of the process.argv array will always be a file system path pointing to the node executable. 
* The second element is the name of the JavaScript file that is being executed. And the third element is the first argument that was actually passed by the user.
* Use the following code to cycle through and print arguments to the console :
* [More Info Here](https://stackabuse.com/command-line-arguments-in-node-js)

 
``` javascript
'use strict';

for (let j = 0; j < process.argv.length; j++) {
    console.log(j + ' -> ' + (process.argv[j]));
}
```


