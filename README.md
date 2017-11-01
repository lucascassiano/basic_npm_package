# basic_npm_package
a boilerplate for nom packages - for compile ES6 to ES5 

## dependencies 
```
npm install --save-dev babel-cli@6 babel-preset-es2015@6 
```

## script
create a script for build the package:
```
"scripts":{
  "build": "babel src --presets babel-preset-es2015 --out-dir dist"
}
```

## main
change main to "./dist/index.js" ~ or whatever other main file name you have

## src folder
create a folder ./src/ and add your .js files to this directory

## compile from ES6 to ES5
```
npm run build
```

## publish
```
npm publish
```
