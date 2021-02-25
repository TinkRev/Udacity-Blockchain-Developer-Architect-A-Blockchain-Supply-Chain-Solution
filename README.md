# Udacity-Blockchain-Developer-Architect-A-Blockchain-Supply-Chain-Solution

Udacity Blockchain Developer Nanodegree Program - Project 3 - Architect a Blockchain Supply Chain Solution
Ethereum Dapp for Tracking Items through Supply Chain - Learn lower level components of establishing a sound web service architecture using Blockchain.

# Write Up
## UML 
See ![UML](./UML)
## Libraries 
Truffle - v5.1.61
Web3 - v1.3.4
## IPFS
Not Used

## Deployed Contract on Rinkeby

### FarmerRole
Transaction ID: 0xe256e54a5b53ddb47b7d09c31b26b09dc857e8acf5233edcb5f49e67f5520f3c
Contract address: 0xbA98bE486061BD56Bbc426C78C4d313Ca04d2416

### DistributorRole
Transaction ID: 0xefc9ee77d28b8a5bc8f1fb55f2c494136c312c29b9583a2f7135b7d72bb8186c
Contract address: 0xEfbA74D4B673683b02D8ee92f53B8eC0280ed654

### RetailerRole
Transaction ID: 0xcfb40cd06bda0fe5563c4af086085d7d3ec4a7508b626c07ba196b5b867b60cb
Contract address: 0xEfbA74D4B673683b02D8ee92f53B8eC0280ed654

### ConsumerRole
Transaction ID: 0x4b807f9d5ff1b1c56d8a6e35817ef33a3ade3d0e0a7e72e8fdc98852ec63143c
Contract address: 0xe5907B12F55A841997cBC71eEd4E82e18cFacc92

### SupplyChain
Transaction ID: 0x2441a85f187a0cfd830dcfb470da55b30597023a17b24f10175d7e291ad2c255
Contract address: 0x946c38eDb1365Eb831DBaCaA1e209C52F620532D


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Install Node.js

Install truffle: ```$ npm install -g truffle```

Install web3: ```$ npm install web3```

Install MataMask

### Installing

A step by step series of examples that tell you how to get a development env running

1. Clone this project
2. Move to project directory, open terminal run ```$ npm install```


## Deployment

Using Truffle to deploy Smart Contract on local:
1. Start Truffle development: ```$ truffle develop```
2. Compile: ```$ truffle(develop)> compile```
3. Deploy: ```$ truffle(develop)> migrate```

Run DApp on local:
```$ npm run dev```


## Running the tests

Run the automated tests for Smart Contract:
1. Start Truffle development: ```$ truffle develop```
2. Compile: ```$ truffle(develop)> compile```
3. Deploy: ```$ truffle(develop)> migrate``` (default network) or ```$ truffle(develop)> migrate --network {{specific_network_in_truffle_config_network}}```
4. Test: ```$ truffle(develop)> test```


Test DAPP
1. Get test address after deployed Smart Contract on local.
2. Import Farmer, Distributor, Retailer, Consumer test address into MetaMask.
3. Using Management Supply Chain Role Address part in DAPP web page give role to each test address.
4. Using each test address to test DAPP.


