# Empty TypeScript Project
This is a simple project to get you started with TypeScript.

## Initial Setup Guide
If this is your first time using this project on a local machine,  
you need to install some dependencies globally.

1. Install TypeScript globally.
    > `npm install -g typescript`
2. Install ts-node globally.
    > `npm install -g ts-node`
3. Install rimraf globally. (to delete the old dist folder)
    > `npm install -g rimraf`
4. Install nodemon globally.
    > `npm install -g nodemon`

## npm commands
* `npm run clean`  
    Cleans the dist directory.
* `npm run build`  
    Cleans the dist directory and compiles the TypeScript files.
* `npm run start` or `npm start`  
    Cleans the dist directory, compiles the TypeScript files, and starts index.js.
* `npm run watch`  
    Automatically compiles TypeScript files when they change.
* `npm run dev`  
    Automatically compiles TypeScript files when they change,  
    and restarts index.js with nodemon (automatically restarts on changes).
