# ETH-beginners-project1
## Description

This project allows the creation of a token using Solidity and allows it for minting and burning, with a total supply and individual balance tracked for each address. It ensures that tokens can only be burned if the sender has a sufficient balance.

## Getting Started

### Executing program
Below are the steps for successful execution of the program -

1. To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

2. Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., token_loki.sol).Then, Copy and paste the following Solidity code into token_loki.sol.This code uses the OpenZeppelin library for an ERC-20 token.

3. To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar and make sure that  the "Compiler" version is set to "0.8.18" (or another compatible version), and then click on the "Compile token_loki.sol" button.

4. Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Now, configure the environment from the "Environment" dropdown, select "Injected Web3" if you want to deploy to a testnet or mainnet using MetaMask. Select "JavaScript VM" for a local, temporary blockchain instance for testing. Select the "token_loki" contract from the dropdown menu, and then under the "Deploy" button, you will see a field to input constructor arguments. Enter the token name and its abbrevation and Click on the "Deploy" button. 

5. Once the contract is deployed,you can interact with your contract directly in Remix. Check the total supply in the "Deployed Contracts" section, expand your deployed MyToken contract. Click on the total_Supply function to view the total supply of tokens. Check total balance by clickig on the total_Balance function. Enter an address (e.g., the deployer address) to check the token balance.

6. Note : No additional files or folders need to be modified when using Remix IDE and you can modify the contract with additional functions like burn, pause, etc by importing other OpenZeppelin contracts for advanced functions. Save your work and export your contracts if needed by downloading the files from the Remix file explorer.
   
## Author
Lokesh Yadav

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
