﻿# ivr-packages

How to use - const isIVR = require('ivr-func')
isIvr(string === "IVR") return boolean


How to publish -
1. Creating two folders:
 -- Test folder
 --package folder
 
2. Creating a new repository in git
3. Uploading package folder to git.
4. Creating index.js in the package folder
5. Writing the logics for the package
6. Exporting the module --> module.exports = <Function to export>.
7. npm link the package folder
8. Creating script.js inside the test folder.
9. npm link <package name>.
10. getting the package --> const isIVR = require('ivr-func').
11. If working, going back the package folder and deploying to git.
12. Ensure to discribe about the package in README.md file.
13. npm login or npm adduser before publish.
14. npm publish.
