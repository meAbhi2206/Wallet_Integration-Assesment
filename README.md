# Solidity Contract with Frontend Integration

This repository contains a set of Solidity contracts along with a React frontend application for interacting with the contracts. It demonstrates a simple smart contract called "Assessment" that allows users to deposit and withdraw funds. The frontend application provides a user-friendly interface to interact with the contract.

## Contract

The `Assessment` contract is implemented in Solidity. It includes the following functionalities:

- Users can deposit funds to the contract.
- Users can withdraw funds from the contract.
- The current balance of the contract can be queried.

## Frontend Application

The frontend application is built using React.js and integrates with the Metamask wallet for interacting with the smart contract. It provides the following features:

- Connect Metamask wallet to the application.
- Display the user's account and balance.
- Deposit funds to the contract.
- Withdraw funds from the contract.

## Prerequisites

To run the project, make sure you have the following installed:

- Node.js
- Metamask wallet extension

## Getting Started

Follow the steps below to run the project locally:

1. Clone the repository:

```shell
git clone https://github.com/your-code address
```
After cloning the github, you will want to do the following to get the code running on your computer.

2. Inside the project directory, in the terminal type: npm i
3. Open two additional terminals in your VS code
4. In the second terminal type: npx hardhat node
5. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
6. Back in the first terminal, type npm run dev to launch the front-end.
7. After this, the project will be running on your localhost. 
Typically at http://localhost:3000/

## Author 
Abhishek Ranjan
## License
This project is licensed under the MIT License.
