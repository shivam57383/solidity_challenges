# Project Title

Creating a Token

## Description

This is a Solidity smart contract for a token called "cyder" with the symbol "CYD". The contract is licensed under the MIT license, as indicated by the SPDX-License-Identifier comment at the top of the code. The contract includes the following public variables:
  tokenname: A string variable that stores the name of the token.
  tokenAbbrv: A string variable that stores the abbreviation or symbol of the token.
  totalSupply: A uint variable that stores the total supply of the token.
The contract also includes a mapping variable called balances, which is a mapping from addresses to uint values. This mapping is used to keep track of the balance of each address that holds the token.

The contract has two functions:
  mint: This function is used to mint new tokens and add them to the balance of a specific address. It takes two parameters: the address to which the tokens will be     added, and the amount of tokens to be added. The function increases the total supply of the token and updates the balance of the specified address.

  burn: This function is used to burn tokens and subtract them from the balance of a specific address. It takes two parameters: the address from which the tokens will    be burned, and the amount of tokens to be burned. The function checks if the address has sufficient balance before subtracting the tokens, and if so, it decreases      the total supply of the token and updates the balance of the specified address.

## Getting Started

just copy the code of my_token.sol file and paste in the REMIX IDE 

### Executing program

* How to run the program

  firstly compile the code and then click on deploy.
  
* Step-by-step bullets

1. Firstly mint the token by pasting the account address and giving the totalsupply value
2. Then burn some token by again pasting the same account address and giving the number of tokens to be burned
3. Again paste the same account address on the Balance button and then click on it.
## Help

Any advise for common problems or issues.

Don't Forget to Compile the code, you can also enable the auto compilation by clicking on the auto compile box


## Authors

Shivam




## License

This project is licensed under the MIT License - see the LICENSE.md file for details


