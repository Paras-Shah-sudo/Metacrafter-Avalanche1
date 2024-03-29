# ErrorHandling
This Solidity program is a simple program that demonstrates the usage of error handling functions in Solidity which are:
1. require()
2. assert()
3. revert()

## Description
This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract contains some test variables. It also contains testing functions which test the funcitonality of each error handling function mentioned above.

## Getting Started
### Executing program
Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Now copy the contents of MyToken.sol (from this repository) to the file opened in the Remix editor.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.7" (or another compatible version), and then click on the "Compile HelloWorld.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "HelloWorld" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by clicking on the buttons for the functions testRequire(), testAssert() and testRevert(). You can also interact with the test variables I have created (a, b, c and x)

> Note: You will have to enter values in the testRequire() and testRevert() functions in order for it to work. They both accept a ```uint``` argument

## Authors
Paras Shah\
[@Paras-Shah-sudo](https://github.com/Paras-Shah-sudo)

## License
This project is licensed under the MIT License - see the LICENSE.md file for details
