![Truffle Pet Shop](http://truffleframework.com/tutorials/images/pet-shop/adoption1.jpeg)

## Prerequsites

* Node.js (and NPM) `https://nodejs.org`
* Truffle `$ npm install -g truffle`
* Testrpc (or any ethereum client) `$ npm install -g ethereumjs-testrpc`

## Setup

1. Run private ethereum network in a console `$ testrpc`
1. Open another console, clone this repo, enter and install node.js dependencies `$ npm install`
1. Compile smart contracts `$ truffle compile`
1. Migrate (deploy) smart contracts to our private network `$ truffle migrate`
1. Test the contracts `$ truffle test`
1. Run app `$ npm run dev` and open in browser `http://localhost:3000`
