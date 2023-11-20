
# Metacrafters ATM React Component

Welcome to the Metacrafters ATM React component! This component allows users to connect their MetaMask wallet, view their account details, check their balance in ETH and PHP, deposit, and withdraw funds.

## Getting Started

To use this component, follow these steps:

1. **Install MetaMask:**
   - Make sure you have the MetaMask extension installed in your browser.

## Usage

### 1. Connect MetaMask Wallet

Click the "Connect" button to connect your MetaMask wallet. Make sure MetaMask is installed, and you have an account.

### 2. View Account Details

Once connected, your account details, including account address, balance in ETH, conversion price, and converted balance in PHP, will be displayed.

### 3. Deposit Funds

- Enter the deposit amount in the provided input field.
- Click the "Deposit" button to initiate the deposit transaction.
- Your balance will be updated after the transaction is confirmed.

### 4. Withdraw Funds

- Enter the withdrawal amount in the provided input field.
- Click the "Withdraw" button to initiate the withdrawal transaction.
- Your balance will be updated after the transaction is confirmed.

## Component Structure

- `HomePage.js`: The main React component file.
- `m-logo.png`: Logo file used in the component.

## Dependencies

- React: The component is built using React.
- ethers: Ethereum library for interacting with smart contracts.
- MetaMask: Wallet provider for Ethereum.

## Notes

- The ATM smart contract address is set to `"0x5FbDB2315678afecb367f032d93F642f64180aa3"` in the code. Adjust it according to your actual smart contract address.

## License

This project is licensed under the [MIT License](LICENSE).

