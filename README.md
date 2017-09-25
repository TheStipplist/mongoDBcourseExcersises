# mongoDBcourseExcersises
collection of my code for the Udemy 'mongo DB for becoming a full stack Developer' by Stephen Grider

currently on Section 9 lecture 9

having error with 'npm run test'

$ node test nodemon
module.js:471
    throw err;
    ^

npm ERR! Windows_NT 10.0.15063
npm ERR! argv "C:\\Program Files\\nodejs\\node.exe" "C:\\Program Files\\nodejs\\node_modules\\npm\\bin\\npm-cli.js" "run" "test"
npm ERR! node v6.11.3
npm ERR! npm  v3.10.10
npm ERR! code ELIFECYCLE
npm ERR! muber@1.0.0 test: `NODE_ENV=test nodemon --exec 'mocha --recursive -R min'`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the muber@1.0.0 test script 'NODE_ENV=test nodemon --exec 'mocha --recursive -R min''.
npm ERR! Make sure you have the latest version of node.js and npm installed.
npm ERR! If you do, this is most likely a problem with the muber package,
npm ERR! not with npm itself.
npm ERR! Tell the author that this fails on your system:
npm ERR!     NODE_ENV=test nodemon --exec 'mocha --recursive -R min'
npm ERR! You can get information on how to open an issue for this project with:
npm ERR!     npm bugs muber
npm ERR! Or if that isn't available, you can get their info via:
npm ERR!     npm owner ls muber
npm ERR! There is likely additional logging output above.

npm ERR! Please include the following file with any support request:
npm ERR!     C:\Users\Barbara\Desktop\mongoDB\MongoCasts\muber\npm-debug.log


this code is written with nodemon mocha and mongoose being installed and listed as dependencies in the config file as well.
i have a windows 10 operating system, my CLI if it helps is gitbash.

