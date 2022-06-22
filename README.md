# Lesson 5 in Patrick's course

In this lesson Patrick explains how to deploy a contract using ethersJS.
He shows how to:

- Compile the contract and generante the ABI using solcJS
- Construct the transaction itself to create the contract in the blockchain
- Create a local blockchain using Gannache
- Using ethers to get the private key and provider from Ganache
- Different ways to deploy to ganache
- Different ways to secure the private key and provider. Specially, he shows a way to encrypt your private key with a password using ethersJS, so you store in your PC the encrypted version... and when you want to deploy you do something like `PASSWORD_PRIVATE_KEY=yourPassword node deploy.js`. So cool!!!
