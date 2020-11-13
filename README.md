# Node-Express

Export info from one js file so that it can be accessed in another js file.
example

```js
module.exports = {
    beBasic, 
    add,
    subtract
}
```
Is going to export three functions created in js file called myModule.js . (beBasic, add and subtract)

```js
const { add, subtract, beBasic } = require('./myModule')
```
Will import those 3 functions to a new js file so they can be used.

Now instead of using browser to check console updates, just type node (document name) to view in terminal. ie. node index.js

Add a gitignore file to stop certain files to be uploaded to github when you push.
To add a git ignore file just enter ```touch .gitignore``` into the directory you need. then in the gitignore file add the names of the files that you dont want pushed to github.