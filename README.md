# Mint and Burn Tokens

## Description

The "Mint and Burn Tokens" project is a Solidity smart contract that allows for the creation and destruction of tokens on the Ethereum blockchain. This contract is designed to serve as a foundation for creating custom Ethereum-based tokens. It includes features for minting (creating) and burning (destroying) tokens, and provides information about the token's name, abbreviation, and total supply.

## Getting Started

### Installing

To use the "Mint and Burn Tokens" contract, follow these steps:

1. Download the Solidity contract file from this repository.

### Executing program

To deploy and interact with the "Mint and Burn Tokens" contract on an Ethereum blockchain, you'll need to use tools like Remix, Truffle, or Hardhat. Here's how to do it using Remix:

1. Open the [Remix IDE](https://remix.ethereum.org/).
2. Create a new Solidity file and paste the code from the "Mint and Burn Tokens" contract.
3. Compile the contract.
4. Deploy the contract to an remix  network,or on any testnet.
5. Interact with the contract by calling its functions (mintSupply and burnSupply) using Remix's interface or any other Testnet wallet.

## Usage

You can use the "Mint and Burn Tokens" contract to create your own Ethereum token with the following features:

1. **Token Information:**
   - `tokenName`: The name of your token (e.g., "GOPAL").
   - `tokenAbbr`: The abbreviation of your token (e.g., "GPL").
   - `totalSupply`: The total supply of your token (initially set to 0).

2. **Balances:**
   - The contract maintains a mapping of addresses to balances, allowing you to check the balance of any token holder.

3. **Minting:**
   - Use the `mintSupply` function to create (mint) new tokens. Provide an address and the value to mint. This increases the total supply and adds the minted tokens to the balance of the specified address.

4. **Burning:**
   - Use the `burnSupply` function to destroy (burn) existing tokens. Provide an address and the value to burn. This decreases the total supply and subtracts the burned tokens from the balance of the specified address. The function includes conditionals to ensure that the sender's balance is sufficient for burning.

## Author

- **Name:** Gopal Yadav
- **Academic Pursuit:** Post Graduation in MBA (1st Year)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
