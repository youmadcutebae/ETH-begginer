# ETH-begginer
# MyToken - A Simple ERC20 Token Contract

This is a basic implementation of an ERC20 token contract written in Solidity. It allows for minting and burning of tokens, as well as keeping track of token balances.

## Description

The `MyToken` contract is a simple ERC20 token contract that allows for the creation, minting, and burning of tokens. It includes the following features:

- Public variables to store the token name, abbreviation, and total supply.
- A mapping to keep track of token balances for each address.
- A `mint` function that increases the total supply and the balance of a specified address.
- A `burn` function that decreases the total supply and the balance of a specified address, with a condition to ensure that the balance is sufficient.

## Getting Started

### Installing

1. Clone the repository or download the contract file `MyToken.sol`.
2. Make sure you have a compatible Solidity compiler installed (version 0.8.18 or later).

### Executing the Program

1. Open a Solidity development environment of your choice (e.g., Remix IDE, Truffle, Hardhat).
2. Create a new file and copy the contents of `MyToken.sol` into it.
3. Compile the contract.
4. Deploy the contract to a local development network or a testnet.
5. Interact with the contract by calling the `mint` and `burn` functions, or by querying the token name, abbreviation, total supply, and balances.

```solidity
// Deploying the contract
MyToken myToken = new MyToken();

// Minting tokens
myToken.mint(yourAddress, 1000);

// Burning tokens
myToken.burn(yourAddress, 500);

// Checking the total supply
uint totalSupply = myToken.totalSupply();

// Checking the balance of an address
uint balance = myToken.balances(yourAddress);
```

## Help

If you encounter any issues or have questions, please refer to the Solidity documentation or seek help from the Solidity community.

## Authors

- Youmadcute - [Your GitHub/Twitter/Website](https://github.com/youmadcute)

## License

This project is licensed under the [MIT License](LICENSE.md).
