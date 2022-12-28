# Solidity - Hardhat - Alchemy - Metamask - Pinata 

Creating and deploying an ERC-721 smart contract on the Goerli test network.

## Getting Started

- Clone the repository
- Moving into the folder with `cd`
- Install dependencies `npm install`
- Create `.env` like this :

    ```
    API_URL = "alchemy api url"
    PRIVATE_KEY = "metamask private key"
    PUBLIC_KEY = "metamask public key"
    ```
- Compile the smart contracts `npx hardhat compile`
- Deploy the smart contracts `npx hardhat --network goerli run scripts/deploy.js`

    - Go to the [Goerli etherscan](https://goerli.etherscan.io/) for check.
    - Copy contract adress from Goerli etherscan or console.
    - Add `CONTRACT_ADDRESS = "contract address"` to `.env`

- Deploy the nft `node scripts/mint-nft.js`


<!-- ### Screenshots
