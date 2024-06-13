# MyToken

## Overview
MyToken is a simple ERC20-like token contract implemented in Solidity. The contract allows for minting and burning of tokens, with a mapping to keep track of balances.

## Token Details
- **Token Name:** The_Name
- **Token Abbreviation:** The_Abbrv
- **Total Supply:** Variable, depends on minting and burning actions.

## Functions
### mint
```solidity
function mint(address _address, uint _value) public

burn
function burn(address _address, uint _value) public


Burns tokens by decreasing the total supply and the balance of the specified address. Ensures the address has sufficient balance before burning.

Deployment
The contract can be deployed using Remix or any other Ethereum development environment. Below are the steps for deploying and testing the contract using Remix:

Open Remix IDE: Go to Remix IDE.

Create a New File: In the File Explorer pane, click on the "+" icon to create a new file. Name the file MyToken.sol.

Copy and Paste the Code: Copy the provided Solidity code and paste it into the new file.

Compile the Contract:

Click on the "Solidity Compiler" tab (the one with the "S" icon).
Ensure the compiler version is set to 0.8.7 or a compatible version.
Click on the "Compile MyToken.sol" button.
Deploy the Contract:

Click on the "Deploy & Run Transactions" tab (the one with the Ethereum logo).
Ensure the "Environment" is set to "JavaScript VM (London)" for local testing.
Click on the "Deploy" button.
Usage
Interacting with the Contract
After deployment, you can interact with the contract functions:

View Token Details:

tokenName: View the token name.
tokenAbbrv: View the token abbreviation.
totalSupply: View the total supply of tokens.
Mint Tokens:

Click on the mint function.
Enter an address and a value.
Click on the "Transact" button.
Check the totalSupply and balances of the specified address to see the updated values.
Burn Tokens:

Click on the burn function.
Enter an address and a value.
Click on the "Transact" button.
Check the totalSupply and balances of the specified address to see the updated values.
