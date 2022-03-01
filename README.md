# ND1309 C2 Ethereum Smart Contracts, Tokens and Dapps - Project Starter

## Versions

- Truffle v5.5.2 (core: 5.5.2)
- OpenZeppelin v2.3.0

## Smart Contract Info

Name: Star <br>
Symbol: STR <br>
Contract Address: [0x27b57f72282F8f3A446386687395167427f3aB67](https://rinkeby.etherscan.io/address/0x27b57f72282F8f3A446386687395167427f3aB67)

## Transaction overview

First I created two accounts for testing this project:

- Account 1: [0xb3E189B0A4b25Ee8e1AEc02Cd9ED798A694ccB6A](https://rinkeby.etherscan.io/address/0xb3E189B0A4b25Ee8e1AEc02Cd9ED798A694ccB6A)
- Account 2: [0x3891507e368aA6F0978E3c89c131ED8e23B99e77](https://ropsten.etherscan.io/address/0x3891507e368aA6F0978E3c89c131ED8e23B99e77)

The first account created a star with an id of 1: [0xaff4bc3a722cc5c0c2d8b8a98e8aa6806bd4b172d1e5b2fc794d979de3a588e9](https://rinkeby.etherscan.io/tx/0xaff4bc3a722cc5c0c2d8b8a98e8aa6806bd4b172d1e5b2fc794d979de3a588e9)<br>
The second account created a star with an id of 2: [0xd66e2bdfff2609ef82e5d858f35fbad784e3e18882319b43b9e6e94ef0a79574](https://rinkeby.etherscan.io/tx/0xd66e2bdfff2609ef82e5d858f35fbad784e3e18882319b43b9e6e94ef0a79574)<br>

Then the second account exchanged the star of id 2, for the star of id 1: [0xefff9fc4add421b5132b8d7dba9fe107c635cdc612a11a3190a04f0813ab0f5d](https://rinkeby.etherscan.io/tx/0xefff9fc4add421b5132b8d7dba9fe107c635cdc612a11a3190a04f0813ab0f5d)<br>

If you test the contract and call the function "ownerOf" with the token of the first star (1) it will show you that the second account owns the first star, and viceversa for the first account and the second star.<br>
