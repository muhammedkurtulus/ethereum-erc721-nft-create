# Solidity - Hardhat - Alchemy - Metamask - Pinata 

Creating and deploying an ERC-721 smart contract on the Goerli test network.

## Getting Started

- Clone the repository
- Moving into the folder with `cd`
- Install dependencies `npm install`
- Create an app on [Alchemy](https://www.alchemy.com/) and generate API key
- Add ether from a faucet : [Goerli Faucet] (https://goerlifaucet.com/) or [This] (https://www.allthatnode.com/faucet/ethereum.dsrv) or ....
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
    - Change `const contractAddress = "your contract adress"` in `mint-nft.js`

- Deploy the NFT `node scripts/mint-nft.js` and check [Goerli etherscan](https://goerli.etherscan.io/)

- For view your NFT in your wallet: 

    - Get metamask mobile app
    - Select Goerli Test Network as your network.
    - Import your NFT: Address: `contract adress` and ID: `1` (collectible ID)


<!-- ### Screenshots
