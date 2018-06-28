# Setting Up FullStack WebDev Project with Vue.js and Express.js

## Setting Up Client

```bash
# install vue-cli
npm install -g vue-cli

# use vue-cli to initialize project
vue init <template-name> <project-name>

# use below command to list available templates
vue list

# install dependencies
npm install

# serve with hot reload at localhost
npm run dev

# install axios for making http requests
npm install --save axios
```

## Setting Up Server

```bash
# initialize server folder
npm init

# install nodemon and eslint
npm install --save nodemon eslint

# initialize eslint
node ./node_modules/eslint/bin/eslint.js --init

# add below scripts in package.json
"start": "./node_modules/nodemon/bin/nodemon.js src/app.js --exec 'npm run lint && node'"
"lint": "./node_modules/.bin/eslint **/*.js"

# create src folder in server folder
mkdir src

# create app.js in src folder
touch app.js

# start server
npm start

# install dependencies
npm install --save express body-parser cors morgan

```
