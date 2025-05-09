# Airdrop Multisender Development Assessment

## Task Details

1. Integrate MetaMask Wallet

- Implement functionality to connect a MetaMask wallet to your application.
- Display the connected wallet address once successfully authenticated.

2. Validate Recipient Addresses from CSV File

- Create functionality to upload a CSV file containing recipient addresses.
- Implement robust validation to ensure addresses are properly formatted (valid Ethereum addresses) and no duplicate or invalid entries are processed.

3. Transfer Tokens to a Specified Recipient Address

- Implement a feature to transfer a predefined token from the connected wallet to a specified recipient address.
- Ensure the transaction is secure and includes proper error handling (insufficient balance or gas issues).

## Setup

> Please use Node version 18.20.8. `nvm alias default 18.20.8`

1. Clone the repository and run `npm install --legacy-peer-deps` to install the dependencies.

2. Run `npm run start` to start the dev server.
