## Introduction

A nodejs express login server for Verus which allow users to login to websites using VerusId login. Works well together with Verus Web Login -> https://github.com/tommyfpedersen/verus-web-login

This project is based on monkins1010 https://github.com/monkins1010/verusid-login-template.

## Requirements

1. Access to a running Verus Node e.g (testnet) https://api.verustest.net, (mainnet) https://api.verus.services or your own - find more information here: https://verus.io/wallet.

2. A VerusId for signing - can be created in Verus Desktop App or Verus CLI - find more information here: https://verus.io/wallet.

3. The private key (WIF) of the R address that holds above VerusId

4. To make a valid login with mobile phone the Verus Login Server needs to be deployed on a public server or tunneled locally with port forward (visual code) or use grok for complete access. Localhost will not work.

## Important notes:

1. Change the name of the .env.example file to .env and update the values to your
   - Login servers Identity,
   - Private Key,
   - Change JWT secret (Use at least 32 random characters)
   - Changes your servers endpoint.

2. Make sure you do not upload your Private key to Github.

3. This project uses https://github.com/VerusCoin/BitGoJS, which is not the same as https://github.com/BitGo/BitGoJS.

4. You need to use YARN since NPM install will give a dependency 404 error using https://github.com/VerusCoin/BitGoJS - may be fixed later on.

## How to run

node index.js
