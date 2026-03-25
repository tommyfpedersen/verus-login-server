## Introduction
A nodejs express login server for Verus which allow users to login to websites using VerusID login. 
Will soon support Redis and how to keep users logged in using loadbalancer with multiple server setup.

This project is based on monkins1010 https://github.com/monkins1010/verusid-login-template created with nodejs.

## Important notes: 
1. Change the name of the .env.example file to .env and update the values to your Login servers Identity and PrivateKey.
2. Make sure you do not upload your Private key to Github.
3. This project uses https://github.com/VerusCoin/BitGoJS, which is not the same as https://github.com/BitGo/BitGoJS.
4. You need to use YARN since NPM install will give a dependency 404 error using https://github.com/VerusCoin/BitGoJS.


## How to run
node index.js
