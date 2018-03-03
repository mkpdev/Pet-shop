PetShop with Ethereum Blockchain
An online petshop with features to adopt and view pets. Uses Truffle for a Ethereum based Blockchain.

Based on the Pet Shop tutorial.

Installation
Install Truffle globally.

npm install -g truffle
Also Requires Ganache to be preinstalled and running for a personal Truffle development blockchain.

Clone the repo.

Run the development console in the repo.

truffle develop
Compile and migrate the smart contracts. Note inside the development console we don't preface commands with truffle.

compile
migrate
Run the liteserver development server (outside the development console) for front-end hot reloading. Smart contract changes must be manually recompiled and migrated.

// Serves the front-end on http://localhost:3000
npm run dev