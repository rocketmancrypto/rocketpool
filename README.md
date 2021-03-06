*NOTE: The current Alpha of Rocket Pool requires the latest [testrpc@v4.1.1](https://github.com/ethereumjs/testrpc) and [truffle@v3.4.9](https://github.com/trufflesuite/truffle) to run locally.

# Welcome to Rocket Pool - Your new Casper friendly Ethereum POS pool

`Rocket Pool` is a next generation decentralised Ethereum proof of stake (POS) pool currently in Alpha and built to be compatible with Casper. Features include Casper compatibility, smart nodes, decentralised infrastructure with automatic smart contract load balancing.

Unlike traditional centralsed POW pools, Rocket Pool utilises the power of smart contracts to create a self regulating decentralised network of smart nodes that allows users with any amount of Ether to earn interest on their deposit and help secure the Ethereum network at the same time. 

The contracts are written in `solidity` and built with the Ethereum framework `truffle`. This project is currently in Alpha and undergoing heavy work.

# Test Rocket Pool

Easiest way to see Rocket Pool Alpha in action is to clone the repo, have testrpc running and the latest version of truffle installed. Make sure you have the [Truffle Default Builder](https://github.com/trufflesuite/truffle-default-builder) first installed as the default builder as a dependency of your Rocket Pool:
```
$ npm install truffle-default-builder --save
```
Start testrpc in a new terminal window using the current block gas limit:
```
$ testrpc -l 6725527
```
Then run:
```
$ truffle test ./test/rocketPool.js
```
to put Rocket Pool through its paces.

# Rocket Pool White Paper

You can read the current Rocket Pool white paper here: [http://www.rocketpool.net/files/RocketPoolWhitePaper.pdf](http://www.rocketpool.net/files/RocketPoolWhitePaper.pdf).

# More Information and Contact

For more information on Rocket Pool, check out our [website here](http://www.rocketpool.net). You can also contact us there for more information.

