# ERC20 and Vault Contracts README

## Overview

This repository contains the smart contracts for an ERC20 token and a Vault system on the Ethereum blockchain. The ERC20 contract adheres to the standard ERC20 token specification, providing basic functionalities such as token transfer, approval, and balance inquiry. The Vault contract is designed to securely store ERC20 tokens, allowing users to deposit and withdraw tokens, with additional features for managing token allowances and vault balances.

## Contracts

### ERC20 Contract

The ERC20 contract implements the standard ERC20 interface. Key functionalities include:

- **Minting and Burning**: Ability to mint new tokens and burn existing tokens.
- **Transfer**: Allows token holders to transfer tokens to another address.
- **Approval and TransferFrom**: Allows token holders to approve other addresses to spend tokens on their behalf.
- **Balance Inquiry**: Check the token balance of any address.
- **Allowance**: Check the remaining number of tokens that an address is allowed to spend on behalf of another address.

### Vault Contract

The Vault contract provides functionalities for secure token storage and management:

- **Deposit**: Users can deposit ERC20 tokens into the Vault.
- **Withdraw**: Users can withdraw their deposited tokens from the Vault.
- **Balance Inquiry**: Users can check their token balance within the Vault.
- **Allowance Management**: Users can set and check allowances for token transfers within the Vault.

## Usage

### ERC20 Contract

1. **Deploying the ERC20 Contract**: Deploy the ERC20 contract using the deployment script.
2. **Minting Tokens**: Mint new tokens to a specified address.
3. **Transferring Tokens**: Transfer tokens from one address to another.
4. **Setting Allowance**: Set an allowance for another address to spend tokens on your behalf.
5. **Using `transferFrom`**: Transfer tokens on behalf of another address using the `transferFrom` function.

### Vault Contract

1. **Deploying the Vault Contract**: Deploy the Vault contract using the deployment script.
2. **Depositing Tokens**: Deposit ERC20 tokens into the Vault.
3. **Withdrawing Tokens**: Withdraw deposited tokens from the Vault.
4. **Checking Balances**: Check the token balance in the Vault.
5. **Managing Allowances**: Set and check allowances for token transfers within the Vault.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- OpenZeppelin for their ERC20 implementation.
- Hardhat for providing a robust development environment.

---
 Thank you for using our ERC20 and Vault contracts!
