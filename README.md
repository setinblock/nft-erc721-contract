## Set in Block NFT Contract

This is a generic ERC-721 non-fungible token (NFT) contract for the Ethereum blockchain.

It is written in Solidity, and is based on [OpenZeppelin](https://openzeppelin.com/) contract standarts.

This contract is deployed on Rinkeby testnet at: [0x2D4Fc4476B168057dc7589aA28e72f2af2017b5A](https://rinkeby.etherscan.io/address/0x2D4Fc4476B168057dc7589aA28e72f2af2017b5A)

**Quickstart**

Clone the project and run: 
`npm install`

To deploy the contract to Rinkeby testnet:
`npx hardhat run scripts/deploy.js --network rinkeby`

To verify the contract on Etherscan Rinkeby testnet:
`npx hardhat verify --network rinkeby CONTRACT_ADDRESS`

**Minting NFTs**

You can mint new NFT tokens using this contract with the help of Set in Block [Mint NFT](https://setinblock.com/mint-nft) user interface.

To mint a new NFT is free, but you'll need to cover the network transaction fee, using your own [MetaMask](https://metamask.io/) wallet.

**Import tokens into OpenSea**

To import your newly minted NFT tokens to OpenSea [testnet](https://testnets.opensea.io), simply log in to your OpenSea account, and your NFTs from this contract should appear automatically. Alternatively, click My Collections, and import existing collection from this smart contract: `0x2D4Fc4476B168057dc7589aA28e72f2af2017b5A`

**Import tokens into MetaMask**

Currently, only MetaMask mobile version supports NFTs. To import NFTs from this smart contract, open your wallet, click NFT section and them import manually by providing the above mentioned smart contract address and your NFT token ID.