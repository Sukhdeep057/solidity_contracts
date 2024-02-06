# MyToken Contract


## Description

This is a simple Ethereum smart contract written in Solidity. The contract, `MyToken`, represents a basic token with functions to mint (create) and burn (destroy) tokens.


## Features
1. **Public Variables**: The contract has public variables that store the details about the token such as the Token Name, Token Abbreviation, and Total Supply.
2. **Balances Mapping**: The contract maintains a mapping of addresses to balances, allowing each address to hold a certain amount of tokens.
3. **Mint Function**: The `mint` function takes an address and a value as parameters. It increases the total supply by the given value and increases the balance of the specified address by the same amount.
4. **Burn Function**: The `burn` function works opposite to the `mint` function. It takes an address and a value as parameters. It deducts the given value from the total supply and from the balance of the specified address. It also ensures that the balance of the address is greater than or equal to the amount that is supposed to be burned.
### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., Token.sol). Copy and paste the  code into the file:

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile Token.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "Token" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the  functions. Click on the "Token" contract in the left-hand sidebar, and then click on the function. Finally, click on the "transact" button to execute the function and retrieve the output.

## Authors

Sukhdeep Singh


## License

This project is licensed under the MIT License. 
