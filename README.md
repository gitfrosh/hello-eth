# Hello Ethereum!

We're going to connect to a smart contract called Greeter that's included with a new Hardhat project. It's been deployed 
to the Ropsten testnet at the address 0xE0282e76237B8eB19A5D08e1741b8b3e2691Dadd, and you can find details about 
it on the EtherScan Ropsten block explorer by searching for that address.

Ethers has a Contract API that abstracts over the details of the blockchain and lets us interact with smart contracts as 
if they were regular JavaScript objects named Contract. To wire up a JavaScript object to a deployed smart contract with 
Ethers, we need two things: the address of the contract, and its Application Binary Interface.

We call the greet() smart contract function and display the output in our HTML.
