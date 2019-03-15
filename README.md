# monotype
Code refactoring 

Installation
1. npm init
2. npm install node-sass
3. In the scripts section add an scss command, under the test command, as it’s shown below:
    "scripts": {
      "test": "echo \"Error: no test specified\" && exit 1",
      "scss": "node-sass --watch scss -o css"
    }
4. To execute our script, we need to run the following command in the terminal: 
  # npm run scss
  
