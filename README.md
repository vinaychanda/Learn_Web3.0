# Learn_Web3.0


# MyToken Smart Contract
This is a smart contract implemented in Solidity for a custom token called "Cred by proof of learn" with an abbreviation of "CRED". The contract allows minting new tokens and burning existing tokens.

## Requirements
- The contract has public variables to store the token name, token abbreviation, and total supply.
- The contract has a mapping of addresses to balances to keep track of the token balance for each address.
- The contract has a mint function that takes an address and a value as parameters. The function increases the total supply by the specified value and increases the balance of the given address by the same amount.
- The contract has a burn function that takes an address and a value as parameters. The function decreases the total supply by the specified value and decreases the balance of the given address by the same amount.
- The burn function checks if the balance of the given address is greater than or equal to the amount that is supposed to be burned.

## Usage
To use this contract, you can deploy it to a compatible blockchain network using a tool like Remix IDE or Truffle Suite. Once the contract is deployed, you can interact with it by calling its functions using a compatible wallet like MetaMask.

## Public Variables
TokenName - A string variable that stores the name of the token.
TokenAbbrv - A string variable that stores the abbreviation of the token.
Totalsupply - An unsigned integer variable that stores the total supply of the token.
## Mapping
balances - A mapping of addresses to unsigned integers that stores the token balance for each address.

## Functions
#### mint(address _address, uint256 _value) public 
- A function that takes an address and a value as parameters. The function increases the total supply by the specified value and increases the balance of the given address by the same amount.
#### burn(address _address, uint256 _value) public 
- A function that takes an address and a value as parameters. The function decreases the total supply by the specified value and decreases the balance of the given address by the same amount. The function also checks if the balance of the given address is greater than or equal to the amount that is supposed to be burned.
## License
This code is released under the MIT License.
