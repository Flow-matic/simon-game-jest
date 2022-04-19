# simon-game-jest

jest was failing as if it wasn’t installed.

How can I avoid "No test specified" errors in npm?

issue that I solved by adding the below code.

You didn't specify which testing framework you're using such as Jest or Mocha.

In case of Jest, add this in your package.json:

"scripts" : { 
    "test" : "jest" 
 }