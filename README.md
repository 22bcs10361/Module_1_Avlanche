# Module_1_Avlanche
# SmartContractProject

## Overview

This project showcases a simple Ethereum smart contract that implements the require(), assert(), and revert() statements to handle input validation, invariant checks, and exceptional situations. The contract ensures secure operations on numerical values by enforcing certain conditions and providing error handling to prevent unexpected behavior.

## Functionality

The smart contract includes the following functions:

1. Require(uint _value): Allows setting the value of a state variable, ensuring that the value is greater than zero using the require() statement.

2. Assert(uint _newValue): Doubles the value of a state variable and verifies the new value satisfies a specific invariant condition using the assert() statement.

3. Revert(): Transfers the entire value of the state variable to the caller and handles specific cases, such as when the value is zero, using the revert() statement.

## Getting Started

### Prerequisites

To interact with the smart contract, you need an Ethereum development environment, such as [Remix IDE](https://remix.ethereum.org/), and an Ethereum wallet to fund the transactions.

### Deploying the Contract

1. Clone this repository to your local machine or use the provided Gitpod link to open the project in an online IDE.

2. Open the function and errors.sol file in your Ethereum development environment.

3. Compile the contract to check for any compilation errors.

4. Deploy the contract to an Ethereum network of your choice (local or testnet) using the development environment's deployment tools.

### Interacting with the Contract

Once the contract is deployed, you can interact with it through its functions:

1. Call Reqire(_value) to set a new numerical value, ensuring it is greater than zero.

2. Call Assert(_newValue) to double the current value and verify the invariant condition.

3. Call Revert() to withdraw the entire value and handle exceptional cases.

## Security Considerations

The contract is designed for educational purposes and may not be suitable for production use without further security audits and enhancements. Always exercise caution when deploying smart contracts to production networks.

## Author

*Priyanshu*

- GitHub: (https://github.com/22bcs10361)
- Email: priyanshu.kumari0031@gmail.com

## License
This project is licensed under the [MIT License](https://github.com/22bcs10361/Module_1_Avlanche/blob/eb85f0fd1bdc28c235704335054c4523a9ad4965/LICENSE)
